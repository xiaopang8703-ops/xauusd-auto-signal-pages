# GPT-5.6 黄金小时点位分析 202611111800

数据时间（UTC）：2026-11-11T18:08:30Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_trend_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3997.86-4005.39 | 4001.62 | 4015.41 | 3985.82, 3979.8, 3973.03 | MISSED_ENTRY_DISTANCE |
| B | sell | 4023.43-4032.45 | 4027.94 | 4043.27 | 4005.39, 3991.84, 3979.8 | WAIT_ENTRY_ZONE |
| C | sell | 3973.03-3979.8 | 3976.41 | 3985.82 | 3966.26, 3956.11, 3932.41 | WAIT_ENTRY_ZONE |
| D | buy | 3979.8-3985.82 | 3982.81 | 3967.61 | 3991.84, 3997.86, 4014.41 | WAIT_ENTRY_ZONE |
| E | buy | 4005.39-4014.41 | 4009.9 | 3997.86 | 4027.94, 4041.47, 4059.51 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 的固定回调做空几何与 trend_down、H1 Strong Sell 及 ADX(14)=42.43 一致，结构质量优于逆势 D/E。
- A 当前为 MISSED_ENTRY_DISTANCE：decision_price=3991.79，距 expected_fill_price=4001.62 为 9.83，超过 max_distance=3.76，因此保留跟踪但不可立即执行。
- RSI(14)=22.37、StochRSI=8.97，且价格接近日内低点与 S1=3985.74，追空过度延伸风险高。
- C 尚无有效突破收盘及回测确认；true H4、实时 DXY/美债收益率与同步公开现货报价缺失，不能据此提升即时执行性。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, utc_synchronized_public_spot_quote
