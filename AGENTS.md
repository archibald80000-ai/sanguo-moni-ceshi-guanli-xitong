# AGENTS.md

## 当前事实时间

- 当前游戏：三国历史 AI 推演。
- 当前时间：214年春季季末；汉纪映射待核。
- 当前档案版本：`SG-214-SPRING-RESULT-1`。
- 当前权威来源：奏疏 `6a68b3397b9086c9b9c41ce7-1` 为最新L3结果。
- 七署官制改革已由最新L3纪要确认到任并履职；后续以 `data/appointments_current.json` 为当前事实。

## 必读入口

1. `CURRENT_ARCHIVE.md`
2. `data/archive_manifest.json`
3. `data/latest_state.json`
4. `data/current_snapshot.json`
5. `data/personnel_current.json`
6. `data/factions_current.json`
7. `data/territories_current.json`
8. `data/powers_current.json`
9. `data/military_current.json`
10. `data/equipment_current.json`
11. `data/appointments_pending.json`
12. `data/current_directives.json`
13. `data/quarterly_workflows.json`
14. `三国档案/01_季度政务/05_当前工作台/建安十八年/基线/README.md`
15. `三国档案/00_总览/五层证据模型.md`

## 五层证据

- `L1_PLAN`：密谈、任命方案、战略目标、政令草案。
- `L2_ORDER`：玩家正式提交的命令，只证明已下令。
- `L3_RESULT`：游戏截图、奏疏、季度反馈，证明游戏实际裁定。
- `L4_STATE`：由最新 L3 归纳出的当前数据库。
- `L5_REVISION`：事后修订与制度设计，不能倒改历史。

## 强制规则

- 截图数字优先按截图原值记录，不自行修正。
- 奏疏负责补充叙事、风险和因果，但未给数值的项目不得补造具体数字。
- 面板“理论收入/产量”不等于府库实收。
- 拟任命不等于任命生效；任命不等于到任；到任不等于完成本季任务。
- 军队总人数、士气、忠诚、补给、满编率分别记录，不互相替代。
- 党派满意度、影响力、叛乱风险分别记录；不得用某一项推定另外两项。
- 同一事实冲突必须并列标记。例如奏疏称“进围成都”，截图却已显示蜀控制蜀地，当前只标记刷新时点待核。
- AI可分析、拟密谈、拟诏书，但不得把推演结果写成已经发生的 L3 事实。

## 当前推演主线

先完成国家化基础：
**信用 → 联盟 → 财政 → 生产 → 军队 → 汉中 → 扩张**。

当前第一阶段重点：
**官制落位 + 党派平衡 + 真实账本 + 归附军稳定 + 地方接管。**

## 目录规则

沿用母版目录与季度闭环，不重构系统。当前游戏资料全部进入 `三国档案/` 与 `data/current_*`；母版中遗留的大明历史文件仅作模板历史，不得覆盖当前三国状态。

## 214年春季特别口径
- 军巡案队定员2000不等于已募兵。
- 都江堰与官仓“立项勘丈”不等于已开工。
- 奏疏“蜀威望70→72”与旧面板“统治者权威70”字段不同，不自动合并。
- 农民满意度正文20→28，末尾附加+1是否已计入待核。
