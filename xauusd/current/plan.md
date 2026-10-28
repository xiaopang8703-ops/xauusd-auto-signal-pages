# XAUUSD Codex Hourly Candidate

This generator output is a candidate packet input only. The writer owns manifest, heartbeat, Validator output, READY, and bridge files.

- plan_id: `xauusd-20261028-115810Z`
- sequence_no: `202610281155`
- created_at_utc: `2026-10-28T11:58:10Z`
- valid_until_utc: `2026-10-28T12:13:10Z`
- action_mode: `alert_only`
- validator_result: `accepted_for_alert_only`
- selected_scenario_id: `E`
- current_mid: `4045.97`
- session: `london`

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

- A: pullback_reject buy enabled=True total=0.62449
- B: pullback_reject buy enabled=True total=0.561054
- C: breakout_retest_fail buy enabled=True total=0.707299
- D: sweep_and_reclaim sell enabled=True total=0.4825
- E: breakout_retest_fail sell enabled=True total=0.707248

## ABCDE Execution Contract

- A: first pullback/reject setup in the main intraday direction.
- B: deeper pullback/reject setup in the main intraday direction.
- C: main-direction breakout/retest continuation setup.
- D: near-side fake-breakout/sweep reversal against the main intraday direction.
- E: far-side invalidation/breakdown-or-breakout retest against the main intraday direction.
- Package4 must consume only the selected scenario; non-selected scenarios are alternatives, not simultaneous orders.

## Selected Trade Geometry

- entry_zone: `4037.03 - 4041.0`
- expected_fill_price: `4039.02`
- stop_loss: `4044.98`
- tp1/tp2/tp3: `4025.11 / 4022.13 / 4007.23`

MT5 must not parse this Markdown file as a trading instruction.
