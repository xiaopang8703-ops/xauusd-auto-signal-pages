# GPT-5.6 黄金小时点位分析 202611112000

数据时间（UTC）：2026-11-11T20:07:00Z；authority=none。

跟踪方案：B/sell；executable_now=wait；veto=false。

市场状态：trend_down_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3987.37-3993.17 | 3990.27 | 4001.12 | 3978.11, 3973.47, 3968.26 | MISSED_ENTRY_DISTANCE |
| B | sell | 4007.07-4014.02 | 4010.54 | 4022.36 | 3993.17, 3982.74, 3973.47 | WAIT_ENTRY_ZONE |
| C | sell | 3968.26-3973.47 | 3970.86 | 3978.11 | 3963.05, 3955.24, 3937.0 | WAIT_ENTRY_ZONE |
| D | buy | 3973.47-3978.11 | 3975.79 | 3964.09 | 3982.74, 3987.37, 4000.12 | WAIT_ENTRY_ZONE |
| E | buy | 3993.17-4000.12 | 3996.64 | 3987.37 | 4010.54, 4020.97, 4034.87 | WAIT_ENTRY_ZONE |

排序：B > A > C > E > D

研究理由：

- B 保持固定 sell 方向并顺应 H1 Strong Sell、trend_down 结构，且 rr_tp1=1.469543，高于 A 与 C；等待较深回拉也可降低当前追空风险。
- MT5 bid=3982.69 已低于 S1=3985.74，RSI(14) 约 20.7，当前下跌明显过度延伸，因此不宜在现价追空。
- B 尚未触及 4007.07-4014.02 entry_zone，固定 PULLBACK_FAIL_REJECT 确认条件未完成，故 executable_now=wait。
- C 尚无 3968.26 下方完成收盘及有效回测证据；true H4 与实时 DXY/美债收益率证据缺失，因此 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, utc_synchronized_public_spot_quote
