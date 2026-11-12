# GPT-5.6 黄金小时点位分析 202611120500

数据时间（UTC）：2026-11-12T05:08:30Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：trend_down；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3986.05-3994.34 | 3990.2 | 4005.27 | 3972.81, 3966.18, 3958.73 | WAIT_ENTRY_ZONE |
| B | sell | 4011.19-4020.78 | 4015.98 | 4032.29 | 3992.01, 3977.61, 3964.81 | WAIT_ENTRY_ZONE |
| C | sell | 3957.62-3964.81 | 3961.22 | 3971.21 | 3950.43, 3939.64, 3914.48 | WAIT_ENTRY_ZONE |
| D | buy | 3964.81-3971.21 | 3968.01 | 3951.87 | 3977.61, 3984.01, 4001.6 | WAIT_ENTRY_ZONE |
| E | buy | 3992.01-4001.6 | 3996.81 | 3984.01 | 4015.98, 4030.37, 4049.55 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A 顺应 H1 Strong Sell、M15 Strong Sell 与 structural_bias=sell，且回抽至 3986.05-3994.34 后确认受阻可避免在 RSI(14)=30.26 附近追空。
- A 当前 zone_touched=false，现价距 expected_fill_price=3990.20 为 12.63，超过 max_distance=4.14，因此结构有效但 executable_now=wait。
- C 尚未完成 3957.62 下破及回测，且其 TP1=3950.43 接近 S1=3951.89，当前 breakout_quality=unconfirmed、延伸风险较高。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_intraday_geopolitical_news, independently_verified_live_dxy_and_treasury_yields, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
