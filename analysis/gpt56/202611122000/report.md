# GPT-5.6 黄金小时点位分析 202611122000

数据时间（UTC）：2026-11-12T20:08:46Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3891.17-3899.97 | 3895.57 | 3911.52 | 3877.11, 3870.07, 3862.16 | WAIT_ENTRY_ZONE |
| B | sell | 3921.07-3931.62 | 3926.35 | 3944.28 | 3899.97, 3884.14, 3870.07 | WAIT_ENTRY_ZONE |
| C | sell | 3862.16-3870.07 | 3866.11 | 3877.11 | 3854.25, 3842.38, 3814.7 | WAIT_ENTRY_ZONE |
| D | buy | 3870.07-3877.11 | 3873.59 | 3855.83 | 3884.14, 3891.17, 3910.52 | WAIT_ENTRY_ZONE |
| E | buy | 3899.97-3910.52 | 3905.24 | 3891.17 | 3926.35, 3942.17, 3963.27 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 3891.17-3899.97 首次回调做空几何与 H1 Strong Sell、structural_bias=sell 及 bearish_pullback 一致，且要求 M15 触区后收盘拒绝，优于当前追空。
- 当前 MT5 bid 3884.09 尚未触及 A 入场区，距 expected_fill_price 11.48，超过 max_distance 4.4；zone_touched=false，因此只能 wait。
- 价格已由日开盘 3981.68 大幅下跌并接近 S3 3864.55，RSI(14)=27.790315 且 ADX(14)=75.678407，当前追空过度延伸风险高。
- C 尚无跌破 3862.16 后的有效回测确认，D/E 为逆 structural_bias 的买入替代方案；其中 D 的 rr_tp1=0.594032 最弱。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
