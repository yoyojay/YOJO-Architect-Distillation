# SINGLE IMAGE VISUAL HANDOFF
## AR77-031｜Ben van Berkel 单张概念视觉验证

## 定位
本模块只负责把**已经由建筑师确认的组织判断**交给一张概念验证图。

它不是多视角效果图系统，也不是 UNStudio 风格生成器。

## 启动条件
必须同时满足：
- 已完成 AR77-031 项目分析；
- 用户已确认 Dominant Strategy；
- Primary Route 已确认；
- Selected DNA 已锁定为 2–4 个；
- 如有 Borrowed Mechanism，仅来自另一策略 1 个有限机制；
- 用户明确要求单张概念视觉验证。

## 01｜Confirmed Facts
只列已确认项目事实与 verified site / climate / light。

## 02｜Confirmed Strategy
Dominant Strategy + optional one Borrowed Mechanism。

## 03｜Route
Primary Route + optional bounded Secondary Route mechanism。

## 04｜Selected DNA
仅列已经锁定的 2–4 个。

## 05｜Spatial Locks
只描述必须在图中被测试的空间关系，例如：
- 主连接系统是否可读；
- 交叉节点是否对应真实程序关系；
- 非线性路径是否仍能定位；
- 平面 / 剖面中已确认的层级关系；
- 未来变化或性能目标在空间上是否可见。

不得新增新几何。

## 06｜Must Not Drift
- 不使用 `Ben van Berkel style` / `UNStudio style`；
- 不复制 Möbius House、Mercedes-Benz Museum、Arnhem Central、Erasmus Bridge；
- 不自动添加 twist / loop / helix / sweeping curve；
- 不自动添加玻璃、金属、混凝土或参数化立面；
- 不让 Rejected Strategy 或未选 DNA 回流；
- 不把效果图冻结成新的设计事实。

## 07｜Single Demonstration Image Prompt
Prompt 只能继承：
confirmed facts + Method / Route + Dominant + optional one Borrowed Mechanism + Selected DNA + verified site / climate / light。

描述：
- current project type;
- real users / activity;
- confirmed spatial organization;
- movement and program relationships;
- verified environment;
- a camera position that reveals the selected spatial test.

Prompt Fact Lock 扫描：
material / structure / façade / geometry / roof / opening / grid / truss / surface / technical / landscape / furniture。

不可追溯的具体信息删除或泛化。

## 08｜Negative Constraints
`no direct imitation of known works; no signature twist, loop or helix; no unsupported material, facade, structural or landscape specificity`

## 09｜Handoff Note
> 这是一张概念验证图，只用于检查已确认的建筑判断进入视觉后是否成立。它不代表最终建筑方案，也不构成完整可视化体系。
