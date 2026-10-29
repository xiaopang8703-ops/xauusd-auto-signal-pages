# GPT-5.6 黄金小时点位分析 202610291400

数据时间（UTC）：2026-10-29T14:05:55Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4032.72-4041.44 | 4037.08 | 4052.9 | 4018.78, 4011.8, 4003.96 | MISSED_ENTRY_DISTANCE |
| B | sell | 4060.79-4071.32 | 4066.06 | 4083.96 | 4039.73, 4023.94, 4009.9 | WAIT_ENTRY_ZONE |
| C | sell | 4002.01-4009.9 | 4005.95 | 4016.92 | 3994.12, 3982.29, 3954.67 | WAIT_ENTRY_ZONE |
| D | buy | 4009.9-4016.92 | 4013.41 | 3995.7 | 4023.94, 4030.96, 4050.26 | WAIT_ENTRY_ZONE |
| E | buy | 4039.73-4050.26 | 4044.99 | 4030.96 | 4066.06, 4081.85, 4102.91 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Strong Sell、结构偏空，而 M15 动能为 buy，符合 bearish_pullback；A 是顺主方向的第一回撤方案。
- A 的 4032.72-4041.44 回撤区与 4052.90 失效位保持清晰空头结构，但当前 bid 4023.90 已距确认价 13.18，超过 max_distance 4.36，追空风险高。
- A 已触区并出现闭合确认，但 runtime=MISSED_ENTRY_DISTANCE；这影响即时执行而不否定其跟踪价值，因此 executable_now=wait。
- C 尚无有效突破及回测，D/E 的反向结构亦未完成所需 sweep、突破或回测确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：aligned_vendor_broker_day_session, official_BEA_PCE_GDP_release_values_times_revisions, official_ECB_outcome_and_exact_event_blackout_clearance, primary_press_conference_and_CME_policy_probabilities, primary_timestamped_DXY_Treasury_yields_oil_geopolitical_updates, synchronized_public_spot_and_MT5_quotes, true_public_H4_completed_bars
