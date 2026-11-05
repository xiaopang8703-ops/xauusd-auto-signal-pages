# GPT-5.6 黄金小时点位分析 202611050900

数据时间（UTC）：2026-11-05T09:04:58Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：高位震荡偏多；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4127.96-4134.3 | 4131.13 | 4112.46 | 4142.45, 4151.51, 4169.63 | WAIT_CONFIRMATION |
| B | buy | 4113.46-4120.71 | 4117.09 | 4101.59 | 4127.96, 4142.45, 4151.51 | MISSED_ENTRY_DISTANCE |
| C | buy | 4142.45-4151.51 | 4146.98 | 4134.3 | 4169.63, 4192.28, 4214.93 | WAIT_ENTRY_ZONE |
| D | sell | 4138.45-4142.45 | 4140.45 | 4165.1 | 4134.3, 4127.96, 4120.71 | WAIT_ENTRY_ZONE |
| E | sell | 4113.46-4120.71 | 4117.09 | 4127.96 | 4091.72, 4086.29, 4059.11 | MISSED_ENTRY_DISTANCE |

排序：C > A > B > E > D

研究理由：

- C 顺应固定 buy 结构，RR TP1=1.786278，并要求 M15 完成突破 4151.51 后回测，能避免高位首根追涨。
- MT5 现价 4129.72/4129.81 尚低于 C 入场区 4142.45-4151.51，且 zone_touched=false、confirmation_crossed=false，因此当前只能 wait。
- H1 公开代理为 Strong Buy，但 RSI14=71.371671、日内已接近 4147.05 高点，过度延伸风险高；true H4 缺失，不能据此确认更高周期突破。
- A 虽已触及入场区且距离合格，但 M15 收盘 4126.72 尚未重新站上 4131.13，且 RR TP1=0.60632，结构质量低于等待确认的 C。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_usd_nominal_and_real_treasury_yields, fresh_timestamped_oil_and_primary_inflation_release, independently_verified_election_results_and_geopolitical_resolution, live_market_implied_fed_probabilities, public_quote_display_timezone_verified, public_technical_selected_timeframe_and_summary_conflict_resolved, synchronized_public_spot_vs_mt5_quote, verified_high_impact_event_times_and_blackout
