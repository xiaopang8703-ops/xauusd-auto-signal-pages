# GPT-5.6 黄金小时点位分析 202611100400

数据时间（UTC）：2026-11-10T04:07:30Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_bias；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4116.75-4125.2 | 4120.98 | 4136.34 | 4103.23, 4096.47, 4088.86 | MISSED_ENTRY_DISTANCE |
| B | sell | 4145.48-4155.62 | 4150.55 | 4167.79 | 4125.2, 4109.99, 4096.47 | WAIT_ENTRY_ZONE |
| C | sell | 4088.86-4096.47 | 4092.66 | 4103.23 | 4081.25, 4069.84, 4043.2 | WAIT_ENTRY_ZONE |
| D | buy | 4096.47-4103.23 | 4099.85 | 4082.77 | 4109.99, 4116.75, 4135.34 | WAIT_ENTRY_ZONE |
| E | buy | 4125.2-4135.34 | 4130.27 | 4116.75 | 4150.55, 4165.76, 4186.04 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的首段回抽做空几何与 H1 Sell、M15 Strong Sell 及 4113.71 枢轴附近阻力一致，结构质量最高。
- MT5 现价接近日低且 StochRSI=4.96，追空过度延伸风险高；A 已为 MISSED_ENTRY_DISTANCE，当前距离 11.03 高于 max_distance 4.22，因此应等待新的合规回抽确认。
- C 尚未完成 4088.86 下破回测，E 亦无有效突破回测；true_mt5_h4 与同步宏观数据缺失，不能据此提升突破质量。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_usd_yields_oil_and_fed_pricing_at_mt5_snapshot, synchronized_public_spot_vs_mt5, true_mt5_h4
