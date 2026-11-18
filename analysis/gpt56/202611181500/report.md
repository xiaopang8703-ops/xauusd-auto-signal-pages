# GPT-5.6 黄金小时点位分析 202611181500

数据时间（UTC）：2026-11-18T15:06:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3767.95-3778.19 | 3773.07 | 3791.48 | 3751.57, 3743.38, 3734.16 | MISSED_ENTRY_DISTANCE |
| B | sell | 3802.77-3815.06 | 3808.91 | 3829.81 | 3778.19, 3759.76, 3743.38 | WAIT_ENTRY_ZONE |
| C | sell | 3734.16-3743.38 | 3738.77 | 3751.57 | 3724.94, 3711.11, 3678.84 | WAIT_ENTRY_ZONE |
| D | buy | 3743.38-3751.57 | 3747.48 | 3726.78 | 3759.76, 3767.95, 3790.48 | WAIT_ENTRY_ZONE |
| E | buy | 3778.19-3790.48 | 3784.34 | 3767.95 | 3808.91, 3827.35, 3851.93 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 回调几何最符合 H1 Strong Sell、tactical sell 与 M15 Buy 所表示的空头回抽结构，且 3767.95-3778.19 接近 S3 3773.1。
- A 已触及入场区并完成 PULLBACK_FAIL_REJECT，但当前 decision_price 3759.72 距 expected_fill_price 13.35，超过 max_distance 5.12，因此只能等待而不能立即执行。
- 价格已从 daily_open 3849.37 跌至 3759.72、位于 S3 下方并接近日内低点，追空过度延伸风险高；C 尚未完成 3734.16 下破及有效回测。
- D、E 均为逆当前 sell 结构的 buy 方案；D 的 rr_tp1 仅 0.593237，E 也未形成 3790.48 上破回测确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_full_day_range, verified_current_oil_and_geopolitics, verified_current_same_timeframe_public_indicators
