# AR77-042｜Richard Meier Architect Skill

可调用的项目判断 Skill：研究重点为实际项目中的场地秩序、公私分区、空间路径与观看、可控日光及人的尺度。目标不是复制迈耶代表作外观。

## 如何调用
在支持 Agent Skill 的环境内载入本包，以自然语言描述项目（地点/功能/用户/一项核心矛盾即可开始）或填写 `AR77_PROJECT_INPUT_FORM_v1.0.md`；用户无需理解内部命令。主调用入口是 `SKILL.md`。

## 包内容
- `SKILL.md`：独立可执行 Runtime（输入/事实/路由/DNA/策略/推荐/批评/Prompt/确认与交接）。
- `references/`：与迈耶证据关联的 Method/Route/DNA/Decision Rules/当代校正细化资料。
- `assets/`：客户输出模板、第一次介绍及已确认后单张图交接。
- `tests/`：客户或接入团队用于真实调用的场景与静态验收清单。
- `agents/openai.yaml`：Skill 发现与调用元信息。
- `runtime_manifest.json`：客户侧功能声明。
- `SHA256SUMS.txt`：包内文件散列。

## 重要边界
- 对未知信息请直接写 `UNKNOWN`；不补造基地、气候、材料或构造。
- 首次完整分析含 120–180 汉字的 Master First Impression，后续不会重复。
- A/B/C 必须来自可追溯的同一问题 Route 和所选 DNA。
- Dominant 独立成立，Borrowed 至多一个，Rejected/未选 DNA 不得回流。
- 完整分析最后仅一个初印象 Prompt；用户确认策略后才能单独启动 Handoff。
- 不等于注册建筑师、工程团队的法律或专业结论。

## 版本状态
CANDIDATE v1.0：尚待独立交付认证与目标 Agent 真实调用验证，不作为冻结的 FINAL 版本。真实目标 Agent Smoke Test：NOT TESTED。
