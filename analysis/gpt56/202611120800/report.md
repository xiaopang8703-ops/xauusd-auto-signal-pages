# GPT-5.6 黄金小时点位分析 202611120800

数据时间（UTC）：2026-11-12T08:08:15Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pressure；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3966.13-3973.15 | 3969.64 | 3982.57 | 3954.89, 3949.28, 3942.96 | MISSED_ENTRY_DISTANCE |
| B | sell | 3989.99-3998.41 | 3994.2 | 4008.51 | 3973.15, 3960.51, 3949.28 | WAIT_ENTRY_ZONE |
| C | sell | 3942.96-3949.28 | 3946.12 | 3954.89 | 3936.64, 3927.16, 3905.04 | WAIT_ENTRY_ZONE |
| D | buy | 3949.28-3954.89 | 3952.09 | 3937.9 | 3960.51, 3966.13, 3981.57 | MISSED_ENTRY_DISTANCE |
| E | buy | 3973.15-3981.57 | 3977.36 | 3966.13 | 3994.2, 4006.83, 4023.67 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 几何与 structural_bias=sell 及 1H Strong Sell 一致，且 entry_zone 已触及、M15 确认已成立。
- MT5 bid=3960.46 已距 A expected_fill_price=3969.64 达 9.18，超过 max_distance=3.51，当前属于 MISSED_ENTRY_DISTANCE，故只能 wait，不能追价。
- RSI_14=24.77、ADX_14=82.81，且价格接近日内低点 3954.77，新增卖出存在较高过度延伸风险。
- C 与 E 的 breakout/retest 均未确认；D 虽有反转确认记录，但 rr_tp1=0.593376，固定几何质量最弱。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
