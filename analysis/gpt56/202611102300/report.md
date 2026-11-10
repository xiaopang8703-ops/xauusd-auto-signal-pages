# GPT-5.6 黄金小时点位分析 202611102300

数据时间（UTC）：2026-11-10T23:09:15Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4037.48-4045.63 | 4041.56 | 4056.4 | 4024.46, 4017.94, 4010.61 | WAIT_ENTRY_ZONE |
| B | sell | 4067.47-4077.23 | 4072.35 | 4088.94 | 4047.95, 4033.3, 4020.28 | WAIT_ENTRY_ZONE |
| C | sell | 4012.96-4020.28 | 4016.62 | 4026.79 | 4005.64, 3994.66, 3969.04 | WAIT_ENTRY_ZONE |
| D | buy | 4020.28-4026.79 | 4023.53 | 4007.1 | 4033.3, 4039.81, 4057.71 | MISSED_ENTRY_DISTANCE |
| E | buy | 4047.95-4057.71 | 4052.83 | 4039.81 | 4072.35, 4086.99, 4106.51 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell 与 structural_bias=sell，并以 4037.48-4045.63 回抽区避免在日内低位直接追空。
- A 当前 zone_touched=false，且 decision_price=4033.25 至 expected_fill_price=4041.56 的 distance=8.31 超过 max_distance=4.08，因此结构有效但只能 wait。
- 现价接近 daily_low=4013.74 与 S2=4019.31，RSI(14)=31.93，继续向下追击的 overextension_risk 较高。
- C 的 4012.96 下破收盘及回测尚未成立，E 的 4057.71 上破回测亦未成立，故 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Synchronized USD, yields, oil and verified live Fed futures, Synchronized external quotes and technicals at MT5 timestamp, True MT5 H4
