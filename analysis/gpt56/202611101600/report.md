# GPT-5.6 黄金小时点位分析 202611101600

数据时间（UTC）：2026-11-10T16:07:15Z；authority=none。

跟踪方案：A/sell；executable_now=veto；veto=true。

市场状态：range_bearish_pressure；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4051.76-4061.96 | 4056.86 | 4075.2 | 4035.44, 4027.28, 4018.1 | MISSED_ENTRY_DISTANCE |
| B | sell | 4084.99-4097.65 | 4091.32 | 4112.84 | 4059.67, 4040.68, 4023.8 | WAIT_ENTRY_ZONE |
| C | sell | 4014.3-4023.8 | 4019.05 | 4032.24 | 4004.8, 3990.55, 3957.3 | WAIT_ENTRY_ZONE |
| D | buy | 4023.8-4032.24 | 4028.02 | 4006.7 | 4040.68, 4049.12, 4072.33 | WAIT_ENTRY_ZONE |
| E | buy | 4059.67-4072.33 | 4066.0 | 4049.12 | 4091.32, 4110.31, 4135.63 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定回调卖出几何与 MT5 日内由 4138.09 下跌至 4040.64、跌破 S1 4078.70，以及公共 H1/M15 Strong Sell 相符。
- A 已触及入场区并完成确认，但当前 bid 4040.64 距 expected_fill_price 4056.86 达 16.22，超过 max_distance 5.10，且 RSI(14) 29.306348，追空过度延伸风险高。
- C 与 E 的突破及回测均未确认；True MT5 H4、同步 USD/收益率及 Fed futures 证据缺失，不能据此提升突破方案。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Synchronized external spot, technicals, USD, yields and oil at MT5 snapshot, True MT5 H4, Verified Fed futures pricing
