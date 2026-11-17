# GPT-5.6 黄金小时点位分析 202611171800

数据时间（UTC）：2026-11-17T18:09:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_with_bearish_bias；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3876.16-3886.63 | 3881.39 | 3900.2 | 3859.4, 3851.02, 3841.6 | WAIT_ENTRY_ZONE |
| B | sell | 3904.89-3917.17 | 3911.03 | 3931.91 | 3880.33, 3861.91, 3845.54 | WAIT_ENTRY_ZONE |
| C | sell | 3836.33-3845.54 | 3840.93 | 3853.72 | 3827.12, 3813.3, 3781.07 | WAIT_ENTRY_ZONE |
| D | buy | 3845.54-3853.72 | 3849.63 | 3828.96 | 3861.91, 3870.1, 3892.61 | WAIT_ENTRY_ZONE |
| E | buy | 3880.33-3892.61 | 3886.47 | 3870.1 | 3911.03, 3929.45, 3954.01 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 的 3876.16-3886.63 回调卖出区位于日内高点 3891.05 下方，符合固定 sell 偏向及 1H Strong Sell、15M Sell 的咨询性技术背景。
- 当前 bid 3861.87 尚未触及 A 区间，距预期成交价 3881.39 为 19.52，超过 max_distance 5.24，且不存在触区后的 M15 收盘确认，因此只能 wait。
- C 与主方向一致，但 3836.33 下破及回测尚未发生；当前 confirmation_crossed=false，故 breakout_quality=unconfirmed。
- 真实 H4 缺失，ADX 11.035245 显示趋势力度偏弱，且 USD、收益率和事件风险覆盖不完整，因此不支持立即追空。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news_other_than_scheduled_release, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
