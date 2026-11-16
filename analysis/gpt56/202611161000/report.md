# GPT-5.6 黄金小时点位分析 202611161000

数据时间（UTC）：2026-11-16T10:07:17Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：震荡偏空延续；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3869.83-3880.21 | 3875.02 | 3893.67 | 3853.23, 3844.92, 3835.58 | WAIT_ENTRY_ZONE |
| B | sell | 3902.52-3915.03 | 3908.78 | 3930.04 | 3877.5, 3858.74, 3842.06 | WAIT_ENTRY_ZONE |
| C | sell | 3832.68-3842.06 | 3837.37 | 3850.4 | 3823.3, 3809.23, 3776.4 | WAIT_ENTRY_ZONE |
| D | buy | 3842.06-3850.4 | 3846.23 | 3825.18 | 3858.74, 3867.08, 3890.01 | WAIT_ENTRY_ZONE |
| E | buy | 3877.5-3890.01 | 3883.76 | 3867.08 | 3908.78, 3927.54, 3952.56 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 回调结构与 H1/M15 Strong Sell、structural_bias=sell 一致；其 3869.83-3880.21 入场区同时邻近 S1=3872.45 与 Pivot=3881.56，结构适配最佳。
- MT5 bid=3858.70 尚低于 A 入场区，entry_zone_distance=11.13，且 zone_touched=false；固定 M15 先触区后失败回落确认尚未成立，因此 executable_now=wait。
- C 尚未完成对 3832.68 的有效突破与回测，breakout_quality=unconfirmed；当前价格又已低于 S2=3855.54 附近，继续追空存在中等过度延伸风险。
- B 距离较深且位于当日高点 3901.29 上方；D/E 均逆当前固定空头结构。true H4 不可用，未从 M15 推断 H4。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_intrahour_usd_and_treasury_moves, verified_public_quote_utc_timestamp
