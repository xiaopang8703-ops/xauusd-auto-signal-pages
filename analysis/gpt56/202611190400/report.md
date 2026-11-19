# GPT-5.6 黄金小时点位分析 202611190400

数据时间（UTC）：2026-11-19T04:05:18Z；authority=none。

跟踪方案：B/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3709.25-3719.07 | 3714.16 | 3731.85 | 3693.53, 3685.68, 3676.84 | MISSED_ENTRY_DISTANCE |
| B | sell | 3776.53-3791.18 | 3783.86 | 3808.76 | 3747.23, 3725.26, 3705.73 | WAIT_ENTRY_ZONE |
| C | sell | 3694.74-3705.73 | 3700.23 | 3715.49 | 3683.75, 3667.26, 3628.8 | MISSED_ENTRY_DISTANCE |
| D | buy | 3705.73-3715.49 | 3710.61 | 3685.95 | 3725.26, 3735.03, 3761.88 | MISSED_ENTRY_DISTANCE |
| E | buy | 3747.23-3761.88 | 3754.56 | 3735.03 | 3783.86, 3805.83, 3835.13 | WAIT_ENTRY_ZONE |

排序：B > A > C > E > D

研究理由：

- B 顺应固定 sell 偏向，3776.53-3791.18 深回撤区位于 Pivot 3771.96 上方，且 rr_tp1=1.471084，结构质量优于其他顺势方案。
- 当前 MT5 bid 3725.22，B 尚未触及 entry_zone 且状态为 WAIT_ENTRY_ZONE，因此只能等待，不能立即执行。
- C 所需 3694.74 下破、收盘确认及回测尚未成立，breakout_quality 为 unconfirmed；true H4 与同步公共技术证据均不可用。

公开数据覆盖：external_macro_only。

缺失证据：current_full_day_public_range, current_same_timeframe_public_indicators, public_futures_technical_proxy, synchronized_dollar_treasury_yield_and_oil_levels, synchronized_public_spot_quote, verified_current_geopolitical_update
