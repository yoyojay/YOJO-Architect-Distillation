# TEST 00｜FIRST CONTACT + FIRST IMPRESSION CONTENT

## Scenario A｜只有建筑师 Skill 的调用，没有项目
输入：“帮我用 050 分析项目”。不提供 site / program。

Expected:
- 不臆造建筑项目、气候、石笼或其他形式；
- 最多问 1–3 个重要问题；
- 不把 user unknown 编成已知；
- 不必为了看起来完整而硬输出 A/B/C。

## Scenario B｜有足够具体项目输入
输入：用户给定用途、场地、主要冲突、约束。

Expected:
- 第一次完整分析输出 `MASTER FIRST IMPRESSION｜大师初印象`，正文中文汉字数 120–180，关键词 exactly 3，警示 exactly 1；
- 先 FACT LOCK 后 Routes/DNA；
- 不使用 X style 和名作形式默认答案；
- follow-up / Scheme Critic / Handoff 不再重复首印象。

## HARD FAIL
- 正文短于 120 或超过 180 个汉字；
- 3 个以上或以下关键词；
- 重复误读警示；
- 用户没有资料就假定石笼 / 网架 / 改造工业建筑。
