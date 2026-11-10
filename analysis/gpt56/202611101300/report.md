# GPT-5.6 黄金小时点位分析 202611101300

数据时间（UTC）：2026-11-10T13:05:00Z；authority=none。

跟踪方案：A/sell；executable_now=veto；veto=true。

市场状态：bearish_intraday_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4078.22-4085.47 | 4081.84 | 4095.16 | 4066.62, 4060.82, 4054.3 | MISSED_ENTRY_DISTANCE |
| B | sell | 4103.86-4112.39 | 4108.12 | 4122.63 | 4086.8, 4073.99, 4062.61 | WAIT_ENTRY_ZONE |
| C | sell | 4056.2-4062.61 | 4059.4 | 4068.3 | 4049.79, 4040.17, 4017.74 | WAIT_ENTRY_ZONE |
| D | buy | 4062.61-4068.3 | 4065.45 | 4051.07 | 4073.99, 4079.68, 4095.33 | WAIT_ENTRY_ZONE |
| E | buy | 4086.8-4095.33 | 4091.07 | 4079.68 | 4108.12, 4120.92, 4137.98 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 sell 几何顺应 H1 Strong Sell；其 4078.22-4085.47 回抽区覆盖已跌破的 S1 4078.70，且已发生 zone touch 与 M15 确认。
- MT5 bid 4073.94 距 A 的确认/预期成交价 7.90，超过 max_distance 3.62，当前追空具有高过度延伸风险。
- CPI 定于 13:30 UTC、距快照仅 25 分钟；同时缺少同步 USD/收益率证据及 True MT5 H4，构成即时执行的正面研究否决。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Current USD, Treasury yields, oil and Fed pricing aligned to MT5, Synchronized external spot and technicals at the MT5 timestamp, True MT5 H4
