# GPT-5.6 黄金小时点位分析 202611060100

数据时间（UTC）：2026-11-06T01:06:28Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_pullback；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4091.79-4099.31 | 4095.55 | 4073.61 | 4108.98, 4119.72, 4141.2 | WAIT_CONFIRMATION |
| B | buy | 4074.61-4083.2 | 4078.9 | 4060.72 | 4091.79, 4108.98, 4119.72 | WAIT_ENTRY_ZONE |
| C | buy | 4108.98-4119.72 | 4114.35 | 4099.31 | 4141.2, 4168.05, 4194.9 | WAIT_ENTRY_ZONE |
| D | sell | 4104.98-4108.98 | 4106.98 | 4135.83 | 4099.31, 4091.79, 4083.2 | MISSED_ENTRY_DISTANCE |
| E | sell | 4074.61-4083.2 | 4078.9 | 4091.79 | 4048.83, 4042.38, 4010.16 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- H1 为 Buy、M15 为 Sell，符合多头结构中的战术回撤；A 位于第一主方向回撤区，且 MT5 价格仍在其固定入场区内。
- A 的已完成 M15 收盘价 4092.18 尚未重新站上 4095.55，confirmation_crossed=false，因此结构可跟踪但当前必须等待确认。
- C 尚无 4119.72 上方有效突破及回测；真实 H4 缺失且公共技术与现货数据覆盖不完整，不能据此提升突破质量或改写固定方向。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
