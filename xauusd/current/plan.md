# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260610-030621Z`
- sequence_no: `202606100300`
- created_at_utc: `2026-06-10T03:06:21Z`
- valid_until_utc: `2026-06-10T04:06:21Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `B`
- current_mid: `4179.73`
- session: `asia`

## Pre-Live Strategy Safety

- H4/Daily bias, regime, ATR dynamic stop, max chase, and structured-news blackout are generator-side safety gates.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- D is observe-only until trend/regime samples justify execution.

## Scenario Ranking

- A: pullback_reject sell enabled=True total=0.620962
- B: breakout_retest_fail sell enabled=True total=0.733462
- C: sweep_and_reclaim buy enabled=False total=-
- D: display_only buy enabled=False total=- observe_only

## Observation Scenarios

- D: reclaim-pullback / structure-flip observation only. It is not present in `trade_scenarios`, not scored by the Validator, and not executable by Package 4.

## Selected Trade Geometry

- entry_zone: `4179.73 - 4186.73`
- expected_fill_price: `4179.73`
- stop_loss: `4224.48`
- tp1/tp2/tp3: `4134.98 / 4090.23 / 4054.44`

MT5 must not parse this Markdown file as a trading instruction.
