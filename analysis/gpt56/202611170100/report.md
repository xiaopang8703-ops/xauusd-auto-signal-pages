# GPT-5.6 黄金小时点位分析 202611170100

数据时间（UTC）：2026-11-17T01:06:32Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_range；延伸风险：high；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3852.25-3858.6 | 3855.43 | 3867.23 | 3842.07, 3836.99, 3831.27 | MISSED_ENTRY_DISTANCE |
| B | sell | 3873.86-3881.49 | 3877.68 | 3890.65 | 3858.6, 3847.16, 3836.99 | WAIT_ENTRY_ZONE |
| C | sell | 3831.27-3836.99 | 3834.13 | 3842.07 | 3825.55, 3816.97, 3796.95 | WAIT_ENTRY_ZONE |
| D | buy | 3836.99-3842.07 | 3839.53 | 3826.69 | 3847.16, 3852.25, 3866.23 | WAIT_ENTRY_ZONE |
| E | buy | 3858.6-3866.23 | 3862.41 | 3852.25 | 3877.68, 3889.12, 3904.38 | MISSED_ENTRY_DISTANCE |

排序：A > B > C > E > D

研究理由：

- A 的 sell 回调几何与 H1 Strong Sell、M15 Strong Sell 及 bearish_continuation 一致，3852.25-3858.60 也贴近当日开盘和前收 3853.17。
- A 已完成入区和闭合柱确认，但当前 bid 3847.12 距确认参考价 3855.43 为 8.31，超过 max_distance 3.17；MISSED_ENTRY_DISTANCE 使其当前应等待而非追空。
- C 的 BREAKOUT_RETEST_FAIL 尚未形成，D/E 属逆向方案且缺少所需扫盘或突破回测证据；B 结构仍有效但入区距离较远。
- True H4 不可用，且公共报价与宏观覆盖不同步，因此不把公共代理证据提升为立即执行依据。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_breaking_news, synchronized_mt5_public_quote, synchronized_public_technical_indicators, verified_current_fed_expectations, verified_intrahour_usd_treasury_and_oil_moves, verified_public_and_broker_day_range_alignment, verified_public_quote_utc_timestamp
