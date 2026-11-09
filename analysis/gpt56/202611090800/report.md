# GPT-5.6 黄金小时点位分析 202611090800

数据时间（UTC）：2026-11-09T08:05:29Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4091.02-4096.45 | 4093.73 | 4077.59 | 4103.44, 4111.2, 4126.72 | WAIT_CONFIRMATION |
| B | buy | 4078.59-4084.81 | 4081.7 | 4068.28 | 4091.02, 4103.44, 4111.2 | MISSED_ENTRY_DISTANCE |
| C | buy | 4103.44-4111.2 | 4107.32 | 4096.45 | 4126.72, 4146.12, 4165.52 | MISSED_ENTRY_DISTANCE |
| D | sell | 4099.44-4103.44 | 4101.44 | 4122.84 | 4096.45, 4091.02, 4084.81 | MISSED_ENTRY_DISTANCE |
| E | sell | 4078.59-4084.81 | 4081.7 | 4091.02 | 4059.97, 4055.32, 4032.04 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 符合 H1 Buy、M15 Strong Sell 所描述的 bullish_pullback，且 4092.62 位于 A 入场区 4091.02–4096.45 内，固定顺势回调几何仍有效。
- A 已触及入场区且距离 1.11 未超过 max_distance=3.0，但已完成 M15 收盘 4086.58 尚未重新站上确认位 4093.73，因此 executable_now=wait。
- 当前价格仍高于 R3=4089.48，日内曾自 4134.18 明显回落，追价与延续突破质量不足；C 的 4111.2 突破及回测尚未确认。
- true_mt5_h4 与快照同步的美元、美债收益率及油价证据缺失，公共数据只能辅助，不能推翻 MT5 锚点或把等待升级为 veto。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_dollar_us_treasury_yields_and_fed_pricing_at_mt5_snapshot, live_oil_at_mt5_snapshot, synchronized_public_spot_vs_mt5, true_mt5_h4
