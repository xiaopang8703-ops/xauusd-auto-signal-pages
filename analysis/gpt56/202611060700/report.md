# GPT-5.6 黄金小时点位分析 202611060700

数据时间（UTC）：2026-11-06T07:06:58Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback_near_range_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4050.88-4064.83 | 4057.86 | 4082.57 | 4028.56, 4017.4, 4004.85 | MISSED_ENTRY_DISTANCE |
| B | sell | 4084.62-4096.05 | 4090.33 | 4109.77 | 4061.76, 4044.61, 4029.37 | WAIT_ENTRY_ZONE |
| C | sell | 4020.79-4029.37 | 4025.08 | 4036.99 | 4012.21, 3999.34, 3969.31 | WAIT_ENTRY_ZONE |
| D | buy | 4029.37-4036.99 | 4033.18 | 4013.93 | 4044.61, 4052.23, 4073.19 | WAIT_ENTRY_ZONE |
| E | buy | 4061.76-4073.19 | 4067.48 | 4052.23 | 4090.34, 4107.48, 4130.34 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Strong Sell、M15 为 Sell，且 MT5 价格低于 S1 4056.40，A 的主方向回调做空结构与当前偏空结构最一致。
- A 已触及入场区并出现确认，但当前 bid 4044.57 距确认价 4057.86 为 13.29，超过 max_distance 6.97，因此结构仍可跟踪但不能立即执行。
- 价格接近日内低点 4035.68，公开指标呈超卖且 StochRSI=100.0，追空过度延伸风险高；C 的 4020.79 下破回测尚未确认。
- D、E 均为逆主方向买入方案；D 的 rr_tp1 仅 0.593766，E 又未完成 4073.19 的突破回测，因此均弱于现有顺势卖出方案。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
