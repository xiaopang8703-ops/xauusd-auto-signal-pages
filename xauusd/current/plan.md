# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20261009-142813Z`
- sequence_no: `202610091425`
- created_at_utc: `2026-10-09T14:28:13Z`
- valid_until_utc: `2026-10-09T14:43:13Z`
- action_mode: `alert_only`
- validator_result: `accepted_for_alert_only`
- selected_scenario_id: `E`
- current_mid: `4183.72`
- session: `new_york_open`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

### Public Source Confluence

- enabled: `False`
- technical_direction: `unknown` confidence=`0.0`
- rsi_state: `unknown` overextension_risk=`none`
- news_alignment: `neutral_or_mixed`
- ABCDE level-map source: `mt5_intraday_adaptive_level_map`
- score effect: emits generator-owned `scenario_adjustments`; Validator recomputes scores from emitted `public_confluence_status`; Package4 gates are unchanged.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.633639
- B: pullback_reject buy enabled=True total=0.572185
- C: breakout_retest_fail buy enabled=True total=0.787349
- D: sweep_and_reclaim sell enabled=True total=0.4875
- E: breakout_retest_fail sell enabled=True total=0.712311

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4171.82 - 4177.11`
- expected_fill_price: `4174.47`
- stop_loss: `4182.4`
- tp1/tp2/tp3: `4155.96 / 4152.0 / 4132.17`

MT5 must not parse this Markdown file as a trading instruction.
