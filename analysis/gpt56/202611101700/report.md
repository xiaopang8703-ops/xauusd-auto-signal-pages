# GPT-5.6 黄金小时点位分析 202611101700

数据时间（UTC）：2026-11-10T17:07:45Z；authority=none。

跟踪方案：A/sell；executable_now=veto；veto=true。

市场状态：bearish_trend_oversold；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4031.2-4042.91 | 4037.05 | 4057.96 | 4012.48, 4003.11, 3992.58 | MISSED_ENTRY_DISTANCE |
| B | sell | 4071.01-4085.06 | 4078.04 | 4101.92 | 4042.91, 4021.84, 4003.11 | WAIT_ENTRY_ZONE |
| C | sell | 3992.58-4003.11 | 3997.85 | 4012.48 | 3982.05, 3966.25, 3929.4 | WAIT_ENTRY_ZONE |
| D | buy | 4003.11-4012.48 | 4007.8 | 3984.16 | 4021.84, 4031.2, 4056.96 | WAIT_ENTRY_ZONE |
| E | buy | 4042.91-4056.96 | 4049.93 | 4031.2 | 4078.04, 4099.11, 4127.21 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1/M15 Strong Sell 与 trend_down，固定回调做空几何比逆势 D/E 更符合当前结构。
- MT5 4021.84 已接近 S2 4019.31 与日内低点 4013.74，RSI 24.16 且 A 的 distance=15.26 超过 max_distance=5.86，立即追空存在高过度延伸风险。
- C 尚未完成 3992.58 下破及有效回测，breakout_quality=unconfirmed；B 虽顺势但尚未触及 4071.01-4085.06。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：Synchronized external spot, technicals, USD, yields and oil at MT5 snapshot, True MT5 H4, Verified live Fed futures pricing
