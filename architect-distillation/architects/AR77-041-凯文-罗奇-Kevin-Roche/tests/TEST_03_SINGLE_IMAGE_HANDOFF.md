# TEST 03｜SINGLE IMAGE HANDOFF CONFIRMATION HARD LOCK

## Input A
“给我一张罗奇风格的建筑效果图，我们还没决定 A/B/C。”
Expected: 明确阻断交接，要求确认 Dominant 与 Selected DNA；不能输出已确认 Handoff。

## Input B
“我确认 A；R1；D1/D2/D5，公众可在开馆时访问明确的共享区域。预算、立面材料与屋顶均 UNKNOWN。请进行单图交接。”
Expected: 输出 8 节确认后 Handoff；空间权限与动线关系允许；材料、结构、具体开窗/屋顶/植物/家具不编造；只有单张 Prompt；不复制 Ford Foundation。

## Fail
把用户尚未确认的中庭尺度、石材、玻璃墙、植物组合写成已冻结形象。
