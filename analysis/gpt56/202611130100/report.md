# GPT-5.6 黄金小时点位分析 202611130100

数据时间（UTC）：2026-11-13T01:05:16Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3891.16-3898.42 | 3894.79 | 3908.14 | 3879.54, 3873.73, 3867.19 | MISSED_ENTRY_DISTANCE |
| B | sell | 3919.84-3928.57 | 3924.2 | 3939.05 | 3902.38, 3889.28, 3877.64 | WAIT_ENTRY_ZONE |
| C | sell | 3871.09-3877.64 | 3874.36 | 3883.46 | 3864.54, 3854.72, 3831.79 | WAIT_ENTRY_ZONE |
| D | buy | 3877.64-3883.46 | 3880.55 | 3865.85 | 3889.28, 3895.1, 3911.11 | MISSED_ENTRY_DISTANCE |
| E | buy | 3902.38-3911.11 | 3906.74 | 3895.1 | 3924.2, 3937.3, 3954.76 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Sell、M15 为 Strong Buy，符合 bearish_pullback；A 是贴近当日高点的首个主方向回调做空方案，结构适配优于反向 D/E。
- A 已触及入场区并以已收盘 M15 完成 PULLBACK_FAIL_REJECT，但当前 distance=5.55 超过 max_distance=3.63，因此结构仍可跟踪、此刻应 wait。
- C 尚未完成 3871.09 下破及回测，breakout_quality=unconfirmed；B 虽 RR 较高但入场区仍远，均不优于已形成拒绝证据的 A。
- 真实 H4、同步现货报价及实时 DXY/美债收益率不可用，公共证据仅作辅助，MT5 3889.24/3889.32 仍为执行锚点。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
