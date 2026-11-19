# GPT-5.6 黄金小时点位分析 202611190800

数据时间（UTC）：2026-11-19T08:07:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3742.13-3751.96 | 3747.05 | 3764.76 | 3726.39, 3718.52, 3709.67 | WAIT_ENTRY_ZONE |
| B | sell | 3775.56-3787.36 | 3781.46 | 3801.52 | 3751.96, 3734.26, 3718.52 | WAIT_ENTRY_ZONE |
| C | sell | 3709.67-3718.52 | 3714.1 | 3726.39 | 3700.82, 3687.55, 3656.57 | WAIT_ENTRY_ZONE |
| D | buy | 3718.52-3726.39 | 3722.45 | 3702.59 | 3734.26, 3742.13, 3763.76 | WAIT_ENTRY_ZONE |
| E | buy | 3751.96-3763.76 | 3757.86 | 3742.13 | 3781.46, 3799.16, 3822.76 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell 与 structural_bias=sell；M15 Buy 更符合 bearish_pullback，且 3742.13-3751.96 回抽区覆盖 prev_close=3742.91，结构质量最佳。
- A 当前 zone_touched=false，bid=3734.22，距 expected_fill_price=12.83，高于 max_distance=4.91，因此只能 wait，不能把 confirmation_crossed 单独视为可执行确认。
- C 与 E 均未形成已完成的突破回测确认；D 虽符合近端反转语义，但 rr_tp1=0.594663 且逆主结构，质量最低。
- 美元偏强及鹰派 Fed 背景支持卖方结构，但同步美债收益率、事件日历和新鲜外部技术数据缺失，只能作为辅助证据，不构成 veto。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：current_synchronized_dollar_and_treasury_yields, fresh_external_technical_summary_and_intraday_indicators, fresh_independently_verified_external_day_range, fresh_oil_and_geopolitics, fresh_synchronized_external_spot_tick, full_text_verification_of_reuters_and_forexr, verified_high_impact_event_schedule
