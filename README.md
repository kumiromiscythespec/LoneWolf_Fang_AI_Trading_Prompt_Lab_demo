# LoneWolf Fang AI Trading Prompt Lab Public Demo

This is a public demo repo. It is not the private development repo. It is research-only. It is sample-only. It uses local CSV demo artifacts only. It does not trade. It does not provide financial advice. It does not connect to exchanges, brokers, accounts, wallets, private APIs, external AI, or servers.

The demo shows an experiment in turning an AI trading prompt workflow into deterministic local research artifacts that can be inspected without exposing the private lab source code.

## What This Demo Shows

- Static reports generated from bundled sample CSV data.
- A local HTML index at `demo/demo_index.html`.
- A static dashboard at `demo/dashboard/dashboard.html`.
- Markdown, JSON, and HTML summaries for human review.
- Schema check outputs for generated JSON artifacts.
- SHA-256 checksums for reproducibility review.

## What This Demo Does Not Show

- The private development repo source code.
- `src/`, `tests/`, full fixtures, private exports, or work-in-progress notes.
- Live market connectivity or account state.
- Order execution, account balance access, wallet access, broker access, or exchange private API access.
- External AI calls, cloud summarization, server runtime, auth, billing, checkout, or entitlement flows.

## Safety Boundary

- Research-only.
- Sample-only.
- Local CSV only.
- Deterministic local artifacts only.
- No financial advice.
- No order execution.
- No external AI.
- No private API.
- No cloud or server runtime.
- No profit claim.

See `docs/public_safety_boundary.md` for the full public boundary.

## How To Inspect The Demo

1. Open `demo/demo_index.html` in a browser.
2. Open `demo/dashboard/dashboard.html` for the static dashboard view.
3. Read `demo/demo_safe_summary.md` for the safety summary generated with the demo pack.
4. Review `demo/summaries/` for compact summaries.
5. Review `demo/schema_checks/` to see compatibility checks for generated JSON files.
6. Verify file hashes with `demo/demo_checksums.sha256`.

No install step, API key, account, wallet, remote model, server, or trading connection is needed.

## Demo Artifact Map

The main generated files are:

- `demo/demo_manifest.json`: generated manifest and safety scan summary.
- `demo/demo_safe_summary.md`: public safety and artifact summary.
- `demo/demo_checksums.sha256`: SHA-256 list for generated files.
- `demo/demo_index.html`: browser index for the static demo.
- `demo/dashboard/`: static dashboard files.
- `demo/reports/`: sample report outputs.
- `demo/summaries/`: compact summaries.
- `demo/schema_checks/`: schema compatibility reports.
- `demo/demo_artifact_pack.zip`: generated artifact pack.
- `demo/artifact_pack/`: convenience copy of the artifact pack zip plus its SHA-256 text file.

See `docs/demo_artifact_map.md` for the detailed map.

## Checksums

The generated checksum list is `demo/demo_checksums.sha256`.

The demo artifact pack SHA-256 recorded in the manifest is:

```text
0daa5298fc4881884a8dcfb03395ec147ef130621ab7436de0f0cddd74e53d78
```

The same zip is also mirrored under `demo/artifact_pack/` with `demo_artifact_pack.sha256.txt` for quick inspection.

## Relation To The Private Lab Repo

The private development repo remains private. This public repo contains only selected sample artifacts and public-facing documentation. It is not a source release and is not enough to reconstruct the private implementation.

## Limitations

- The data is sample CSV data only.
- The outputs are static and deterministic.
- The demo does not forecast future markets.
- The demo does not rank assets or outcomes.
- The demo is not for investment decisions.
- The demo is intended for public review of artifacts, boundaries, and reproducibility checks as static files.

## Public Release Note And SNS Text

- Public note draft: `docs/release_note.md`
- Social post drafts: `docs/social_post_drafts.md`
