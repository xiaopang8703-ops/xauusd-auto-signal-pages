# GPT-5.6 黄金小时点位分析 202611060800

数据时间（UTC）：2026-11-06T08:05:13Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4063.21-4071.99 | 4067.6 | 4083.53 | 4049.17, 4042.14, 4034.24 | WAIT_ENTRY_ZONE |
| B | sell | 4093.07-4103.61 | 4098.34 | 4116.26 | 4071.99, 4056.19, 4042.14 | WAIT_ENTRY_ZONE |
| C | sell | 4034.24-4042.14 | 4038.19 | 4049.17 | 4026.34, 4014.49, 3986.84 | MISSED_ENTRY_DISTANCE |
| D | buy | 4042.14-4049.17 | 4045.65 | 4027.92 | 4056.19, 4063.21, 4082.53 | MISSED_ENTRY_DISTANCE |
| E | buy | 4071.99-4082.53 | 4077.26 | 4063.21 | 4098.34, 4114.15, 4135.23 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Strong Sell、M15 为 Buy，符合 bearish_pullback；A 的首次回调失败做空几何与固定 sell 结构最匹配。
- 现价 4056.15 接近 MT5 S1 4056.40 和日内低点 4035.68，直接追空过度延伸风险高，等待回抽 A 区域更合理。
- A 尚未触及 4063.21-4071.99 入场区，且距确认价 11.45 超过 max_distance 4.39，因此当前只能 wait。
- C 与 E 均无已完成的有效突破回测；D 虽有扫低回收迹象，但逆主方向且 rr_tp1 仅 0.594473。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
