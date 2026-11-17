# GPT-5.6 黄金小时点位分析 202611170800

数据时间（UTC）：2026-11-17T08:05:02Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：range_with_buy_bias；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 3865.63-3869.91 | 3867.77 | 3854.84 | 3875.42, 3881.53, 3893.75 | WAIT_ENTRY_ZONE |
| B | buy | 3860.17-3867.22 | 3863.69 | 3848.6 | 3874.27, 3888.36, 3897.17 | WAIT_ENTRY_ZONE |
| C | buy | 3875.42-3881.53 | 3878.48 | 3869.91 | 3893.75, 3909.03, 3924.3 | MISSED_ENTRY_DISTANCE |
| D | sell | 3871.42-3875.42 | 3873.42 | 3890.7 | 3869.91, 3865.63, 3860.73 | MISSED_ENTRY_DISTANCE |
| E | sell | 3855.84-3860.73 | 3858.28 | 3865.63 | 3841.14, 3837.46, 3819.09 | WAIT_ENTRY_ZONE |

排序：C > B > A > E > D

研究理由：

- C顺应固定buy结构且rr_tp1=1.781797，为主方向方案中风险回报最佳；但M15尚未收于breakout_level=3881.53之上，突破与回踩均未确认。
- MT5锚点3866.89距C入场区下沿3875.42为8.53，当前状态MISSED_ENTRY_DISTANCE且超过max_distance=6.11，因此结构可跟踪但不可立即执行。
- 当前为低ADX的区间整理，H1公共代理偏强但true H4不可用；A、B虽更接近现价，其rr_tp1仅0.591647和0.701127。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_public_technical_indicators, independently_verified_breaking_news, synchronized_mt5_public_quote, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
