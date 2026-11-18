# GPT-5.6 黄金小时点位分析 202611182300

数据时间（UTC）：2026-11-18T23:06:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：sell_biased_consolidation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3733.54-3742.45 | 3737.99 | 3754.15 | 3719.28, 3712.15, 3704.13 | WAIT_ENTRY_ZONE |
| B | sell | 3765.83-3775.97 | 3770.9 | 3788.14 | 3745.55, 3730.34, 3716.82 | WAIT_ENTRY_ZONE |
| C | sell | 3709.22-3716.82 | 3713.02 | 3723.58 | 3701.62, 3690.22, 3663.62 | WAIT_ENTRY_ZONE |
| D | buy | 3716.82-3723.58 | 3720.2 | 3703.14 | 3730.34, 3737.1, 3755.69 | MISSED_ENTRY_DISTANCE |
| E | buy | 3745.55-3755.69 | 3750.62 | 3737.1 | 3770.9, 3786.11, 3806.39 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应固定 structural_bias=sell，并以首次回撤失败确认入场；相较继续向下追击的 C，其固定几何更适合在日内大跌后跟踪。
- MT5 现价 3730.30 尚未触及 A 的 3733.54-3742.45 entry_zone；虽 confirmation_crossed=true，但 zone_touched=false 且 distance=7.69 超过 max_distance=4.45，因此当前只能 wait。
- 当日从 3849.37 下跌至最低 3719.86，且旧公共代理显示 4-hour RSI(14)=22.00552，提示高 overextension_risk；该代理并非 true H4，只作为辅助风险证据。
- C 尚无有效突破及回测，D 的 RR_TP1=0.594373 且已为 MISSED_ENTRY_DISTANCE；当前没有足够证据支持反转或突破方案优先于 A。

公开数据覆盖：external_macro_only。

缺失证据：current_same_timeframe_public_indicators, exact_public_spot_quote_utc_due_to_timestamp_conflict, public_futures_technical_proxy, synchronized_dollar_treasury_yield_and_oil_levels, synchronized_public_spot_and_full_day_range, verified_current_geopolitical_update
