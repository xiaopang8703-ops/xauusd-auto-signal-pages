# GPT-5.6 黄金小时点位分析 202611130800

数据时间（UTC）：2026-11-13T08:05:16Z；authority=none。

跟踪方案：A/sell；executable_now=wait；veto=false。

市场状态：bearish_continuation；延伸风险：medium；突破质量：unconfirmed。

以下点位原样来自对应小时信号，GPT 仅作独立排序和研究判断。

| 方案 | 方向 | 入场区 | 预期成交 | 止损 | 止盈 | 状态 |
|---|---|---|---|---|---|---|
| A | sell | 3906.97-3914.65 | 3910.81 | 3924.87 | 3894.67, 3888.53, 3881.62 | WAIT_ENTRY_ZONE |
| B | sell | 3928.71-3937.7 | 3933.2 | 3948.49 | 3910.73, 3897.25, 3885.27 | WAIT_ENTRY_ZONE |
| C | sell | 3878.52-3885.27 | 3881.89 | 3891.26 | 3871.77, 3861.64, 3838.02 | WAIT_ENTRY_ZONE |
| D | buy | 3885.27-3891.26 | 3888.27 | 3873.12 | 3897.25, 3903.24, 3919.72 | WAIT_ENTRY_ZONE |
| E | buy | 3910.73-3919.72 | 3915.22 | 3903.24 | 3933.2, 3946.69, 3964.67 | WAIT_ENTRY_ZONE |

排序：A > C > B > E > D

研究理由：

- A 延续固定 sell 结构，3906.97-3914.65 回抽区接近经典枢轴 3910.56，且 H1 Sell、M15 Strong Sell 与 ADX 41.28703 支持回抽做空框架。
- 当前 MT5 bid 3897.21 尚未触及 A 入场区，距预期成交价 3910.81 为 13.60，超过 max_distance 3.84，因此只能等待，不能追空。
- C 同向但尚无 3878.52 下破收盘及有效回测；B 同向但位于当日高点 3923.19 上方，D/E 则逆于当前固定 bearish_continuation 结构。
- true H4、同步外部现货以及实时 DXY/美债收益率证据缺失，且 13:30 UTC 有 PPI 事件，支持保留 A 跟踪但不支持立即执行。

公开数据覆盖：partial_public_plus_system_proxy。

缺失证据：independently_verified_live_dxy_and_treasury_yields, independently_verified_live_oil_and_intraday_geopolitical_news, time_aligned_external_technical_confirmation, utc_synchronized_public_spot_quote
