# GPT-5.6 黄金小时点位分析 202611180600

数据时间（UTC）：2026-11-18T06:05:18Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range_near_day_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3791.38-3802.32 | 3796.85 | 3816.44 | 3773.88, 3765.13, 3755.29 | MISSED_ENTRY_DISTANCE |
| B | sell | 3829.52-3841.66 | 3835.59 | 3856.23 | 3805.24, 3787.02, 3770.83 | WAIT_ENTRY_ZONE |
| C | sell | 3761.72-3770.83 | 3766.27 | 3778.92 | 3752.61, 3738.94, 3707.06 | WAIT_ENTRY_ZONE |
| D | buy | 3770.83-3778.92 | 3774.88 | 3754.43 | 3787.02, 3795.12, 3817.38 | WAIT_ENTRY_ZONE |
| E | buy | 3805.24-3817.38 | 3811.31 | 3795.12 | 3835.59, 3853.8, 3878.08 | WAIT_ENTRY_ZONE |

排序：A > B > E > C > D

研究理由：

- 结构偏向为 sell、战术动量为 buy，属于 bearish_pullback；A 的首层回撤卖出几何最贴合当前结构。
- MT5 现价 3787.02 已低于 S2 3805.02、接近日低 3780.18 与 S3 3773.10，继续追空存在较高过度延伸风险。
- A 虽已完成触区和确认，但当前 distance=9.87 超过 max_distance=5.47，状态为 MISSED_ENTRY_DISTANCE，因此结构仍可跟踪但即时应 wait。
- C 尚无有效突破及回测，D/E 为逆向方案；同时 true H4 和公共技术代理不可用，不能据此升级逆转或突破判断。

公开数据覆盖：external_macro_only。

缺失证据：public_futures_technical_proxy, synchronized_dollar_and_treasury_yields, synchronized_public_spot_and_day_range, verified_current_public_intraday_oscillators, verified_live_oil_and_geopolitics
