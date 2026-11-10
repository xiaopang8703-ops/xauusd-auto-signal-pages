# GPT-5.6 黄金小时点位分析 202611102200

数据时间（UTC）：2026-11-10T22:05:15Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_near_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4037.48-4045.63 | 4041.56 | 4056.4 | 4024.46, 4017.94, 4010.61 | WAIT_ENTRY_ZONE |
| B | sell | 4067.65-4077.57 | 4072.61 | 4089.47 | 4047.81, 4032.93, 4019.7 | WAIT_ENTRY_ZONE |
| C | sell | 4012.26-4019.7 | 4015.98 | 4026.32 | 4004.82, 3993.66, 3967.62 | WAIT_ENTRY_ZONE |
| D | buy | 4019.7-4026.32 | 4023.01 | 4006.31 | 4032.93, 4039.54, 4057.73 | WAIT_ENTRY_ZONE |
| E | buy | 4047.81-4057.73 | 4052.77 | 4039.54 | 4072.61, 4087.49, 4107.33 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- MT5 报价 4032.88/4032.99 接近日低 4013.74，且 H1 公共技术代理为 Strong Sell，固定 sell 方向的 A 作为首次回抽计划最符合当前结构。
- A 的 4037.48-4045.63 入场区尚未触及，当前 distance=8.68 高于 max_distance=4.08；PULLBACK_FAIL_REJECT 又要求先触区再以 M15 收盘确认，因此只能 wait。
- 价格自日开 4138.09 大幅下跌并逼近 S2=4019.31，RSI(14)=32.471116，追空过度延伸风险高；C 尚无有效跌破及回测确认。
- B 距离更远；E 需先完成反向失效突破；D 的 rr_tp1=0.594012 最弱，故均低于 A。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Fresh post-CPI news update for this slot, Same-time USD, Treasury yields, oil and verified live Fed pricing, Synchronized public spot and indicators at MT5 timestamp, True MT5 H4
