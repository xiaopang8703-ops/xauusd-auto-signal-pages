# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260615-100043Z`
- sequence_no: `202606151000`
- created_at_utc: `2026-06-15T10:00:43Z`
- valid_until_utc: `2026-06-15T11:00:43Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `C`
- current_mid: `4336.76`
- session: `london`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.2719
- B: pullback_reject buy enabled=True total=0.422796
- C: breakout_retest_fail buy enabled=True total=0.819958
- D: sweep_and_reclaim sell enabled=True total=0.27
- E: breakout_retest_fail sell enabled=True total=0.516131

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4332.92 - 4356.81`
- expected_fill_price: `4344.86`
- stop_loss: `4309.02`
- tp1/tp2/tp3: `4404.59 / 4464.32 / 4524.04`

MT5 must not parse this Markdown file as a trading instruction.
