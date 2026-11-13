# GPT-5.6 黄金小时点位分析 202611130900

数据时间（UTC）：2026-11-13T09:06:16Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_bias；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3906.97-3914.65 | 3910.81 | 3924.87 | 3894.67, 3888.53, 3881.62 | WAIT_ENTRY_ZONE |
| B | sell | 3933.03-3942.37 | 3937.7 | 3953.58 | 3914.35, 3900.34, 3887.89 | WAIT_ENTRY_ZONE |
| C | sell | 3880.89-3887.89 | 3884.39 | 3894.11 | 3873.89, 3863.39, 3838.89 | WAIT_ENTRY_ZONE |
| D | buy | 3887.89-3894.11 | 3891.0 | 3875.29 | 3900.34, 3906.57, 3923.69 | MISSED_ENTRY_DISTANCE |
| E | buy | 3914.35-3923.69 | 3919.02 | 3906.57 | 3937.7, 3951.71, 3970.39 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Sell 与固定 structural_bias=sell，3906.97-3914.65 回撤区邻近 Pivot 3910.56，结构匹配度最高。
- MT5 bid 3900.29 尚未触及 A 入场区，zone_touched=false 且距 expected_fill_price 10.52 超过 max_distance 3.84，因此当前只能 wait。
- C 仍是有效的顺势备选，但尚无 M15 收盘跌破 3880.89 及有效回测；true H4 evidence 不可用，不能补推确认。
- 15m Strong Sell、1h Sell 支持卖方排序，但公开技术数据不同步且 DXY、收益率等缺失，只作 advisory，MT5 仍为执行锚。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
