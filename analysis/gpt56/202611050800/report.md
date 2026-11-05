# GPT-5.6 黄金小时点位分析 202611050800

数据时间（UTC）：2026-11-05T08:08:13Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_pullback_in_range；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4126.15-4132.95 | 4129.55 | 4109.59 | 4141.7, 4151.43, 4170.89 | WAIT_CONFIRMATION |
| B | buy | 4110.59-4118.37 | 4114.48 | 4097.92 | 4126.15, 4141.7, 4151.43 | MISSED_ENTRY_DISTANCE |
| C | buy | 4141.7-4151.43 | 4146.57 | 4132.95 | 4170.89, 4195.22, 4219.54 | WAIT_ENTRY_ZONE |
| D | sell | 4137.7-4141.7 | 4139.7 | 4166.03 | 4132.95, 4126.15, 4118.37 | WAIT_ENTRY_ZONE |
| E | sell | 4110.59-4118.37 | 4114.48 | 4126.15 | 4087.25, 4081.41, 4052.24 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 的固定 buy 回调结构符合 H1 偏多与 bullish_pullback；MT5 ask 4128.13 位于 4126.15-4132.95 入场区，且距离 1.42 未超出 3.4。
- A 尚未满足 M15 收盘确认：confirmation_close 4124.23 未越过 reclaim_level 4129.55，因此当前应 wait，而非结构性 NO_TRADE 或 veto。
- 日内价格已由 4061.26 低点大幅反弹，公共 RSI14 为 71.784563，均值回归风险使追价风险为 medium；C 的 4151.43 突破及回测尚未确认。
- D 与 E 均为逆主方向 sell，其中 D 的 rr_tp1 仅 0.256362；B 虽结构仍有效，但已处于 MISSED_ENTRY_DISTANCE，故排序低于 A 与 C。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_usd_nominal_and_real_treasury_yields, fresh_timestamped_oil_and_primary_inflation_release, independently_verified_election_results_and_geopolitical_resolution, live_market_implied_fed_probabilities, newer_gold_news_direct_page_fetch_unavailable, public_quote_display_timezone_verified, public_technical_selected_table_timeframe_verified, synchronized_public_spot_vs_mt5_quote, verified_high_impact_event_times_and_blackout
