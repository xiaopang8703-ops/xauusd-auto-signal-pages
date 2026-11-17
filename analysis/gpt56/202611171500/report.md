# GPT-5.6 黄金小时点位分析 202611171500

数据时间（UTC）：2026-11-17T15:05:47Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3863.79-3871.99 | 3867.89 | 3882.82 | 3850.69, 3844.13, 3836.76 | MISSED_ENTRY_DISTANCE |
| B | sell | 3891.65-3901.48 | 3896.57 | 3913.28 | 3871.99, 3857.24, 3844.13 | WAIT_ENTRY_ZONE |
| C | sell | 3836.76-3844.13 | 3840.45 | 3850.69 | 3829.39, 3818.34, 3792.54 | WAIT_ENTRY_ZONE |
| D | buy | 3844.13-3850.69 | 3847.41 | 3830.86 | 3857.24, 3863.79, 3881.82 | WAIT_ENTRY_ZONE |
| E | buy | 3871.99-3881.82 | 3876.9 | 3863.79 | 3896.57, 3911.31, 3930.97 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- H1 为 Strong Sell（score=-3），M15 为 Buy（score=1），结合 ADX(14)=10.453196 的区间环境，更符合 bearish_pullback，结构上优先跟踪顺势回撤方案 A。
- A 的 3863.79-3871.99 回撤区靠近 Pivot 3862.27，且已触区并出现低于 3867.89 的闭合确认；固定卖出几何与当前结构一致。
- 当前 bid=3857.2 距 A 的 expected_fill_price=3867.89 达 10.69，超过 max_distance=4.1，状态为 MISSED_ENTRY_DISTANCE；继续追空不满足即时执行条件，应等待而非改写方案。
- 本周期缺少 true H4、同步现货报价及最新 USD/收益率/Fed 数据，公共证据仅作辅助，MT5 锚点优先。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_public_technical_indicators, independently_verified_breaking_news_other_than_scheduled_release, synchronized_mt5_public_quote, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
