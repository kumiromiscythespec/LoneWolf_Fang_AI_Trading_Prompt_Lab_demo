# LoneWolf Fang AI Trading Prompt Lab Schema Check

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This check is limited to format compatibility, input differences, safety display differences, and verification questions.

## Input File
- **input_file**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/artifact_pack_manifest/pack_manifest.json

## Detected Schema
- **detected_report_type**: artifact_pack
- **detected_schema_version**: lwf_ai_trading_prompt_lab.artifact_pack.v1
- **legacy_detected**: False
- **compatibility_status**: compatible

## Required Fields
- **present**:
  - schema_version
  - metadata
  - safety_boundary
  - inputs
  - included_files
  - skipped_files
  - warnings
  - errors
  - forbidden_scan
  - limitations
  - no_advice_disclaimer
- **missing**:
  - No entries.

## Optional Fields
- **present**:
  - metadata.generated_at
  - metadata.pack_name
  - metadata.source_mode
  - metadata.base_dir
  - metadata.output_zip
  - metadata.file_count
  - metadata.total_bytes
  - included_files[].source_path
  - included_files[].archive_path
  - included_files[].size_bytes
  - included_files[].sha256
  - included_files[].detected_report_type
  - included_files[].schema_version
  - forbidden_scan.scanned_files
  - forbidden_scan.hit_count
  - forbidden_scan.hits
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
