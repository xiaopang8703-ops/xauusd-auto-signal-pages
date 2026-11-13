# GPT-5.6 黄金小时点位分析 202611130600

数据时间（UTC）：2026-11-13T06:07:16Z；authority=none。

跟踪方案：A/sell；executable_now=veto；veto=true。

市场状态：range_bearish；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3903.1-3911.67 | 3907.39 | 3922.96 | 3889.38, 3882.52, 3874.8 | MISSED_ENTRY_DISTANCE |
| B | sell | 3932.25-3942.54 | 3937.39 | 3954.89 | 3911.67, 3896.24, 3882.52 | WAIT_ENTRY_ZONE |
| C | sell | 3874.8-3882.52 | 3878.66 | 3889.38 | 3867.08, 3855.5, 3828.48 | WAIT_ENTRY_ZONE |
| D | buy | 3882.52-3889.38 | 3885.95 | 3868.62 | 3896.24, 3903.1, 3921.96 | WAIT_ENTRY_ZONE |
| E | buy | 3911.67-3921.96 | 3916.82 | 3903.1 | 3937.39, 3952.83, 3973.41 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A符合H1与M15卖出倾向，3903.10-3911.67回抽失败结构优于追击区间低位。
- A虽已触区并出现确认，但当前bid 3896.20距确认/预期成交价3907.39达11.19，超过max_distance 4.29，立即追空构成不可接受的过度延伸。
- C尚未完成3874.80下破及回测；E也未完成3921.96上破确认，当前breakout_quality为unconfirmed。
- 真H4证据缺失，外部技术读数不同步且宏观覆盖不完整，因此不以公共代理改写MT5锚点或固定A-E结构。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
