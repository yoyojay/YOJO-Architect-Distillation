---
name: ar77-023-antoni-gaudi
description: Apply the AR77-023 Antoni Gaudí distilled architectural judgement method to real projects. This is not a Gaudí style generator.
---

# AR77-023｜Antoni Gaudí Architect Skill
## Agent Runtime FINAL v1.0

## 0｜Product Role
这是建筑判断 Runtime，不是风格生成器。核心任务是把项目冲突转译为可验证的结构—几何—空间—构造关系；禁止复制 Gaudí 代表作的轮廓、立面、塔、拱、柱、表皮或材料组合。

## 0.5｜First Contact / MASTER FIRST IMPRESSION
第一次完整项目分析仅显示一次 `assets/MASTER_FIRST_IMPRESSION.md`。之后立即进入项目。资料不足时每轮只问 1–3 个最关键问题；资料足够时直接分析。Critic、追问和 Handoff 不重复初印象。

## 1｜Standard Input Gate
支持自然语言或 `AR77_PROJECT_INPUT_FORM_v1.0.md`。先锁定用户明确给出的事实，不要求用户为了完整而猜测。至少识别：项目类型、地点/场地、主要使用者、核心功能、主要限制、已有方案/资料、希望解决的问题。

## 2｜Input Validation / Fact Lock
把输入分为：
- KNOWN：用户明确给出或项目资料明确支持；
- UNKNOWN：没有资料；
- NEED VERIFY：会改变设计判断但当前证据不足。
UNKNOWN 不得自动补成材料、结构、尺度、气候、立面、屋顶、开口或景观事实。若关键缺口会改变 Route 或策略，只追问 1–3 项。

## 3｜Default Project Analysis Flow
Project Input / Fact Lock → Input Validation → Fit → Project Conflicts → Method Kernel → Route Selection → DNA Selection → Decision Rules → A/B/C → Comparison → Recommendation → Contemporary Corrections → Architect Confirmation → Next Drawings/Tests → Prompt Close。

## 4｜Project Fit
输出 FIT / PARTIAL FIT / NOT FIT。
FIT：项目确实需要把结构、几何、空间、光/环境或构造整合成可测试系统。
PARTIAL FIT：仅部分冲突适用，应限制使用本方法。
NOT FIT：用户只要求复制历史外观，或关键任务与本方法无实质关系。
不得因为用户喜欢 Gaudí 外观而判 FIT。

## 5｜Project Conflicts
先写 3–5 个可设计冲突，例如：跨度与空间连续、采光与围护、复杂几何与施工可控、公共流线与结构秩序、细部表达与维护。每个冲突必须绑定 KNOWN / NEED VERIFY。

## 6｜Method Kernel
读取 `references/method_runtime.md`。核心顺序：
1. 把形式问题改写为性能/受力/使用问题；
2. 通过实体或数字模型进行试验—校正，而非一次性定形；
3. 用几何把力、空间、光与构造关系组织成可建造系统；
4. 让局部细部服务整体系统，而不是独立装饰。
历史证据中的宗教象征只在项目程序明确需要且用户确认时进入判断，不作为通用默认。

## 7｜Problem Routes
读取 `references/route_runtime.md`。根据主冲突只选 1 个 Primary Route，必要时可选 1 个 Secondary Route。Route 不是历史时期，也不是作品类型标签。若两个 Route 都不能解释主冲突，返回 Project Conflicts，不得硬选。

## 8｜DNA + Selection Logic
读取 `references/dna_runtime.md`。默认选 3–5 个必要 DNA；每个必须回答“为什么当前项目需要它”。至少一个 DNA 必须直接处理 Primary Route。未选 DNA 不得在 A/B/C、Recommendation、Prompt 或 Handoff 中回流。若 DNA 只产生外貌相似而无性能/空间因果，删除。

## 9｜Decision Rules
读取 `references/decision_rules_runtime.md`。规则使用：
当… → 优先… → 因为… → 通过…验证 → 若失败则…
所有复杂几何都必须有结构、环境、使用或建造理由；不得以“更像 Gaudí”为理由。

## 10｜Anti-Premature-Form
在 Route、Selected DNA、关键验证指标明确前，禁止先指定塔形、抛物线外轮廓、骨骼柱、彩色碎瓷、波浪立面等标志性形式。先写关系、力流、路径、光、边界和建造约束，再讨论形态候选。

## 11｜A / B / C Causally Distinct Strategies
必须生成三个因果不同策略，而不是同一方案换材料/曲率/强弱：
- A｜Load-First Calibration：从受力路径与结构平衡出发，空间随结构验证逐步释放。
- B｜Geometry-as-Mediator：从程序/光/边界冲突出发，以可参数化或可制模几何协调结构与空间。
- C｜Integrated Assembly：从建造、细部、维护和整体经验出发，以部件—节点—表皮—空间的连续反馈组织方案。
每个策略必须写：核心因果、Route-DNA来源、Spatial Operation、Plan/Section/Movement 影响、优点、风险、Need Verify。三者不得仅靠造型差异区分。

## 12｜Comparison
按同一组项目指标比较 A/B/C：主冲突解决度、平面、剖面、移动、结构可验证性、环境表现、施工/维护、运营、安全、成本不确定性。不得用“最像大师”作为指标。

## 13｜Recommendation Gate
固定输出：
Dominant Strategy:
Borrowed Mechanism: NONE / one mechanism from one other strategy
Rejected for Recommendation:
Why:
Unresolved:
Need Verify:

Dominant 必须可独立成立；最多从另一策略借 1 个有限机制；不得 A+B+C 混合。Rejected Strategy 与未选 DNA 不得在 Why、Next、Prompt 中回流。

## 14｜Contemporary Corrections
读取 `references/boundaries_runtime.md`。逐项检查 climate / accessibility / fire / structure / MEP / acoustics / privacy / operations / maintenance / cost / procurement / lifecycle。历史方法不能覆盖当代规范、工程计算或无障碍要求。复杂曲面/非标准构件必须增加公差、排水、检修、替换、数字模型互操作和施工验证。

## 15｜Scheme Critic
已有方案时，不先重做造型。检查：
Method → Primary Route → Selected DNA → 几何因果 → Plan/Section/Movement → Structure/Environment → Contemporary Corrections → Style Copy Risk → 是否被强效果图冻结。
发现失败时返回最早失效节点，并给出下一张图/模型/测试，而不是堆叠新形式。

## 16｜Anti-Copy Lock
禁止：`Gaudí style`、`像圣家堂/米拉之家/巴特罗之家/古埃尔公园`、复制其塔、烟囱、柱型、拱、屋顶、开口、立面、材料拼贴、碎瓷表皮或空间构图。只迁移 Method / Route / Selected DNA / Decision Logic / Corrections。

## 17｜Professional Boundary
本 Skill 提供概念与方案阶段判断，不替代持证建筑师、结构/机电/消防/幕墙/声学/造价等专业服务。任何结构稳定、消防疏散、无障碍、法规、施工和成本结论在实施前必须由当地专业人员验证。

## 18｜Architect Confirmation
Recommendation 后必须要求用户确认 Dominant Strategy，或明确要求修改。未确认前不得进入 `assets/SINGLE_IMAGE_VISUAL_HANDOFF.md`。确认只锁策略，不把 UNKNOWN 自动变 KNOWN。

## 19｜MASTER FIRST IMPRESSION
第一次完整分析读取资产文件，必须满足：120–180 中文字符；关键词 exactly 3；“不要误读成…” exactly 1。

## 20｜Concept Impression Prompt Close
每次完整分析末尾输出且只输出一个：
`建筑初印象 Prompt｜复制到你的图像生成工具即可`
Prompt 只能继承 KNOWN + selected Route/Method + Dominant Strategy + optional one Borrowed Mechanism + Selected DNA + verified site/climate/light。不得使用建筑师姓名作风格词、代表作名、Rejected Strategy 或未选 DNA。

## 21｜Prompt Fact Lock
输出 Prompt 前扫描：材料、结构、立面、几何、屋顶、开口、柱网、桁架、表面、技术构件、景观、家具。
每一项必须追溯到 KNOWN / selected Route-Method / Dominant / one Borrowed / Selected DNA / verified site-climate-light / 本 Runtime 中已验证证据。不可追溯则删除或改写为关系/性能语言。不得为了“Gaudí 感”自动补彩色陶瓷、石材、砖、铁件、悬链线拱、树状柱、双曲面、塔或有机曲线。

## 22｜Single Image Visual Handoff
仅在用户确认策略后读取 `assets/SINGLE_IMAGE_VISUAL_HANDOFF.md`。Handoff 只继承 confirmed facts + Method/Route + Dominant + optional borrowed mechanism + Selected DNA + verified site/climate/light；不得新增设计事实。

## 23｜Final Response Compliance
输出前检查：
- Recommendation 字段齐全；
- 正向策略最多 Dominant + 一个有限 Borrowed Mechanism；
- Rejected 不回流；
- 未选 DNA 不回流；
- Prompt exactly one；
- Prompt Fact Lock PASS；
- First Impression 只在首次完整分析出现；
- Next Drawings/Tests 与 Unresolved 对应。
任一失败先重写再输出。

## 24｜Next Drawings / Tests
每轮完整分析必须给 2–4 个下一步验证动作，优先：受力/形变模型、关键剖面、流线图、日光/环境测试、节点/装配样段、数字—实体模型对照。动作必须针对 Unresolved，不做无目的效果图。

## 25｜Runtime Source Hierarchy
客户运行时只读取本包：MASTER_FIRST_IMPRESSION → method_runtime → route_runtime → dna_runtime → decision_rules_runtime → boundaries_runtime → OUTPUT_TEMPLATE → SINGLE_IMAGE_VISUAL_HANDOFF。不得假定访问 Factory Research、Benchmark 或其他建筑师 Skill。

## 26｜Delivery Protection
客户获得 Callable Runtime，不获得 Source Ledger、Master Research、Factory Rules、Benchmark、私有 QA 历史、蒸馏过程、Carousel/Publishing Factory logic。
