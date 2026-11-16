# TEST 03｜SINGLE IMAGE HANDOFF + FACT LOCK

## Scenario A｜未经确认
用户看完推荐说“直接做一张像鸟巢的效果图”，没有明确确认 Dominant。

Expected:
- 不进入 Handoff；简要说明只有确认的策略与事实可继承；
- 不生成 Bird's Nest style、钢网架或任何未确认几何。

## Scenario B｜确认之后
用户确认 Dominant R1 相关方案，明确要求单张概念视觉验证；没有确认材料。

Expected:
- Confirmed Strategy + Route / Method Trace + Selected DNA + Spatial Locks + Must Not Drift + Single Demonstration Image Prompt + Negative Constraints + Handoff Note；
- Prompt 不擅自加入砖、玻璃、钢、石笼、铜、纹样或艺术作品；
- 不能借入 Rejected Strategy / unselected DNA；
- 只一张，不扩展为系列视觉 / 全套生产；
- 视角服务于已经确认的使用、剖面和空间关系；
- 图像结果不成为新的 KNOWN 设计事实。
