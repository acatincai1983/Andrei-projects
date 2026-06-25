# Andrei's Project Context

## Owner
- **Name:** Andrei
- **Email:** A_ACATINCAI@yahoo.com
- **GitHub repo:** acatincai1983/Andrei-projects
- **Default branch for new work:** `claude/relaxed-pascal-g1j6fu`

## Document & Deliverable Preferences
- When asked to create a playbook, report, or structured document — **always produce an Excel (.xlsx) file** as the primary deliverable, not just HTML or Markdown.
- Also produce an HTML version when it adds value (e.g. for browser preview / print-to-PDF), but Excel comes first.
- Documents must be **fully styled and professional**:
  - Navy/blue header bands (`#0D2340` / `#1A5FA8`)
  - Colour-coded approval/status badges (green = Pre-Approved, amber = CS TL / warning, red = RL / high-risk, purple = FBP)
  - Frozen header rows in all Excel sheets
  - Alternating row shading
  - Notes/guardrails columns highlighted in amber
  - Tab colours set per section
- Always send the finished file directly to the user via `SendUserFile`.

## MCM Retention Playbook Context
- **Product:** MY Compliance Management (MCM) — SHEQ software, acquired by The Access Group in July 2025.
- **Division:** Access Learning Division
- **Team:** MCM Retentions Team / MCM Customer Success
- **Current playbook file:** `MCM_Retention_Playbook_v1.0.xlsx` (7 tabs: Cover, S1–S5, Reference & Guardrails)

### Approval Level Key
| Badge | Level | Meaning |
|---|---|---|
| Pre-Approved | Green | Agent can proceed — no escalation needed |
| CS TL | Amber | MCM Customer Success Team Lead sign-off |
| RL | Red | Retention Lead sign-off |
| FBP | Purple | Financial Business Partner sign-off |

### Key Guardrails (always apply)
- FOC giveaway ≤ 1/3 of customer ARR
- Complete FOC Request Form before committing PS/consultancy time
- All save attempts logged in CRM
- Discounts apply on recontract only (unless stated)
- Competitor price matching requires written quote
- Any offer above Pre-Approved must be confirmed in writing before communicating to customer
- Mis-selling cases → escalate to FBP immediately
- Debt recovery → Finance team involved from the outset

### Churn Sections (5)
1. Commercial / Price (Budget Issues, Price Increase Dispute, Competitor Move, Budget & Debt Issues)
2. Poor Customer Service (Support Quality, Low Adoption, Failed Implementation, Mis-sold, Account Management, Lack of Engagement)
3. Limited Product Functionality (Feature Gap, UI/Usability, Low ROI / Module Underuse)
4. Product Performance / Reliability (Bugs/Defects, System Outages)
5. Strategic / Business Change (Internal Restructure, M&A/Closure, Regulatory Change)

### MCM Modules
Risk Assessments, Incident & Accident Reporting, Audits & Inspections, Training Record Management, Permit to Work, Asset Management, Legal Register & Legal Updates, Document Management, Contractors Management, Environmental Aspects, Non-Conformance Reporting, Action Tracking, COSHH / SDS Substance Database, Online Training / eLearning

### Approval Contacts (TBC — fill in when confirmed)
- MCM Customer Success Team Lead: TBC
- Retention Lead: TBC
- Financial Business Partner (FBP): TBC
- MCM Product Team: TBC
- PS / Consultancy Lead: TBC

## Compliance Frameworks Supported
ISO 9001, ISO 14001, ISO 45001, RIDDOR, COSHH

## Git Workflow
- Always develop on the designated feature branch (specified at session start)
- Commit with clear messages, always push when done
- Do not create PRs unless explicitly asked
