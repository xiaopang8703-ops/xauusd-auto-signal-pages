# GPT-5.6 黄金小时点位分析 202611161100

数据时间（UTC）：2026-11-16T11:08:47Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3879.56-3888.38 | 3883.97 | 3899.96 | 3865.46, 3858.4, 3850.47 | WAIT_ENTRY_ZONE |
| B | sell | 3909.54-3920.12 | 3914.83 | 3932.82 | 3888.38, 3872.51, 3858.4 | WAIT_ENTRY_ZONE |
| C | sell | 3850.47-3858.4 | 3854.43 | 3865.46 | 3842.54, 3830.64, 3802.89 | MISSED_ENTRY_DISTANCE |
| D | buy | 3858.4-3865.46 | 3861.93 | 3844.13 | 3872.51, 3879.56, 3898.96 | MISSED_ENTRY_DISTANCE |
| E | buy | 3888.38-3898.96 | 3893.67 | 3879.56 | 3914.83, 3930.7, 3951.86 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Sell、M15 为 Strong Buy，符合空头结构中的反弹；A 的 3879.56-3888.38 回撤区覆盖 Pivot 3881.56，并接近前收 3889.35，结构匹配最佳。
- MT5 bid 3872.46 尚未触及 A 入场区，且距预期成交价 3883.97 为 11.51，高于 max_distance 4.41，因此当前应 wait，而非结构性 NO_TRADE。
- C 尚无有效下破及回测确认；D 虽出现扫低回收形态，但逆主方向且 rr_tp1 仅 0.594382，固定几何质量较弱。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_intrahour_usd_and_treasury_moves, verified_public_quote_utc_timestamp
