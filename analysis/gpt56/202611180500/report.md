# GPT-5.6 黄金小时点位分析 202611180500

数据时间（UTC）：2026-11-18T05:05:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3791.38-3802.32 | 3796.85 | 3816.44 | 3773.88, 3765.13, 3755.29 | MISSED_ENTRY_DISTANCE |
| B | sell | 3826.57-3839.44 | 3833.0 | 3854.88 | 3800.83, 3781.53, 3764.37 | WAIT_ENTRY_ZONE |
| C | sell | 3754.73-3764.37 | 3759.55 | 3772.95 | 3745.09, 3730.63, 3696.89 | WAIT_ENTRY_ZONE |
| D | buy | 3764.37-3772.95 | 3768.66 | 3747.02 | 3781.53, 3790.11, 3813.7 | WAIT_ENTRY_ZONE |
| E | buy | 3800.83-3813.7 | 3807.26 | 3790.11 | 3833.0, 3852.31, 3878.05 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 structural_bias=sell 与 trend_down，固定回调做空几何比逆势 D/E 更符合当前结构。
- A 已触及入场区并出现闭合柱确认，但当前 distance=15.36 超过 max_distance=5.47，追空风险高，因此结构上继续跟踪、即时执行为 wait。
- C 尚无有效突破与回测确认且 rr_tp1=1.079104；B 虽同向且 rr_tp1=1.470293，但距离入场区 45.08，当前相关性弱于 A。
- true H4 不可用且同步公共技术证据缺失；美元与利率背景仅提供外部宏观偏空佐证，不能覆盖 MT5 执行锚。

公开数据覆盖：external_macro_only。

缺失证据：public_futures_technical_proxy, synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_day_range, verified_live_oil_and_geopolitics, verified_same_timeframe_public_technical_indicators
