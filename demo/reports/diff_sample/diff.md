# LoneWolf Fang AI Trading Prompt Lab Diff Report

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This diff is limited to analysis differences, input differences, safety display differences, and verification questions.

## Report Type
- **report_type**: single_report

## Input Files
- **base**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/reports/analyze_sample/report.json
- **other**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/reports/analyze_sample/report.json

## Compatibility Summary
- **compatible**: True
- **base_report_type**: single_report
- **other_report_type**: single_report
- **base_schema_version**: lwf_ai_trading_prompt_lab.report.v1
- **other_schema_version**: lwf_ai_trading_prompt_lab.report.v1
- **base_legacy_detected**: False
- **other_legacy_detected**: False
- **compat_mode**: strict
- **compatible_for_diff**: True
- **warnings**:
- **errors**:
- **migration_notes**:
- **required_field_status**:
  - **base**:
    - **present**:
      - schema_version
      - metadata
      - input_summary
      - validation_summary
      - market_structure
      - trend_assessment
      - volatility_assessment
      - risk_assessment
      - scenario_notes
      - research_questions
      - limitations
      - no_advice_disclaimer
    - **missing**:
  - **other**:
    - **present**:
      - schema_version
      - metadata
      - input_summary
      - validation_summary
      - market_structure
      - trend_assessment
      - volatility_assessment
      - risk_assessment
      - scenario_notes
      - research_questions
      - limitations
      - no_advice_disclaimer
    - **missing**:
- **schema_policy**: schema_registry_fail_closed
- **comparison_item_key_policy**: not_applicable

## Notable Changes
- No differences detected in compared report sections.

## Coverage Drift
- **available**: True
- **overall_severity**: none

### Timestamp Drift Summary
- **base_timestamp_quality_label**: minor_warnings
- **other_timestamp_quality_label**: minor_warnings
- **timestamp_quality_changed**: False
- **timestamp_quality_label_change**:
  - **base**: minor_warnings
  - **other**: minor_warnings
  - **direction**: unchanged
  - **step_delta**: 0
- **duplicate_timestamp_count_delta**: 0
- **gap_count_delta**: 0
- **irregular_interval_count_delta**: 0
- **largest_gap_ms_delta**: n/a
- **matches_expected_timeframe_changed**: n/a
- **inferred_interval_changed**: False
- **drift_severity**: none

### Calendar Coverage Drift Summary
- **base_coverage_quality_label**: missing_sections
- **other_coverage_quality_label**: missing_sections
- **coverage_quality_changed**: False
- **coverage_quality_label_change**:
  - **base**: missing_sections
  - **other**: missing_sections
  - **direction**: unchanged
  - **step_delta**: 0
- **coverage_ratio_delta**: 0
- **missing_bar_estimate_delta**: 0
- **missing_days_count_delta**: 0
- **sparse_days_count_delta**: 0
- **missing_months_count_delta**: 0
- **sparse_months_count_delta**: 0
- **largest_missing_window_days_delta**: 0
- **out_of_range_count_delta**: 0
- **requested_range_changed**: False
- **expected_range_changed**: False
- **drift_severity**: none

### Notable Drift
- No coverage drift detected in compared diagnostic sections.

### Item Drift
No entries.

### Coverage Drift Research Questions
- Which local CSV rows explain changed gaps, duplicates, or missing coverage windows?
- Did timeframe, expected start date, or expected end date settings change between runs?
- Are observed drift fields caused by input data changes or report generation settings?
- Are required safety labels still present in every exported format?

### Coverage Drift Limitations
- Coverage drift compares generated local report JSON files only.
- It is limited to input data quality, timestamp quality, calendar coverage, and verification questions.
- It does not forecast market behavior.
- It does not rank symbols, timeframes, or reports by expected outcome.
- It does not decide which asset, timeframe, or report should be used.

## Indicator Drift
- **available**: True
- **overall_severity**: none

### Notable Indicator Changes
- No indicator context drift detected.

### Label Changes
| Context | Field | Base Label | Other Label | Changed |
| --- | --- | --- | --- | --- |
| momentum_context | label | strong_positive_momentum | strong_positive_momentum | False |
| range_position_context | label | near_recent_high | near_recent_high | False |
| drawdown_recovery_context | label | at_or_near_peak | at_or_near_peak | False |
| volume_context | label | normal_volume | normal_volume | False |
| realized_volatility_context | label | low_volatility_context | low_volatility_context | False |
| candle_structure_context | label | wick_dominant | wick_dominant | False |
| trend_consistency_context | label | consistent_up_context | consistent_up_context | False |

### Numeric Deltas
| Field | Base Value | Other Value | Absolute Delta |
| --- | --- | --- | --- |
| candle_latest_body_range_ratio | 0.1625 | 0.1625 | 0 |
| drawdown_current_drawdown_pct | 0 | 0 | 0 |
| momentum_latest_value | 87.2796 | 87.2796 | 0 |
| range_close_position_in_range | 0.953224 | 0.953224 | 0 |
| realized_volatility_latest | 0.00401354 | 0.00401354 | 0 |
| trend_consistency_score | 96.6667 | 96.6667 | 0 |
| volume_latest_z_score | -0.0414 | -0.0414 | 0 |

### Item Indicator Drift
No entries.

### Indicator Drift Research Questions
- Which local CSV rows explain changed indicator context labels?
- Did deterministic period settings or source CSV windows change between reports?
- Do indicator context changes align with timestamp and calendar coverage drift?

### Indicator Drift Limitations
- Indicator drift compares generated local report JSON files only.
- Severity labels describe context-change size, not expected market outcomes.
- Legacy reports without indicator family sections are marked unavailable rather than rewritten.

## Numeric Diffs
| Field Path | Base Value | Other Value | Absolute Delta | Pct Delta | Direction |
| --- | --- | --- | --- | --- | --- |
| calendar_coverage.coverage_range_summary.actual_first_ts | 1735689600000 | 1735689600000 | 0 | 0 | unchanged |
| calendar_coverage.coverage_range_summary.actual_last_ts | 1746835200000 | 1746835200000 | 0 | 0 | unchanged |
| calendar_coverage.coverage_range_summary.expected_end_ts | 1767225600000 | 1767225600000 | 0 | 0 | unchanged |
| calendar_coverage.coverage_range_summary.expected_start_ts | 1735689600000 | 1735689600000 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[0].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[0].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[0].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[100].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[100].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[100].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[101].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[101].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[101].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[102].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[102].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[102].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[103].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[103].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[103].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[104].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[104].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[104].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[105].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[105].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[105].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[106].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[106].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[106].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[107].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[107].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[107].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[108].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[108].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[108].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[109].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[109].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[109].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[10].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[10].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[10].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[110].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[110].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[110].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[111].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[111].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[111].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[112].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[112].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[112].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[113].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[113].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[113].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[114].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[114].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[114].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[115].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[115].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[115].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[116].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[116].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[116].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[117].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[117].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[117].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[118].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[118].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[118].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[119].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[119].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[119].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[11].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[11].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[11].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[120].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[120].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[120].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[121].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[121].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[121].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[122].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[122].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[122].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[123].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[123].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[123].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[124].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[124].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[124].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[125].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[125].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[125].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[126].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[126].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[126].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[127].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[127].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[127].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[128].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[128].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[128].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[129].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[129].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[129].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[12].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[12].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[12].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[130].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[130].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[130].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[131].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[131].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[131].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[132].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[132].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[132].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[133].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[133].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[133].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[134].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[134].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[134].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[135].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[135].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[135].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[136].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[136].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[136].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[137].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[137].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[137].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[138].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[138].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[138].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[139].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[139].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[139].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[13].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[13].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[13].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[140].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[140].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[140].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[141].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[141].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[141].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[142].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[142].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[142].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[143].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[143].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[143].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[144].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[144].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[144].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[145].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[145].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[145].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[146].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[146].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[146].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[147].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[147].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[147].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[148].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[148].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[148].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[149].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[149].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[149].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[14].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[14].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[14].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[150].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[150].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[150].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[151].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[151].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[151].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[152].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[152].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[152].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[153].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[153].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[153].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[154].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[154].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[154].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[155].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[155].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[155].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[156].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[156].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[156].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[157].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[157].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[157].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[158].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[158].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[158].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[159].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[159].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[159].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[15].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[15].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[15].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[160].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[160].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[160].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[161].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[161].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[161].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[162].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[162].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[162].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[163].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[163].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[163].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[164].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[164].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[164].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[165].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[165].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[165].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[166].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[166].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[166].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[167].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[167].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[167].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[168].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[168].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[168].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[169].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[169].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[169].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[16].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[16].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[16].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[170].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[170].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[170].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[171].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[171].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[171].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[172].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[172].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[172].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[173].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[173].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[173].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[174].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[174].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[174].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[175].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[175].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[175].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[176].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[176].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[176].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[177].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[177].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[177].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[178].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[178].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[178].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[179].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[179].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[179].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[17].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[17].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[17].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[180].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[180].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[180].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[181].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[181].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[181].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[182].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[182].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[182].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[183].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[183].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[183].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[184].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[184].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[184].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[185].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[185].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[185].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[186].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[186].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[186].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[187].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[187].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[187].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[188].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[188].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[188].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[189].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[189].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[189].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[18].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[18].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[18].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[190].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[190].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[190].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[191].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[191].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[191].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[192].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[192].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[192].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[193].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[193].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[193].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[194].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[194].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[194].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[195].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[195].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[195].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[196].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[196].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[196].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[197].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[197].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[197].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[198].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[198].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[198].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[199].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[199].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[199].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[19].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[19].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[19].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[1].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[1].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[1].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[200].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[200].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[200].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[201].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[201].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[201].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[202].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[202].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[202].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[203].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[203].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[203].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[204].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[204].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[204].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[205].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[205].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[205].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[206].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[206].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[206].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[207].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[207].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[207].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[208].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[208].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[208].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[209].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[209].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[209].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[20].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[20].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[20].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[210].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[210].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[210].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[211].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[211].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[211].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[212].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[212].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[212].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[213].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[213].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[213].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[214].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[214].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[214].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[215].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[215].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[215].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[216].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[216].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[216].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[217].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[217].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[217].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[218].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[218].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[218].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[219].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[219].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[219].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[21].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[21].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[21].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[220].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[220].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[220].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[221].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[221].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[221].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[222].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[222].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[222].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[223].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[223].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[223].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[224].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[224].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[224].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[225].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[225].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[225].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[226].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[226].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[226].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[227].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[227].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[227].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[228].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[228].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[228].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[229].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[229].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[229].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[22].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[22].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[22].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[230].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[230].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[230].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[231].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[231].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[231].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[232].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[232].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[232].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[233].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[233].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[233].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[234].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[234].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[234].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[235].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[235].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[235].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[236].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[236].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[236].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[237].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[237].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[237].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[238].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[238].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[238].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[239].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[239].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[239].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[23].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[23].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[23].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[240].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[240].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[240].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[241].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[241].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[241].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[242].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[242].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[242].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[243].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[243].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[243].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[244].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[244].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[244].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[245].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[245].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[245].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[246].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[246].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[246].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[247].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[247].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[247].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[248].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[248].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[248].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[249].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[249].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[249].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[24].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[24].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[24].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[250].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[250].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[250].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[251].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[251].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[251].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[252].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[252].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[252].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[253].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[253].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[253].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[254].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[254].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[254].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[255].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[255].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[255].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[256].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[256].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[256].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[257].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[257].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[257].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[258].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[258].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[258].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[259].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[259].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[259].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[25].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[25].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[25].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[260].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[260].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[260].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[261].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[261].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[261].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[262].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[262].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[262].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[263].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[263].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[263].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[264].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[264].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[264].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[265].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[265].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[265].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[266].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[266].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[266].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[267].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[267].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[267].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[268].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[268].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[268].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[269].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[269].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[269].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[26].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[26].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[26].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[270].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[270].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[270].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[271].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[271].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[271].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[272].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[272].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[272].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[273].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[273].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[273].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[274].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[274].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[274].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[275].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[275].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[275].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[276].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[276].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[276].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[277].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[277].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[277].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[278].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[278].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[278].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[279].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[279].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[279].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[27].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[27].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[27].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[280].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[280].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[280].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[281].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[281].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[281].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[282].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[282].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[282].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[283].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[283].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[283].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[284].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[284].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[284].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[285].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[285].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[285].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[286].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[286].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[286].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[287].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[287].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[287].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[288].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[288].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[288].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[289].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[289].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[289].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[28].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[28].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[28].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[290].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[290].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[290].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[291].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[291].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[291].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[292].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[292].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[292].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[293].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[293].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[293].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[294].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[294].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[294].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[295].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[295].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[295].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[296].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[296].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[296].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[297].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[297].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[297].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[298].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[298].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[298].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[299].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[299].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[299].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[29].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[29].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[29].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[2].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[2].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[2].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[300].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[300].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[300].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[301].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[301].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[301].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[302].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[302].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[302].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[303].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[303].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[303].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[304].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[304].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[304].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[305].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[305].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[305].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[306].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[306].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[306].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[307].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[307].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[307].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[308].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[308].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[308].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[309].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[309].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[309].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[30].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[30].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[30].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[310].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[310].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[310].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[311].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[311].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[311].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[312].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[312].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[312].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[313].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[313].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[313].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[314].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[314].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[314].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[315].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[315].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[315].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[316].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[316].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[316].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[317].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[317].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[317].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[318].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[318].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[318].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[319].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[319].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[319].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[31].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[31].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[31].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[320].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[320].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[320].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[321].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[321].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[321].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[322].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[322].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[322].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[323].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[323].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[323].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[324].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[324].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[324].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[325].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[325].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[325].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[326].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[326].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[326].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[327].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[327].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[327].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[328].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[328].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[328].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[329].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[329].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[329].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[32].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[32].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[32].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[330].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[330].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[330].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[331].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[331].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[331].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[332].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[332].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[332].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[333].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[333].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[333].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[334].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[334].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[334].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[335].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[335].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[335].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[336].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[336].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[336].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[337].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[337].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[337].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[338].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[338].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[338].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[339].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[339].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[339].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[33].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[33].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[33].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[340].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[340].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[340].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[341].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[341].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[341].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[342].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[342].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[342].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[343].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[343].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[343].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[344].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[344].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[344].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[345].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[345].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[345].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[346].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[346].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[346].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[347].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[347].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[347].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[348].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[348].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[348].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[349].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[349].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[349].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[34].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[34].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[34].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[350].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[350].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[350].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[351].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[351].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[351].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[352].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[352].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[352].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[353].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[353].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[353].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[354].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[354].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[354].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[355].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[355].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[355].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[356].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[356].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[356].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[357].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[357].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[357].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[358].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[358].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[358].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[359].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[359].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[359].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[35].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[35].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[35].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[360].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[360].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[360].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[361].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[361].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[361].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[362].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[362].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[362].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[363].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[363].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[363].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[364].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[364].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[364].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[36].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[36].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[36].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[37].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[37].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[37].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[38].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[38].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[38].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[39].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[39].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[39].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[3].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[3].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[3].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[40].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[40].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[40].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[41].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[41].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[41].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[42].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[42].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[42].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[43].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[43].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[43].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[44].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[44].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[44].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[45].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[45].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[45].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[46].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[46].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[46].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[47].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[47].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[47].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[48].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[48].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[48].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[49].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[49].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[49].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[4].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[4].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[4].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[50].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[50].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[50].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[51].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[51].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[51].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[52].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[52].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[52].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[53].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[53].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[53].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[54].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[54].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[54].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[55].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[55].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[55].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[56].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[56].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[56].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[57].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[57].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[57].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[58].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[58].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[58].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[59].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[59].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[59].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[5].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[5].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[5].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[60].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[60].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[60].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[61].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[61].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[61].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[62].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[62].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[62].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[63].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[63].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[63].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[64].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[64].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[64].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[65].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[65].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[65].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[66].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[66].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[66].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[67].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[67].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[67].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[68].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[68].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[68].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[69].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[69].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[69].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[6].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[6].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[6].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[70].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[70].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[70].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[71].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[71].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[71].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[72].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[72].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[72].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[73].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[73].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[73].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[74].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[74].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[74].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[75].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[75].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[75].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[76].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[76].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[76].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[77].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[77].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[77].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[78].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[78].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[78].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[79].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[79].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[79].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[7].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[7].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[7].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[80].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[80].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[80].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[81].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[81].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[81].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[82].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[82].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[82].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[83].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[83].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[83].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[84].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[84].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[84].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[85].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[85].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[85].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[86].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[86].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[86].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[87].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[87].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[87].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[88].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[88].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[88].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[89].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[89].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[89].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[8].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[8].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[8].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[90].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[90].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[90].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[91].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[91].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[91].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[92].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[92].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[92].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[93].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[93].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[93].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[94].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[94].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[94].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[95].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[95].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[95].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[96].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[96].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[96].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[97].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[97].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[97].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[98].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[98].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[98].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[99].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[99].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[99].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[9].actual_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[9].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_coverage[9].expected_bars | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.daily_expected_bar_count | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.full_days_count | 130 | 130 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.missing_days_count | 235 | 235 | 0 | 0 | unchanged |
| calendar_coverage.daily_coverage_summary.partial_days_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.daily_coverage_summary.sparse_days_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.actual_unique_timestamp_count | 130 | 130 | 0 | 0 | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.after_expected_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.before_expected_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.coverage_ratio | 0.356164 | 0.356164 | 0 | 0 | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.expected_bar_count | 365 | 365 | 0 | 0 | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.expected_interval_ms | 86400000 | 86400000 | 0 | 0 | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.extra_out_of_range_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.expected_vs_actual_bar_count.missing_bar_estimate | 235 | 235 | 0 | 0 | unchanged |
| calendar_coverage.longest_missing_calendar_window.longest_missing_window_days | 235 | 235 | 0 | 0 | unchanged |
| calendar_coverage.longest_missing_calendar_window.missing_windows[0].days | 235 | 235 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.full_months_count | 4 | 4 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.missing_months_count | 7 | 7 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[0].actual_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[0].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[0].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[10].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[10].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[10].expected_bars | 30 | 30 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[11].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[11].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[11].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[1].actual_bars | 28 | 28 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[1].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[1].expected_bars | 28 | 28 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[2].actual_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[2].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[2].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[3].actual_bars | 30 | 30 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[3].coverage_ratio | 1 | 1 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[3].expected_bars | 30 | 30 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[4].actual_bars | 10 | 10 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[4].coverage_ratio | 0.322581 | 0.322581 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[4].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[5].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[5].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[5].expected_bars | 30 | 30 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[6].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[6].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[6].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[7].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[7].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[7].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[8].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[8].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[8].expected_bars | 30 | 30 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[9].actual_bars | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[9].coverage_ratio | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.monthly_coverage[9].expected_bars | 31 | 31 | 0 | 0 | unchanged |
| calendar_coverage.monthly_coverage_summary.partial_months_count | 0 | 0 | 0 | n/a | unchanged |
| calendar_coverage.monthly_coverage_summary.sparse_months_count | 1 | 1 | 0 | 0 | unchanged |
| indicator_family.candle_structure_context.average_body_range_ratio | 0.355501 | 0.355501 | 0 | 0 | unchanged |
| indicator_family.candle_structure_context.latest_body_range_ratio | 0.1625 | 0.1625 | 0 | 0 | unchanged |
| indicator_family.candle_structure_context.wick_dominance_ratio | 0.8375 | 0.8375 | 0 | 0 | unchanged |
| indicator_family.drawdown_recovery_context.current_drawdown_pct | 0 | 0 | 0 | n/a | unchanged |
| indicator_family.drawdown_recovery_context.distance_to_peak_pct | 0 | 0 | 0 | n/a | unchanged |
| indicator_family.drawdown_recovery_context.max_drawdown_pct | -2.6951 | -2.6951 | 0 | 0 | unchanged |
| indicator_family.drawdown_recovery_context.recovery_from_trough_pct | 0 | 0 | 0 | n/a | unchanged |
| indicator_family.metadata.periods.body_range | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.realized_volatility | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.rolling_range | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.rsi_like | 14 | 14 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.trend_consistency_returns | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.trend_consistency_sma_long | 50 | 50 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.trend_consistency_sma_short | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.metadata.periods.volume_z | 20 | 20 | 0 | 0 | unchanged |
| indicator_family.momentum_context.latest_value | 87.2796 | 87.2796 | 0 | 0 | unchanged |
| indicator_family.momentum_context.recent_average | 95.1552 | 95.1552 | 0 | 0 | unchanged |
| indicator_family.range_position_context.close_position_in_range | 0.953224 | 0.953224 | 0 | 0 | unchanged |
| indicator_family.range_position_context.distance_to_high_pct | 0.2942 | 0.2942 | 0 | 0 | unchanged |
| indicator_family.range_position_context.distance_to_low_pct | 5.9955 | 5.9955 | 0 | 0 | unchanged |
| indicator_family.range_position_context.rolling_high | 12613 | 12613 | 0 | 0 | unchanged |
| indicator_family.range_position_context.rolling_low | 11822 | 11822 | 0 | 0 | unchanged |
| indicator_family.realized_volatility_context.latest_realized_volatility | 0.00401354 | 0.00401354 | 0 | 0 | unchanged |
| indicator_family.realized_volatility_context.median_realized_volatility | 0.00484741 | 0.00484741 | 0 | 0 | unchanged |
| indicator_family.realized_volatility_context.volatility_percentile_like | 13.1818 | 13.1818 | 0 | 0 | unchanged |
| indicator_family.trend_consistency_context.consistency_score | 96.6667 | 96.6667 | 0 | 0 | unchanged |
| indicator_family.trend_consistency_context.positive_return_ratio | 0.9 | 0.9 | 0 | 0 | unchanged |
| indicator_family.volume_context.latest_volume | 1250 | 1250 | 0 | 0 | unchanged |
| indicator_family.volume_context.latest_z_score | -0.0414 | -0.0414 | 0 | 0 | unchanged |
| indicator_family.volume_context.rolling_mean | 1254.2 | 1254.2 | 0 | 0 | unchanged |
| indicator_family.volume_context.rolling_std | 101.435 | 101.435 | 0 | 0 | unchanged |
| input_summary.accepted_rows | 130 | 130 | 0 | 0 | unchanged |
| input_summary.latest_close | 12576 | 12576 | 0 | 0 | unchanged |
| input_summary.recent_return20_pct | 5.9656 | 5.9656 | 0 | 0 | unchanged |
| input_summary.total_return_pct | 27.1202 | 27.1202 | 0 | 0 | unchanged |
| market_structure.latest_close | 12576 | 12576 | 0 | 0 | unchanged |
| market_structure.range20 | 111.2 | 111.2 | 0 | 0 | unchanged |
| market_structure.range_pct20 | 0.9077 | 0.9077 | 0 | 0 | unchanged |
| market_structure.sma20 | 12235.7 | 12235.7 | 0 | 0 | unchanged |
| market_structure.sma50 | 11685.8 | 11685.8 | 0 | 0 | unchanged |
| risk_assessment.max_drawdown_pct | -2.6951 | -2.6951 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.coverage_ratio | 0.356164 | 0.356164 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.largest_missing_window_days | 235 | 235 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.missing_bar_estimate | 235 | 235 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.missing_days_count | 235 | 235 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.missing_months_count | 7 | 7 | 0 | 0 | unchanged |
| timestamp_diagnostics.calendar_coverage_summary.sparse_days_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.interval_diagnostics.gap_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.interval_diagnostics.inferred_interval_ms | 86400000 | 86400000 | 0 | 0 | unchanged |
| timestamp_diagnostics.interval_diagnostics.interval_counts_top[0].count | 129 | 129 | 0 | 0 | unchanged |
| timestamp_diagnostics.interval_diagnostics.interval_counts_top[0].interval_ms | 86400000 | 86400000 | 0 | 0 | unchanged |
| timestamp_diagnostics.interval_diagnostics.irregular_interval_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.interval_diagnostics.long_interval_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.interval_diagnostics.short_interval_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.ordering_diagnostics.duplicate_timestamp_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.ordering_diagnostics.original_out_of_order_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.timeframe_consistency.expected_interval_mismatch_count | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.timestamp_normalization_summary.normalized_first_timestamp | 1735689600000 | 1735689600000 | 0 | 0 | unchanged |
| timestamp_diagnostics.timestamp_normalization_summary.normalized_last_timestamp | 1746835200000 | 1746835200000 | 0 | 0 | unchanged |
| timestamp_diagnostics.timestamp_normalization_summary.rows_seen | 130 | 130 | 0 | 0 | unchanged |
| timestamp_diagnostics.timestamp_normalization_summary.rows_with_invalid_timestamp | 0 | 0 | 0 | n/a | unchanged |
| timestamp_diagnostics.timestamp_normalization_summary.rows_with_non_positive_timestamp | 0 | 0 | 0 | n/a | unchanged |
| trend_assessment.recent_return20_pct | 5.9656 | 5.9656 | 0 | 0 | unchanged |
| validation_summary.accepted_rows | 130 | 130 | 0 | 0 | unchanged |
| validation_summary.input_rows | 130 | 130 | 0 | 0 | unchanged |
| validation_summary.rejected_rows | 0 | 0 | 0 | n/a | unchanged |
| volatility_assessment.recent_tail_average_pct | 0.3886 | 0.3886 | 0 | 0 | unchanged |
| volatility_assessment.rolling_volatility20 | 0.4014 | 0.4014 | 0 | 0 | unchanged |

## Label Diffs
No entries.

## Added Items
No entries.

## Removed Items
No entries.

## Research Questions
- Which input rows or validation warnings explain the changed fields?
- Do changed labels come from changed data, changed report generation, or a different input file?
- Are safety disclaimers unchanged and visible in all exported formats?
- Do timestamp or calendar coverage drift fields point to changed local CSV quality?
- Do indicator context drift fields point to changed deterministic observation labels?

## Limitations
- This diff compares generated local report JSON files only.
- It does not forecast market behavior.
- It does not rank reports by expected outcome.
- It does not decide which asset or timeframe should be used.
- It is limited to analysis differences, input differences, safety display differences, and verification questions.

## No Advice Disclaimer
- **labels**: ('RESEARCH ONLY', 'NO FINANCIAL ADVICE', 'NO ORDER EXECUTION', 'LOCAL CSV ONLY', 'NOT A PROFIT GUARANTEE')
- **text**: This diff is research only. It is not financial advice. It uses local CSV report files only, performs no order execution, and is not a profit guarantee.
