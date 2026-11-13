# GPT-5.6 黄金小时点位分析 202611130700

数据时间（UTC）：2026-11-13T07:08:46Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3906.97-3914.65 | 3910.81 | 3924.87 | 3894.67, 3888.53, 3881.62 | WAIT_ENTRY_ZONE |
| B | sell | 3933.09-3942.31 | 3937.7 | 3953.37 | 3914.65, 3900.82, 3888.53 | WAIT_ENTRY_ZONE |
| C | sell | 3881.62-3888.53 | 3885.07 | 3894.67 | 3874.71, 3864.34, 3840.16 | MISSED_ENTRY_DISTANCE |
| D | buy | 3888.53-3894.67 | 3891.6 | 3876.09 | 3900.82, 3906.97, 3923.87 | MISSED_ENTRY_DISTANCE |
| E | buy | 3914.65-3923.87 | 3919.26 | 3906.97 | 3937.7, 3951.53, 3969.97 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 与固定 sell 结构一致，3906.97-3914.65 入场区覆盖 classic pivot 3910.56；H1 Sell、M15 Strong Sell、ADX 44.37849 支持等待反抽失败后延续。
- A 当前尚未触及入场区，decision_price 3900.78 距 expected_fill_price 3910.81 为 10.03，超过 max_distance 3.84，因此结构可跟踪但 executable_now=wait。
- C 虽顺应主方向，但 BREAKOUT_RETEST_FAIL 尚未完成，confirmation_crossed=false，故 breakout_quality=unconfirmed；B 更深且位于当日高点 3923.19 上方，触发概率次于 A。
- 真实 H4、同步外部现货以及实时 DXY/美债收益率证据缺失，公共技术数据仅作辅助；该不完整性不足以否决 MT5 锚定的 A，但不支持立即执行。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
