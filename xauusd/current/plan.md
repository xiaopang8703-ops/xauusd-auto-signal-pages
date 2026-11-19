# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20261119-195533Z`
- sequence_no: `202611191955`
- created_at_utc: `2026-11-19T19:55:33Z`
- valid_until_utc: `2026-11-19T20:15:33Z`
- action_mode: `alert_only`
- validator_result: `accepted_for_alert_only`
- selected_scenario_id: `A`
- current_mid: `3667.01`
- session: `late_new_york`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

### Public Source Confluence

- enabled: `True`
- technical_direction: `sell` confidence=`1.0`
- rsi_state: `neutral` overextension_risk=`none`
- news_alignment: `neutral_or_mixed`
- ABCDE level-map source: `mt5_intraday_adaptive_level_map`
- score effect: emits generator-owned `scenario_adjustments`; Validator recomputes scores from emitted `public_confluence_status`; Package4 gates are unchanged.

## Scenario Ranking

- A: pullback_reject sell enabled=True total=0.744427
- B: pullback_reject sell enabled=True total=0.768716
- C: breakout_retest_fail sell enabled=True total=0.592492
- D: sweep_and_reclaim buy enabled=True total=0.308056
- E: breakout_retest_fail buy enabled=True total=0.567546

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `3675.54 - 3686.19`
- expected_fill_price: `3680.86`
- stop_loss: `3699.98`
- tp1/tp2/tp3: `3658.48 / 3649.96 / 3640.37`

MT5 must not parse this Markdown file as a trading instruction.
