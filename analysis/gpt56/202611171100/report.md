# GPT-5.6 黄金小时点位分析 202611171100

数据时间（UTC）：2026-11-17T11:05:17Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pressure；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3861.5-3867.39 | 3864.44 | 3875.47 | 3852.06, 3847.35, 3842.04 | MISSED_ENTRY_DISTANCE |
| B | sell | 3881.55-3888.63 | 3885.09 | 3897.13 | 3867.39, 3856.78, 3847.35 | WAIT_ENTRY_ZONE |
| C | sell | 3842.04-3847.35 | 3844.69 | 3852.06 | 3836.73, 3828.77, 3810.18 | WAIT_ENTRY_ZONE |
| D | buy | 3847.35-3852.06 | 3849.7 | 3837.79 | 3856.78, 3861.5, 3874.47 | WAIT_ENTRY_ZONE |
| E | buy | 3867.39-3874.47 | 3870.93 | 3861.5 | 3885.09, 3895.71, 3909.87 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 3861.50–3867.39 回调卖出区覆盖 classic pivot 3862.27，且与 H1/M15 Strong Sell、固定 structural_bias=sell 一致，结构上是最直接的主方向方案。
- MT5 bid 3856.74 已距 A 的 expected_fill_price 3864.44 达 7.70，超过 max_distance 3.00，runtime=MISSED_ENTRY_DISTANCE；当前追空风险高，应等待而非立即执行。
- C 尚未完成 3842.04 下破并回测，E 也未完成 3874.47 上破回测；true H4 缺失且公共宏观覆盖不完整，因此 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
