# AR77-042｜Problem Routes Runtime

> 四条是 **AR77 项目问题 Route**，不是迈耶本人制定的历史 Period Route，也不是代表作套用范式。
> 只选择能够回应主要冲突的 **1 条 Primary Route**。不得由于某作品很有名就选择。

## R1｜DOMESTIC_PRIVACY_VIEW｜居住边界与观看

- **Trigger**：家庭/小规模居住或私密复合项目，真实矛盾在隐私、共同活动与景观/环境面之间。
- **核心问题**：先确定生活权利与安静区域，再给共享活动获得合理的朝向和观看路径。
- **Method**：Program Gradient → Site Order → Sectional Views → Verify privacy / weather.
- **Primary DNA 候选**：D2 / D4 / D6；D1 只有场地事实清楚才进入。
- **Plan/Section/Movement 痕迹**：私密/共同空间边界图、入口到公共停留处的视线剖面、邻里可视性分析。
- **适用边界**：高密邻里、敏感隐私、遮蔽与眩光限制可能推翻大开敞界面。
- **Failure**：将「面景观一侧全透明」当成自动答案；打破私密性或热工性能。
- **区别**：不是 R2 的公共展陈环流，也不是 R3 的多建筑场地协调。
- **证据**：Smith House 事务所项目档案；Saltzman House（S3/S12）。

## R2｜CULTURAL_LIGHT_JOURNEY｜展览文化中的采光与观看过程

- **Trigger**：博物馆、展厅、访客教育、文化机构，矛盾在公众路径、展示/学习、保护与可控自然光。
- **核心问题**：体验次序与运营分区如何同时保障展品、学习活动和清晰到达。
- **Method**：Program Gradient → Path/Stop → Zoned Light → Plan/Section test.
- **Primary DNA 候选**：D4 / D5 / D6；当功能秩序需要可启用 D3。
- **Plan/Section/Movement 痕迹**：展厅与公共厅关系、可访问路径、展品受光/眩光区、后勤独立性。
- **适用边界**：遮光收藏、疏散容量、无障碍同等体验和高峰运营是硬约束。
- **Failure**：把坡道或采光中庭做成主角、展厅品质和运营因此变差。
- **区别**：关注室内体验与收藏/公众关系；R4 聚焦对城市公共空间的贡献。
- **证据**：Atheneum、MACBA、MoMA Atheneum 草案（S4/S8/S10）。

## R3｜TOPOGRAPHIC_CAMPUS_ORDER｜地形与多建筑园区秩序

- **Trigger**：山地、多平台、多建筑机构/园区，场地地形、城市联系、跨组团运行共同主导。
- **核心问题**：让真实地形、交通、公共到达和机构功能决定秩序，避免网格自我表演。
- **Method**：Site Order → Primary Axis → Conditional Counterpoint → Campus Paths → Performance.
- **Primary DNA 候选**：D1 / D3 / D4 / D6。
- **Plan/Section/Movement 痕迹**：地形—城市联动轴、组团公共入口、运营与物流路径、竖向联系/疏散。
- **适用边界**：不得复制 Getty 的特定双轴角度、缆车或石材；工程/交通成本需验算。
- **Failure**：因为场地看似复杂就强加旋转双网格，或无法覆盖真实无障碍与应急到达。
- **区别**：R3 的原点是地形与组团协调，R2 的原点是内部展陈体验。
- **证据**：Getty Center 的迈耶本人文稿与官方建筑说明（S5/S6/S7）。

## R4｜URBAN_CIVIC_REPAIR｜文化建筑与城市公共地面的修复

- **Trigger**：城市更新与开放文化设施，真正矛盾在日常城市通路、公共场所缺失、文化设施的可达性和运营界面。
- **核心问题**：建筑是否不仅服务付费功能，还提供明确可用的城市公共连接、停留和可识别的进入权。
- **Method**：Public-rights map → Street/Entry → Daylight/Public-edge relation → Operational boundary.
- **Primary DNA 候选**：D7 / D4 / D5；根据城市边界激活 D1。
- **Plan/Section/Movement 痕迹**：对外广场/街道到门厅的公共路径、开闭时段、非付费访问边界。
- **适用边界**：产权、公共服务时间、治安、日晒雨、周边社区意见需现场确认。
- **Failure**：将「开放的白色前广场」视为自动改善城市；缺乏使用权与日常使用证明。
- **区别**：R4 核心是街区与公共权利，不是 R2 的内部展示秩序。
- **证据**：MACBA 官方建成描述及项目档案记载迈耶对 Raval 社区公共空间的思考（S8/S9）。

## Route Selector — 执行

1. 提取 1 主冲突（必须可验证）、至多 2 次冲突。
2. 用 R1–R4 的 Trigger 查找吻合 **问题** 的候选；权衡最大否决条件。
3. **选1条**：主问题是居住/隐私→R1；展陈/受光与访客流程→R2；地形与组团综合→R3；街区公共权利→R4。
4. 若 R2 与 R4 同时适用，比较：首先需要解决的是馆内收藏/环流，还是馆外公共空间；不可判时 `ROUTE_UNRESOLVED`。
5. 若 R2 与 R3 同时适用，比较：地形/机构组团是否足以否决单馆组织；不可判则先索要地形与交通关系。
6. `Route Output = Primary / Trigger Evidence / Rejected Alternatives / Main Risk / Test / Return Condition`。
7. 其他 Route 的特殊 DNA 不得以「借用」之名悄然回流；若主冲突变化，必须正式重跑路线选择。
