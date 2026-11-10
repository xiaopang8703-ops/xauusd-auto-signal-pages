# GPT-5.6 黄金小时点位分析 202611101900

数据时间（UTC）：2026-11-10T19:06:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_breakdown；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4031.2-4042.91 | 4037.05 | 4057.96 | 4012.48, 4003.11, 3992.58 | MISSED_ENTRY_DISTANCE |
| B | sell | 4068.46-4080.09 | 4074.28 | 4094.05 | 4045.2, 4027.76, 4012.26 | WAIT_ENTRY_ZONE |
| C | sell | 4003.54-4012.26 | 4007.9 | 4020.01 | 3994.82, 3981.74, 3951.22 | WAIT_ENTRY_ZONE |
| D | buy | 4012.26-4020.01 | 4016.14 | 3996.56 | 4027.76, 4035.51, 4056.83 | MISSED_ENTRY_DISTANCE |
| E | buy | 4045.2-4056.83 | 4051.01 | 4035.51 | 4074.28, 4091.72, 4114.98 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Strong Sell 与固定 sell 结构，且已完成入区和 M15 PULLBACK_FAIL_REJECT 确认，结构质量最高。
- 当前 bid 4027.71 距 A 确认价 4037.05 为 9.34，超过 max_distance 5.86；MISSED_ENTRY_DISTANCE 仅使当前不可执行，因此结论为 wait。
- 价格接近日低 4013.74 与 S2 4019.31，RSI_14 29.379397 且日内跌幅显著，追空过度延伸风险高。
- C 尚未完成 4003.54 下破与回测；D 的 rr_tp1 仅 0.593463，E 又逆固定 sell 结构，故均不优于 A。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Synchronized USD, Treasury yields, oil and verified live Fed pricing, Synchronized public spot and technicals at the MT5 snapshot, True MT5 H4
