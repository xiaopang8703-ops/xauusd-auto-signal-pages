# GPT-5.6 黄金小时点位分析 202611171900

数据时间（UTC）：2026-11-17T19:09:03Z；authority=none。

跟踪方案：A/sell；executable_now=veto；veto=true。

市场状态：range_bearish_pressure；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3862.61-3871.66 | 3867.14 | 3883.53 | 3848.11, 3840.87, 3832.72 | MISSED_ENTRY_DISTANCE |
| B | sell | 3893.4-3904.27 | 3898.84 | 3917.31 | 3871.66, 3855.36, 3840.87 | WAIT_ENTRY_ZONE |
| C | sell | 3832.72-3840.87 | 3836.8 | 3848.11 | 3824.57, 3812.34, 3783.82 | WAIT_ENTRY_ZONE |
| D | buy | 3840.87-3848.11 | 3844.49 | 3826.2 | 3855.36, 3862.61, 3882.53 | WAIT_ENTRY_ZONE |
| E | buy | 3871.66-3882.53 | 3877.1 | 3862.61 | 3898.84, 3915.14, 3936.88 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 与 H1 Sell、M15 Strong Sell 及 bearish_continuation 一致，固定回调做空结构优于逆势 D/E；当前 ADX_14=10.522456，区间环境下也优先等待回调而非追逐突破。
- A 已触及入场区并出现收盘确认，但 decision_price=3855.32 距 expected_fill_price=3867.14 达 11.82，显著超过 max_distance=4.52，属于不可接受的过度延伸，当前执行应 veto。
- B 仍是有效的更深回调备选；C 的 3832.72 向下突破、收盘及回测尚未发生，因此 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_public_intraday_technical_indicators, fresh_synchronized_public_spot_and_day_range, live_usd_and_treasury_yields, verified_live_oil_and_geopolitics
