# GPT-5.6 黄金小时点位分析 202611122300

数据时间（UTC）：2026-11-12T23:07:16Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback_near_range_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3880.19-3888.76 | 3884.48 | 3900.05 | 3866.47, 3859.62, 3851.9 | WAIT_ENTRY_ZONE |
| B | sell | 3911.05-3920.48 | 3915.76 | 3931.8 | 3892.19, 3878.04, 3865.46 | WAIT_ENTRY_ZONE |
| C | sell | 3858.39-3865.46 | 3861.93 | 3871.75 | 3851.32, 3840.71, 3815.97 | WAIT_ENTRY_ZONE |
| D | buy | 3865.46-3871.75 | 3868.61 | 3852.73 | 3878.04, 3884.33, 3901.62 | WAIT_ENTRY_ZONE |
| E | buy | 3892.19-3901.62 | 3896.9 | 3884.33 | 3915.76, 3929.91, 3948.77 | WAIT_ENTRY_ZONE |

排序：A > B > C > D > E

研究理由：

- A 顺应 H1 Strong Sell 与固定 sell 结构，且第一回撤区 3880.19-3888.76 比 B 更适合作为当前主跟踪方案。
- A 尚未触及 entry zone，且 decision_price 到 expected_fill_price 的 distance=6.52 超过 max_distance=4.29，因此只能 wait，不能立即执行。
- 价格接近日内低点与 S3=3864.55，RSI(14)≈27 且 ADX 较高，继续追空存在高 overextension risk。
- C 尚无跌破 3858.39 后有效回测的完成证据，BREAKOUT_RETEST_FAIL 条件未成立，breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
