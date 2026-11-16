# GPT-5.6 黄金小时点位分析 202611161700

数据时间（UTC）：2026-11-16T17:08:02Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3873.5-3882.29 | 3877.89 | 3893.85 | 3859.42, 3852.39, 3844.47 | WAIT_ENTRY_ZONE |
| B | sell | 3903.41-3913.97 | 3908.69 | 3926.64 | 3882.29, 3866.46, 3852.39 | WAIT_ENTRY_ZONE |
| C | sell | 3844.47-3852.39 | 3848.43 | 3859.42 | 3836.55, 3824.67, 3796.95 | WAIT_ENTRY_ZONE |
| D | buy | 3852.39-3859.42 | 3855.9 | 3838.13 | 3866.46, 3873.5, 3892.85 | MISSED_ENTRY_DISTANCE |
| E | buy | 3882.29-3892.85 | 3887.57 | 3873.5 | 3908.69, 3924.53, 3945.65 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 3873.50–3882.29 回撤区同时贴近 S1 3872.45 与 Pivot 3881.56，符合 H1 Sell、M15 Buy 所描述的 bearish_pullback 结构。
- MT5 bid 3866.42 尚未触及 A 入场区，zone_touched=false，且距预期成交价 11.47 超过 max_distance 4.39，因此结构有效但当前应 wait，不能追空。
- C 的下破回测尚未确认；true H4、同步公共报价及实时 USD/美债收益率证据均缺失，公共数据只能提供辅助判断。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_quote_utc_timestamp
