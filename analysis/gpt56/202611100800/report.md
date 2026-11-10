# GPT-5.6 黄金小时点位分析 202611100800

数据时间（UTC）：2026-11-10T08:06:30Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4118.49-4126.55 | 4122.52 | 4137.22 | 4105.61, 4099.16, 4091.91 | MISSED_ENTRY_DISTANCE |
| B | sell | 4144.97-4153.25 | 4149.11 | 4163.19 | 4128.41, 4115.98, 4104.93 | WAIT_ENTRY_ZONE |
| C | sell | 4098.72-4104.93 | 4101.83 | 4110.46 | 4092.51, 4083.2, 4061.46 | WAIT_ENTRY_ZONE |
| D | buy | 4104.93-4110.46 | 4107.69 | 4093.75 | 4115.98, 4121.5, 4136.69 | WAIT_ENTRY_ZONE |
| E | buy | 4128.41-4136.69 | 4132.55 | 4121.5 | 4149.11, 4161.53, 4178.09 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Sell、M15 Strong Sell 与固定 bearish_continuation 结构，且已完成 entry-zone touch 和 M15 PULLBACK_FAIL_REJECT 确认，结构质量最高。
- A 当前 distance=6.58 已超过 max_distance=4.03，状态为 MISSED_ENTRY_DISTANCE；同时价格接近日内低位且 StochRSI=19.20，追空过度延伸风险高，因此 executable_now=wait。
- C 尚未完成 4098.72 下破及有效回测，breakout_quality=unconfirmed；真 H4 与同步 USD、收益率、油价证据不可用，不能据此外推更强趋势确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：live_usd_yields_oil_and_fed_pricing_at_mt5_snapshot, synchronized_public_spot_vs_mt5, true_mt5_h4
