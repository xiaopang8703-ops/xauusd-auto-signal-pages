# GPT-5.6 黄金小时点位分析 202611101000

数据时间（UTC）：2026-11-10T10:07:15Z；authority=none。

跟踪方案：B/sell；executable_now=wait；veto=false。

市场状态：bearish_trend_near_S1；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4087.63-4095.14 | 4091.39 | 4105.15 | 4075.61, 4069.61, 4062.85 | MISSED_ENTRY_DISTANCE |
| B | sell | 4113.16-4122.17 | 4117.66 | 4132.98 | 4095.14, 4081.62, 4069.61 | MISSED_ENTRY_DISTANCE |
| C | sell | 4062.85-4069.61 | 4066.23 | 4075.61 | 4056.09, 4045.95, 4022.29 | WAIT_ENTRY_ZONE |
| D | buy | 4069.61-4075.61 | 4072.61 | 4057.44 | 4081.62, 4087.63, 4104.15 | WAIT_ENTRY_ZONE |
| E | buy | 4095.14-4104.15 | 4099.64 | 4087.63 | 4117.66, 4131.18, 4149.2 | MISSED_ENTRY_DISTANCE |

排序：B > A > C > E > D

研究理由：

- B 的 sell 回撤区 4113.16-4122.17 与 Pivot 4113.71 重合，符合 H1 Strong Sell、trend_down 与 bearish_continuation，且 rr_tp1=1.469974 优于 A/C。
- MT5 bid 4081.58 已接近日低 4081.13 与 S1 4078.70，距离 B 预期成交价 4117.66 为 36.08，超过 max_distance 4.5，因此结构上跟踪 B，但当前只能 wait。
- 当日自 4138.09 下跌至 4081.62 附近，且 RSI14=38.65、StochRSI=21.56、ADX14=17.90，低位追空的过度延伸风险高。
- C 尚未完成 4062.85 下破及回测确认；D 逆 sell 主结构且 rr_tp1=0.593935，E 也未完成 4104.15 上破回测。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Live USD, yields, oil and Fed pricing at MT5 snapshot, Synchronized external spot at MT5 snapshot, True MT5 H4
