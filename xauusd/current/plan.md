# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260624-040126Z`
- sequence_no: `202606240400`
- created_at_utc: `2026-06-24T04:01:26Z`
- valid_until_utc: `2026-06-24T05:01:26Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `B`
- current_mid: `4061.63`
- session: `asia`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.364955
- B: pullback_reject buy enabled=True total=0.744853
- C: breakout_retest_fail buy enabled=True total=0.400319
- D: sweep_and_reclaim sell enabled=True total=0.275247
- E: breakout_retest_fail sell enabled=True total=0.523566

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4004.23 - 4045.28`
- expected_fill_price: `4024.76`
- stop_loss: `3926.59`
- tp1/tp2/tp3: `4121.92 / 4239.61 / 4280.66`

MT5 must not parse this Markdown file as a trading instruction.
