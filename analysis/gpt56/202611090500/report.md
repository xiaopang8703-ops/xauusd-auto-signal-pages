# GPT-5.6 黄金小时点位分析 202611090500

数据时间（UTC）：2026-11-09T05:08:59Z；authority=none。

跟踪方案：C/buy；executable_now=wait；veto=false。

市场状态：uptrend_overextended；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | buy | 4120.22-4127.95 | 4124.09 | 4101.54 | 4137.9, 4148.95, 4171.05 | READY_TO_SUBMIT_DRY_RUN |
| B | buy | 4108.06-4116.33 | 4112.19 | 4094.65 | 4124.6, 4141.14, 4151.48 | MISSED_ENTRY_DISTANCE |
| C | buy | 4137.9-4148.95 | 4143.42 | 4127.95 | 4171.05, 4198.68, 4226.3 | WAIT_ENTRY_ZONE |
| D | sell | 4133.9-4137.9 | 4135.9 | 4165.52 | 4127.95, 4120.22, 4111.38 | WAIT_ENTRY_ZONE |
| E | sell | 4102.54-4111.38 | 4106.96 | 4120.22 | 4076.02, 4069.39, 4036.24 | WAIT_ENTRY_ZONE |

排序：C > A > B > E > D

研究理由：

- C 顺应 H1 Strong Buy 与 M15 Buy 的上行结构，并以 BREAKOUT_RETEST_FAIL 约束追涨，rr_tp1=1.786037，结构质量优于低首目标盈亏比的 A/B。
- 当前 MT5 ask=4122.48，尚未触及 C 入场区 4137.90–4148.95，也未完成 4148.95 上方收盘及回测；distance=20.94 超过 max_distance=11.05，因此只能 wait。
- 价格显著高于 R3=4089.48 且接近日高 4134.18，追涨与过度延伸风险高；必须等待已完成 M15 突破和有效回测。
- true_mt5_h4、实时美元/美债收益率/Fed 定价均不可用，外部报价仅作辅助，不能替代 MT5 锚点或把 C 判为已确认。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：synchronized_public_spot_vs_mt5, true_mt5_h4, verified_current_oil_geopolitics, verified_live_usd_yields_fed_pricing
