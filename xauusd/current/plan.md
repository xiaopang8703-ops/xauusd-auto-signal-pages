# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260612-140056Z`
- sequence_no: `202606121400`
- created_at_utc: `2026-06-12T14:00:56Z`
- valid_until_utc: `2026-06-12T15:00:56Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `A`
- current_mid: `4191.64`
- session: `new_york_open`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject sell enabled=True total=0.763462
- B: breakout_retest_fail buy enabled=True total=0.650962
- C: breakout_retest_fail sell enabled=True total=0.650962
- D: sweep_and_reclaim buy enabled=True total=0.650962
- E: sweep_and_reclaim buy enabled=True total=0.650962

## ABCDE Execution Contract

- A: primary pullback/reject setup in the main intraday direction.
- B: counter-direction repair/reclaim setup after the key turn line is accepted.
- C: primary breakout/retest-fail continuation setup.
- D/E: sweep/reclaim recovery setups for exhaustion or extreme reclaim conditions.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4199.64 - 4204.64`
- expected_fill_price: `4191.64`
- stop_loss: `4225.6`
- tp1/tp2/tp3: `4157.68 / 4123.72 / 4096.55`

MT5 must not parse this Markdown file as a trading instruction.
