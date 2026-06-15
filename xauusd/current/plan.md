# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260615-210138Z`
- sequence_no: `202606152100`
- created_at_utc: `2026-06-15T21:01:38Z`
- valid_until_utc: `2026-06-15T22:01:38Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `A`
- current_mid: `4309.16`
- session: `unknown`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject sell enabled=True total=0.737573
- B: pullback_reject sell enabled=True total=0.389353
- C: breakout_retest_fail sell enabled=True total=0.368545
- D: sweep_and_reclaim buy enabled=True total=0.249042
- E: breakout_retest_fail buy enabled=True total=0.445345

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4309.02 - 4332.92`
- expected_fill_price: `4320.97`
- stop_loss: `4357.81`
- tp1/tp2/tp3: `4261.23 / 4237.34 / 4213.44`

MT5 must not parse this Markdown file as a trading instruction.
