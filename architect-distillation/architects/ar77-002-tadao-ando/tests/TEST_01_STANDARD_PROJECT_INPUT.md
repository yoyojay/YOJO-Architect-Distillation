# TEST 01｜标准项目表项目调用

PASS:

- [ ] Input Validation 先发生
- [ ] UNKNOWN 不被自动补成事实
- [ ] 有 FIT / PARTIAL FIT / NOT FIT
- [ ] 3–5 Core Spatial Conflicts
- [ ] 明确 Period Route
- [ ] 不混五条 Route
- [ ] 选择 4–7 DNA
- [ ] A/B/C 因果不同
- [ ] 当代校正存在
- [ ] 有天气 / 无障碍 / 排水 / 材料风险
- [ ] 有建筑师确认点
- [ ] 给出下一步 1–2 张图
- [ ] 不自动进入完整出图

HARD FAIL:

- 直接给 Tadao Ando style
- 自动使用清水混凝土
- 复制代表作
- 三案只是换造型
- 露天路径无无障碍 / 避雨校正
- 不做气候与排水校正


## FINAL v1.2 Additional Gates

PASS:

- [ ] 首次完整项目分析有一次约 150 字大师初印象
- [ ] 信息不足时每轮只问 1–3 个关键问题
- [ ] 未进入 Selected DNA 的 DNA 不得在策略 / 推荐中重新作为核心或补充机制出现
- [ ] 推荐只能是单一策略，或一个主策略 + 另一个策略的一个有限机制
- [ ] 推荐最多正向涉及 2 个策略，A+B+C = HARD FAIL
- [ ] 推荐中的 Dominant / Borrowed 不得超出已选 Route
- [ ] 被 Reject 的第三策略不得在 Keep / Next / Prompt 中重新进入
- [ ] 完整项目分析最后只有一个建筑初印象 Prompt
- [ ] Prompt 只使用 KNOWN + 已选 Route + Dominant + 单一 Borrowed + Selected DNA
- [ ] Prompt 不把清水混凝土 / 斜墙 / 光缝 / 三角庭院 / 水面当默认答案

HARD FAIL ADDITIONS:

- 推荐同时正向引用 A、B、C
- 未选 DNA 以“子机制 / 补充机制”方式重新进入
- 推荐或 Prompt 偷换到未选择 Route
- Prompt 出现 `Tadao Ando style` 或代表作名称
- Prompt 自动补入未经项目判断支持的安藤式图像符号


## v1.3 Prompt Fact Lock Regression

HARD FAIL:

- Prompt 把未知材料自动写成 `exposed concrete`
- Prompt 自动生成 `deep reveals`
- Prompt 自动生成未经确认的 concrete / brick / timber / steel / glass
- Prompt 自动生成未经确认的 solid wall construction / water plane / roof geometry
- Prompt 为了“像安藤”补充十字光、斜墙、清水混凝土等具体图像元素

PASS:

- 未确认材料保持中性表达
- 未确认开口 / 边界使用 light / shade / glare / privacy / protection 等性能关系表达
- 每个具体视觉描述都能追溯到 KNOWN / Dominant / Borrowed / Selected DNA / verified site-climate-light evidence
