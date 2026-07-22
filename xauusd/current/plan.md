# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260722-062536Z`
- sequence_no: `202607220625`
- created_at_utc: `2026-07-22T06:25:36Z`
- valid_until_utc: `2026-07-22T06:45:36Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `E`
- current_mid: `4123.47`
- session: `unknown`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

### Public Source Confluence

- enabled: `True`
- technical_direction: `buy` confidence=`0.8`
- rsi_state: `extreme_overbought` overextension_risk=`high`
- news_alignment: `neutral_or_mixed`
- ABCDE level-map source: `mt5_intraday_adaptive_level_map`
- score effect: emits generator-owned `scenario_adjustments`; Validator recomputes scores from emitted `public_confluence_status`; Package4 gates are unchanged.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.33771
- B: pullback_reject buy enabled=True total=0.418259
- C: breakout_retest_fail buy enabled=True total=0.529836
- D: sweep_and_reclaim sell enabled=True total=0.23
- E: breakout_retest_fail sell enabled=True total=0.702323

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4118.4 - 4124.05`
- expected_fill_price: `4121.23`
- stop_loss: `4129.7`
- tp1/tp2/tp3: `4101.44 / 4097.2 / 4076.0`

MT5 must not parse this Markdown file as a trading instruction.
