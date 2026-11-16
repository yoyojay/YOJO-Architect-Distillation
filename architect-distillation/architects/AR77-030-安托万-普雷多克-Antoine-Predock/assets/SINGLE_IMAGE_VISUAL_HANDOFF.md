# SINGLE IMAGE VISUAL HANDOFF
## AR77-030｜Antoine Predock 单张概念视觉验证

### 定位

本模块只负责：

**把已经确认的空间判断交给一张概念验证图。**

它不是风格生成器、完整效果图系统、多视角控制器或最终建筑设计。

### 启动条件

必须同时满足：

- 已完成 AR77-030 项目分析；
- Primary Route 已确认；
- Dominant Strategy 已由用户确认；
- optional Borrowed Mechanism 已固定；
- Selected DNA = 2–4；
- verified site / climate / light 已与 UNKNOWN 分开；
- 用户明确要求单张概念视觉验证。

任何一项缺失：不启动。

### 输出

## 01｜Confirmed Strategy
Dominant Strategy + optional one Borrowed Mechanism only.

## 02｜Confirmed Method / Route
Primary Route + allowed Secondary mechanism, if any.

## 03｜Selected DNA
只列已经确认的 2–4 个 DNA。

## 04｜Spatial Locks
只写必须被图像检验的关系，例如：
- site force visibly changes ground / orientation / threshold;
- path creates a legible sequence of approach, pause and reorientation;
- key vantage points correspond to real site or program relationships;
- public landscape continuity remains compatible with operation;
- verified strata / memory is spatially traceable, if D04 is selected.

## 05｜Must Not Drift
- 不使用 `Antoine Predock style`；
- 不以任何 Predock 代表作作为视觉目标；
- 不复制其轮廓、坡道、塔、墙、屋顶、开口、材料组合或空间构图；
- 不把岩体感、沙漠色、纪念性巨构当默认；
- 不加入 Rejected Strategy、未选 Route 或未选 DNA；
- 不新增未经确认的建筑事实。

## 06｜Single Demonstration Image Prompt
Prompt 只能继承：
- confirmed project facts;
- confirmed Method / Route;
- confirmed Dominant Strategy;
- one allowed Borrowed Mechanism;
- Selected DNA;
- verified site / climate / light.

## 07｜Prompt Fact Lock
逐项扫描：
material / structure / façade / geometry / roof / opening / column-grid / truss / surface / technical components / landscape / furniture。

不可追溯到允许来源的具体信息：
**删除或改写为关系 / 性能语言。**

## 08｜Negative Constraints
只写与当前策略直接相关的防漂移约束。

## 09｜Handoff Note
> 这是一张概念验证图，用于检查已确认的设计判断进入视觉后是否成立；它不代表最终设计，也不扩展为完整效果图体系。
