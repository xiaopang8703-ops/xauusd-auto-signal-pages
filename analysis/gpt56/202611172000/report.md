# GPT-5.6 黄金小时点位分析 202611172000

数据时间（UTC）：2026-11-17T20:07:48Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3852.49-3860.4 | 3856.44 | 3870.89 | 3839.83, 3833.5, 3826.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3879.38-3888.87 | 3884.12 | 3900.26 | 3860.4, 3846.16, 3833.5 | WAIT_ENTRY_ZONE |
| C | sell | 3826.39-3833.5 | 3829.94 | 3839.83 | 3819.28, 3808.61, 3783.73 | WAIT_ENTRY_ZONE |
| D | buy | 3833.5-3839.83 | 3836.66 | 3820.7 | 3846.16, 3852.49, 3869.89 | WAIT_ENTRY_ZONE |
| E | buy | 3860.4-3869.89 | 3865.14 | 3852.49 | 3884.12, 3898.36, 3917.34 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的固定 sell 几何最贴合 H1/M15 Strong Sell：回调区 3852.49–3860.40 覆盖前收盘/日开盘 3853.17，并位于 Pivot 3862.27 下方。
- A 已触区并出现 M15 确认，但当前 bid 3846.12 距预期成交价 10.32，超过 max_distance 3.96，状态为 MISSED_ENTRY_DISTANCE，因此只能等待而不能追价。
- ADX 11.840615、StochRSI 0.0 且价格接近日内低位，追空过度延伸风险高；C/E 均无已完成的突破回测确认。
- 本周期无 true H4，且实时美元、收益率等公共证据不完整；这些限制不推翻 MT5 锚定的 A 结构，但降低立即执行把握。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_usd_and_treasury_yield_levels, synchronized_public_spot_and_day_range_timestamps, verified_current_numeric_public_intraday_indicators, verified_live_oil_and_geopolitics
