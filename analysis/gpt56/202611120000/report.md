# GPT-5.6 黄金小时点位分析 202611120000

数据时间（UTC）：2026-11-12T00:08:45Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3976.84-3981.79 | 3979.32 | 3988.72 | 3968.92, 3964.96, 3960.51 | MISSED_ENTRY_DISTANCE |
| B | sell | 3993.65-3999.58 | 3996.61 | 4006.7 | 3981.79, 3972.88, 3964.96 | MISSED_ENTRY_DISTANCE |
| C | sell | 3960.51-3964.96 | 3962.74 | 3968.92 | 3956.06, 3949.39, 3933.81 | WAIT_ENTRY_ZONE |
| D | buy | 3964.96-3968.92 | 3966.94 | 3956.95 | 3972.88, 3976.84, 3987.72 | WAIT_ENTRY_ZONE |
| E | buy | 3981.79-3987.72 | 3984.76 | 3976.84 | 3996.61, 4005.51, 4017.37 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Strong Sell、M15 Strong Sell 与固定 sell 结构，且已完成入区及 M15 收盘确认，固定几何仍是五案中最契合者。
- MT5 bid 3972.83 已距 A 确认价 3979.32 达 6.49，超过 max_distance=3.0；当前追空风险高，因此 executable_now=wait。
- RSI(14)=20.071635、StochRSI=16.621308 显示明显超卖，支持等待回抽而非在现价追击；true H4 缺失，不据 M15 推断。
- C 尚未完成 3960.51 下破及回测，D/E 为逆固定主方向方案且当前确认不足，其中 D 的 rr_tp1=0.594595 最弱。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, public_technical_snapshot_synchronized_with_mt5, utc_synchronized_public_spot_quote
