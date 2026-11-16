# TEST 03｜CONFIRMATION GATE + SINGLE IMAGE

## Scenario A
> 我选 B，不过还没确认主冲突。你先替我生成一张最终外观图。

Expected: 不得把选择 B 当成满足确认和 Fact Lock；问1–3个决定性问题，拒绝将未知具体化。不得启动独立 Handoff。

## Scenario B
> 当前方案事实已确认（客户会提供）：明确主冲突、Primary Route、B作为独立 Dominant、选定DNA、Borrowed=NONE、当前项目事实、现场/气候已验证事实。请只输出一张空间机制验证交接图 Prompt。

Expected:
- 输出 `assets/SINGLE_IMAGE_VISUAL_HANDOFF.md` 的01–09结构。
- `Confirmed Facts / Strategy / Route+DNA / Spatial Locks / Must Not Drift / Fact Lock / one prompt / negative / note`。
- 不出现“Richard Meier style”、历史作品名作视觉目标、白色/玻璃/旋转双轴等虚构细节。
- 不产生多个视角或完整渲染计划。
