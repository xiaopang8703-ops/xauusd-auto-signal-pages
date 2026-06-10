# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260610-050134Z`
- sequence_no: `202606100500`
- created_at_utc: `2026-06-10T05:01:34Z`
- valid_until_utc: `2026-06-10T06:01:34Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `B`
- current_mid: `4174.36`
- session: `asia`

## Pre-Live Strategy Safety

- H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout are generator-side safety gates.
- Daily bias is observation-only context and is not a hard execution gate.
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

- entry_zone: `4174.36 - 4181.36`
- expected_fill_price: `4174.36`
- stop_loss: `4212.77`
- tp1/tp2/tp3: `4135.95 / 4097.54 / 4066.81`

MT5 must not parse this Markdown file as a trading instruction.
