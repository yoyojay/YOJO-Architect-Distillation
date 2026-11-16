# AR77-041 | Project-Problem Route Runtime
以下 Routes 是依据来源事实构造的**当代项目调度分类**，不是 Kevin Roche 本人历史分期或命名。各 Route 只能经触发条件选择，不可按外观相似性套用。

## R1 | CIVIC_COMMON_INTERIOR — 机构内核转成公共/共同场所
- **Trigger**：机构内多个使用群体有交集，但公共与内部工作易互相干扰；需要明确社会使命的空间。
- **Core conflict**：共享关系如何成立而不越过安保、私密、气候及运营边界？
- **Method**：定参与者与访问时段 → 判断公共空间能否实际被使用 → 组织内部使用单元环绕或邻接共同交流场所 → 通过剖面与动线控制透明/隔离等级。
- **Primary DNA**：D1、D2、D5；可按证据补 D7。
- **Proof**：公开区与许可区平剖路径图、运维时段图、声学/热工指标。
- **Applicability limits**：不适用于必须全封闭无访客且空间收益不足的项目；不强制封闭高大中庭。
- **Failure risk**：视觉上壮观但社会上不可达；高体积空间能源负担；机构工作被干扰。
- **Distinct from R2**：R1 以**机构共同生活的内部节点**为主因；R2 以**建筑—公共地面**为主因。
- **Evidence**：[E1/E2/E4/E9 KNOWN; community-node transfer SUPPORTED INTERPRETATION]

## R2 | MUSEUM_PARK_EXCHANGE — 公共文化与城市/景观共同组织
- **Trigger**：博物馆/文化/社区建筑同时承担公共开放空间、街区连通或户外活动。
- **Core conflict**：门票/展陈/保藏与免费可达的城市公共生活如何并存？
- **Method**：先定义免费通行范围与开放时段 → 将场地与建筑地面视为共同编排对象 → 区分展品安全路线、城市路径与运营服务 → 以可检验界面/层级组织差异。
- **Primary DNA**：D1、D3、D5；可按证据补 D6。
- **Proof**：城市场地步行图、公共/收费区矩阵、无障碍断面、排水维护路径。
- **Applicability limits**：无公共运营承诺时不自动生成城市公园；热/雨/消防需优先。
- **Failure risk**：公园沦为只可看的景观；屋顶渗漏/维护过大；展陈被穿越干扰。
- **Distinct from R1**：R2 的首要矛盾在**城市地表与文化设施共享**，不是室内机构交往。
- **Evidence**：[E1/E5/E6 KNOWN; routing abstraction SUPPORTED INTERPRETATION]

## R3 | INSTITUTIONAL_GROWTH — 复杂机构的连续改造与增建
- **Trigger**：大型馆舍/校园/研究机构需要分期扩建、既有遗产衔接、多入口与人群导航。
- **Core conflict**：新增功能如何增容却不破坏既有机构可读性及历史价值？
- **Method**：调查已有空间骨架 → 标识不能更动的构件/历史区域 → 测试节点和主次路径 → 在可撤回的增建/替代方案中检验流线与设备可升级性。
- **Primary DNA**：D1、D4、D5、D6；按实际复杂度只保留必要项。
- **Proof**：新旧连接图、分期表、容量/疏散模拟、通行与维护连续性。
- **Applicability limits**：单体新建且无成长需求不应生硬使用此 Route。
- **Failure risk**：计划中的连接最终无法实施；价值高的原有建筑被牺牲；混乱寻路。
- **Distinct from R4**：R3 处理**既有机构系统的时间和多期连接**；R4 处理**当下工作人群的环境与协作**。
- **Evidence**：[E3/E7 KNOWN; staged routing SUPPORTED INTERPRETATION]

## R4 | WORKPLACE_HUMAN_ENVIRONMENT — 工作需求与协作环境协同
- **Trigger**：总部、园区、研究办公或机构工作空间需要改善人员工作条件、协作与识别。
- **Core conflict**：工作效率与协作/身份认同如何避免成为等级化、不被使用的纪念性空间？
- **Method**：根据真实团队、访客与工作流程重组接触点 → 对照日照、噪声、私密与密度 → 测试公共/半公共支持空间，先以运营成果判断，不设唯一标志形式。
- **Primary DNA**：D1、D2、D7；必要时增 D5。
- **Proof**：工位/团队邻接、会面时间分配、声学、能源与维护费用。
- **Applicability limits**：不强制玻璃办公、巨型门厅或植物中庭；受控实验/高度机密机构需更严格。
- **Failure risk**：将视觉通透误判为社交质量；空间浪费与维护负担。
- **Distinct from R1**：R4 面向工作绩效与内部组织，R1 首先面向机构公共使命。
- **Evidence**：[E1/E2/E4/E8 KNOWN; workplace logic SUPPORTED INTERPRETATION]

## Route selection algorithm
1. 从项目事实找**最具否决权的主要矛盾**；若多个等权，用用户业务和公共义务排优先级。
2. 从 R1–R4 只选 1 个 Primary；次要路线只能作为对比参照，不可导入未选 DNA。
3. 同时触发 R1 与 R2 时：若可证明日常公众通行的首要问题是城市/室外地面，选 R2；若核心是机构内不同使用者的相遇与访问治理，选 R1。
4. 同时触发 R3 与 R4 时：若既有遗产与分期是不可改变的主问题，选 R3；否则按实际职场任务选 R4。
5. 若没有匹配 Route，标 `ROUTE_UNRESOLVED`，直接用 Method 基础流程进行谨慎分析，禁止伪造历史 Route。
