# GPT-5.6 黄金小时点位分析 202611111300

数据时间（UTC）：2026-11-11T13:06:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_with_bearish_pressure；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4044.7-4050.03 | 4047.36 | 4057.43 | 4036.18, 4031.91, 4027.12 | MISSED_ENTRY_DISTANCE |
| B | sell | 4062.83-4069.23 | 4066.03 | 4076.91 | 4050.03, 4040.44, 4031.91 | WAIT_ENTRY_ZONE |
| C | sell | 4027.12-4031.91 | 4029.51 | 4036.18 | 4022.33, 4015.14, 3998.38 | WAIT_ENTRY_ZONE |
| D | buy | 4031.91-4036.18 | 4034.05 | 4023.29 | 4040.44, 4044.7, 4056.43 | WAIT_ENTRY_ZONE |
| E | buy | 4050.03-4056.43 | 4053.23 | 4044.7 | 4066.03, 4075.63, 4088.43 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 与 H1 结构性 sell 偏向一致，4044.7-4050.03 已触及且 M15 PULLBACK_FAIL_REJECT 已确认，固定几何仍具备跟踪价值。
- 当前 bid 4040.4 距 A 确认价 4047.36 为 6.96，超过 max_distance=3.0，runtime=MISSED_ENTRY_DISTANCE；此时追空过度延伸风险高，应等待而非执行。
- 15m 与 1h 公共技术代理均为 Strong Sell，但真 H4 缺失且实时收益率、美元和同步现货数据不完整，因此仅作为 MT5 锚点后的辅助证据。
- C 与 E 均未形成已完成突破及有效回测，breakout_quality=unconfirmed；B 结构与 RR 较好但尚未触及 4062.83-4069.23。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_real_yields, public_quote_utc_offset, synchronized_dollar_oil_and_yield_quotes, synchronized_public_spot_tick
