# GPT-5.6 黄金小时点位分析 202611092200

数据时间（UTC）：2026-11-09T22:07:29Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：range_bullish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4139.47-4145.3 | 4142.39 | 4125.15 | 4152.8, 4161.12, 4177.76 | WAIT_CONFIRMATION |
| B | buy | 4126.15-4132.81 | 4129.48 | 4115.16 | 4139.47, 4152.8, 4161.12 | WAIT_ENTRY_ZONE |
| C | buy | 4145.56-4153.53 | 4149.55 | 4138.38 | 4169.47, 4189.39, 4209.32 | MISSED_ENTRY_DISTANCE |
| D | sell | 4148.8-4152.8 | 4150.8 | 4173.6 | 4145.3, 4139.47, 4132.81 | WAIT_ENTRY_ZONE |
| E | sell | 4126.15-4132.81 | 4129.48 | 4139.47 | 4106.17, 4101.18, 4076.2 | WAIT_ENTRY_ZONE |

排序：C > A > B > E > D

研究理由：

- H1 结构偏 buy，公开 1H/15M 技术均为 Strong Buy；C 顺应主方向且 rr_tp1=1.783348，优于 A/B 的低于 1 回报风险比。
- MT5 现价 4141.06/4141.21 尚未完成对 4153.53 的 M15 收盘突破及随后回测，故 C 结构可跟踪但 executable_now=wait。
- 价格接近日高 4148.72，日内涨幅较大且 M15 ATR=8.3265，首次突破存在追价风险；固定回测确认尚未成立，breakout_quality=unconfirmed。
- true_mt5_h4 与同步宏观快照缺失，外部 H4 和 GC=F 仅作咨询依据，不能覆盖 MT5 执行锚点或建立新的方向。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_us_dollar_yields_oil_and_fed_pricing_at_mt5_snapshot, synchronized_public_spot_vs_mt5, true_mt5_h4
