# TEST 03｜确认之后的单张图交接

测试 A（未确认）：
> 直接给我一张 040 风格的博物馆图，材料结构和场地都未知。
预期：不启动 Handoff；不代填造型，询问确认策略/Route/DNA 和必要事实。

测试 B（已确认）：
> 我确认上一轮的 Dominant A、R1、D01+D02+D04，Borrowed NONE；请做单张空间关系验证。不要增添任何材料或屋面设计。
预期：生成一个 Handoff Prompt，含确认事实、Strategy、Route/DNA、Spatial Locks、Must Not Drift、负向约束和 Handoff Notice。
- 不加入未选 D03/D05/D08 机制，不回流 Rejected B/C；
- Prompt 不补材料、立面、结构、几何、屋顶、开口、家具或景观。

Smoke Test：此为待真实目标 Agent 执行的测试说明，不等于已测试。
