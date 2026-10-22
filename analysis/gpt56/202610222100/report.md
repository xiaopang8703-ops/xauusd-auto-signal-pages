# GPT-5.6 黄金小时点位分析 202610222100

数据时间（UTC）：2026-10-22T21:07:53Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_near_low；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4033.42-4041.74 | 4037.58 | 4052.72 | 4020.12, 4013.46, 4005.98 | WAIT_ENTRY_ZONE |
| B | sell | 4056.89-4066.15 | 4061.52 | 4077.26 | 4038.37, 4024.47, 4012.12 | WAIT_ENTRY_ZONE |
| C | sell | 4005.17-4012.12 | 4008.64 | 4018.29 | 3998.22, 3987.8, 3963.47 | WAIT_ENTRY_ZONE |
| D | buy | 4012.12-4018.29 | 4015.2 | 3999.61 | 4024.47, 4030.65, 4047.63 | WAIT_ENTRY_ZONE |
| E | buy | 4038.37-4047.63 | 4043.0 | 4030.65 | 4061.52, 4075.41, 4093.93 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 的 4033.42-4041.74 回抽卖区与 H1 Strong Sell、固定 sell 结构及公共阻力 4032.52-4042.49 最吻合。
- MT5 4024.47 已接近日低 4021.07，RSI14 约 29.54，直接追空存在较高超跌延伸风险。
- A 尚未触及 entry_zone，且 distance=13.17 超过 max_distance=4.16，因此结构可跟踪但当前应 wait。
- C 尚无 4005.17 下破收盘及有效回测，BREAKOUT_RETEST_FAIL 质量仍为 unconfirmed。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：fresh_cme_fedwatch_probabilities, primary_source_geopolitical_confirmation, primary_source_us_macro_actuals_and_release_times, public_indicator_selected_timeframe_verified, synchronized_dxy_yields_oil_ticks, synchronous_public_spot_time_verified
