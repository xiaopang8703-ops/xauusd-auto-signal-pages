# GPT-5.6 黄金小时点位分析 202611181100

数据时间（UTC）：2026-11-18T11:07:03Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：high；突破质量：weak。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3774.61-3782.68 | 3778.64 | 3793.37 | 3761.69, 3755.23, 3747.97 | MISSED_ENTRY_DISTANCE |
| B | sell | 3802.06-3811.75 | 3806.9 | 3823.38 | 3782.68, 3768.15, 3755.23 | WAIT_ENTRY_ZONE |
| C | sell | 3747.97-3755.23 | 3751.6 | 3761.69 | 3740.71, 3729.82, 3704.41 | WAIT_ENTRY_ZONE |
| D | buy | 3755.23-3761.69 | 3758.46 | 3742.16 | 3768.15, 3774.61, 3792.37 | WAIT_ENTRY_ZONE |
| E | buy | 3782.68-3792.37 | 3787.52 | 3774.61 | 3806.9, 3821.44, 3840.82 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell、M15 Sell 与固定 sell 结构，且已完成入区触碰及 M15 收盘确认，结构质量最高。
- 当前 bid 3768.11 已低于 A 的确认价 3778.64 达 10.53，超过 max_distance 4.03，MISSED_ENTRY_DISTANCE 只支持等待回撤，不能追价执行。
- 价格已跌破 S3 3773.1、接近日低 3757.34，RSI(14)=26.34 且日内跌幅显著，继续追空的过度延伸风险高。
- C 尚未完成 3747.97 下破与回测；D/E 为逆主方向 buy，其中 D 的 rr_tp1 仅 0.594479，当前均不优于 A。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_matching_day_range, verified_current_oil_and_geopolitics, verified_same_timestamp_spot_technical_indicators
