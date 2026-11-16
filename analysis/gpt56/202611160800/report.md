# GPT-5.6 黄金小时点位分析 202611160800

数据时间（UTC）：2026-11-16T08:08:02Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_pullback；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3859.27-3870.75 | 3865.01 | 3885.53 | 3840.91, 3831.72, 3821.39 | MISSED_ENTRY_DISTANCE |
| B | sell | 3902.12-3914.92 | 3908.52 | 3930.28 | 3876.52, 3857.31, 3840.24 | WAIT_ENTRY_ZONE |
| C | sell | 3830.63-3840.24 | 3835.43 | 3848.77 | 3821.02, 3806.61, 3772.97 | WAIT_ENTRY_ZONE |
| D | buy | 3840.24-3848.77 | 3844.51 | 3822.94 | 3857.31, 3865.85, 3889.32 | WAIT_ENTRY_ZONE |
| E | buy | 3876.52-3889.32 | 3882.92 | 3865.85 | 3908.52, 3927.72, 3953.32 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- H1 为 Strong Sell，结构方向为 sell；MT5 现价低于 Pivot 3881.56、前收盘 3889.35 与日开盘 3889.34，因此首个顺势回撤方案 A 的结构匹配度最高。
- A 已触及入场区且 M15 收盘 3856.52 完成对 3865.01 的下破确认，但当前 bid 3857.26 距确认位 7.75，超过 max_distance 5.74，故应 wait 而非追价执行。
- 现价接近 S2 3855.54，且已明显低于日内高点 3901.29；即时追空存在高过度延伸风险，同时 C 所需的 3830.63 下破及回测尚未确认。
- 公共证据覆盖不完整且 true H4 不可用；GC=F 与现货不同步，因此仅作辅助，未形成推翻 MT5 锚点与 A 固定几何的材料矛盾。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_intrahour_usd_and_treasury_moves, verified_public_quote_utc_timestamp
