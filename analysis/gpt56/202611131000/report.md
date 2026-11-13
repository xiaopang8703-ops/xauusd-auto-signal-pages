# GPT-5.6 黄金小时点位分析 202611131000

数据时间（UTC）：2026-11-13T10:07:31Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：range_bearish_pullback；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3906.97-3914.65 | 3910.81 | 3924.87 | 3894.67, 3888.53, 3881.62 | WAIT_ENTRY_ZONE |
| B | sell | 3936.68-3946.27 | 3941.48 | 3957.78 | 3917.5, 3903.12, 3890.34 | WAIT_ENTRY_ZONE |
| C | sell | 3883.14-3890.34 | 3886.74 | 3896.73 | 3875.94, 3865.14, 3839.94 | WAIT_ENTRY_ZONE |
| D | buy | 3890.34-3896.73 | 3893.53 | 3877.38 | 3903.12, 3909.51, 3927.09 | MISSED_ENTRY_DISTANCE |
| E | buy | 3917.5-3927.09 | 3922.3 | 3909.51 | 3941.48, 3955.86, 3975.04 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 的 sell 方向符合 H1 Strong Sell 与 bearish_pullback；3906.97-3914.65 入场区覆盖 classic pivot 3910.56，3924.87 止损位于当日高点 3923.19 上方。
- A 仍为有效跟踪方案，但当前尚未触及入场区，且 distance=7.73 超过 max_distance=3.84，因此 executable_now=wait。
- C 同向延续但 3883.14 下破及回测尚未确认；D/E 为逆向方案，其中 D 的 rr_tp1=0.593808 且处于 MISSED_ENTRY_DISTANCE。
- 真实 H4、同步外部现货报价及实时 DXY/美债收益率证据缺失；公共证据仅作辅助，MT5 3903.08/3903.17 仍为执行锚点。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
