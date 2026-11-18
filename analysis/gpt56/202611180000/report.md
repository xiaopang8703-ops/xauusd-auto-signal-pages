# GPT-5.6 黄金小时点位分析 202611180000

数据时间（UTC）：2026-11-18T00:07:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3849.91-3857.07 | 3853.49 | 3866.67 | 3838.45, 3832.72, 3826.27 | MISSED_ENTRY_DISTANCE |
| B | sell | 3874.27-3882.87 | 3878.57 | 3893.19 | 3857.07, 3844.18, 3832.72 | WAIT_ENTRY_ZONE |
| C | sell | 3826.27-3832.72 | 3829.49 | 3838.45 | 3819.82, 3810.15, 3787.57 | WAIT_ENTRY_ZONE |
| D | buy | 3832.72-3838.45 | 3835.59 | 3821.11 | 3844.18, 3849.91, 3865.67 | WAIT_ENTRY_ZONE |
| E | buy | 3857.07-3865.67 | 3861.37 | 3849.91 | 3878.57, 3891.47, 3908.67 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 的 3849.91–3857.07 回抽区与日开盘价 3849.37、日内高点 3853.10 邻近，且符合 H1 Strong Sell、M15 Sell 与固定 sell 方向。
- A 已完成区域触及和确认，但当前决策价距确认基准 9.35，超过 max_distance=3.58；结构仍可跟踪，当前不可追价，故 executable_now=wait。
- ADX=14.34889 显示趋势力度有限，市场更接近偏空震荡；真实 H4 缺失且 C/E 均无已确认突破回测，因此突破质量为 unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_new_utc_day_range, verified_current_numeric_public_intraday_indicators, verified_live_oil_and_geopolitics
