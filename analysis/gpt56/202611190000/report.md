# GPT-5.6 黄金小时点位分析 202611190000

数据时间（UTC）：2026-11-19T00:06:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3733.54-3742.45 | 3737.99 | 3754.15 | 3719.28, 3712.15, 3704.13 | WAIT_CONFIRMATION |
| B | sell | 3771.59-3781.24 | 3776.41 | 3792.82 | 3752.29, 3737.82, 3724.95 | WAIT_ENTRY_ZONE |
| C | sell | 3717.72-3724.95 | 3721.34 | 3731.39 | 3710.49, 3699.64, 3674.34 | WAIT_ENTRY_ZONE |
| D | buy | 3724.95-3731.39 | 3728.17 | 3711.94 | 3737.82, 3744.25, 3761.94 | WAIT_ENTRY_ZONE |
| E | buy | 3752.29-3761.94 | 3757.11 | 3744.25 | 3776.41, 3790.89, 3810.19 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A符合structural_bias=sell与tactical_momentum=buy构成的bearish_pullback，且固定入场区3733.54-3742.45覆盖当前MT5价格。
- A虽已zone_touched且within_max_distance，但M15收盘3740.18尚未完成PULLBACK_FAIL_REJECT所需的3737.99下方确认，因此executable_now=wait。
- 宏观资料偏空但不同步，公共技术序列因PUBLIC_CONFLUENCE_SERIES_DISCONTINUITY_DETECTED被剔除，且无true H4证据，不能据此提高突破或即时执行置信度。

公开数据覆盖：external_macro_only。

缺失证据：current_day_public_range, current_same_timeframe_public_indicators, exact_prior_public_quote_utc_due_to_timestamp_conflict, fresh_nov19_public_spot_quote, public_futures_technical_proxy, synchronized_dollar_treasury_yield_and_oil_levels, verified_current_geopolitical_update
