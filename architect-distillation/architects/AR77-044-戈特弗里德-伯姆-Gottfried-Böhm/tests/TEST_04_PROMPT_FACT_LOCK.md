# TEST 04｜PROMPT FACT LOCK REGRESSION

**Fixture**：项目只确认人行连接与遗产建筑关系，尚无结构材料、景观及立面设计。
**Inject unverified prompt terms**：`exposed concrete, zigzag folded roof, pointed tower, colored clerestories, rough stone, steel truss, precise column grid, reflective pool, timber benches`。

**Expected**：
- 逐项追溯 materials / structure / façade / geometry / roof / opening / walls / column grid / truss / finish / technical components / landscape / planting / furniture。
- 不能证实的逐项删除/改写为 relationship/performance wording。
- Rejected Strategy 和未选 DNA 不得以负向/增强词偷偷进 Prompt。
- 一轮只生成 1 个 Concept Impression Prompt。
- Prompt failure only rewrites Prompt; does not falsely mark Runtime FAIL。
