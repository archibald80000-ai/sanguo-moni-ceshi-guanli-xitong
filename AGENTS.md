# AGENTS.md

## 当前活动游戏
- 游戏：**崇祯新局**
- 第0回合：天启七年冬季，崇祯已登基。
- 下一回合：崇祯一年春季。
- 当前版本：`CZ-NEW-BASELINE-0`
- 当前只录入L0公开System规则，尚未收到L1 pgsql背景数据库。

## 必读入口
1. `ACTIVE_GAME.json`
2. `CURRENT_ARCHIVE.md`
3. `崇祯新局/README.md`
4. `崇祯新局/00_底层规则/00_System原文.md`
5. `崇祯新局/00_底层规则/01_硬规则.json`
6. `崇祯新局/00_底层规则/02_数据库字段速查.json`
7. `崇祯新局/00_底层规则/03_时间与回合规则.json`
8. `崇祯新局/00_底层规则/04_证据与裁定层级.md`
9. `崇祯新局/01_当前状态/current_state.json`
10. `崇祯新局/01_当前状态/current_directives.json`

## 权威层级
- L0_SYSTEM_RULE：公开Mod底层System。
- L1_DB_BACKGROUND：本局pgsql背景数据库。
- L2_PLAYER_ORDER：皇帝圣旨，只证明下令。
- L3_GAME_RESULT：游戏季度反馈，证明实际发生。
- L4_CURRENT_STATE：由最新L3汇总的当前状态。
- L5_REVISION：修订与数据治理，不倒改历史。

## 绝对规则
- 架空世界线只依赖本局pgsql背景，不用历史直接知识补事实。
- 现代白话文简体中文；纪年“崇祯X年X季”。
- 1950年代后科技硬否决；超自然不成立。
- 1回合=1季度=3个月；1年=4回合。
- 国库treasury与内帑privacy严格分账。
- ministers没有loyalty/morale；provinces没有morale/supply；regimes只有corruption/prestige/currency_policy三个可用数值指标。
- troops.salary_rate是满饷率，不是满编率。
- ship类型composition.count是舰船数，不是船员数。
- disaster_level只能是正常/轻微/中等/严重。
- 不在ministers表不代表人物不存在，合理人物可按圣旨create。
- 官员不质疑圣旨；命令含糊时会按执行者有利方式理解。

## 跨局隔离
- `魏震华夏-三国/`已封存，只读。
- 仓库旧“崇祯/CZ”文件为LEGACY，不得向本局注入任何世界事实或数值。
- 根目录旧`data/*_current.json`不是本局当前状态，本局只读取`崇祯新局/`命名空间。
