# GPT-5.6 黄金小时点位分析 202611101800

数据时间（UTC）：2026-11-10T18:07:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4031.2-4042.91 | 4037.05 | 4057.96 | 4012.48, 4003.11, 3992.58 | WAIT_ENTRY_ZONE |
| B | sell | 4067.77-4081.99 | 4074.88 | 4099.05 | 4039.33, 4017.99, 3999.02 | WAIT_ENTRY_ZONE |
| C | sell | 3988.35-3999.02 | 3993.68 | 4008.51 | 3977.68, 3961.67, 3924.33 | WAIT_ENTRY_ZONE |
| D | buy | 3999.02-4008.51 | 4003.77 | 3979.81 | 4017.99, 4027.47, 4053.55 | WAIT_ENTRY_ZONE |
| E | buy | 4039.33-4053.55 | 4046.44 | 4027.47 | 4074.88, 4096.21, 4124.65 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 与 M15 均为 Strong Sell，ADX(14)=51.87，固定 sell 方向的 A 顺应下降结构，并通过首次回抽拒绝避免直接追空。
- MT5 价格 4017.95 已接近当日低点 4013.74 与 S2 4019.31，且 RSI(14)=23.63，当前延伸风险高。
- A 尚未触及 4031.20-4042.91 入场区，distance=19.10 超过 max_distance=5.86；必须先触区并取得合规 M15 收盘拒绝，因此当前只能 wait。
- True H4 缺失且同步宏观覆盖不完整，不能据此改写趋势，但 C 的 3988.35 突破回测仍未确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Synchronized USD, Treasury yields, oil and independently verified live Fed pricing, Synchronized public spot and technicals at the MT5 snapshot, True MT5 H4
