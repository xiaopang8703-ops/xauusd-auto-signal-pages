# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260617-120153Z`
- sequence_no: `202606171200`
- created_at_utc: `2026-06-17T12:01:53Z`
- valid_until_utc: `2026-06-17T13:01:53Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `E`
- current_mid: `4322.54`
- session: `new_york_open`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject sell enabled=True total=0.424071
- B: pullback_reject sell enabled=True total=0.430345
- C: breakout_retest_fail sell enabled=True total=0.392916
- D: sweep_and_reclaim buy enabled=True total=0.298474
- E: breakout_retest_fail buy enabled=True total=0.767187

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4380.23 - 4405.5`
- expected_fill_price: `4392.86`
- stop_loss: `4357.47`
- tp1/tp2/tp3: `4443.41 / 4481.31 / 4531.85`

MT5 must not parse this Markdown file as a trading instruction.
