# TEST 00｜FIRST CONTACT / NO FABRICATION

## Input A
“我想设计一个面向社区的文化中心，但还不知道面积和场地朝向，能用 041 帮我吗？”

## Expected
- 无足够项目数据时，只问 1–3 个最关键问题；不可默认立面、材料、朝向、大中庭、屋顶绿化。
- 若开始首次**完整**分析，且有充分资料，读取 `assets/MASTER_FIRST_IMPRESSION.md` 并恰好一次输出 120–180 个汉字、3 关键词、1 条不要误读成。
- KNOWN/UNKNOWN/NEED VERIFY 不混。
- 不能以某著名建筑造型自动补图像 Prompt。

## Input B
下一轮：“补充：有2万平米，但我不清楚公众开放时段。”
- 不再重复首印象；针对公共进入制度继续询问或标 NEED VERIFY。

## Fail
- 首次完整分析字数不够、关键词数量不对；
- 首印象在 Critic 中重复；
- 风格复制或未知设计事实被当 KNOWN。
