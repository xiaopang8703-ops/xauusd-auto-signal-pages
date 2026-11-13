# GPT-5.6 黄金小时点位分析 202611131100

数据时间（UTC）：2026-11-13T11:05:31Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3895.63-3902.65 | 3899.14 | 3912.07 | 3884.39, 3878.78, 3872.46 | MISSED_ENTRY_DISTANCE |
| B | sell | 3919.49-3927.91 | 3923.7 | 3938.01 | 3902.65, 3890.01, 3878.78 | WAIT_ENTRY_ZONE |
| C | sell | 3872.46-3878.78 | 3875.62 | 3884.39 | 3866.14, 3856.66, 3834.54 | WAIT_ENTRY_ZONE |
| D | buy | 3878.78-3884.39 | 3881.59 | 3867.4 | 3890.01, 3895.63, 3911.07 | WAIT_ENTRY_ZONE |
| E | buy | 3902.65-3911.07 | 3906.86 | 3895.63 | 3923.7, 3936.33, 3953.17 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell、M15 Strong Sell 与固定 sell 结构，回调失败后延续下行的几何质量最佳。
- A 已触及 entry_zone 且完成确认，但当前 bid 3889.96 距 expected_fill_price 3899.14 为 9.18，超过 max_distance 3.51；立即执行属于追价，应等待而非结构性否定。
- B 与 C 同属顺势 sell 备选，但 B 尚未触及 entry_zone，C 尚无有效跌破及回测确认；当前 breakout_quality 为 unconfirmed。
- D/E 为逆固定主方向的 buy 情景；D 的 rr_tp1 仅 0.593376，E 仍缺少对 3911.07 的有效突破回测，因此结构优先级低于顺势方案。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
