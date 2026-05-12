# LoneWolf Fang AI Trading Prompt Lab Timestamp Diagnostics

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This report is limited to input data quality, timestamp gaps, duplicates, interval variation, calendar coverage, and verification questions.

## Input
- **input_csv**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/samples/sample_ohlcv.csv
- **symbol**: BTC/USDT
- **timeframe**: 5m

## Timestamp Normalization
- **timestamp_unit**: unknown
- **normalized_first_iso**: 2025-01-01T00:00:00+00:00
- **normalized_last_iso**: 2025-05-10T00:00:00+00:00
- **rows_seen**: 130
- **rows_with_invalid_timestamp**: 0
- **rows_with_non_positive_timestamp**: 0

## Inferred Interval
- **inferred_interval_ms**: 86400000
- **inferred_interval_label**: 1d
- **interval_inference_method**: mode_of_positive_intervals

## Duplicate Summary
- **duplicate_timestamp_count**: 0
- **duplicate_policy**: duplicate timestamps are retained in sorted rows; diagnostics report repeated timestamp rows.
- No entries.

## Gap Summary
- **gap_count**: 0
- **largest_gap_label**: n/a
- **largest_gap_start_iso**: n/a
- **largest_gap_end_iso**: n/a

## Irregular Interval Summary
- **irregular_interval_count**: 0
- **short_interval_count**: 0
- **long_interval_count**: 0

## Timeframe Consistency
- **expected_timeframe**: 5m
- **expected_interval_ms**: 300000
- **matches_expected_timeframe**: False
- **expected_interval_mismatch_count**: 129
- **expected_interval_mismatch_examples**:
  -
    - **start_ts**: 1735689600000
    - **end_ts**: 1735776000000
    - **start_iso**: 2025-01-01T00:00:00+00:00
    - **end_iso**: 2025-01-02T00:00:00+00:00
    - **interval_ms**: 86400000
    - **interval_label**: 1d
  -
    - **start_ts**: 1735776000000
    - **end_ts**: 1735862400000
    - **start_iso**: 2025-01-02T00:00:00+00:00
    - **end_iso**: 2025-01-03T00:00:00+00:00
    - **interval_ms**: 86400000
    - **interval_label**: 1d
  -
    - **start_ts**: 1735862400000
    - **end_ts**: 1735948800000
    - **start_iso**: 2025-01-03T00:00:00+00:00
    - **end_iso**: 2025-01-04T00:00:00+00:00
    - **interval_ms**: 86400000
    - **interval_label**: 1d
  -
    - **start_ts**: 1735948800000
    - **end_ts**: 1736035200000
    - **start_iso**: 2025-01-04T00:00:00+00:00
    - **end_iso**: 2025-01-05T00:00:00+00:00
    - **interval_ms**: 86400000
    - **interval_label**: 1d
  -
    - **start_ts**: 1736035200000
    - **end_ts**: 1736121600000
    - **start_iso**: 2025-01-05T00:00:00+00:00
    - **end_iso**: 2025-01-06T00:00:00+00:00
    - **interval_ms**: 86400000
    - **interval_label**: 1d
- **timeframe_warning**: Observed timestamp spacing differs from the supplied timeframe.

## Calendar Coverage
- **coverage_quality_label**: missing_sections
- **expected_start_date**: 2025-01-01
- **expected_end_date**: 2025-12-31
- **actual_first_iso**: 2025-01-01T00:00:00+00:00
- **actual_last_iso**: 2025-05-10T00:00:00+00:00
- **requested_range_source**: cli
- **coverage_ratio**: 0.001237
- **expected_bar_count**: 105120
- **actual_unique_timestamp_count**: 130
- **missing_bar_estimate**: 104990
- **missing_days_count**: 235
- **sparse_days_count**: 130
- **missing_months_count**: 7
- **longest_missing_window_days**: 235
- **monthly_coverage**:
  -
    - **month**: 2025-01
    - **expected_bars**: 8928
    - **actual_bars**: 31
    - **coverage_ratio**: 0.003472
    - **status**: sparse
  -
    - **month**: 2025-02
    - **expected_bars**: 8064
    - **actual_bars**: 28
    - **coverage_ratio**: 0.003472
    - **status**: sparse
  -
    - **month**: 2025-03
    - **expected_bars**: 8928
    - **actual_bars**: 31
    - **coverage_ratio**: 0.003472
    - **status**: sparse
  -
    - **month**: 2025-04
    - **expected_bars**: 8640
    - **actual_bars**: 30
    - **coverage_ratio**: 0.003472
    - **status**: sparse
  -
    - **month**: 2025-05
    - **expected_bars**: 8928
    - **actual_bars**: 10
    - **coverage_ratio**: 0.00112
    - **status**: sparse
  -
    - **month**: 2025-06
    - **expected_bars**: 8640
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-07
    - **expected_bars**: 8928
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-08
    - **expected_bars**: 8928
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-09
    - **expected_bars**: 8640
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-10
    - **expected_bars**: 8928
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-11
    - **expected_bars**: 8640
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
  -
    - **month**: 2025-12
    - **expected_bars**: 8928
    - **actual_bars**: 0
    - **coverage_ratio**: 0.0
    - **status**: missing
- **research_notes**:
  - Calendar coverage diagnostics are input data quality observations for local CSV review only.
  - Low calendar coverage can make deterministic analysis sensitive to the supplied date subset.
  - Missing daily or monthly sections can create period imbalance in local CSV analysis.
  - Sparse daily coverage means some dates have very few bars compared with the expected interval.
  - These diagnostics do not rank symbols, timeframes, reports, or expected market outcomes.

## Timestamp Quality Label
- **timestamp_quality_label**: minor_warnings

## Research Notes
- Timestamp diagnostics are input data quality observations for local CSV review only.
- Observed timestamp spacing differs from the supplied timeframe.
- These diagnostics do not rank symbols, timeframes, reports, or expected market outcomes.

## Limitations
- This diagnostics report inspects timestamp quality in a local CSV file only.
- It does not evaluate future market behavior.
- It does not decide which symbol, timeframe, or report is better.
- It is limited to input data quality, timestamp gaps, duplicates, interval variation, calendar coverage, and verification questions.

## No Advice Disclaimer
- **labels**: ('RESEARCH ONLY', 'NO FINANCIAL ADVICE', 'NO ORDER EXECUTION', 'LOCAL CSV ONLY', 'NOT A PROFIT GUARANTEE')
- **text**: This diagnostics report is research only. It is not financial advice. It uses local CSV data only, performs no order execution, and is not a profit guarantee.
