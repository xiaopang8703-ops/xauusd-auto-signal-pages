# GPT-5.6 黄金小时点位分析 202611172300

数据时间（UTC）：2026-11-17T23:06:03Z；authority=none。

跟踪方案：B/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：low；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3852.49-3860.4 | 3856.44 | 3870.89 | 3839.83, 3833.5, 3826.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3883.89-3892.95 | 3888.42 | 3903.82 | 3865.77, 3852.19, 3840.11 | WAIT_ENTRY_ZONE |
| C | sell | 3833.32-3840.11 | 3836.72 | 3846.15 | 3826.53, 3816.35, 3792.58 | WAIT_ENTRY_ZONE |
| D | buy | 3840.11-3846.15 | 3843.13 | 3827.89 | 3852.19, 3858.23, 3874.83 | WAIT_ENTRY_ZONE |
| E | buy | 3865.77-3874.83 | 3870.3 | 3858.23 | 3888.42, 3902.01, 3920.13 | WAIT_ENTRY_ZONE |

排序：B > A > C > E > D

研究理由：

- B 的 sell 几何与 structural_bias=sell、1H Strong Sell 一致，且 entry_zone 3883.89-3892.95 同 daily_high=3891.05、R1=3892.19 形成上沿阻力汇合，rr_tp1=1.470779。
- ADX_14=14.022362 显示区间动能偏弱，C/E 尚无有效突破及回测确认；true H4 不可用，因此不能提高突破方案等级。
- 当前 bid=3852.15，B 为 WAIT_ENTRY_ZONE，距 entry_zone 31.74，尚未触区并完成 M15 PULLBACK_FAIL_REJECT；这要求 wait，但不否定其结构有效性。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_dollar_and_treasury_yield_levels, synchronized_public_spot_and_new_session_day_range, verified_current_numeric_public_intraday_indicators, verified_live_oil_and_geopolitics
