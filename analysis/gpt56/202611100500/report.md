# GPT-5.6 黄金小时点位分析 202611100500

数据时间（UTC）：2026-11-10T05:08:45Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 4118.49-4126.55 | 4122.52 | 4137.22 | 4105.61, 4099.16, 4091.91 | WAIT_ENTRY_ZONE |
| B | sell | 4145.89-4155.56 | 4150.73 | 4167.16 | 4126.55, 4112.05, 4099.16 | WAIT_ENTRY_ZONE |
| C | sell | 4091.91-4099.16 | 4095.53 | 4105.61 | 4084.66, 4073.78, 4048.41 | WAIT_ENTRY_ZONE |
| D | buy | 4099.16-4105.61 | 4102.39 | 4086.11 | 4112.05, 4118.49, 4136.22 | WAIT_ENTRY_ZONE |
| E | buy | 4126.55-4136.22 | 4131.39 | 4118.49 | 4150.73, 4165.23, 4184.57 | WAIT_ENTRY_ZONE |

排序：A > B > C > E > D

研究理由：

- A符合H1结构不可用条件下现有的sell结构偏向与bearish_pullback背景，且4118.49–4126.55回撤区接近Pivot 4113.71上方，固定几何较B更贴近当前区间。
- 当前MT5 bid 4112.00尚未触及A入场区，距expected_fill_price 10.52，高于max_distance 4.03；PULLBACK_FAIL_REJECT的先触区再闭合确认条件未完成，因此仅可wait。
- 价格已接近日低4108.11且M15战术动量为buy，直接追空存在medium过度延伸风险，但这不否定A作为首选跟踪方案。
- true_mt5_h4与同步公开技术证据缺失，且美国CPI定于13:30 UTC发布；公开宏观信息仅作辅助，不能替代05:08:45Z的MT5执行锚点。

公开数据覆盖：external_macro_only。

缺失证据：live_usd_yields_oil_and_fed_pricing_at_mt5_snapshot, public_futures_technical_proxy, synchronized_public_spot_vs_mt5, true_mt5_h4
