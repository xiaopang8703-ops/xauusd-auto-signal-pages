# GPT-5.6 黄金小时点位分析 202611130000

数据时间（UTC）：2026-11-13T00:06:31Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3891.16-3898.42 | 3894.79 | 3908.14 | 3879.54, 3873.73, 3867.19 | WAIT_ENTRY_ZONE |
| B | sell | 3915.86-3924.58 | 3920.22 | 3935.04 | 3898.42, 3885.35, 3873.73 | WAIT_ENTRY_ZONE |
| C | sell | 3867.19-3873.73 | 3870.46 | 3879.54 | 3860.65, 3850.84, 3827.95 | WAIT_ENTRY_ZONE |
| D | buy | 3873.73-3879.54 | 3876.64 | 3861.96 | 3885.35, 3891.16, 3907.14 | MISSED_ENTRY_DISTANCE |
| E | buy | 3898.42-3907.14 | 3902.78 | 3891.16 | 3920.22, 3933.3, 3950.74 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 Sell 与 M15 Buy 构成 bearish_pullback，A 的首层顺势回调卖出几何最符合当前结构。
- A 的 3891.16-3898.42 入场区、3908.14 止损及 3879.54 首目标保持结构有效，优于逆势且 rr_tp1 仅 0.593324 的 D。
- 当前 MT5 bid 3885.30 尚未触及 A 入场区，且缺少触区后的 M15 closed-bar PULLBACK_FAIL_REJECT，因此只能 wait。
- C 与 E 均未形成所需突破及回测，true H4 和同步外部确认不可用，不能将其评为已确认突破。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
