# GPT-5.6 黄金小时点位分析 202611052100

数据时间（UTC）：2026-11-05T21:05:13Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_continuation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4094.51-4104.88 | 4099.69 | 4118.32 | 4077.93, 4069.63, 4060.3 | MISSED_ENTRY_DISTANCE |
| B | sell | 4129.76-4142.2 | 4135.98 | 4157.13 | 4104.88, 4086.22, 4069.63 | WAIT_ENTRY_ZONE |
| C | sell | 4060.3-4069.63 | 4064.97 | 4077.93 | 4050.97, 4036.98, 4004.32 | WAIT_ENTRY_ZONE |
| D | buy | 4069.63-4077.93 | 4073.78 | 4052.84 | 4086.22, 4094.51, 4117.32 | WAIT_ENTRY_ZONE |
| E | buy | 4104.88-4117.32 | 4111.1 | 4094.51 | 4135.98, 4154.64, 4179.52 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 与 H1 Sell、M15 Strong Sell 及 bearish_continuation 一致；已触及 4094.51-4104.88，M15 收盘 4098.96 满足 PULLBACK_FAIL_REJECT。
- 当前 MT5 bid 4086.17 距确认价 13.52，超过 max_distance 5.18，追空风险高，因此结构上继续跟踪 A，但 executable_now=wait。
- C 与 E 的 BREAKOUT_RETEST_FAIL 均未完成突破确认；D 逆主方向且 rr_tp1 仅 0.594078。
- true H4 不可用且公共证据覆盖不完整，但未形成足以否定 A 固定结构的同时间正面冲突。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
