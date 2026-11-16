# AR77-041｜SINGLE IMAGE VISUAL HANDOFF
## 仅在明确确认策略后进行单张空间关系可视化验证

**本模块不是通用效果图生产，也不是项目图纸审查。** 若用户尚未明确确认 Dominant Strategy 和 Selected DNA，返回 `HANDOFF BLOCKED: awaiting architect confirmation`，直接询问确认；不得拿先前概念 Prompt 充当已确认交接。

### Activation verification
1. 用户明确确认主策略；
2. Primary Route 与 Selected DNA 已确定并未被更改；
3. 若有 Borrowed Mechanism，恰好来自另一策略的一个有限、可剥离机制；
4. 项目事实清单 KNOWN / NEED VERIFY 已核对；
5. 用户确实要求单张视觉验证。

### Output (required)
**01｜Confirmed Strategy**：独立成立的主策略，解释其因果，不可写成“几个方向融合”。
**02｜Selected Route / Method**：单一 Primary Problem Route，说明启动矛盾和方法链。
**03｜Selected DNA**：保留原选中名单及空间操作，不增加未选 DNA。
**04｜Spatial Locks**：计划/剖面/权限/城市关系里必须保持的可验证空间关系。
**05｜Must Not Drift**：禁止复制福特基金会的通高园庭、奥克兰博物馆的台地轮廓、馆舍复制；禁止无来源材料、幕墙、屋顶、柱网、家具和植物。
**06｜Single Demonstration Image Prompt**：一条单图 Prompt，描述真实项目类别和经用户确认的空间关系，视角只要求看得出关键使用/通行机制。只列已证实现场/气候/光照。
**07｜Negative Constraints**：项目相关的禁止误解与事实锁，不是通用装饰禁词清单。
**08｜Handoff Note**：这是一张概念验证图，只测已确认设计判断进入可视化后是否成立，不是整套视觉生产与施工图。

### Pre-render Fact Lock
按材料 / 结构 / 立面 / 几何 / 屋顶 / 开口 / 柱网 / 桁架 / 表面 / 技术构件 / 景观 / 家具逐项查是否可追溯：
`Confirmed Facts + Confirmed Route-Method + Confirmed Dominant + ≤1 Borrowed + Confirmed Selected DNA + verified site/climate/light`。
若任何项只是为了“看起来像 Roche”，立即删除或改写为关系/性能语言。

不得借此补充 UNKNOWN 或引入 Rejected Strategy。发现确认后关键事实变化，撤销旧的 Handoff，返回项目确认。
