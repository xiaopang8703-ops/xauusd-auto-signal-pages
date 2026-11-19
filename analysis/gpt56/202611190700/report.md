# GPT-5.6 黄金小时点位分析 202611190700

数据时间（UTC）：2026-11-19T07:05:33Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：range_bullish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 3735.74-3743.67 | 3739.7 | 3716.62 | 3753.87, 3765.2, 3787.86 | WAIT_CONFIRMATION |
| B | buy | 3717.62-3726.68 | 3722.15 | 3703.02 | 3735.74, 3753.87, 3765.2 | WAIT_ENTRY_ZONE |
| C | buy | 3753.87-3765.2 | 3759.53 | 3743.67 | 3787.86, 3816.18, 3844.51 | WAIT_ENTRY_ZONE |
| D | sell | 3749.87-3753.87 | 3751.87 | 3782.19 | 3743.67, 3735.74, 3726.68 | WAIT_ENTRY_ZONE |
| E | sell | 3717.62-3726.68 | 3722.15 | 3735.74 | 3690.42, 3683.62, 3649.62 | WAIT_ENTRY_ZONE |

排序：A > C > E > B > D

研究理由：

- A 的固定 buy 回调结构与 structural_bias=buy、trend_context=bullish_pullback 一致，且当前 ask=3738.05 位于 A 入场区间 3735.74-3743.67 内。
- A 尚未满足 M15 收盘确认：confirmation_close=3732.9 低于 reclaim_level=3739.7，confirmation_crossed=false，因此结构可跟踪但当前应 wait。
- 真 H4 缺失且外部技术序列因 PUBLIC_CONFLUENCE_SERIES_DISCONTINUITY_DETECTED 被拒绝；同时较早的强美元与高收益率信息对黄金构成逆风，增加不确定性但不足以形成即时 veto。
- C 的固定顺势结构和 rr_tp1=1.786255 优于其余备用方案，但突破与回踩均未确认；D 的 rr_tp1=0.270449 最弱。

公开数据覆盖：external_macro_only。

缺失证据：current_synchronized_dollar_and_treasury_yields, fresh_external_technical_summary_and_indicators, fresh_oil_and_geopolitics, fresh_synchronized_external_spot_tick, public_futures_technical_proxy, reuters_full_article_access, timestamp_verified_external_day_range, verified_high_impact_event_schedule
