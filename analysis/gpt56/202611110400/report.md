# GPT-5.6 黄金小时点位分析 202611110400

数据时间（UTC）：2026-11-11T04:09:15Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4036.88-4043.78 | 4040.33 | 4053.06 | 4025.84, 4020.32, 4014.11 | MISSED_ENTRY_DISTANCE |
| B | sell | 4076.4-4084.45 | 4080.42 | 4094.11 | 4060.3, 4048.22, 4037.48 | WAIT_ENTRY_ZONE |
| C | sell | 4031.45-4037.48 | 4034.47 | 4042.85 | 4025.42, 4016.37, 3995.27 | WAIT_ENTRY_ZONE |
| D | buy | 4037.48-4042.85 | 4040.16 | 4026.63 | 4048.22, 4053.59, 4068.35 | WAIT_ENTRY_ZONE |
| E | buy | 4060.3-4068.35 | 4064.32 | 4053.59 | 4080.42, 4092.5, 4108.6 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 回调结构最符合 H1 Sell、M15 Buy 所示的 bearish_pullback，且止损 4053.06 位于当日高点 4052.75 上方。
- A 已触及 entry_zone，但当前 bid 4048.17 距 expected_fill_price 4040.33 为 7.84，超过 max_distance 3.45，因此结构可继续跟踪但不可立即执行。
- C 的 4031.45 向下突破及回测尚未确认；当前 range 环境不支持把未完成突破视为可执行延续。
- D 虽与短线 buy 动能一致，但逆于主要 sell 结构且 rr_tp1 仅 0.595713，结构质量低于 A、B、C 和需正式失效后才成立的 E。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_nominal_and_real_yields, live_oil_quote, live_usd_index, public_spot_quote_utc_offset, synchronized_public_spot_tick
