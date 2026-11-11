# GPT-5.6 黄金小时点位分析 202611112200

数据时间（UTC）：2026-11-11T22:06:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_trend_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3992.0-3997.18 | 3994.59 | 4004.39 | 3983.72, 3979.58, 3974.92 | WAIT_ENTRY_ZONE |
| B | sell | 4009.6-4015.81 | 4012.7 | 4023.26 | 3997.18, 3987.86, 3979.58 | WAIT_ENTRY_ZONE |
| C | sell | 3974.92-3979.58 | 3977.25 | 3983.72 | 3970.26, 3963.27, 3946.96 | WAIT_ENTRY_ZONE |
| D | buy | 3979.58-3983.72 | 3981.65 | 3971.19 | 3987.86, 3992.0, 4003.39 | MISSED_ENTRY_DISTANCE |
| E | buy | 3997.18-4003.39 | 4000.28 | 3992.0 | 4012.7, 4022.02, 4034.44 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell 与 trend_down，3992.0-3997.18 回抽失败结构优于在日低附近追空，且止损 4004.39、TP1 3983.72 的固定几何仍有效。
- A 当前 zone_touched=false、entry_zone_distance=4.18，且 distance=6.77 超过 max_distance=3.0，因此只能 wait，不能立即执行。
- 现价接近 daily_low=3982.65 与 S1=3985.74，RSI(14)=22.280419、ADX(14)=54.37303，显示强趋势同时存在较高超卖延伸风险。
- C 尚未完成 3974.92 下破及有效回测，D 虽已触发回收条件但 RR_TP1=0.59369 且逆主趋势；B、E 保留为更远条件方案。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, utc_synchronized_public_spot_quote
