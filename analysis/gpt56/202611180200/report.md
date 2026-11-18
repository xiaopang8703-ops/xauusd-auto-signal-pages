# GPT-5.6 黄金小时点位分析 202611180200

数据时间（UTC）：2026-11-18T02:09:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3809.51-3818.21 | 3813.86 | 3829.64 | 3795.61, 3788.65, 3780.83 | MISSED_ENTRY_DISTANCE |
| B | sell | 3839.07-3849.5 | 3844.28 | 3862.02 | 3818.21, 3802.56, 3788.65 | WAIT_ENTRY_ZONE |
| C | sell | 3780.83-3788.65 | 3784.74 | 3795.61 | 3773.01, 3761.28, 3733.91 | WAIT_ENTRY_ZONE |
| D | buy | 3788.65-3795.61 | 3792.13 | 3774.57 | 3802.56, 3809.51, 3828.64 | WAIT_ENTRY_ZONE |
| E | buy | 3818.21-3828.64 | 3823.43 | 3809.51 | 3844.28, 3859.93, 3880.79 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- H1 与 M15 公共技术代理均为 Strong Sell，固定 A 顺应 trend_down 与 bearish_continuation，且回调失败做空结构优于逆势 D/E。
- A 已触及 entry_zone 并出现闭合确认，但当前 bid 3802.52 距 expected_fill_price 3813.86 为 11.34，超过 max_distance 4.35，因此结构仍可跟踪但当前只能 wait。
- RSI_14=29.034262、StochRSI=12.934106，且价格接近 S2=3805.02，直接追空的过度延伸风险为 high。
- C 尚未完成 3780.83 下破及有效回测；true H4 不可用且同步公开现货、美元与美债收益率数据缺失，故 breakout_quality=unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_synchronized_public_spot_and_day_range, synchronized_usd_and_treasury_yield_levels, verified_current_public_technical_indicators, verified_live_oil_and_geopolitics
