# GPT-5.6 黄金小时点位分析 202611171400

数据时间（UTC）：2026-11-17T14:05:17Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3861.5-3867.39 | 3864.44 | 3875.47 | 3852.06, 3847.35, 3842.04 | MISSED_ENTRY_DISTANCE |
| B | sell | 3888.96-3897.31 | 3893.14 | 3907.33 | 3872.26, 3859.73, 3848.59 | WAIT_ENTRY_ZONE |
| C | sell | 3842.33-3848.59 | 3845.46 | 3854.16 | 3836.07, 3826.68, 3804.77 | MISSED_ENTRY_DISTANCE |
| D | buy | 3848.59-3854.16 | 3851.38 | 3837.32 | 3859.73, 3865.3, 3880.61 | MISSED_ENTRY_DISTANCE |
| E | buy | 3872.26-3880.61 | 3876.44 | 3865.3 | 3893.14, 3905.66, 3922.36 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 3861.50–3867.39 卖出区覆盖 MT5 经典枢轴 3862.27，符合固定 sell 结构及 H1/M15 Strong Sell 背景。
- A 已触区并出现收盘确认，但当前 distance=4.75 超过 max_distance=3.0，且状态为 MISSED_ENTRY_DISTANCE；结构仍可跟踪，当前应等待而非追价。
- ADX(14)=10.90 显示趋势力度弱，StochRSI=20.14 接近超卖；C 尚无有效向下突破确认，追空过度延伸风险为 medium。
- 真实 H4 缺失，公共报价与技术指标不同步，且 USD、收益率和油价组不可用，因此公共证据仅作辅助。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news_other_than_scheduled_release, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
