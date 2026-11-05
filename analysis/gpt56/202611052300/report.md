# GPT-5.6 黄金小时点位分析 202611052300

数据时间（UTC）：2026-11-05T23:08:28Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_continuation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4096.13-4105.08 | 4100.6 | 4116.81 | 4081.81, 4074.65, 4066.6 | MISSED_ENTRY_DISTANCE |
| B | sell | 4126.54-4137.27 | 4131.91 | 4150.15 | 4105.08, 4088.97, 4074.65 | WAIT_ENTRY_ZONE |
| C | sell | 4066.6-4074.65 | 4070.62 | 4081.81 | 4058.55, 4046.47, 4018.3 | WAIT_ENTRY_ZONE |
| D | buy | 4074.65-4081.81 | 4078.23 | 4060.16 | 4088.97, 4096.13, 4115.81 | WAIT_ENTRY_ZONE |
| E | buy | 4105.08-4115.81 | 4110.44 | 4096.13 | 4131.91, 4148.0, 4169.46 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 几何与 H1 Sell、M15 Strong Sell 及 bearish_continuation 一致，4100.6 附近回抽失败结构优于其余方案。
- A 已触及入场区且 M15 收于 4088.94，满足 PULLBACK_FAIL_REJECT 的方向性确认；但当前距 4100.6 为 11.68，超过 max_entry_distance_from_confirm=4.47，因此只能等待，不能追价执行。
- StochRSI=1.889372 且 ADX=46.563875，当前继续追空的过度延伸风险高；C 与 E 的 BREAKOUT_RETEST_FAIL 均尚未完成突破回测确认。
- true H4 evidence 不可用，且同步公开技术、实时 USD/收益率及 broker_specific_event_blackout_window 缺失，因此不从 M15 推断 H4，MT5 仍为执行锚点。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, contemporaneous_public_technical_table, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
