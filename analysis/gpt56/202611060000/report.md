# GPT-5.6 黄金小时点位分析 202611060000

数据时间（UTC）：2026-11-06T00:07:28Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_trend_high_volatility；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4110.83-4120.73 | 4115.78 | 4133.61 | 4094.99, 4087.07, 4078.16 | WAIT_ENTRY_ZONE |
| B | sell | 4144.49-4156.37 | 4150.43 | 4170.63 | 4120.73, 4102.91, 4087.07 | WAIT_ENTRY_ZONE |
| C | sell | 4078.16-4087.07 | 4082.61 | 4094.99 | 4069.25, 4055.88, 4024.7 | MISSED_ENTRY_DISTANCE |
| D | buy | 4087.07-4094.99 | 4091.03 | 4071.03 | 4102.91, 4110.83, 4132.61 | MISSED_ENTRY_DISTANCE |
| E | buy | 4120.73-4132.61 | 4126.67 | 4110.83 | 4150.43, 4168.25, 4192.01 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 与 H1 Sell、M15 Strong Sell、ADX 46.83 的高波动空头延续结构一致，首个回撤区 4110.83-4120.73 优于反向 D/E。
- A 尚未触及入场区，且固定 M15 PULLBACK_FAIL_REJECT 确认链未完成，因此当前只能 wait。
- C 尚无 4078.16 下方有效收盘及回测失败证据，breakout_quality 为 unconfirmed；B 虽结构有效但属于更深且更远的回撤。
- 真实 H4 缺失，公共现货与 MT5 未同步，宏观覆盖不完整；这些限制降低置信度，但不足以否定 A 的固定结构。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
