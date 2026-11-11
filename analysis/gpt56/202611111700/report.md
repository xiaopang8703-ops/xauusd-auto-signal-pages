# GPT-5.6 黄金小时点位分析 202611111700

数据时间（UTC）：2026-11-11T17:09:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4004.64-4011.69 | 4008.16 | 4021.16 | 3993.34, 3987.7, 3981.35 | MISSED_ENTRY_DISTANCE |
| B | sell | 4028.63-4037.1 | 4032.86 | 4047.26 | 4011.69, 3998.99, 3987.7 | WAIT_ENTRY_ZONE |
| C | sell | 3981.35-3987.7 | 3984.52 | 3993.34 | 3975.0, 3965.48, 3943.25 | WAIT_ENTRY_ZONE |
| D | buy | 3987.7-3993.34 | 3990.52 | 3976.27 | 3998.99, 4004.64, 4020.16 | WAIT_ENTRY_ZONE |
| E | buy | 4011.69-4020.16 | 4015.93 | 4004.64 | 4032.86, 4045.57, 4062.51 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A与H1/M15 Strong Sell及固定sell结构一致，且已完成entry_zone触碰和PULLBACK_FAIL_REJECT确认，结构质量优于其余方案。
- 当前bid 3998.95距A确认价4008.16为9.21，超过max_distance 3.53，runtime为MISSED_ENTRY_DISTANCE，因此不可追空，executable_now=wait。
- RSI_14约24.21、StochRSI约7.66且价格接近日低3998.58，短线超卖与延伸风险高；C尚未完成3981.35下破及回测，breakout_quality仍为unconfirmed。
- D和E均为逆固定主方向的buy方案，当前尚无有效sweep/reclaim或far-side invalidation证据；true H4不可用，未作H4推断。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, utc_synchronized_public_spot_quote
