# GPT-5.6 黄金小时点位分析 202611170500

数据时间（UTC）：2026-11-17T05:06:02Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：range_bullish_bias；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 3872.56-3878.78 | 3875.67 | 3857.34 | 3886.78, 3895.67, 3913.45 | WAIT_CONFIRMATION |
| B | buy | 3858.34-3865.45 | 3861.89 | 3846.67 | 3872.56, 3886.78, 3895.67 | MISSED_ENTRY_DISTANCE |
| C | buy | 3886.78-3895.67 | 3891.23 | 3878.78 | 3913.45, 3935.67, 3957.9 | WAIT_ENTRY_ZONE |
| D | sell | 3882.78-3886.78 | 3884.78 | 3909.01 | 3878.78, 3872.56, 3865.45 | WAIT_ENTRY_ZONE |
| E | sell | 3858.34-3865.45 | 3861.89 | 3872.56 | 3837.0, 3831.66, 3804.99 | MISSED_ENTRY_DISTANCE |

排序：C > A > B > E > D

研究理由：

- C 顺应固定 buy 结构，确认后 RR_tp1=1.784739，在 A-E 中兼具方向一致性与较优固定盈亏比。
- 当前 MT5 ask=3874.38，尚未突破 3895.67，C 的 entry_zone 未触及且 BREAKOUT_RETEST_FAIL 未确认，因此只能 wait。
- A 虽位于入场区且符合 buy 偏向，但 M15 收盘 3875.09 尚未越过确认位 3875.67，且 RR_tp1 仅 0.60611。
- 真实 H4 缺失，外部技术指标不同步且日内接近高位，故突破质量为 unconfirmed、追涨风险为 medium。

公开数据覆盖：external_macro_only。

缺失证据：independently_verified_breaking_news, public_futures_technical_proxy, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
