# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260611-130211Z`
- sequence_no: `202606111300`
- created_at_utc: `2026-06-11T13:02:11Z`
- valid_until_utc: `2026-06-11T14:02:11Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `C`
- current_mid: `4082.55`
- session: `new_york_open`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.651017
- B: breakout_retest_fail sell enabled=True total=0.650906
- C: breakout_retest_fail buy enabled=True total=0.763517
- D: sweep_and_reclaim sell enabled=True total=0.650906
- E: sweep_and_reclaim sell enabled=True total=0.650906

## ABCDE Execution Contract

- A: primary pullback/reject setup in the main intraday direction.
- B: counter-direction repair/reclaim setup after the key turn line is accepted.
- C: primary breakout/retest-fail continuation setup.
- D/E: sweep/reclaim recovery setups for exhaustion or extreme reclaim conditions.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4075.25 - 4082.25`
- expected_fill_price: `4082.25`
- stop_loss: `4040.78`
- tp1/tp2/tp3: `4123.73 / 4165.2 / 4198.38`

MT5 must not parse this Markdown file as a trading instruction.
