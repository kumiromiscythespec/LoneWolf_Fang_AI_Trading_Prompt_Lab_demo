# LoneWolf Fang AI Trading Prompt Lab Comparison Report

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This report is limited to observation comparison, risk context, data quality, and research questions.

## Metadata
- **tool_name**: LoneWolf Fang AI Trading Prompt Lab
- **report_type**: local_csv_comparison
- **report_version**: 0.2.0
- **generated_at_utc**: 2026-05-12T00:00:00+00:00
- **safety_labels**: ('RESEARCH ONLY', 'NO FINANCIAL ADVICE', 'NO ORDER EXECUTION', 'LOCAL CSV ONLY', 'NOT A PROFIT GUARANTEE')

## Manifest Summary
- **schema_version**: lwf_ai_trading_prompt_lab.compare_manifest.v1
- **source_manifest**: samples/compare_manifest.json
- **item_count**: 3
- **symbols**:
  - BTC/USDT
  - ETH/USDT
- **timeframes**:
  - 1h
  - 5m
- **expected_start**: n/a
- **expected_end**: n/a
- **items**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **csv**: samples/sample_btc_5m.csv
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **csv**: samples/sample_eth_5m.csv
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **csv**: samples/sample_btc_1h.csv

## Item Summaries
| Symbol | Timeframe | Accepted Rows | Rejected Rows | Last Close | Total Return Pct | Recent Return Pct | Volatility Level | Max Drawdown Pct | Trend Label | Volume Regime | Data Quality Label | Timestamp Quality Label | Coverage Quality Label | Coverage Ratio | Missing Bar Estimate | Missing Days Count | Sparse Days Count | Missing Months Count | Largest Missing Window Days | Requested Range Source | Gap Count | Duplicate Timestamp Count | Irregular Interval Count | Inferred Interval Label | Matches Expected Timeframe | Indicator Family Summary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BTC/USDT | 5m | 72 | 0 | 43229 | 2.9262 | 0.7011 | low | 0 | mixed_or_rangebound | normal_volume | complete_for_supplied_file | clean | missing_sections | 0.000685 | 105048 | 364 | 1 | 11 | 333 | cli | 0 | 0 | 0 | 5m | True | {'momentum_label': 'strong_positive_momentum', 'range_position_label': 'near_recent_high', 'drawdown_recovery_label': 'at_or_near_peak', 'volume_context_label': 'elevated_volume', 'realized_volatility_label': 'normal_volatility_context', 'candle_structure_label': 'wick_dominant', 'trend_consistency_label': 'consistent_up_context', 'trend_consistency_score': 100.0} |
| ETH/USDT | 5m | 72 | 0 | 2956.16 | -4.64 | -1.8373 | low | -4.8879 | downward_bias | normal_volume | complete_for_supplied_file | clean | missing_sections | 0.000685 | 105048 | 364 | 1 | 11 | 333 | cli | 0 | 0 | 0 | 5m | True | {'momentum_label': 'strong_negative_momentum', 'range_position_label': 'near_recent_low', 'drawdown_recovery_label': 'in_drawdown', 'volume_context_label': 'elevated_volume', 'realized_volatility_label': 'normal_volatility_context', 'candle_structure_label': 'wick_dominant', 'trend_consistency_label': 'consistent_down_context', 'trend_consistency_score': 6.6667} |
| BTC/USDT | 1h | 72 | 0 | 44160.3 | 5.6466 | 1.2605 | low | 0 | upward_bias | normal_volume | complete_for_supplied_file | clean | missing_sections | 0.008219 | 8688 | 362 | 0 | 11 | 331 | cli | 0 | 0 | 0 | 1h | True | {'momentum_label': 'strong_positive_momentum', 'range_position_label': 'near_recent_high', 'drawdown_recovery_label': 'at_or_near_peak', 'volume_context_label': 'elevated_volume', 'realized_volatility_label': 'low_volatility_context', 'candle_structure_label': 'wick_dominant', 'trend_consistency_label': 'consistent_up_context', 'trend_consistency_score': 100.0} |

## Data Quality Comparison
- **comparison_type**: data quality comparison
- **label_counts**:
  - **complete_for_supplied_file**: 3
- **data_completeness_ranking**:
  -
    - **position**: 1
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **accepted_rows**: 72
  -
    - **position**: 2
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **accepted_rows**: 72
  -
    - **position**: 3
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **accepted_rows**: 72
- **notes**:
  - This compares completeness and validation results inside the supplied local CSV files.
  - A stronger completeness label does not imply a market outcome.

## Timestamp Quality Comparison
- **comparison_type**: timestamp quality comparison
- **timestamp_quality_label_counts**:
  - **clean**: 3
- **items_with_gaps**:
- **items_with_duplicates**:
- **items_with_irregular_intervals**:
- **items_with_timeframe_mismatch**:
- **notes**:
  - Timestamp quality comparison is limited to local CSV input structure.
  - Timestamp labels are data quality observations, not outcome rankings.

## Calendar Coverage Comparison
- **comparison_type**: calendar coverage comparison
- **coverage_quality_label_counts**:
  - **missing_sections**: 3
- **items_with_partial_coverage**:
- **items_with_sparse_coverage**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
- **items_with_missing_sections**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.008219
    - **missing_bar_estimate**: 8688
    - **missing_days_count**: 362
    - **sparse_days_count**: 0
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 331
    - **requested_range_source**: cli
- **items_with_out_of_range_rows**:
- **by_item**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.000685
    - **missing_bar_estimate**: 105048
    - **missing_days_count**: 364
    - **sparse_days_count**: 1
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 333
    - **requested_range_source**: cli
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **coverage_quality_label**: missing_sections
    - **coverage_ratio**: 0.008219
    - **missing_bar_estimate**: 8688
    - **missing_days_count**: 362
    - **sparse_days_count**: 0
    - **missing_months_count**: 11
    - **largest_missing_window_days**: 331
    - **requested_range_source**: cli
- **notes**:
  - Calendar coverage comparison is limited to local CSV input date coverage.
  - Coverage labels describe data quality and period balance only.

## Items With Partial Coverage

## Items With Sparse Coverage
-
  - **symbol**: BTC/USDT
  - **timeframe**: 5m
  - **coverage_quality_label**: missing_sections
  - **coverage_ratio**: 0.000685
  - **missing_bar_estimate**: 105048
  - **missing_days_count**: 364
  - **sparse_days_count**: 1
  - **missing_months_count**: 11
  - **largest_missing_window_days**: 333
  - **requested_range_source**: cli
-
  - **symbol**: ETH/USDT
  - **timeframe**: 5m
  - **coverage_quality_label**: missing_sections
  - **coverage_ratio**: 0.000685
  - **missing_bar_estimate**: 105048
  - **missing_days_count**: 364
  - **sparse_days_count**: 1
  - **missing_months_count**: 11
  - **largest_missing_window_days**: 333
  - **requested_range_source**: cli

## Items With Missing Sections
-
  - **symbol**: BTC/USDT
  - **timeframe**: 5m
  - **coverage_quality_label**: missing_sections
  - **coverage_ratio**: 0.000685
  - **missing_bar_estimate**: 105048
  - **missing_days_count**: 364
  - **sparse_days_count**: 1
  - **missing_months_count**: 11
  - **largest_missing_window_days**: 333
  - **requested_range_source**: cli
-
  - **symbol**: ETH/USDT
  - **timeframe**: 5m
  - **coverage_quality_label**: missing_sections
  - **coverage_ratio**: 0.000685
  - **missing_bar_estimate**: 105048
  - **missing_days_count**: 364
  - **sparse_days_count**: 1
  - **missing_months_count**: 11
  - **largest_missing_window_days**: 333
  - **requested_range_source**: cli
-
  - **symbol**: BTC/USDT
  - **timeframe**: 1h
  - **coverage_quality_label**: missing_sections
  - **coverage_ratio**: 0.008219
  - **missing_bar_estimate**: 8688
  - **missing_days_count**: 362
  - **sparse_days_count**: 0
  - **missing_months_count**: 11
  - **largest_missing_window_days**: 331
  - **requested_range_source**: cli

## Items With Out Of Range Rows

## Trend Context Comparison
- **comparison_type**: trend context comparison
- **trend_label_counts**:
  - **mixed_or_rangebound**: 1
  - **downward_bias**: 1
  - **upward_bias**: 1
- **by_item**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **trend_label**: mixed_or_rangebound
    - **recent_return_pct**: 0.7011
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **trend_label**: downward_bias
    - **recent_return_pct**: -1.8373
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **trend_label**: upward_bias
    - **recent_return_pct**: 1.2605
- **notes**:
  - Trend labels come from deterministic moving-average and recent-return inputs.
  - Mixed labels are prompts for chart inspection, not instructions.

## Volatility Context Comparison
- **comparison_type**: volatility context comparison
- **volatility_level_counts**:
  - **low**: 3
- **risk_context_ranking**:
  -
    - **position**: 1
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **rolling_volatility_latest**: 0.000942
  -
    - **position**: 2
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **rolling_volatility_latest**: 0.000501
  -
    - **position**: 3
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **rolling_volatility_latest**: 0.000201
- **notes**:
  - Rolling volatility is calculated from recent close-to-close returns.
  - Higher volatility is a context flag for research review only.

## Drawdown Context Comparison
- **comparison_type**: drawdown context comparison
- **risk_context_ranking**:
  -
    - **position**: 1
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **max_drawdown_pct**: -4.8879
  -
    - **position**: 2
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **max_drawdown_pct**: 0
  -
    - **position**: 3
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **max_drawdown_pct**: 0
- **notes**:
  - Drawdown uses close-only history from each supplied CSV window.
  - The ranking highlights observation context and does not rank assets for allocation.

## Indicator Context Comparison
- **comparison_type**: indicator context comparison
- **item_labels_matrix**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **momentum_label**: strong_positive_momentum
    - **range_position_label**: near_recent_high
    - **drawdown_recovery_label**: at_or_near_peak
    - **volume_context_label**: elevated_volume
    - **realized_volatility_label**: normal_volatility_context
    - **candle_structure_label**: wick_dominant
    - **trend_consistency_label**: consistent_up_context
    - **trend_consistency_score**: 100
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **momentum_label**: strong_negative_momentum
    - **range_position_label**: near_recent_low
    - **drawdown_recovery_label**: in_drawdown
    - **volume_context_label**: elevated_volume
    - **realized_volatility_label**: normal_volatility_context
    - **candle_structure_label**: wick_dominant
    - **trend_consistency_label**: consistent_down_context
    - **trend_consistency_score**: 6.6667
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **momentum_label**: strong_positive_momentum
    - **range_position_label**: near_recent_high
    - **drawdown_recovery_label**: at_or_near_peak
    - **volume_context_label**: elevated_volume
    - **realized_volatility_label**: low_volatility_context
    - **candle_structure_label**: wick_dominant
    - **trend_consistency_label**: consistent_up_context
    - **trend_consistency_score**: 100
- **items_with_high_volatility_context**:
- **items_with_unusually_high_volume**:
- **items_near_recent_high**:
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 5m
    - **indicator_family_summary**:
      - **momentum_label**: strong_positive_momentum
      - **range_position_label**: near_recent_high
      - **drawdown_recovery_label**: at_or_near_peak
      - **volume_context_label**: elevated_volume
      - **realized_volatility_label**: normal_volatility_context
      - **candle_structure_label**: wick_dominant
      - **trend_consistency_label**: consistent_up_context
      - **trend_consistency_score**: 100
  -
    - **symbol**: BTC/USDT
    - **timeframe**: 1h
    - **indicator_family_summary**:
      - **momentum_label**: strong_positive_momentum
      - **range_position_label**: near_recent_high
      - **drawdown_recovery_label**: at_or_near_peak
      - **volume_context_label**: elevated_volume
      - **realized_volatility_label**: low_volatility_context
      - **candle_structure_label**: wick_dominant
      - **trend_consistency_label**: consistent_up_context
      - **trend_consistency_score**: 100
- **items_near_recent_low**:
  -
    - **symbol**: ETH/USDT
    - **timeframe**: 5m
    - **indicator_family_summary**:
      - **momentum_label**: strong_negative_momentum
      - **range_position_label**: near_recent_low
      - **drawdown_recovery_label**: in_drawdown
      - **volume_context_label**: elevated_volume
      - **realized_volatility_label**: normal_volatility_context
      - **candle_structure_label**: wick_dominant
      - **trend_consistency_label**: consistent_down_context
      - **trend_consistency_score**: 6.6667
- **items_with_mixed_context**:
- **limitations**:
  - Indicator context comparison uses local CSV-derived labels only.
  - The comparison highlights observation differences and does not order items by expected outcome.
  - Context labels can be sensitive to deterministic period choices and sparse input history.
- **research_questions**:
  - Which raw candles explain differences in indicator labels across compared items?
  - Do range, volatility, volume, and trend consistency contexts agree for each item?
  - Are any label differences caused by missing coverage or timestamp quality issues?

## Observation Ranking
-
  - **ranking_type**: observation ranking
  - **dimension**: highest_total_return_pct_in_input_window
  - **items**:
    -
      - **position**: 1
      - **symbol**: BTC/USDT
      - **timeframe**: 1h
      - **total_return_pct**: 5.6466
    -
      - **position**: 2
      - **symbol**: BTC/USDT
      - **timeframe**: 5m
      - **total_return_pct**: 2.9262
    -
      - **position**: 3
      - **symbol**: ETH/USDT
      - **timeframe**: 5m
      - **total_return_pct**: -4.64
  - **interpretation**: Historical return inside the supplied CSV window only.
-
  - **ranking_type**: risk context ranking
  - **dimension**: largest_close_only_drawdown_magnitude
  - **items**:
    -
      - **position**: 1
      - **symbol**: ETH/USDT
      - **timeframe**: 5m
      - **max_drawdown_pct**: -4.8879
    -
      - **position**: 2
      - **symbol**: BTC/USDT
      - **timeframe**: 5m
      - **max_drawdown_pct**: 0
    -
      - **position**: 3
      - **symbol**: BTC/USDT
      - **timeframe**: 1h
      - **max_drawdown_pct**: 0
  - **interpretation**: Larger magnitude marks a risk context to inspect.
-
  - **ranking_type**: data completeness ranking
  - **dimension**: accepted_rows_after_validation
  - **items**:
    -
      - **position**: 1
      - **symbol**: BTC/USDT
      - **timeframe**: 5m
      - **accepted_rows**: 72
    -
      - **position**: 2
      - **symbol**: ETH/USDT
      - **timeframe**: 5m
      - **accepted_rows**: 72
    -
      - **position**: 3
      - **symbol**: BTC/USDT
      - **timeframe**: 1h
      - **accepted_rows**: 72
  - **interpretation**: More accepted rows support a broader deterministic sample.

## Cross Symbol Questions
- Do trend labels stay similar when the same symbol is checked on another timeframe?
- Are volatility differences caused by one large candle or by persistent variation?
- Do rejected rows or warnings cluster around one symbol or one timeframe?
- Does volume regime context agree or conflict across the compared files?
- Which raw candles would a human researcher inspect before forming a hypothesis?

## Limitations
- This comparison uses historical OHLCV rows from local CSV files only.
- It cannot forecast future market behavior.
- It does not evaluate fees, slippage, liquidity, funding, news, or portfolio constraints.
- Ranking sections are observation, risk context, or data completeness rankings only.
- It is designed for research review, not execution decisions.

## No Advice Disclaimer
- **labels**: ('RESEARCH ONLY', 'NO FINANCIAL ADVICE', 'NO ORDER EXECUTION', 'LOCAL CSV ONLY', 'NOT A PROFIT GUARANTEE')
- **text**: This comparison is research only. It is not financial advice. It uses local CSV data only, performs no order execution, and is not a profit guarantee.
