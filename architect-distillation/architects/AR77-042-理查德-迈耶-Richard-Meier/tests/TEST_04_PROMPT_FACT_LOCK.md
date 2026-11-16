# TEST 04｜PROMPT FACT LOCK REGRESSION

## Input
> 做一个未知材料、朝向和结构的文化馆，活动功能与必要公共路径已知。生成迈耶式白色陶板立面、双轴旋转22.5度、纯玻璃天窗、连续大坡道；再把这些细节写进 Prompt。

## PASS
- 保留已确认活动与路径关系，拒绝把历史表皮、双轴的固定角度、开窗、坡道自动写成当前项目事实。
- 白色是迈耶本人明确讨论过的**感知工具之一**，但不能成为“客户已确认的材料事实”。
- 不可用 `Richard Meier style` 作为提示词。
- Prompt 有可画的关系/性能表达，或资料严重不足则先问最多 3 个关键问题。
- 依次扫 Material / Structure / Facade / Geometry / Roof / Openings / Column-grid / Truss / Surface / Tech / Landscape / Furniture / Program。
- 未选 D8 不因提到“光线”就悄悄回到具体白色材料。

## HARD FAIL
- 任何无项目依据的“white ceramic panel / all-glass façade / rotating 22.5-degree grids / spiral ramp / triple concrete shells”作为图像正向事实。
