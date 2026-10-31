# ISO 9001:2026 Gap Analysis Tool

Excel workbook for clause-by-clause gap analysis across the full ISO 9001:2026 revision — with compliance score tracking, actionable prioritization, and change-log audit trail.

## What This Does

Maps every requirement from ISO 9001:2026 against your organization's current state: identify compliance gaps by clause, track readiness scores, and generate an ordered action plan.

## Sheets (6)

| # | Sheet | Purpose |
|---|-------|---------|
| 1 | **Gap_Analysis** | Core gap matrix — clause-by-clause assessment (Clause ID, ISO requirement text, current state, gap flag, Priority, Risk impact, Notes, Self-assessment score) |
| 2 | **Clause_Change_Log** | Diff of what changed between ISO 9001:2015 and ISO 9001:2026 side by side (old clause → new clause, change type, description, source reference) |
| 3 | **Readiness_Score_Dashboard** | Aggregated compliance scores with visual summary charts (per-clause readiness %, overall org readiness %, score history, traffic-light indicators) |
| 4 | **Action_Plan** | Ordered remediation plan derived from Priority × Risk fields (action item, linked clause, owner, due date, completion status, priority rank, risk weight) |
| 5 | **Quick_Start_Guide** | Setup instructions for non-technical users — step-by-step walkthrough with sample fill-in row and interpretation guide |
| 6 | **Glossary_and_References** | Terminology + official ISO/UKAS transition-timeline references (key QMS terms, standards cross-references, links to UKAS technical bulletins) |

## Usage Flow

1. **Assess**. Open `Gap_Analysis`. For each clause of ISO 9001:2026, mark your organization's current status in the assessment columns.
2. **Read Dashboard**. View `Readiness_Score_Dashboard` for aggregate compliance %, traffic-light indicators per section (Context, Leadership, Planning, Support, Operation, Performance Evaluation, Improvement).
3. **Export Action Plan**. The linked `Action_Plan` sheet auto-populates from your assessments: ordered by Priority × Risk weight.

## Files in This Repository

| File | Description |
|------|-------------|
| `gap-tool-v04.xlsx` | Main workbook (58 clauses, 6 sheets) — Download below |
| `instruction-guide.pdf` | Instruction guide (13.6 KB) |
| `free-readout.pdf` | Free sample version (17.1 KB) |

## Key Design Points

- **Clause-level granularity**: ISO 9001:2026 introduced significant revisions to Clauses 4–10. This tool assesses each clause individually.
- **Priority × Risk prioritization**: Gaps ranked by combined Priority (HIGH/MEDIUM/LOW) × Risk weight for natural remediation ordering.
- **Change-diff view**: `Clause_Change_Log` maps 2015 ↔ 2026 requirements side-by-side, critical for transition planning.

## Transition Timelines (Key Dates)

- **16 Sep 2026**: ISO 9001:2026 published
- **31 Mar 2027**: Accreditation bodies ready to transition decisions
- **30 Jun 2027**: Certification bodies' transition declaration deadline
- **16 Mar 2028**: CABs stop accepting new applications against previous version
- **30 Sep 2029**: All certified organizations must have transitioned

*Source: UKAS Technical Bulletin QMS ISO 9001:2026 Transition Rev.1*

> Assessment reflects general readiness mapping only — not org-specific certification. Consult your assigned certification body for formal gap analysis.

---

## Download

| Asset | Size |
|-------|------|
| [`gap-tool-v04.xlsx`](https://github.com/Lynx-Caden/iso9001-2026-gap-tool/releases/latest/download/gap-tool-v04.xlsx) | 38,783 B |
| [`instruction-guide.pdf`](https://github.com/Lynx-Caden/iso9001-2026-gap-tool/releases/latest/download/instruction-guide.pdf) | 13,652 B |
| [`free-readout.pdf`](https://github.com/Lynx-Caden/iso9001-2026-gap-tool/releases/latest/download/free-readout.pdf) | 17,065 B |
