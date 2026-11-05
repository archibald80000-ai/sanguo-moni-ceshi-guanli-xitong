# data读取说明

当前事实时间：**218年冬季季末/219年春季开局**。

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
`三国档案/01_季度政务/03_朝政纪要/218年/冬季/奏疏6a68b3397b9086c9b9c41ce7-20.md`

补充朝议风险：
`三国档案/05_情报与朝议/218年冬_朝议风险补充.md`

## 当前关键裁定
- 雍州、凉州仍属魏，不能提前改属蜀。
- 徐晃当前约15400为推算值，不是精确总兵力。
- 马超补给过程曾95→89，但季末经补给后终值100。
- 火枪库存2000、火炮110。
- 当前稳定产能仍是火枪1000/季、火炮100/季。
- 第二火枪厂目标新增2000/季、第二火炮厂目标新增200/季，均尚未验收，不能提前并入稳定产能。
- 新增50万亩项目仅启动清丈授田，不能提前修改现有民田。
- 工商200万周转资本已投入，但利润和回款尚未提交。
- 季度财政核算+3524172.04，当前府库6982915.76、内库6808501。
- 腐败9→7，益州集团满意88→87。
- 通货供应55→58。
- 系统事件“民心+1”未指定地区，不分配到具体州郡。

## 数据规则
- 季末终值优先于战役过程节点。
- 推算兵力必须标记“约”或“推算”，不能伪装成精确值。
- 产能、库存、在建扩产严格分开。
- 项目开办不等于项目完工。
- 工商周转资本不等于经营利润。
- 外围控制不等于州级归属迁移。
- 朝议截图属于风险与建议证据层，不覆盖L3季度纪要。
- 政令目标不得覆盖季度纪要实际结果。
