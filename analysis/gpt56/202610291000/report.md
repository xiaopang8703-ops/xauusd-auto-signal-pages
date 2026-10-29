# GPT-5.6 黄金小时点位分析 202610291000

数据时间（UTC）：2026-10-29T10:04:55Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4038.09-4045.82 | 4041.95 | 4056.09 | 4025.73, 4019.55, 4012.6 | WAIT_ENTRY_ZONE |
| B | sell | 4064.36-4073.63 | 4068.99 | 4084.75 | 4045.82, 4031.91, 4019.55 | WAIT_ENTRY_ZONE |
| C | sell | 4012.6-4019.55 | 4016.07 | 4025.73 | 4005.65, 3995.22, 3970.9 | WAIT_ENTRY_ZONE |
| D | buy | 4019.55-4025.73 | 4022.64 | 4007.04 | 4031.91, 4038.09, 4055.09 | MISSED_ENTRY_DISTANCE |
| E | buy | 4045.82-4055.09 | 4050.45 | 4038.09 | 4068.99, 4082.9, 4101.44 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 回调几何与 H1 Strong Sell、structural_bias=sell 及 bearish_pullback 一致，4038.09-4045.82 回调区优于追空。
- A 尚未触及 entry_zone，当前距离 expected_fill_price 为 10.08，超过 max_distance=3.87，因此结构有效但 executable_now=wait。
- 当前价接近 S1=4024.02 和日内低点 4015.89，立即卖出存在较高追空风险；C/E 也未形成已完成的突破回测。
- true H4 与关键事件时点确认缺失，公共宏观证据仅作辅助，不覆盖 MT5 锚点或改写 A-E 几何。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：aligned_vendor_and_broker_day_session, primary_PCE_GDP_calendar_exact_release_times_and_event_blackout_clearance, primary_press_conference_and_CME_rate_probabilities, primary_timestamped_DXY_Treasury_yields_oil_and_geopolitical_updates, synchronized_public_spot_and_MT5_quotes, true_public_H4_completed_bars
