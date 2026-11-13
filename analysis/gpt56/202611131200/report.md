# GPT-5.6 黄金小时点位分析 202611131200

数据时间（UTC）：2026-11-13T12:06:31Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3895.63-3902.65 | 3899.14 | 3912.07 | 3884.39, 3878.78, 3872.46 | MISSED_ENTRY_DISTANCE |
| B | sell | 3921.12-3928.71 | 3924.92 | 3937.82 | 3905.94, 3894.55, 3884.43 | WAIT_ENTRY_ZONE |
| C | sell | 3878.74-3884.43 | 3881.59 | 3889.49 | 3873.05, 3864.51, 3844.6 | WAIT_ENTRY_ZONE |
| D | buy | 3884.43-3889.49 | 3886.96 | 3874.19 | 3894.55, 3899.61, 3913.53 | MISSED_ENTRY_DISTANCE |
| E | buy | 3905.94-3913.53 | 3909.74 | 3899.61 | 3924.92, 3936.3, 3951.48 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 与 structural_bias=sell、H1 Strong Sell 及 bearish_pullback 结构一致，且已完成入区和闭合 M15 跌破 3899.14 的拒绝确认。
- A 当前 distance=4.64 已超过 max_distance=3.51，追价风险使其 executable_now=wait，但不否定其结构跟踪价值。
- C 与 E 均未完成所需突破及回测，D 为逆主方向且 rr_tp1=0.594362；同时 true H4 缺失，不能据 M15 推断更高周期确认。
- 13:30 UTC 的 PPI 临近，且 DXY、美债收益率等实时宏观组缺失，支持等待而非形成结构性 veto。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
