# 三国AI推演辅助管理系统

这是三国历史 AI 推演游戏的个人政务档案库。系统完整继承原“模拟测试管理系统”的季度闭环、五层证据、密谈、诏书、执行结果、人事、军队、地方、财政与战略管理方法；档案主目录统一使用 `三国档案/`。

## 当前状态

- 当前时间：**214年春季季末**（汉纪映射待核）。
- 当前阶段：**七署首季运行完成 / 进入真实业务验证阶段**。
- 当前档案版本：`SG-214-SPRING-RESULT-1`。
- 当前权威事实：奏疏 `6a68b3397b9086c9b9c41ce7-1`。
- 七署改革已正式到任并完成首季履职。

## AI强制读档顺序

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
13. `三国档案/01_季度政务/05_当前工作台/建安十八年/基线/README.md`
14. `三国档案/00_总览/五层证据模型.md`

## 核心事实规则

- L1计划、L2命令、L3游戏结果、L4当前状态、L5事后修订必须分开。
- 面板产量和理论税银不能冒充府库现金。
- 官职拟任命不能冒充正式到任。
- 军队编制、人数、忠诚、士气、补给分别记录。
- 截图与奏疏冲突时并列保存，不静默选择一个版本。

## 季度闭环

```text
收到游戏反馈/截图
→ 更新L3证据
→ 生成L4当前快照
→ 密谈与问题拆解
→ 玩家确认方向
→ L2正式政令
→ 责任人/资源/验收/失败线
→ 游戏推演
→ 下季反馈回填
```

## 当前新增结构化数据

- `data/factions_current.json`：四大党派。
- `data/territories_current.json`：五块控制地。
- `data/powers_current.json`：主要国家/势力面板。
- `data/military_current.json`：截图可见军队。
- `data/equipment_current.json`：装备库存与季度产量。
- `data/appointments_pending.json`：七署拟任命。
- `data/personnel_current.json`：当前可见大臣与现职。

## 本地使用

```powershell
git clone "https://github.com/archibald80000-ai/sanguo-moni-ceshi-guanli-xitong.git"
cd ".\sanguo-moni-ceshi-guanli-xitong"
git pull
python main.py
```

仓库：<https://github.com/archibald80000-ai/sanguo-moni-ceshi-guanli-xitong>
