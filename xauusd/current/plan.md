# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20260810-000053Z`
- sequence_no: `202608100000`
- created_at_utc: `2026-08-10T00:00:53Z`
- valid_until_utc: `2026-08-10T01:00:53Z`
- action_mode: `demo_trade`
- validator_result: `accepted_for_demo_trade`
- selected_scenario_id: `B`
- current_mid: `4336.56`
- session: `asia`

## Pre-Live Strategy Safety

- Real reviewed H4/H1 bias alignment, regime, ATR dynamic stop, max chase, and structured-news blackout may be generator-side safety gates.
- M15-aggregated H4/H1 proxy bias is observation-only and must not be treated as execution authority.
- Daily bias is observation-only context and is not a hard execution gate.
- `draw_only` candidates may still be emitted for observation when a gate is active.
- `dry_run_trade` / `demo_trade` candidates are fail-closed when a `STRATEGY_HARD_GATE_*` rejection exists.
- A/B/C/D/E are mutually exclusive candidate scenarios; only `selected_scenario_id` is executable for a published signal.

### Public Source Confluence

- enabled: `True`
- technical_direction: `buy` confidence=`0.5`
- rsi_state: `neutral` overextension_risk=`none`
- news_alignment: `neutral_or_mixed`
- ABCDE level-map source: `mt5_intraday_adaptive_level_map`
- score effect: emits generator-owned `scenario_adjustments`; Validator recomputes scores from emitted `public_confluence_status`; Package4 gates are unchanged.

## Scenario Ranking

- A: pullback_reject buy enabled=True total=0.58832
- B: pullback_reject buy enabled=True total=0.566414
- C: breakout_retest_fail buy enabled=True total=0.70125
- D: sweep_and_reclaim sell enabled=True total=0.33875
- E: breakout_retest_fail sell enabled=True total=0.63875

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4320.26 - 4327.5`
- expected_fill_price: `4323.88`
- stop_loss: `4308.39`
- tp1/tp2/tp3: `4334.75 / 4349.24 / 4358.3`

MT5 must not parse this Markdown file as a trading instruction.
