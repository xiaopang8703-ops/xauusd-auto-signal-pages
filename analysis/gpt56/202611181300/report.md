# GPT-5.6 黄金小时点位分析 202611181300

数据时间（UTC）：2026-11-18T13:05:18Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3762.27-3771.2 | 3766.73 | 3782.91 | 3747.97, 3740.83, 3732.79 | MISSED_ENTRY_DISTANCE |
| B | sell | 3792.62-3803.33 | 3797.97 | 3816.18 | 3771.2, 3755.12, 3740.83 | WAIT_ENTRY_ZONE |
| C | sell | 3732.79-3740.83 | 3736.81 | 3747.97 | 3724.75, 3712.69, 3684.55 | WAIT_ENTRY_ZONE |
| D | buy | 3740.83-3747.97 | 3744.4 | 3726.36 | 3755.12, 3762.27, 3781.91 | MISSED_ENTRY_DISTANCE |
| E | buy | 3771.2-3781.91 | 3776.55 | 3762.27 | 3797.97, 3814.04, 3835.46 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Strong Sell、M15 Strong Sell 与 ADX_14=57.51833 的空头延续结构，且已完成 entry_zone 触及及 PULLBACK_FAIL_REJECT 确认。
- 当前 MT5 bid=3755.08 距 A 的 confirmation_close=3743.64 为 11.65，超过 max_distance=4.46，因此只能 wait，不能追价。
- RSI_14=20.942032、Stoch_RSI=0.0，且价格接近日内低点 3742.85，显示高过度延伸风险；C 尚未完成 3732.79 下破与回测确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_full_day_range, verified_current_oil_and_geopolitics, verified_current_same_timeframe_public_indicators
