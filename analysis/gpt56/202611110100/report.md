# GPT-5.6 黄金小时点位分析 202611110100

数据时间（UTC）：2026-11-11T01:08:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4036.88-4043.78 | 4040.33 | 4053.06 | 4025.84, 4020.32, 4014.11 | MISSED_ENTRY_DISTANCE |
| B | sell | 4060.34-4068.62 | 4064.48 | 4078.56 | 4043.78, 4031.36, 4020.32 | WAIT_ENTRY_ZONE |
| C | sell | 4014.11-4020.32 | 4017.22 | 4025.84 | 4007.9, 3998.59, 3976.85 | WAIT_ENTRY_ZONE |
| D | buy | 4020.32-4025.84 | 4023.08 | 4009.14 | 4031.36, 4036.88, 4052.06 | WAIT_ENTRY_ZONE |
| E | buy | 4043.78-4052.06 | 4047.92 | 4036.88 | 4064.48, 4076.9, 4093.46 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 的固定 sell 几何同时符合 H1 Strong Sell、M15 Sell 与 bearish_continuation，4036.88-4043.78 回抽区也覆盖日开盘 4035.65 上方阻力带。
- 当前 MT5 bid 4031.32 接近日低 4031.02，RSI_14=33.40 且 ADX_14=70.77；在 A 已触发 MISSED_ENTRY_DISTANCE、距确认价 9.01 大于 max_distance 3.45 时追空具有高过度延伸风险。
- A 仍具结构有效性，但当前不在 entry_zone 且已超出允许距离，因此 executable_now=wait，而非结构性 NO_TRADE 或研究 veto。
- C 尚未完成 4014.11 下破及回测确认；True MT5 H4、同步 USD/美债收益率及新鲜滚动新闻均不可用，不能把未确认突破提升为即时执行依据。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Fresh news after UTC rollover, Same-time USD, Treasury yields, oil and verified Fed pricing, Synchronized external quotes and technicals, True MT5 H4
