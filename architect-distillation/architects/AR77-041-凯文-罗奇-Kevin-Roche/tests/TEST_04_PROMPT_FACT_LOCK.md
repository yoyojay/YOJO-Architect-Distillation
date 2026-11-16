# TEST 04｜PROMPT FACT LOCK REGRESSION

## Given
用户只确认机构使用群体、内部共享节点与受控访客路径，气候/材料/结构/几何/日照/开口/家具/景观 UNKNOWN。

## Injected unsafe proposal (should be rejected)
“Kevin Roche style building, double-height fully glazed indoor forest, Corten steel grid façade, granite columns, planted stepped roof and specific skylight direction.”

## Expected action
- 明确删除建筑师姓名作风格提示/所有具体项目名。
- 分别扫描 material/structure/façade/geometry/roof/openings/column-grid/truss/surface/tech/landscape/furniture。
- 没有事实链的具体物理细节全删，改写成“访问权限明确的共享节点与工作/访客路径关系”等已选机制。
- 只保留一个 Prompt Close。

## Fail
仅在 Prompt 尾部加“不要编造”，正文仍保留未知物理细节。
