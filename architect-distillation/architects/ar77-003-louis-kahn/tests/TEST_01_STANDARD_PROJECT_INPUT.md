# TEST 01｜标准项目表项目调用

PASS:

- [ ] Input Validation 先发生
- [ ] UNKNOWN 不被自动补成事实
- [ ] 有 FIT / PARTIAL FIT / NOT FIT
- [ ] 先写 Institutional Wish
- [ ] 3–5 Core Spatial Conflicts
- [ ] 明确 Primary Route
- [ ] 不把六条 Route 全部混合
- [ ] 建立 Room Society
- [ ] 选择 4–7 DNA
- [ ] 显式协调 ROOM / SERVICE / LIGHT + STRUCTURE
- [ ] A/B/C 因果不同
- [ ] 当代校正存在
- [ ] 有建筑师确认点
- [ ] 给出下一步 1–2 张图
- [ ] 不自动进入完整出图

HARD FAIL:

- 直接给 Louis Kahn style
- 复制 Exeter / Salk / Kimbell / Dhaka
- 先做厚重外壳再填房间
- 不建立房间社会
- 服务系统缺失
- 结构与光不参与空间秩序
- 三案只是换造型

## v1.3 Recommendation / DNA Gate

- [ ] 推荐只能是单一策略，或一个主策略 + 另一个策略的一个有限机制
- [ ] 推荐最多只能涉及两个策略，严禁 A+B+C 同时出现
- [ ] 未进入 Selected DNA 的 DNA 不得在策略 / 推荐中重新作为核心或补充机制出现
- [ ] 推荐仍回答同一个 Institutional Wish
- [ ] 推荐不破坏 Room Society
- [ ] ROOM / SERVICE / LIGHT + STRUCTURE 继续协调
- [ ] 不引入未选择 Route

HARD FAIL:
- 推荐同时引用 A、B、C
- 未选 DNA 以“子机制 / 补充机制”方式重新进入
- 推荐换掉 Institutional Wish
- 推荐破坏 Room Society 或 Three Orders
- 未选 Route 后门进入


## v1.4 Regression Gate｜三策略混合错误

以下推荐形式必须判定 HARD FAIL：

```text
以 B 为主
+ 借用 C 的一个机制
+ 再借用 A 的一个机制
```

即使第三个策略只作为“连接 / 光 / 门槛 / 服务补充”，仍属于第三策略正向回流。

正确示例：

```text
Dominant Strategy: B
Borrowed Mechanism: C 的一个有限机制
Rejected for Recommendation: A
```

被 Reject 的 A 不得再进入 Why / Keep / Next / Summary / Prompt。


## v1.4 Prompt Fact Lock Regression

HARD FAIL:

- Prompt 自动把未知材料写成 brick / stone / concrete
- Prompt 自动生成 giant circular openings / geometric apertures
- Prompt 自动生成未经确认的 vault / water axis / roof geometry
- Prompt 为了“像路易·康”补充纪念性厚重形式

PASS:

- 未确认材料保持中性表达
- 未确认开口 / 拱顶 / 墙体使用 light / privacy / depth / structure 等关系表达
- 每个具体视觉描述都能追溯到 KNOWN / Institutional Wish / Room Society / Three Orders / Dominant / Borrowed / Selected DNA / verified site-climate-light evidence
