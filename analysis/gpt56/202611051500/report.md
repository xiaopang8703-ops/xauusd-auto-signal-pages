# GPT-5.6 黄金小时点位分析 202611051500

数据时间（UTC）：2026-11-05T15:07:28Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：range_bullish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4111.21-4117.82 | 4114.51 | 4095.1 | 4126.32, 4135.77, 4154.67 | WAIT_CONFIRMATION |
| B | buy | 4096.1-4103.65 | 4099.88 | 4083.76 | 4111.21, 4126.32, 4135.77 | MISSED_ENTRY_DISTANCE |
| C | buy | 4126.32-4135.77 | 4131.05 | 4117.82 | 4154.67, 4178.3, 4201.92 | MISSED_ENTRY_DISTANCE |
| D | sell | 4122.32-4126.32 | 4124.32 | 4149.95 | 4117.82, 4111.21, 4103.65 | MISSED_ENTRY_DISTANCE |
| E | sell | 4096.1-4103.65 | 4099.88 | 4111.21 | 4073.42, 4067.75, 4039.4 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- H1 为 Buy、M15 为 Strong Sell，符合 bullish_pullback；A 是顺结构方向的首个回调方案，且固定入场区 4111.21-4117.82 与 MT5 当前价 4113.15 重合。
- A 已触及入场区且距离合格，但已完成 M15 收盘 4112.37 尚未越过确认位 4114.51，因此结构有效但当前只能 wait。
- C 的顺势突破回测结构与 RR 较好，但 4135.77 上方有效突破及回测均未确认；D/E 为逆向条件方案，D 的 RR_TP1 仅 0.253609。
- 真实 H4 缺失，公开报价与技术页面存在时间及价格冲突，且高影响事件时点未核实；MT5 仍为执行锚，公开证据仅作辅助。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_usd_and_treasury_nominal_real_yields, fresh_timestamped_oil_and_primary_inflation_release, live_market_implied_fed_probabilities, primary_verified_election_results_boe_decision_and_iran_resolution, public_quote_display_timezone_and_cross_page_price_conflict_resolved, public_technical_selected_timeframe_and_daily_summary_conflict_resolved, synchronized_public_spot_vs_mt5_quote, verified_high_impact_event_times_and_blackout
