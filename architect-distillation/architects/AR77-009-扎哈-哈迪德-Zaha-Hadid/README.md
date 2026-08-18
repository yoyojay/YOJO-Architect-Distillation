# AR77-009｜Zaha Hadid Architect Skill

这是客户可调用的建筑判断 Runtime，不是风格提示词包。

## 快速开始
你可以直接用自然语言描述项目，也可以填写 `AR77_PROJECT_INPUT_FORM_v1.0.md`。  
Skill 会先做 KNOWN / UNKNOWN / NEED VERIFY，再判断项目适配、问题路由、Method、Selected DNA、A/B/C、Recommendation 与当代修正。

## 关键规则
- Architectural Judgement，不复制外观。
- 完整分析默认选择 1 条 Primary Problem Route、2–4 个 DNA。
- A/B/C 必须因果不同。
- 推荐只允许 Dominant + 最多一个 Borrowed Mechanism。
- 完整分析最后只有一个 `建筑初印象 Prompt`，且必须通过 Prompt Fact Lock。
- Smoke Test 尚未在目标 Agent 中执行，因此 Method Kernel 尚未冻结。
