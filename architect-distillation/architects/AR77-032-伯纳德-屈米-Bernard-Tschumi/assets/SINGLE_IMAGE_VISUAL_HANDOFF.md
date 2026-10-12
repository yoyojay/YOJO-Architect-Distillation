# SINGLE IMAGE VISUAL HANDOFF
## AR77-032｜Bernard Tschumi 单张概念视觉验证

### 定位
只把**已经确认的建筑判断**交给一张概念验证图。
不是完整效果图系统，不是多视角生产，不是风格模仿器。

### 启动条件
- 已完成 AR77-032 项目分析；
- 用户已明确确认 Dominant Strategy；
- Primary Route 已确认；
- Selected DNA 已确认；
- 若有 Borrowed Mechanism，只能一个且已确认；
- 用户明确要求单张概念视觉验证。

条件不全：返回 Architect Confirmation，不生成 Handoff。

## 01｜Confirmed Strategy
只写已确认 Dominant Strategy + optional one Borrowed Mechanism。

## 02｜Primary Route
写已确认 Route；不引入未选 Route。

## 03｜Selected DNA
只列已确认 DNA；未选 DNA 不得回流。

## 04｜Spatial Locks
只写必须在图中可见的关系，例如：
- event 与空间的已确认关系；
- movement 的层级 / 交叉 / 停留逻辑；
- program 叠置或分离；
- context-content 的已确认策略关系；
- concept 在 plan / section / sequence 中留下的痕迹。

## 05｜Must Not Drift
- 不使用 `Bernard Tschumi style`；
- 不复制 Parc de la Villette / Le Fresnoy / Lerner Hall / Acropolis Museum 等代表作；
- 不自动补 red follies / red steel / diagonal promenade / glass ramp / giant canopy / fragmented geometry / cones；
- 不加入 Rejected Strategy；
- 不加入未选 DNA；
- 不新增未经确认的材料、结构、立面、屋顶、开口或景观事实。

## 06｜Single Demonstration Image Prompt
Prompt 只继承：
confirmed project facts + confirmed Method / Route + Dominant + optional one Borrowed Mechanism + Selected DNA + verified site/climate/light。

优先描述：
- current project type;
- actual activity / movement;
- spatial sequence;
- program relation;
- context relation;
- view that can test the confirmed judgement.

Prompt Fact Lock：任何具体 material / structure / façade / geometry / roof / opening / technical component 必须有可追溯依据；否则删除或改为性能 / 关系语言。

## 07｜Negative Constraints
只写当前项目真正需要的负约束，不建立“风格负面提示词库”。

## 08｜Handoff Note
> 这是一张概念验证图，用于检查已确认的建筑判断进入视觉后是否仍成立。它不代表完整效果图体系；后续视觉生产应进入建筑师既有流程或独立专业可视化系统。
