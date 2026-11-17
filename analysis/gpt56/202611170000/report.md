# GPT-5.6 黄金小时点位分析 202611170000

数据时间（UTC）：2026-11-17T00:05:47Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3861.92-3868.76 | 3865.34 | 3877.97 | 3850.98, 3845.51, 3839.35 | MISSED_ENTRY_DISTANCE |
| B | sell | 3885.92-3893.54 | 3889.73 | 3902.68 | 3870.68, 3859.26, 3849.11 | WAIT_ENTRY_ZONE |
| C | sell | 3843.39-3849.11 | 3846.25 | 3854.18 | 3837.67, 3829.09, 3809.07 | WAIT_ENTRY_ZONE |
| D | buy | 3849.11-3854.18 | 3851.64 | 3838.81 | 3859.26, 3864.34, 3878.3 | MISSED_ENTRY_DISTANCE |
| E | buy | 3870.68-3878.3 | 3874.49 | 3864.34 | 3889.73, 3901.16, 3916.4 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 sell 方向符合 H1 Strong Sell 与 bearish_pullback 结构，3861.92-3868.76 入场区同时覆盖经典枢轴 3862.27。
- A 已完成入区及闭合柱确认，但当前 distance=6.13 超过 max_distance=3.42，状态为 MISSED_ENTRY_DISTANCE，因此只能等待而不能立即追价。
- 当前 M15 Buy、RSI 约 47 且 StochRSI=100，显示区间内反弹与短线过热并存；真 H4 缺失，不能据此强化趋势结论。
- C、E 的突破与回测均未确认；D 逆 sell 结构且 rr_tp1=0.59392，结构质量最低。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
