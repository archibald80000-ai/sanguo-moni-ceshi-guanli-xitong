# data读取说明

当前事实时间：**218年秋季季末/218年冬季开局**。

## 权威读取顺序
1.archive_manifest.json
2.latest_state.json
3.current_snapshot.json
4.military_current.json
5.army_roster_current.json
6.equipment_current.json
7.fiscal_current.json
8.territories_current.json
9.technology_current.json
10.factions_current.json
11.social_groups_current.json
12.powers_current.json
13.personnel_current.json
14.intelligence_current.json
15.current_directives.json

唯一L3权威季度结果：
`三国档案/01_季度政务/03_朝政纪要/218年/秋季/奏疏6a68b3397b9086c9b9c41ce7-19.md`

## 当前关键裁定
- 雍州、凉州仍属魏，不能提前改属蜀。
- 雍州外围粮仓、驿路及部分郡治已由蜀控制，徐晃退守州府。
- 龙骧补给85→80是途中消耗节点，季末最终值为95。
- 前线季末补给：张飞90、白毦94、黄忠92、镇北92、马超95、龙骧95。
- 火枪1000/季、火炮100/季、盔甲2000/季是稳定产能，不得直接追加为本季库存。
- 当前库存：火枪1000、火炮10、盔甲8245。
- 新垦20万亩已落籍，但粮税主要收益待后续收成。
- 季度财政核算+743845，当前府库5698743.72、内库7478501。
- 腐败度9、益州满意88是本季新增治理风险。

## 数据规则
- 明确季末终值优先于战役过程节点。
- 产能与库存严格分开。
- 外围控制不等于州级归属迁移。
- 新垦落籍不等于当季粮税已经完全兑现。
- 政令目标不得覆盖季度纪要实际结果。
