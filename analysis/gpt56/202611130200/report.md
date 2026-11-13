# GPT-5.6 黄金小时点位分析 202611130200

数据时间（UTC）：2026-11-13T02:09:16Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback_range；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3917.76-3925.51 | 3921.64 | 3935.81 | 3905.36, 3899.16, 3892.18 | WAIT_ENTRY_ZONE |
| B | sell | 3944.11-3953.41 | 3948.76 | 3964.57 | 3925.51, 3911.56, 3899.16 | WAIT_ENTRY_ZONE |
| C | sell | 3892.18-3899.16 | 3895.67 | 3905.36 | 3885.2, 3874.73, 3850.3 | MISSED_ENTRY_DISTANCE |
| D | buy | 3899.16-3905.36 | 3902.26 | 3886.6 | 3911.56, 3917.76, 3934.81 | MISSED_ENTRY_DISTANCE |
| E | buy | 3925.51-3934.81 | 3930.16 | 3917.76 | 3948.76, 3962.71, 3981.31 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Sell、M15 为 Strong Buy，符合 bearish_pullback；A 是顺结构方向的首个回撤方案，3917.76-3925.51 入场区紧邻 3916.83 日内高点。
- MT5 当前 bid/ask 为 3911.51/3911.60，A 尚未触及入场区，也没有触区后的 M15 闭合拒绝确认，因此结构可跟踪但当前只能 wait。
- StochRSI 90.400523 且日内价格已明显高于 3878.63 开盘价，短线过热风险为 medium；同时 true H4、实时美元及美债收益率证据缺失，不能提高即时执行置信度。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
