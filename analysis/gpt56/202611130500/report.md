# GPT-5.6 黄金小时点位分析 202611130500

数据时间（UTC）：2026-11-13T05:08:46Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_bias；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3917.76-3925.51 | 3921.64 | 3935.81 | 3905.36, 3899.16, 3892.18 | MISSED_ENTRY_DISTANCE |
| B | sell | 3950.39-3960.12 | 3955.26 | 3971.8 | 3930.93, 3916.34, 3903.37 | WAIT_ENTRY_ZONE |
| C | sell | 3896.08-3903.37 | 3899.72 | 3909.86 | 3888.79, 3877.86, 3852.34 | WAIT_ENTRY_ZONE |
| D | buy | 3903.37-3909.86 | 3906.61 | 3890.25 | 3916.34, 3922.82, 3940.66 | MISSED_ENTRY_DISTANCE |
| E | buy | 3930.93-3940.66 | 3935.8 | 3922.82 | 3955.26, 3969.85, 3989.31 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 的固定 sell 几何与 H1 Sell、tactical_momentum=sell 及 bearish_continuation 一致，且已完成入区触碰和 M15 收盘确认。
- 当前 bid 3916.29 距确认价 3921.64 为 5.35，超过 max_distance=3.88，追价风险使 executable_now=wait，但不否定 A 的结构有效性。
- C 仍需先有效跌破 3896.08并完成回测；当前 confirmation_crossed=false，因此 breakout_quality=unconfirmed。
- 真 H4、同步外部技术确认及实时 DXY/美债收益率证据缺失，公共信息仅作辅助，MT5 仍为执行锚点。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
