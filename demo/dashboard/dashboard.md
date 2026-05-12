# LoneWolf Fang AI Trading Prompt Lab Dashboard

**RESEARCH ONLY**
**NO FINANCIAL ADVICE**
**NO ORDER EXECUTION**
**LOCAL CSV ONLY**
**NOT A PROFIT GUARANTEE**

This dashboard is limited to report inventory, schema status, data quality summary, safety status, and local file links.

## Run
- **input_dir**: C:/LoneWolf_Fang_AI_Trading_Prompt_Lab/exports/public_demo_repo_seed/reports
- **generated_at**: 2026-05-12T00:00:00+00:00
- **report_count**: 4
- **skipped_count**: 0
- **max_files**: 100
- **recursive**: true

## Summary Counts
- **count_by_report_type**:
  - comparison_report: 1
  - diagnostics_report: 1
  - diff_report: 1
  - single_report: 1
- **count_by_schema_status**:
  - compatible: 4
- **count_by_safety_status**:
  - passed: 4
- **count_by_coverage_quality_label**:
  - missing_sections: 3
  - unknown: 1
- **count_by_timestamp_quality_label**:
  - clean: 1
  - minor_warnings: 2
  - unknown: 1
- **count_by_indicator_context_presence**:
  - absent: 1
  - present: 3
- **reports_with_warnings**: 0
- **reports_with_errors**: 0

## Report Inventory
| Relative Path | Report Type | Schema Status | Safety Status | Coverage Quality Label | Timestamp Quality Label | Indicator Family Present | Links |
| --- | --- | --- | --- | --- | --- | --- | --- |
| analyze_sample/report.json | single_report | compatible | passed | missing_sections | minor_warnings | true | [json](../reports/analyze_sample/report.json), [md](../reports/analyze_sample/report.md), [html](../reports/analyze_sample/report.html) |
| compare_sample/comparison.json | comparison_report | compatible | passed | missing_sections | clean | true | [json](../reports/compare_sample/comparison.json), [md](../reports/compare_sample/comparison.md), [html](../reports/compare_sample/comparison.html) |
| diff_sample/diff.json | diff_report | compatible | passed | n/a | n/a | true | [json](../reports/diff_sample/diff.json), [md](../reports/diff_sample/diff.md), [html](../reports/diff_sample/diff.html) |
| diagnostics_sample/diagnostics.json | diagnostics_report | compatible | passed | missing_sections | minor_warnings | false | [json](../reports/diagnostics_sample/diagnostics.json), [md](../reports/diagnostics_sample/diagnostics.md), [html](../reports/diagnostics_sample/diagnostics.html) |

## Warnings And Errors
- No warnings, errors, or skipped files.

## Limitations
- The dashboard scans local JSON files and summarizes known report shapes.
- Unknown JSON files are listed with unknown schema status when they are valid objects.
- Invalid JSON files and oversized JSON files are recorded under skipped files.
- The dashboard does not rank symbols, reports, timeframes, or expected outcomes.
- The dashboard is a static local export and does not run a local server.

## No Advice Disclaimer
- **labels**:
  - RESEARCH ONLY
  - NO FINANCIAL ADVICE
  - NO ORDER EXECUTION
  - LOCAL CSV ONLY
  - NOT A PROFIT GUARANTEE
- **text**: This dashboard is research only. It is not financial advice. It uses local CSV report files only, performs no order execution, and is not a profit guarantee.
