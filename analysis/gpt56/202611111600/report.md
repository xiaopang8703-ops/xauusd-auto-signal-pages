# GPT-5.6 黄金小时点位分析 202611111600

数据时间（UTC）：2026-11-11T16:09:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_near_daily_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4010.56-4017.67 | 4014.11 | 4027.22 | 3999.16, 3993.47, 3987.06 | MISSED_ENTRY_DISTANCE |
| B | sell | 4034.77-4043.32 | 4039.04 | 4053.58 | 4017.67, 4004.86, 3993.47 | WAIT_ENTRY_ZONE |
| C | sell | 3987.06-3993.47 | 3990.26 | 3999.16 | 3980.65, 3971.04, 3948.6 | WAIT_ENTRY_ZONE |
| D | buy | 3993.47-3999.16 | 3996.31 | 3981.93 | 4004.86, 4010.56, 4026.22 | WAIT_ENTRY_ZONE |
| E | buy | 4017.67-4026.22 | 4021.94 | 4010.56 | 4039.04, 4051.87, 4068.97 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- H1与M15公共技术代理均为Strong Sell，且MT5价格位于日内低位，A顺应固定sell结构并提供最近的回撤跟踪几何。
- A已触及入场区并出现收盘确认，但当前bid 4004.81距确认价4014.11为9.30，超过max_distance 3.56，因此结构仍可跟踪但不可立即执行。
- RSI(14)约25.4、StochRSI为0且价格接近日低4000.63，追空过度延伸风险高；C尚无有效突破3987.06及回测确认。
- D逆主方向且rr_tp1仅0.594576；E同为逆向方案且未完成4026.22突破确认，结构质量均弱于A、B、C。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, utc_synchronized_public_spot_quote
