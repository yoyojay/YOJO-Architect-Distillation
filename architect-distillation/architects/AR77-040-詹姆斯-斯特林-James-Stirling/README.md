# AR77-040｜James Stirling Architect Skill

**版本：** Candidate v1.0（尚待完整交付认证，非 FINAL）。  
**用途：** 面向真实建筑项目的前期判断、适配、空间冲突、Routes 与 DNA 筛选、三套因果不同的策略、单一主导推荐、概念初印象 Prompt、现有方案批评与确认后的单张视觉验证 Handoff。

## 使用
在支持 Skill 的 Agent 中安装本目录或 ZIP，调用“使用 $ar77-040-james-stirling 帮我分析以下建筑项目：……”，也可直接贴自然语言项目资料。填写 `AR77_PROJECT_INPUT_FORM_v1.0.md` 可提高信息完整度，但不是前置条件。没有足够资料每轮只问 1–3 项。

先读主 `SKILL.md`（完整 Runtime），再按需读取：
- `references/method_runtime.md`：建筑师方法的已验证依据与转译边界；
- `references/route_runtime.md`：项目问题路由；
- `references/dna_runtime.md`：可筛选空间判断机制；
- `references/decision_rules_runtime.md`：决策与失败回退；
- `references/boundaries_runtime.md`：当代专业校正；
- `assets/OUTPUT_TEMPLATE.md`：固定分析输出；
- `assets/MASTER_FIRST_IMPRESSION.md`：首次完整分析的 167 中文字首印象；
- `assets/SINGLE_IMAGE_VISUAL_HANDOFF.md`：确认后单张图交接；
- `tests/`：客户可自行验收的检查与样例。

## 方法边界
历史斯特林曾提出建筑应表达使用活动，并探索类型关系与空间组合；本 Skill 的 Route/DNA 是有来源的当代操作抽象，不是他的原话或历史官方标签。不可要求复制其作品或“Stirling style”。

## 当前验收
静态检查及 ZIP 完整性检查：见随包的 tests 清单，自主查验。真实目标 Agent Smoke Test：**NOT TESTED**。当前仍需交付认证，不能将本包称为 FINAL。
