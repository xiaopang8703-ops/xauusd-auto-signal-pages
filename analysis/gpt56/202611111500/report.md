# GPT-5.6 黄金小时点位分析 202611111500

数据时间（UTC）：2026-11-11T15:08:30Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_near_day_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4020.95-4027.32 | 4024.14 | 4035.97 | 4010.75, 4005.65, 3999.92 | MISSED_ENTRY_DISTANCE |
| B | sell | 4042.62-4050.27 | 4046.44 | 4059.45 | 4027.32, 4015.85, 4005.65 | WAIT_ENTRY_ZONE |
| C | sell | 3999.92-4005.65 | 4002.78 | 4010.75 | 3994.19, 3985.6, 3965.54 | WAIT_ENTRY_ZONE |
| D | buy | 4005.65-4010.75 | 4008.2 | 3995.34 | 4015.85, 4020.95, 4034.97 | MISSED_ENTRY_DISTANCE |
| E | buy | 4027.32-4034.97 | 4031.14 | 4020.95 | 4046.44, 4057.92, 4073.22 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 的回调做空几何与 H1/M15 Strong Sell、structural_bias=sell 及低于日开盘价和 Pivot 的位置一致，止损 4035.97 也贴近日开盘/前收 4035.65 的失效边界。
- 当前 bid 4015.80 已较 A 的确认价 4024.14 低 8.34，超过 max_distance=3.19，且 runtime=MISSED_ENTRY_DISTANCE，因此不能追空，应等待新的合规回调与闭合确认。
- RSI(14)=28.68、StochRSI=2.27，价格接近日低 4010.63，显示即时下行过度延伸风险高，但这不否定 A 的结构跟踪价值。
- C 尚未完成 3999.92 下破与回测，true H4 不可用且公共宏观覆盖不完整，因此 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_real_yields, public_quote_utc_offset, synchronized_dollar_oil_and_yield_quotes, synchronized_public_spot_tick
