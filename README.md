# RWD Sentinel — prototype

Data-quality anomaly detection, investigation & governance for procured real-world healthcare datasets.

A single-file, self-contained HTML prototype (no build, no dependencies). It detects, investigates, dispositions, and governs data-quality anomalies across procured real-world datasets, and closes three loops most anomaly tools leave open:

1. **Release acceptance** — a recorded fitness-for-use verdict per dataset refresh, with restrictions that travel with the release.
2. **Study impact** — findings → affected measures/periods → dependent studies → proceed/pause, with quantified bias.
3. **Vendor management** — escalation tickets, SLA tracking, evidence-based remediation verification, and a cross-release scorecard.

## Highlights
- **Two real-world datasets** (switch in the header): a procured **claims** database and a **Vantage Ambulatory EHR Network** source, each with its own cohort and mock anomalies.
- **Data Source & Config screen** — review metadata, a per-domain data summary, field inventory, and a pre-scan readiness checklist *before* scanning. Findings are generated only when you explicitly run the scan.
- **Fully developed investigation** on the claims dataset (outpatient-encounter shortfall) — six tabs, ranked hypotheses with a genuine real-world-change rule-out, executable checks, quantified bias, independent review, and an immutable approved report.
- Signature **expected-range band** evidence charts, decomposed investigation-priority scores, role gating (Analyst / Reviewer / Executive), and an append-only audit trail.

## Data
All entities are **synthetic**. Datasets, vendors, cohorts, findings, studies, and people are fictional and for demonstration only.

## Run locally
Just open `index.html` in any modern browser — there is nothing to build or install.
