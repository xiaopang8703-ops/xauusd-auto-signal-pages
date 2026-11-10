# GPT-5.6 黄金小时点位分析 202611100300

数据时间（UTC）：2026-11-10T03:08:00Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：range_bullish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4111.37-4117.64 | 4114.51 | 4096.02 | 4125.71, 4134.68, 4152.62 | WAIT_CONFIRMATION |
| B | buy | 4101.88-4108.85 | 4105.36 | 4090.41 | 4115.83, 4129.78, 4138.49 | WAIT_ENTRY_ZONE |
| C | buy | 4125.71-4134.68 | 4130.19 | 4117.64 | 4152.62, 4175.05, 4197.47 | MISSED_ENTRY_DISTANCE |
| D | sell | 4121.71-4125.71 | 4123.71 | 4148.14 | 4117.64, 4111.37, 4104.19 | MISSED_ENTRY_DISTANCE |
| E | sell | 4097.02-4104.19 | 4100.6 | 4111.37 | 4075.5, 4070.12, 4043.22 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Buy、M15 为 Strong Sell，符合上涨结构内回调；A 的 buy 几何与主结构一致，且入场区邻近日低 4110.03 与 Pivot 4113.71。
- A 已触及并处于 4111.37–4117.64 入场区，距离条件合格，但已完成 M15 收盘 4111.54 尚未重新站上确认位 4114.51，因此只能 wait。
- 当前无有效突破与回测证据，C 的 breakout_quality 仍为 unconfirmed；真 H4、同步 USD/收益率/原油/Fed 数据缺失，增加中等过度延伸与证据不完整风险。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_usd_yields_oil_and_fed_pricing_at_mt5_snapshot, synchronized_public_spot_vs_mt5, true_mt5_h4
