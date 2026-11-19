# GPT-5.6 黄金小时点位分析 202611190500

数据时间（UTC）：2026-11-19T05:05:18Z；authority=none。

跟踪方案：B/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3709.25-3719.07 | 3714.16 | 3731.85 | 3693.53, 3685.68, 3676.84 | WAIT_ENTRY_ZONE |
| B | sell | 3775.09-3789.03 | 3782.06 | 3805.76 | 3747.21, 3726.31, 3707.73 | WAIT_ENTRY_ZONE |
| C | sell | 3697.28-3707.73 | 3702.51 | 3717.02 | 3686.83, 3671.16, 3634.58 | WAIT_ENTRY_ZONE |
| D | buy | 3707.73-3717.02 | 3712.38 | 3688.92 | 3726.31, 3735.6, 3761.15 | WAIT_ENTRY_ZONE |
| E | buy | 3747.21-3761.15 | 3754.18 | 3735.6 | 3782.06, 3802.97, 3830.85 | WAIT_ENTRY_ZONE |

排序：B > C > A > E > D

研究理由：

- B 与 sell 结构偏向一致，3775.09-3789.03 位于 classic pivot 3771.96 上方，且 rr_tp1=1.470464，为主方向回调方案中结构质量最佳。
- 当前 MT5 bid 3726.26，B 尚未触及入场区，entry_zone_distance=48.83，所需 M15 PULLBACK_FAIL_REJECT 也未形成，因此 executable_now=wait。
- C 可作为跌破延续备选，但 3697.28 下破及有效回测尚未确认；true H4 不可用，不能由 M15 代理推断。
- 公开技术与同步现货、美元及收益率数据缺失；历史宏观材料偏鹰但仅具咨询作用，MT5 仍为执行锚点。

公开数据覆盖：external_macro_only。

缺失证据：current_full_day_public_range, current_same_timeframe_public_indicators, public_futures_technical_proxy, synchronized_dollar_treasury_yield_and_oil_levels, synchronized_public_spot_quote, verified_current_geopolitical_update
