# GPT-5.6 黄金小时点位分析 202611061100

数据时间（UTC）：2026-11-06T11:08:13Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4072.46-4080.65 | 4076.56 | 4091.48 | 4059.36, 4052.81, 4045.43 | MISSED_ENTRY_DISTANCE |
| B | sell | 4100.31-4110.14 | 4105.22 | 4121.94 | 4080.65, 4065.91, 4052.81 | WAIT_ENTRY_ZONE |
| C | sell | 4045.43-4052.81 | 4049.12 | 4059.36 | 4038.05, 4026.98, 4001.15 | WAIT_ENTRY_ZONE |
| D | buy | 4052.81-4059.36 | 4056.09 | 4039.53 | 4065.91, 4072.46, 4090.48 | WAIT_ENTRY_ZONE |
| E | buy | 4080.65-4090.48 | 4085.57 | 4072.46 | 4105.23, 4119.97, 4139.63 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 回调拒绝结构最符合 H1 Sell、M15 tactical sell 与当前 bearish_continuation，但其确认后 decision_price 距 expected_fill_price 10.69，超过 max_distance 4.1，禁止追价并应等待新触发。
- 当前 MT5 mid 4065.91 已接近 S1 4056.4，且明显低于 daily_open/prev_close 4096.87/4096.86，继续即时卖出具有较高过度延伸风险。
- C 的 4045.43 向下突破及回测尚未确认；D/E 为逆主方向 buy，D 的 rr_tp1 仅 0.592995，结构质量低于 A/B/C。
- true H4 不可用，公开技术证据仅低置信度且关键事件窗口未核实，因此不把 advisory public evidence 提升为立即执行依据。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
