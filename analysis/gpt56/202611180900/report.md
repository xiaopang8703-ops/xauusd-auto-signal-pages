# GPT-5.6 黄金小时点位分析 202611180900

数据时间（UTC）：2026-11-18T09:06:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_trend_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3778.62-3787.46 | 3783.04 | 3799.06 | 3764.48, 3757.41, 3749.46 | WAIT_ENTRY_ZONE |
| B | sell | 3804.26-3813.93 | 3809.1 | 3825.53 | 3784.92, 3770.43, 3757.55 | WAIT_ENTRY_ZONE |
| C | sell | 3750.3-3757.55 | 3753.93 | 3763.99 | 3743.05, 3732.18, 3706.8 | MISSED_ENTRY_DISTANCE |
| D | buy | 3757.55-3763.99 | 3760.77 | 3744.5 | 3770.43, 3776.87, 3794.59 | MISSED_ENTRY_DISTANCE |
| E | buy | 3784.92-3794.59 | 3789.76 | 3776.87 | 3809.1, 3823.6, 3842.94 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1与M15均为Strong Sell，ADX_14=44.13059，A作为S3下破后的首个顺势回抽方案，与固定sell结构最一致。
- 现价3770.38尚未触及A入场区3778.62-3787.46，且must_touch_entry_zone_before_confirmation=true、distance=12.66高于max_distance=4.42，因此当前只能wait。
- RSI_14=21.919778且价格已接近日内低位，追空过度延伸风险高；等待A的M15回抽失败确认优于直接执行。
- C要求有效跌破3750.3并完成回测失败，但当前确认收盘3770.0且confirmation_crossed=false，突破质量仍为unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_full_day_range, verified_current_spot_rsi_macd, verified_live_geopolitics
