# GPT-5.6 黄金小时点位分析 202611170400

数据时间（UTC）：2026-11-17T04:06:47Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：偏多区间整理；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 3867.87-3874.25 | 3871.06 | 3852.27 | 3882.46, 3891.59, 3909.85 | WAIT_CONFIRMATION |
| B | buy | 3856.47-3863.58 | 3860.02 | 3844.8 | 3870.69, 3884.92, 3893.81 | WAIT_ENTRY_ZONE |
| C | buy | 3882.46-3891.59 | 3887.03 | 3874.25 | 3909.85, 3932.68, 3955.5 | WAIT_ENTRY_ZONE |
| D | sell | 3878.46-3882.46 | 3880.46 | 3905.29 | 3874.25, 3867.87, 3860.57 | MISSED_ENTRY_DISTANCE |
| E | sell | 3853.27-3860.57 | 3856.92 | 3867.87 | 3831.37, 3825.9, 3798.52 | WAIT_ENTRY_ZONE |

排序：C > A > B > E > D

研究理由：

- C 顺应固定 buy 结构，TP1 风险回报 1.785603，优于 A、B，且突破回踩几何提供明确失效边界。
- 当前 MT5 ask 3869.74 尚低于 C 入场区 3882.46-3891.59，M15 也未完成突破 3891.59 及有效回踩，因此只能 wait。
- 市场处于偏多区间整理，ADX 约 21 且 true H4 缺失；若无闭合突破与回踩，直接追随上破存在中等过度延伸风险。
- A 虽已触及入场区且距离合格，但 M15 确认尚未跨越 3871.06，且 TP1 风险回报仅 0.606706，结构质量次于 C。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
