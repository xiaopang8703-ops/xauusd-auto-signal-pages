# GPT-5.6 黄金小时点位分析 202611051700

数据时间（UTC）：2026-11-05T17:09:28Z；authority=none。

跟踪方案：A/buy；executable_now=yes；veto=false。

市场状态：高波动偏多区间；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4118.77-4128.88 | 4123.83 | 4094.68 | 4141.87, 4156.31, 4185.19 | READY_TO_SUBMIT_DRY_RUN |
| B | buy | 4095.68-4107.22 | 4101.45 | 4077.35 | 4118.77, 4141.87, 4156.31 | MISSED_ENTRY_DISTANCE |
| C | buy | 4141.87-4156.31 | 4149.09 | 4128.88 | 4185.19, 4221.29, 4257.39 | WAIT_ENTRY_ZONE |
| D | sell | 4137.87-4141.87 | 4139.87 | 4177.97 | 4128.88, 4118.77, 4107.22 | WAIT_ENTRY_ZONE |
| E | sell | 4095.68-4107.22 | 4101.45 | 4118.77 | 4061.02, 4052.36, 4009.03 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > D > E

研究理由：

- A 与 H1 Strong Buy、M15 Buy 及固定 buy 结构一致；已触及 4118.77-4128.88，M15 收盘 4127.52 完成确认，当前 ask 4121.71 仍在区间且 distance=2.12 未超过 max_distance=5.05。
- 价格接近日内高点 4147.05，StochRSI=100 且 ADX14=51.99，追高和回撤风险为中等，但尚未形成否决 A 的同时间结构冲突。
- C 的 RR 更优但 4156.31 突破与回测均未确认，因此只适合后续跟踪；B、D、E 当前几何或确认质量弱于 A。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_inflation_release_and_timestamped_oil, fresh_primary_usd_nominal_and_real_yields, live_market_implied_fed_probabilities, primary_boe_decision_election_and_iran_resolution, synchronized_public_spot_vs_mt5, verified_display_quote_timezones, verified_event_times_and_blackout, verified_selected_public_technical_timeframe
