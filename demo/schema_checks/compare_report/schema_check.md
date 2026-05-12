# LoneWolf Fang AI Trading Prompt Lab Schema Check

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This check is limited to format compatibility, input differences, safety display differences, and verification questions.

## Input File
- **input_file**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/reports/compare_sample/comparison.json

## Detected Schema
- **detected_report_type**: comparison_report
- **detected_schema_version**: lwf_ai_trading_prompt_lab.comparison_report.v1
- **legacy_detected**: False
- **compatibility_status**: compatible

## Required Fields
- **present**:
  - schema_version
  - metadata
  - manifest_summary
  - item_summaries
  - data_quality_comparison
  - trend_context_comparison
  - volatility_context_comparison
  - drawdown_context_comparison
  - observation_ranking
  - cross_symbol_questions
  - limitations
  - no_advice_disclaimer
- **missing**:
  - No entries.

## Optional Fields
- **present**:
  - timestamp_quality_comparison
  - calendar_coverage_comparison
  - indicator_context_comparison
  - deterministic_summary
  - item_summaries[].indicator_family_summary
  - items_with_partial_coverage
  - items_with_sparse_coverage
  - items_with_missing_sections
  - items_with_out_of_range_rows
  - metadata.report_version
  - metadata.generated_at_utc
  - metadata.safety_labels
  - manifest_summary.schema_version
- **missing**:
  - No entries.

## Deprecated Fields
- No entries.

## Unknown Fields
- No entries.

## Warnings
- No entries.

## Errors
- No entries.

## Safety Summary
- **required_disclaimers_present**: True
- **missing_required_disclaimers**:
- **forbidden_phrase_hits**:
- **safe_to_review**: True

## Limitations
- This schema check validates local JSON structure only.
- It does not evaluate market outcomes.
- It does not decide which report is better.
- It is limited to format compatibility, input differences, safety display differences, and verification questions.

## No Advice Disclaimer
- **labels**: ('RESEARCH ONLY', 'NO FINANCIAL ADVICE', 'NO ORDER EXECUTION', 'LOCAL CSV ONLY', 'NOT A PROFIT GUARANTEE')
- **text**: This schema check is research only. It is not financial advice. It uses local JSON files only, performs no order execution, and is not a profit guarantee.
