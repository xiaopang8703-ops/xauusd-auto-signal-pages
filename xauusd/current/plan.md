# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260619-160239Z`
- sequence_no: `202606191600`
- created_at_utc: `2026-06-19T16:02:39Z`
- valid_until_utc: `2026-06-19T17:02:39Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `B`
- current_mid: `4148.7`
- session: `london_new_york_overlap`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.401765
- B: pullback_reject buy enabled=True total=0.779648
- C: breakout_retest_fail buy enabled=True total=0.419786
- D: sweep_and_reclaim sell enabled=True total=0.322117
- E: breakout_retest_fail sell enabled=True total=0.561297

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4103.23 - 4148.78`
- expected_fill_price: `4126.0`
- stop_loss: `4011.63`
- tp1/tp2/tp3: `4239.38 / 4375.53 / 4421.08`

MT5 must not parse this Markdown file as a trading instruction.
