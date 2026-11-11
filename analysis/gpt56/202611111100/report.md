# GPT-5.6 黄金小时点位分析 202611111100

数据时间（UTC）：2026-11-11T11:06:00Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4059.81-4065.55 | 4062.68 | 4073.43 | 4050.63, 4046.04, 4040.88 | WAIT_ENTRY_ZONE |
| B | sell | 4074.83-4081.09 | 4077.96 | 4088.6 | 4062.31, 4052.93, 4044.59 | WAIT_ENTRY_ZONE |
| C | sell | 4039.9-4044.59 | 4042.24 | 4048.76 | 4035.21, 4028.18, 4011.76 | WAIT_ENTRY_ZONE |
| D | buy | 4044.59-4048.76 | 4046.68 | 4036.15 | 4052.93, 4057.1, 4068.57 | MISSED_ENTRY_DISTANCE |
| E | buy | 4062.31-4068.57 | 4065.44 | 4057.1 | 4077.96, 4087.35, 4099.87 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- MT5中价4052.93低于经典枢轴4063.65，H1为Sell且M15为Strong Sell；A的4059.81-4065.55回抽区覆盖枢轴附近并符合固定sell结构。
- A尚未触及入场区，当前距预期成交价9.80，高于max_distance 3.00，因此结构可跟踪但应wait。
- C仍缺少4039.90下破及回测确认，B位于当日高点4066.99上方更深处；真实H4不可用，不能据M15推断。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_geopolitical_update, live_real_yields, public_quote_utc_offset, synchronized_public_spot_tick, synchronized_usd_oil_and_yield_quotes
