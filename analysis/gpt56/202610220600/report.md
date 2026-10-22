# GPT-5.6 黄金小时点位分析 202610220600

数据时间（UTC）：2026-10-22T06:09:22Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4096.12-4102.73 | 4099.42 | 4111.67 | 4085.54, 4080.25, 4074.3 | WAIT_ENTRY_ZONE |
| B | sell | 4128.7-4138.37 | 4133.53 | 4149.97 | 4109.36, 4094.86, 4081.97 | WAIT_ENTRY_ZONE |
| C | sell | 4074.72-4081.97 | 4078.34 | 4088.42 | 4067.47, 4056.59, 4031.22 | MISSED_ENTRY_DISTANCE |
| D | buy | 4081.97-4088.42 | 4085.19 | 4068.92 | 4094.86, 4101.3, 4119.03 | MISSED_ENTRY_DISTANCE |
| E | buy | 4109.36-4119.03 | 4114.19 | 4101.3 | 4133.53, 4148.04, 4167.38 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- H1与M15公共技术代理均为Strong Sell，ADX14约32，支持A的主方向回撤做空结构。
- A的4096.12-4102.73回撤区最接近当前MT5锚点，但尚未触区，PULLBACK_FAIL_REJECT的闭合M15确认链不完整，因此仅可等待。
- 当前价格已明显低于日开盘与前收盘，且公开RSI接近超卖区，直接追空存在中等过度延伸风险。
- C尚无有效跌破4074.72后的回测失败确认；D与E为逆主方向买入，其中D的TP1风险回报仅0.594345。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_cme_fedwatch_probabilities, independently_verified_us_event_calendar_and_release_times, primary_source_geopolitical_confirmation, resolved_public_overview_technical_header_discrepancy, sub15minute_public_technical_table, synchronized_dxy_yields_oil_ticks, synchronous_public_spot_time_verified
