# LoneWolf Fang AI Trading Prompt Lab Schema Check

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This check is limited to format compatibility, input differences, safety display differences, and verification questions.

## Input File
- **input_file**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/reports/analyze_sample/report.json

## Detected Schema
- **detected_report_type**: single_report
- **detected_schema_version**: lwf_ai_trading_prompt_lab.report.v1
- **legacy_detected**: False
- **compatibility_status**: compatible

## Required Fields
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
  - No entries.

## Optional Fields
- **present**:
  - timestamp_diagnostics
  - calendar_coverage
  - indicator_family
  - deterministic_summary
  - timestamp_diagnostics.calendar_coverage_summary
  - metadata.report_version
  - metadata.generated_at_utc
  - metadata.safety_labels
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
