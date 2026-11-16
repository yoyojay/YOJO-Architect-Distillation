# AR77-042｜SINGLE IMAGE VISUAL HANDOFF

## 定位
仅将客户**已经明确确认**的空间判断交给**一张**概念图用于验证。不同于项目分析结尾的 Concept Impression Prompt；不是图像上传识别、效果图批量生产、3D 模型控制或施工成果。

## Activation Gate (ALL REQUIRED)
1. 完整项目分析已完成，核心事实仍有版本化记录。
2. 客户**明确确认** `Dominant Strategy`，它能独立回应主冲突。
3. `Borrowed Mechanism` 是 NONE 或只来自另一策略的一个有限机制，并被客户确认。
4. `Primary Route`、`Selected DNA`、已验证地形/气候/光线及空间边界明确。
5. 已审查安全/无障碍/结构/消防/运营等风险，不把未知变成完成事实。
6. 用户要求「单张概念图验证」；若缺确认则只问 1–3 项问题，不自行选择。

## Output Contract
### 01｜Confirmed Facts
每项写信息来源/确认状态；UNKNOWN 不进入图像描述。

### 02｜Confirmed Strategy / Borrow
仅 Dominant + 可选一个 Borrowed（注明不带入原策略其他内容）；Rejected 只写在禁止漂移区，不进正向 Prompt。

### 03｜Primary Route / Selected DNA
逐条说明必须看见的 `Route → DNA → Plan/Section/Movement Trace`，不包含未选项。

### 04｜Spatial Locks
至少3个**可目测**但不强迫造型的条件，例如已确认的使用分区、入口—停驻关系、保留的真实视线、经核验的日光/遮蔽目标；每条都指向确认事实或已选 DNA。

### 05｜Must Not Drift
不能新增白色建筑表皮、全玻璃幕墙、跨层坡道、旋转双网格、雕塑曲墙、著名案例体量，不能用 `Richard Meier style`、Getty、Atheneum、MACBA、Smith House 等名字作为图像参考。

### 06｜Prompt Fact Lock
逐项扫描材料/结构/立面/几何/屋顶/开口/柱网/桁架/表面/技术构件/景观/家具。若无确认依据，删除具体细节或改写为空间关系/性能描述。无法完成扫描，拒绝 Handoff。

### 07｜One Image Prompt
以一个最能检验 Dominant 因果链的视角（外部/室内/空间剖透视中选1），写当前项目类型、可核查的场地事实、已确认组织、人的活动/路径与可观察的空间痕迹。`realistic architectural concept study` 可写，不新增外形事实。只输出 **一个** image prompt。

### 08｜Negative Constraints
只针对该项目具体误读：禁止复制历史作品、风格化装饰、违反已确认公共/私密/光线和路线的元素。

### 09｜Handoff Note
这是一张初步空间机制验证图，不是全流程可视化、规范审核或建造文件。结果若和已确认空间事实矛盾，返回平剖面和 Prompt Fact Lock 修正；不得让强视觉效果反过来冻结尚未验证的设计。
