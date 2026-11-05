# data 读取说明

当前游戏为三国蜀汉推演，**当前事实时间：218年春季季末/218年夏季开局**。

## 权威读取顺序
1. `archive_manifest.json`
2. `latest_state.json`
3. `current_snapshot.json`
4. `military_current.json`
5. `army_roster_current.json`
6. `navy_current.json`
7. `equipment_current.json`
8. `fiscal_current.json`
9. `territories_current.json`
10. `technology_current.json`
11. `factions_current.json`
12. `social_groups_current.json`
13. `powers_current.json`
14. `personnel_current.json`
15. `ministers_current.json`
16. `intelligence_current.json`
17. `current_directives.json`

唯一L3权威季度结果：
`三国档案/01_季度政务/03_朝政纪要/218年/春季/奏疏6a68b3397b9086c9b9c41ce7-17.md`

## 当前关键裁定
- 汉中已由魏转蜀，军政接管开始。
- 夏侯、张郃、张鲁均已被俘；原3军有效建制终结。
- 曹仁、于禁继续被俘，5名重要魏将均在押。
- 曹仁部、于禁部、刘璋旧部、新募军4旧号已废，46900人重编为虎威、武卫、骁武3军。
- 三支新军的士气、忠诚、补给、经验、满饷率尚未给出终值。
- 汉水水师470舰12000人；长江水师230舰。
- 7座国家级工业节点、30座地方建筑均已正式完工。
- 当前装备为冷兵器75272、盔甲7540、马匹20960、投石机4610、四轮车971、弩车1540、木牛流马195。
- 季末府库9329196.22，内库5328501。
- 财政面板收入2233.6万、支出2259.88万，军队维护费1918.48万；该面板周期未明，不与季度核算直接相加。
- 蜀主权威100，军人叛乱风险8，腐败7。
- 汉中新接管人口、粮食、税基、民心、城防待核。
- 火器科技链仅为截图可见候选，不得视为已经解锁。

## 数据规则
- 季度纪要明确终值优先于政令目标。
- 同季截图用于补足结构面板和候选信息，不能越权把“可见节点”升级为“已掌握”。
- 建制终结后的降军人员与旧军番号必须分开；不得因“所属魏→蜀”就继续保留为原名现役蜀军。
- 财政结构面板与季度府库结算为不同口径，禁止重复相加。
- 新取得领土若未给人口税基，禁止自行按旧魏人口拆分推算。
