# GPT-5.6 黄金小时点位分析 202610220700

数据时间（UTC）：2026-10-22T07:07:22Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4096.12-4102.73 | 4099.42 | 4111.67 | 4085.54, 4080.25, 4074.3 | MISSED_ENTRY_DISTANCE |
| B | sell | 4127.23-4137.39 | 4132.31 | 4149.58 | 4106.91, 4091.66, 4078.11 | WAIT_ENTRY_ZONE |
| C | sell | 4070.48-4078.11 | 4074.3 | 4084.88 | 4062.85, 4051.4, 4024.7 | WAIT_ENTRY_ZONE |
| D | buy | 4078.11-4084.88 | 4081.49 | 4064.38 | 4091.66, 4098.44, 4117.07 | WAIT_ENTRY_ZONE |
| E | buy | 4106.91-4117.07 | 4111.99 | 4098.44 | 4132.31, 4147.55, 4167.87 | WAIT_ENTRY_ZONE |

排序：A > B > C > D > E

研究理由：

- A顺应H1 Strong Sell与structural_bias=sell，4096.12-4102.73回撤区已触及并出现PULLBACK_FAIL_REJECT确认，结构质量最高。
- 当前bid 4091.61距A确认价4099.42为7.81，超过max_distance 3.3且状态为MISSED_ENTRY_DISTANCE，追空风险高，因此executable_now=wait。
- C尚未完成4070.48下破回测，D/E逆主方向且确认条件未成立；true H4不可用，滞后的公共技术数据仅作辅助。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_cme_fedwatch_probabilities, independently_verified_us_event_calendar_and_release_times, primary_source_geopolitical_confirmation, sub15minute_public_technical_table, synchronized_dxy_yields_oil_ticks, synchronous_public_spot_time_verified
