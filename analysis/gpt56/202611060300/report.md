# GPT-5.6 黄金小时点位分析 202611060300

数据时间（UTC）：2026-11-06T03:07:43Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_at_support；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4074.15-4086.87 | 4080.51 | 4103.13 | 4053.81, 4043.64, 4032.19 | WAIT_ENTRY_ZONE |
| B | sell | 4115.21-4131.45 | 4123.33 | 4150.94 | 4082.73, 4058.38, 4036.73 | WAIT_ENTRY_ZONE |
| C | sell | 4024.56-4036.73 | 4030.64 | 4047.56 | 4012.39, 3994.13, 3951.54 | WAIT_ENTRY_ZONE |
| D | buy | 4036.73-4047.56 | 4042.14 | 4014.82 | 4058.38, 4069.2, 4098.97 | WAIT_ENTRY_ZONE |
| E | buy | 4082.73-4098.97 | 4090.85 | 4069.2 | 4123.33, 4147.69, 4180.17 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- MT5 报价 4058.34/4058.42 已逼近日低 4056.11 与 S1 4056.40；在 H1/M15 均为 Strong Sell 的背景下，A 的 4074.15-4086.87 首次顺势回撤结构优于当前位置追空。
- A 尚未触及入场区，距 expected_fill_price 4080.51 为 22.17，超过 max_distance 6.36；即使 confirmation_crossed=true，zone_touched=false 仍不满足 PULLBACK_FAIL_REJECT，因此只能 wait。
- 当前位于日内支撑附近且自开盘显著下跌，延伸风险高；C 的下破及回测尚未形成，true H4 缺失且公共宏观覆盖不完整，但这些不足尚未构成对 A 固定结构的 veto。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
