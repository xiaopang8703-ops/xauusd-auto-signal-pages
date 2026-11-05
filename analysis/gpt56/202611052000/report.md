# GPT-5.6 黄金小时点位分析 202611052000

数据时间（UTC）：2026-11-05T20:06:13Z；authority=none。

跟踪方案：A/buy；executable_now=wait；veto=false。

市场状态：bullish_range；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4101.89-4110.84 | 4106.36 | 4080.45 | 4122.34, 4135.11, 4160.65 | READY_TO_SUBMIT_DRY_RUN |
| B | buy | 4081.45-4091.67 | 4086.56 | 4065.12 | 4101.89, 4122.34, 4135.11 | WAIT_ENTRY_ZONE |
| C | buy | 4122.34-4135.11 | 4128.73 | 4110.84 | 4160.65, 4192.57, 4224.5 | WAIT_ENTRY_ZONE |
| D | sell | 4118.34-4122.34 | 4120.34 | 4154.26 | 4110.84, 4101.89, 4091.67 | WAIT_ENTRY_ZONE |
| E | sell | 4081.45-4091.67 | 4086.56 | 4101.89 | 4050.79, 4043.12, 4004.8 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1/M15 Buy 与 structural_bias=buy，已触及 4101.89–4110.84，并由已收 M15 在 4106.36 上方确认。
- MT5 ask=4104.50 位于 A 入场区且 runtime 显示 within_max_distance=true；但 TP1 RR=0.61675，结构优势有限。
- verified_high_impact_blackout_times 不可用，且公开现货报价未与 MT5 同步，当前缺少支持立即执行所需的事件时点证据，因此等待而非 veto。
- C 尚未完成 4135.11 突破及回踩，breakout_quality=unconfirmed；D/E 与当前买方结构相反。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5, verified_high_impact_blackout_times
