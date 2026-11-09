# GPT-5.6 黄金小时点位分析 202611090400

数据时间（UTC）：2026-11-09T04:05:14Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4115.78-4124.03 | 4119.9 | 4095.92 | 4134.64, 4146.43, 4170.01 | WAIT_CONFIRMATION |
| B | buy | 4108.06-4116.33 | 4112.19 | 4094.65 | 4124.6, 4141.14, 4151.48 | MISSED_ENTRY_DISTANCE |
| C | buy | 4134.64-4146.43 | 4140.53 | 4124.03 | 4170.01, 4199.49, 4228.96 | WAIT_ENTRY_ZONE |
| D | sell | 4130.64-4134.64 | 4132.64 | 4164.11 | 4124.03, 4115.78, 4106.35 | WAIT_ENTRY_ZONE |
| E | sell | 4096.92-4106.35 | 4101.64 | 4115.78 | 4068.62, 4061.55, 4026.17 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- H1 结构偏多且 M15 战术动能偏空，符合主升结构中的回调；A 是当前固定几何中最直接的顺势回调方案。
- A 已触及入场区且仍在 max_distance 内，但已完成的 M15 收盘 4115.63 尚未重新站上 reclaim_level 4119.9，因此只能 wait。
- MT5 中价较 prev_close 高约 52.16、并高于 R3 约 28.66，追涨过度延伸风险高；C 的 4146.43 突破及回测也尚未发生。
- true_mt5_h4、同步公开现货及当前 USD/美债收益率证据缺失，公共信息仅作辅助，不足以推翻 MT5 锚定的 A 结构。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_public_spot_vs_mt5, true_mt5_h4, verified_current_oil_geopolitics_headlines, verified_current_usd_treasury_yield_fed_pricing
