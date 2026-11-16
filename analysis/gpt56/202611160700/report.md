# GPT-5.6 黄金小时点位分析 202611160700

数据时间（UTC）：2026-11-16T07:06:02Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3859.27-3870.75 | 3865.01 | 3885.53 | 3840.91, 3831.72, 3821.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3902.95-3916.63 | 3909.79 | 3933.05 | 3875.59, 3855.07, 3836.83 | WAIT_ENTRY_ZONE |
| C | sell | 3826.57-3836.83 | 3831.7 | 3845.95 | 3816.31, 3800.92, 3765.01 | MISSED_ENTRY_DISTANCE |
| D | buy | 3836.83-3845.95 | 3841.39 | 3818.36 | 3855.07, 3864.19, 3889.27 | MISSED_ENTRY_DISTANCE |
| E | buy | 3875.59-3889.27 | 3882.43 | 3864.19 | 3909.79, 3930.31, 3957.67 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- MT5 3855.03 位于 Pivot 3881.56、S1 3872.45 下方并接近 S2 3855.54；公开 1H Strong Sell 与 ADX(14) 51.827782 支持固定 sell 主方向，但无 true H4 证据。
- A 已触及 entry_zone 且出现闭合柱拒绝确认，固定几何最贴合当前 bearish_pullback；B 过深，C 尚无有效 breakout-retest。
- A 当前 distance 9.98 超过 max_distance 5.74，且价格已运行至 S2 附近，立即追空存在过度延伸风险，因此 executable_now=wait。
- D 为逆势且 rr_tp1=0.594008；E 需要突破并回测 3889.27，但当前未触区且 confirmation_crossed=false。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_intrahour_usd_and_treasury_moves, verified_public_quote_utc_timestamp
