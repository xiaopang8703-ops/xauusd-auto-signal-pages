# GPT-5.6 黄金小时点位分析 202611061000

数据时间（UTC）：2026-11-06T10:05:28Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4063.21-4071.99 | 4067.6 | 4083.53 | 4049.17, 4042.14, 4034.24 | WAIT_CONFIRMATION |
| B | sell | 4105.07-4115.29 | 4110.18 | 4127.55 | 4084.63, 4069.31, 4055.69 | WAIT_ENTRY_ZONE |
| C | sell | 4048.03-4055.69 | 4051.86 | 4062.5 | 4040.37, 4028.88, 4002.07 | WAIT_ENTRY_ZONE |
| D | buy | 4055.69-4062.5 | 4059.1 | 4041.9 | 4069.31, 4076.12, 4094.85 | WAIT_ENTRY_ZONE |
| E | buy | 4084.63-4094.85 | 4089.74 | 4076.12 | 4110.18, 4125.51, 4145.95 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1结构与战术动量均为sell，而M15 Strong Buy更符合空头结构中的反弹；A是当前固定几何中最直接的主方向回调方案。
- A已触及entry_zone且距离、点差与新鲜度合格，但M15 PULLBACK_FAIL_REJECT尚未成立：confirmation_close=4072.56，confirmation_crossed=false，因此当前只能wait。
- 价格低于daily_open/prev_close及MT5 pivot_classic=4101.72，但已下移约1.46个ATR_H1，且StochRSI=80.379526，追空存在中等过度延伸风险。
- C与E均无已完成的突破回测确认；真实H4缺失、公共证据不同步且13:30 UTC有Employment Situation，不能据此升级为即时执行。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
