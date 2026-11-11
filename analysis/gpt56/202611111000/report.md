# GPT-5.6 黄金小时点位分析 202611111000

数据时间（UTC）：2026-11-11T10:08:15Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_bias；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4059.81-4065.55 | 4062.68 | 4073.43 | 4050.63, 4046.04, 4040.88 | WAIT_ENTRY_ZONE |
| B | sell | 4079.31-4086.19 | 4082.75 | 4094.45 | 4065.55, 4055.22, 4046.04 | WAIT_ENTRY_ZONE |
| C | sell | 4040.88-4046.04 | 4043.46 | 4050.63 | 4035.72, 4027.98, 4009.92 | WAIT_ENTRY_ZONE |
| D | buy | 4046.04-4050.63 | 4048.34 | 4036.75 | 4055.22, 4059.81, 4072.43 | MISSED_ENTRY_DISTANCE |
| E | buy | 4065.55-4072.43 | 4068.99 | 4059.81 | 4082.75, 4093.07, 4106.83 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 的 4059.81-4065.55 回撤卖出区覆盖经典 Pivot 4063.65，符合 H1 Sell、M15 Strong Sell 与固定 sell 结构。
- A 尚未触及 entry_zone，且当前距 expected_fill_price 7.50、高于 max_distance 3.00，因此结构有效但 executable_now=wait。
- C 顺应 bearish_continuation，但 4040.88 下破及回测尚未确认；D 虽曾扫低回收，但 RR_TP1=0.593615 且属于逆主方向方案。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_real_yields, public_quote_utc_offset, synchronized_public_spot_tick, synchronized_usd_oil_and_yield_quotes
