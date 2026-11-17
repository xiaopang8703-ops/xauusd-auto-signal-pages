# GPT-5.6 黄金小时点位分析 202611171600

数据时间（UTC）：2026-11-17T16:05:03Z；authority=none。

跟踪方案：A/buy；executable_now=yes；veto=false。

市场状态：区间内偏多延续；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 3868.69-3875.73 | 3872.21 | 3851.6 | 3884.78, 3894.84, 3914.96 | READY_TO_SUBMIT_DRY_RUN |
| B | buy | 3852.6-3860.64 | 3856.62 | 3839.53 | 3868.69, 3884.78, 3894.84 | MISSED_ENTRY_DISTANCE |
| C | buy | 3884.78-3894.84 | 3889.81 | 3875.73 | 3914.96, 3940.11, 3965.26 | MISSED_ENTRY_DISTANCE |
| D | sell | 3880.78-3884.78 | 3882.78 | 3909.93 | 3875.73, 3868.69, 3860.64 | MISSED_ENTRY_DISTANCE |
| E | sell | 3852.6-3860.64 | 3856.62 | 3868.69 | 3828.46, 3822.43, 3792.25 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 顺应固定 buy 结构与 H1 Buy 背景；已触及 3868.69-3875.73，M15 收盘 3875.72 完成确认，ask 3870.75 位于入场区且距确认价 1.46 小于 max_distance 3.52。
- A 的即时几何、确认和距离条件均满足，当前资料未显示明确事件禁入或实质证据矛盾，因此 executable_now=yes；但 StochRSI 86.460738 且 ADX 11.136494，追高与区间震荡风险使 overextension_risk=medium。
- C 符合主方向且 RR 较优，但尚未完成 3894.84 上方收盘突破及回踩，故 breakout_quality=unconfirmed；B 仍具结构意义，但当前距离状态只影响即时执行。
- D 为逆主方向且 rr_tp1=0.259669，E 仅适用于原多头结构失效后的反向突破回踩；当前证据均不支持其优先于 A。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_public_technical_indicators, independently_verified_breaking_news_other_than_scheduled_release, synchronized_mt5_public_quote, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
