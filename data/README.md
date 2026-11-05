# data 读取说明

当前游戏为三国蜀汉推演，**当前事实时间：216年夏季季末**。

## 权威读取顺序
1. `archive_manifest.json`
2. `latest_state.json`
3. `current_snapshot.json`
4. `military_current.json`
5. `equipment_current.json`
6. `factions_current.json`
7. `social_groups_current.json`
8. `powers_current.json`
9. `territories_current.json`
10. `current_directives.json`

唯一L3权威结果为：
`三国档案/01_季度政务/03_朝政纪要/216年/夏季/奏疏6a68b3397b9086c9b9c41ce7-10.md`

## 重要规则
- 用户已裁定：此前仓库“当前档案”均为错误。
- 216年夏季 current 文件已按最新完整纪要重新构建。
- 最新纪要没有重新确认的旧绝对值，不得从历史/current旧版本自动继承。
- 历史文件、旧 `game_state.json`、旧快照等只能用于追溯，不得覆盖当前L4。
- 工程“已启动”不等于“已完工”；交州“商路渗透”不等于“据点/领土控制”。
- 府库主终值9141229.72与另列-11500事件存在包含关系待核，未核前不得重复扣除。
