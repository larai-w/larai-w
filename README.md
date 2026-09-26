# Hi, I'm larai-w

**I build software for caregiving and independent living, with a focus on reliable data and AWS serverless systems.**

I create and maintain the VEAI LAB. products, from browser interfaces to backend services, infrastructure and automated checks. I am a certified project manager (PMP), and my experience as a young carer informs the problems I choose to work on.

## Start here: engineering evidence

### [Open Care Evidence Toolkit](https://github.com/larai-w/open-care-evidence-toolkit)

An offline Python toolkit for inspecting synthetic care observations before they enter analytics or ML pipelines.

- **Data quality:** deterministic JSON/CSV checks with stable rule IDs and explicit missingness semantics.
- **Evaluation:** [controlled data-quality experiments](https://github.com/larai-w/open-care-evidence-toolkit/tree/main/benchmarks), including false alarms and missed problems.
- **Time and lineage:** [history replay](https://github.com/larai-w/open-care-evidence-toolkit/blob/main/HISTORY.md) distinguishes observation, revision and arrival times to prevent later information from entering earlier snapshots.
- **Reproducibility:** [CLI/browser compatibility](https://github.com/larai-w/open-care-evidence-toolkit/blob/main/docs/input-compatibility.md), synthetic fixtures and [CI](https://github.com/larai-w/open-care-evidence-toolkit/actions/workflows/test.yml).

This is data-quality and pipeline engineering evidence. The toolkit does not train or evaluate an ML model, and its examples do not establish clinical performance.

### Application engineering

| Project | What to inspect |
| --- | --- |
| [CareQuest](https://github.com/larai-w/carequest) | Local-first TypeScript PWA, optional Cognito authentication, backup/restore boundaries, Vitest and Playwright checks. [App](https://veai.jp/carequest/) |
| [CareReady](https://github.com/larai-w/careready-belongings-checker) | Offline belongings checklist for care transitions. [App](https://veai.jp/ready/) |
| [GutPacer](https://github.com/larai-w/GutPacer-ParkinSync-Module) | Bowel and medication records, Lambda/DynamoDB, LINE reminders and explicit observation semantics. In development. |
| [ParkinSync](https://github.com/larai-w/ParkinSync) | Synthetic health-data research and a deterministic HL7 FHIR R4 evidence path. No clinical inference. |

## Open-source contributions

**Merged**

- [Home Assistant frontend #54083](https://github.com/home-assistant/frontend/pull/54083) — accessible names for analytics consent switches.
- [Microduck #241](https://github.com/pollen-robotics/microduck/pull/241) — fresh camera snapshots through robotctl and console HTTP.

**Open PRs** — status checked on 2026-09-26; links show the current state.

- [OHDSI DataQualityDashboard #699](https://github.com/OHDSI/DataQualityDashboard/pull/699) — enabling `DEATH.person_id` uniqueness checks across supported CDM versions.
- [DuckDB documentation #7309](https://github.com/duckdb/duckdb-web/pull/7309) — recursive Parquet directory inputs, checked against two CLI versions.
- [Microduck #330](https://github.com/pollen-robotics/microduck/pull/330) — enforcing per-component artifact size budgets and required files.
- [stack-chan #702](https://github.com/stack-chan/stack-chan/pull/702) — deterministic synchronization for gallery samples.
- [gitleaks-action #237](https://github.com/gitleaks/gitleaks-action/pull/237) — documenting which commits are scanned for each event type.

## Tools and working approach

- **Languages:** Python, TypeScript and JavaScript.
- **Cloud:** AWS Lambda, DynamoDB, Cognito, S3/CloudFront and CDK.
- **Quality:** synthetic fixtures, regression checks, CI and explicit data contracts.
- **Delivery:** small reviewable changes, documented limitations and traceable implementation evidence.

My solo projects use AI-assisted development. The linked source, checks and review history show what has been implemented and evaluated; they should be read alongside each project's limitations.

More products: [Medication Promise](https://veai.jp/apps/medication-promise/), [EchoCare](https://veai.jp/apps/echocare/) and [かんたん家族サポート](https://veai.jp/kazoku-support/).

[VEAI LAB.](https://veai.jp/) · [Engineering and product writing](https://veai.jp/blog/) · [Cloud and delivery work](https://hire-veai.com/)
