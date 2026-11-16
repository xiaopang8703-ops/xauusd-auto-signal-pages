# GPT-5.6 黄金小时点位分析 202611160300

数据时间（UTC）：2026-11-16T03:09:17Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3880.46-3891.78 | 3886.12 | 3906.37 | 3862.34, 3853.28, 3843.09 | MISSED_ENTRY_DISTANCE |
| B | sell | 3918.96-3932.55 | 3925.75 | 3948.86 | 3891.78, 3871.4, 3853.28 | WAIT_ENTRY_ZONE |
| C | sell | 3843.09-3853.28 | 3848.19 | 3862.34 | 3832.9, 3817.61, 3781.95 | WAIT_ENTRY_ZONE |
| D | buy | 3853.28-3862.34 | 3857.81 | 3834.94 | 3871.4, 3880.46, 3905.37 | WAIT_ENTRY_ZONE |
| E | buy | 3891.78-3905.37 | 3898.57 | 3880.46 | 3925.75, 3946.14, 3973.32 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Strong Sell 与 structural_bias=sell，且 3880.46-3891.78 回调区覆盖 Pivot 3881.56 附近，结构质量最佳。
- 当前 bid 3871.36 已较 A expected_fill_price 3886.12 低 14.76，超过 max_distance 5.66；MISSED_ENTRY_DISTANCE 使其只能等待，不能追空。
- C 符合主方向延续但尚未完成 3843.09 下破及回测；true H4 不可用，因此 breakout_quality=unconfirmed。
- 现价接近 S1 3872.45 和日内低点 3860.25，叠加 StochRSI 低位，立即追空的过度延伸风险高。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_intrahour_usd_and_treasury_moves, verified_public_quote_utc_timestamp
