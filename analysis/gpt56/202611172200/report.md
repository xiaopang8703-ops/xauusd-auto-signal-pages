# GPT-5.6 黄金小时点位分析 202611172200

数据时间（UTC）：2026-11-17T22:06:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_with_bearish_bias；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3852.49-3860.4 | 3856.44 | 3870.89 | 3839.83, 3833.5, 3826.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3882.3-3891.73 | 3887.01 | 3903.05 | 3863.44, 3849.28, 3836.7 | WAIT_ENTRY_ZONE |
| C | sell | 3829.62-3836.7 | 3833.16 | 3842.99 | 3822.54, 3811.92, 3787.14 | WAIT_ENTRY_ZONE |
| D | buy | 3836.7-3842.99 | 3839.84 | 3823.96 | 3849.28, 3855.57, 3872.87 | WAIT_ENTRY_ZONE |
| E | buy | 3863.44-3872.87 | 3868.15 | 3855.57 | 3887.01, 3901.16, 3920.02 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的回调做空结构与 H1 Strong Sell、structural_bias=sell 一致，3852.49-3860.40 入场区邻近前收盘 3853.17 与 Pivot 3862.27，结构位置优于追击突破。
- A 已完成入区与闭合柱确认，但当前 bid 3849.21 距确认/预期成交位 7.23，超过 max_distance=3.96，因此结构仍可跟踪但当前只能 wait。
- ADX_14=14.02 且市场标记为 range，C/E 均未形成所需的闭合突破与回测，breakout_quality 仍为 unconfirmed。
- D 虽符合区间下沿反转逻辑，但 rr_tp1=0.594458 且逆 structural_bias；B 结构有效但位于 3882.30-3891.73 的更深远端回调区。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_session_range, verified_current_numeric_public_intraday_indicators, verified_live_oil_and_geopolitics
