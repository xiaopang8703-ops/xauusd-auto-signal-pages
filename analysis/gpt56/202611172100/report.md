# GPT-5.6 黄金小时点位分析 202611172100

数据时间（UTC）：2026-11-17T21:06:48Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_with_bearish_bias；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3852.49-3860.4 | 3856.44 | 3870.89 | 3839.83, 3833.5, 3826.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3881.47-3890.65 | 3886.06 | 3901.67 | 3863.11, 3849.34, 3837.1 | WAIT_ENTRY_ZONE |
| C | sell | 3830.22-3837.1 | 3833.66 | 3843.22 | 3823.34, 3813.02, 3788.94 | WAIT_ENTRY_ZONE |
| D | buy | 3837.1-3843.22 | 3840.16 | 3824.72 | 3849.34, 3855.46, 3872.29 | WAIT_ENTRY_ZONE |
| E | buy | 3863.11-3872.29 | 3867.7 | 3855.46 | 3886.06, 3899.83, 3918.19 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 公共技术代理为 Strong Sell，固定结构偏向 sell；A 是最接近当前价格的主方向回撤方案，且已完成 entry-zone touch 与 M15 收盘确认。
- A 当前 decision_price=3849.29 距 expected_fill_price=3856.44 为 7.15，超过 max_distance=3.96，因此结构仍可跟踪但不可立即执行。
- ADX_14=13.205794、StochRSI=12.776337，叠加价格接近日内低位，显示弱趋势与短线超伸风险，不宜在回撤卖出价下方追空。
- C 的 3830.22 下破及回测尚未确认；D/E 为逆固定主方向方案，其中 D 的 rr_tp1=0.59456，结构质量最低。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_public_spot_and_day_range, synchronized_usd_and_treasury_yield_levels, verified_current_numeric_public_intraday_indicators, verified_live_oil_and_geopolitics
