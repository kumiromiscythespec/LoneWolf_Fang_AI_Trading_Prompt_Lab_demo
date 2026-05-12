# LoneWolf Fang AI Trading Prompt Lab Schema Check

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This check is limited to format compatibility, input differences, safety display differences, and verification questions.

## Input File
- **input_file**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/dashboard/dashboard_index.json

## Detected Schema
- **detected_report_type**: dashboard_index
- **detected_schema_version**: lwf_ai_trading_prompt_lab.dashboard_index.v1
- **legacy_detected**: False
- **compatibility_status**: compatible

## Required Fields
- **present**:
  - schema_version
  - metadata
  - safety_boundary
  - summary
  - reports
  - skipped_files
  - limitations
  - no_advice_disclaimer
- **missing**:
  - No entries.

## Optional Fields
- **present**:
  - metadata.generated_at
  - metadata.input_dir
  - metadata.report_count
  - metadata.skipped_count
  - metadata.max_files
  - metadata.recursive
  - summary.count_by_report_type
  - summary.count_by_schema_status
  - summary.count_by_safety_status
  - summary.count_by_coverage_quality_label
  - summary.count_by_timestamp_quality_label
  - summary.count_by_indicator_context_presence
  - summary.reports_with_warnings
  - summary.reports_with_errors
  - safety_boundary.labels
  - deterministic_summary
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
