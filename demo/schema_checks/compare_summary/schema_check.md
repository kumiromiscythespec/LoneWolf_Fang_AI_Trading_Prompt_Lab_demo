# LoneWolf Fang AI Trading Prompt Lab Schema Check

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This check is limited to format compatibility, input differences, safety display differences, and verification questions.

## Input File
- **input_file**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/summaries/compare_summary/summary.json

## Detected Schema
- **detected_report_type**: summary_report
- **detected_schema_version**: lwf_ai_trading_prompt_lab.summary.v1
- **legacy_detected**: False
- **compatibility_status**: compatible

## Required Fields
- **present**:
  - schema_version
  - metadata
  - safety_boundary
  - summary
  - safety_review
  - source_digest
  - no_advice_disclaimer
- **missing**:
  - No entries.

## Optional Fields
- **present**:
  - metadata.generated_at
  - metadata.input_path
  - metadata.detected_report_type
  - metadata.input_schema_version
  - metadata.style
  - metadata.max_bullets
  - safety_boundary.labels
  - summary.headline
  - summary.brief_bullets
  - summary.data_quality_notes
  - summary.schema_status_notes
  - summary.safety_status_notes
  - summary.indicator_context_notes
  - summary.coverage_notes
  - summary.drift_notes
  - summary.artifact_notes
  - summary.research_questions
  - summary.limitations
  - safety_review.allowed_template_only
  - safety_review.required_disclaimers_present
  - safety_review.forbidden_phrase_hits
  - safety_review.advice_like_wording_hits
  - safety_review.status
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
