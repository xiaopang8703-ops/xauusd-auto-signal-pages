# GPT-5.6 黄金小时点位分析 202611111200

数据时间（UTC）：2026-11-11T12:06:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4049.28-4054.61 | 4051.95 | 4062.0 | 4040.74, 4036.48, 4031.68 | MISSED_ENTRY_DISTANCE |
| B | sell | 4067.39-4073.78 | 4070.59 | 4081.45 | 4054.61, 4045.01, 4036.48 | WAIT_ENTRY_ZONE |
| C | sell | 4031.68-4036.48 | 4034.08 | 4040.74 | 4026.88, 4019.68, 4002.88 | WAIT_ENTRY_ZONE |
| D | buy | 4036.48-4040.74 | 4038.61 | 4027.84 | 4045.01, 4049.28, 4061.0 | WAIT_ENTRY_ZONE |
| E | buy | 4054.61-4061.0 | 4057.81 | 4049.28 | 4070.59, 4080.17, 4092.95 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 与 H1 Sell、M15 Strong Sell 及 bearish_continuation 一致，且已完成 entry-zone touch 与 closed-bar confirmation，固定几何仍具最佳顺势结构。
- A 当前 distance=6.98，超过 max_distance=3.0，状态为 MISSED_ENTRY_DISTANCE；不可追价，故 executable_now=wait。
- C 尚未完成 4031.68 下破与回测确认；D/E 为逆原始 sell thesis 的 buy 情景，D 的 rr_tp1=0.594243 尤弱。
- true H4 evidence unavailable；公共技术信号存在分歧且缺少同步美元、收益率与现货报价，仅作 MT5 anchor 的辅助证据。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_real_yields, public_quote_utc_offset, synchronized_dollar_oil_and_yield_quotes, synchronized_public_spot_tick
