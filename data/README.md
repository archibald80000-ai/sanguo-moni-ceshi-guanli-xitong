# data 读取说明

当前游戏为三国蜀汉推演，**当前事实时间：217年冬季季末/218年春季开局**。

## 权威读取顺序
1. `archive_manifest.json`
2. `latest_state.json`
3. `current_snapshot.json`
4. `military_current.json`
5. `army_roster_current.json`
6. `navy_current.json`
7. `equipment_current.json`
8. `factions_current.json`
9. `social_groups_current.json`
10. `powers_current.json`
11. `territories_current.json`
12. `technology_current.json`
13. `personnel_current.json`
14. `ministers_current.json`
15. `intelligence_current.json`
16. `current_directives.json`
17. `panel_snapshot_217_winter.json`

唯一L3权威季度结果为：
`三国档案/01_季度政务/03_朝政纪要/217年/冬季/奏疏6a68b3397b9086c9b9c41ce7-16.md`

## 当前关键裁定
- 曹仁、于禁本人均已被俘在押。
- 曹仁部1.64万人、于禁部1.05万人已整建制归降蜀国，合计约2.69万人；当前士气与补给均为0，属于待重整降军，不得当作即时可战精锐。
- 襄樊北伐已结束；汉水、荆北要道及襄樊北门军事控制归蜀。
- 汉中未克，夏侯/张郃/张鲁当前士气补给为35/3、45/3、33/5。
- 冬季实际新增人口8万，当前全国人口180万；政令目标50万未实现。
- 新垦田有实际效果但纪要未给亩数，禁止写成20万亩已完成。
- 高炉冶金、炒钢法已正式解锁。
- 人民币改制与天下银行已启动；通货定量仍以55为最近确认值。
- 红颜50人已分遣就道，但稳定节点和收益尚未结算。
- 最终府库7904483.32；上季末到冬季国策起点存在40万未解释账差，保留待核。

## 数据规则
- 季度纪要明确终值优先于政令目标。
- 同季截图补足纪要未列的当前绝对面板；若截图与纪要明确事件冲突，纪要优先。
- 工程“启动/拨款”不等于“完工/投产”。
- 军队“归降”不等于“立即具备战力”，需看士气、补给、忠诚和整编状态。
- 旧 `game_state.json` 为历史异项目遗留数据，不属于当前蜀汉current权威层，不得覆盖上述current文件。
