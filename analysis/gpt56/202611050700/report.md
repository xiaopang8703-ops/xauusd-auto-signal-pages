# GPT-5.6 黄金小时点位分析 202611050700

数据时间（UTC）：2026-11-05T07:05:13Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_range_near_high；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4126.94-4134.39 | 4130.66 | 4108.93 | 4143.95, 4154.59, 4175.87 | WAIT_CONFIRMATION |
| B | buy | 4109.93-4118.44 | 4114.18 | 4096.18 | 4126.94, 4143.95, 4154.59 | MISSED_ENTRY_DISTANCE |
| C | buy | 4143.95-4154.59 | 4149.27 | 4134.39 | 4175.87, 4202.47, 4229.07 | WAIT_ENTRY_ZONE |
| D | sell | 4139.95-4143.95 | 4141.95 | 4170.55 | 4134.39, 4126.94, 4118.44 | WAIT_ENTRY_ZONE |
| E | sell | 4109.93-4118.44 | 4114.18 | 4126.94 | 4084.43, 4078.06, 4046.18 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 与 H1 结构性买入方向及 M15 战术动量一致，且回调区已触及、当前仍在固定入场区和 max_distance 内。
- A 尚未满足 M15 closed-bar reclaim：confirmation_close=4127.27 低于 4130.66，故结构有效但 executable_now=wait。
- RSI14=73.64304、ADX14=63.005663，价格接近日高 4147.05，追涨与过度延伸风险高；C 的 4154.59 突破及回测尚未确认。
- 真实 H4 与已核验事件黑窗资料缺失，公共报价不同步且仅作辅助，MT5 bid/ask 4129.03/4129.12 仍为执行锚点。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_treasury_nominal_and_real_yields, fresh_primary_usd_and_market_implied_fed_probabilities, fresh_timestamped_oil_and_primary_inflation_release, independently_verified_election_results, public_quote_display_timezone_verified, public_technical_selected_table_timeframe_verified, synchronized_public_spot_vs_mt5_quote, verified_high_impact_calendar_and_event_blackout
