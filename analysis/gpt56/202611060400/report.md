# GPT-5.6 黄金小时点位分析 202611060400

数据时间（UTC）：2026-11-06T04:07:43Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4050.88-4064.83 | 4057.86 | 4082.57 | 4028.56, 4017.4, 4004.85 | MISSED_ENTRY_DISTANCE |
| B | sell | 4098.31-4115.05 | 4106.68 | 4135.14 | 4064.83, 4039.72, 4017.4 | WAIT_ENTRY_ZONE |
| C | sell | 4004.85-4017.4 | 4011.12 | 4028.56 | 3992.3, 3973.47, 3929.55 | WAIT_ENTRY_ZONE |
| D | buy | 4017.4-4028.56 | 4022.98 | 3994.81 | 4039.72, 4050.88, 4081.57 | WAIT_ENTRY_ZONE |
| E | buy | 4064.83-4081.57 | 4073.2 | 4050.88 | 4106.68, 4131.79, 4165.27 | MISSED_ENTRY_DISTANCE |

排序：A > C > B > E > D

研究理由：

- A 顺应 H1 Strong Sell 与固定 sell 结构，且已完成入区及 M15 拒绝确认，固定几何在五案中最完整。
- MT5 bid 4039.67 距 A 确认价 4057.86 为 18.19，超过 max_distance 6.97，状态为 MISSED_ENTRY_DISTANCE，因此当前只能 wait。
- 价格已跌破 S1 4056.40并接近日内低点，RSI 37.06、StochRSI 7.31显示下跌延伸，追空风险高。
- C 尚未完成 4004.85 下破与有效回测；B仍远离入场区，D逆势且 rr_tp1 仅0.594249，E缺少反向突破确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：broker_specific_event_blackout_window, fresh_primary_inflation_release, independently_timestamped_live_usd_nominal_real_yields_and_oil, live_rate_probabilities, public_indicator_table_selected_timeframe, public_spot_display_timezone, synchronized_public_spot_and_mt5
