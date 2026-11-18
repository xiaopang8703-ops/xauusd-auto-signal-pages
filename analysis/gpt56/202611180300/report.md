# GPT-5.6 黄金小时点位分析 202611180300

数据时间（UTC）：2026-11-18T03:08:33Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3809.51-3818.21 | 3813.86 | 3829.64 | 3795.61, 3788.65, 3780.83 | MISSED_ENTRY_DISTANCE |
| B | sell | 3842.58-3854.49 | 3848.53 | 3868.78 | 3818.76, 3800.89, 3785.01 | WAIT_ENTRY_ZONE |
| C | sell | 3776.07-3785.01 | 3780.54 | 3792.95 | 3767.13, 3753.72, 3722.43 | WAIT_ENTRY_ZONE |
| D | buy | 3785.01-3792.95 | 3788.98 | 3768.92 | 3800.89, 3808.83, 3830.67 | WAIT_ENTRY_ZONE |
| E | buy | 3818.76-3830.67 | 3824.72 | 3808.83 | 3848.53, 3866.4, 3890.22 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell、structural_bias=sell 与 bearish_continuation，固定回调做空几何在五个方案中结构一致性最高。
- A 已触及入场区并出现收盘确认，但当前 distance=13.01 超过 max_distance=4.35，且状态为 MISSED_ENTRY_DISTANCE，因此只能等待新的合规机会，不能立即执行。
- MT5 价格接近日内低点且低于 S2=3805.02，RSI_14=26.674705、Stoch_RSI=8.893346，追空过度延伸风险高。
- C 的 3776.07 向下突破及回测尚未确认；D/E 为逆主方向方案，且 D 的 rr_tp1=0.593719，结构质量较弱。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_equivalent_day_range, verified_current_public_intraday_indicators, verified_live_oil_and_geopolitics
