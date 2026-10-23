# Project Status — GTM Signals Intelligence Engine

## Current Status

**Current Milestone:** Milestone 1 — Signal Data Model

**Overall Project Status:** In Progress

## Milestones

- [x] Milestone 0 — Environment + Repository Setup
- [ ] Milestone 1 — Signal Data Model
- [ ] Milestone 2 — Marketplace + PRM Scoring Engine
- [ ] Milestone 3 — SQL Database
- [ ] Milestone 4 — First Real External API
- [ ] Milestone 5 — Hiring Signals
- [ ] Milestone 6 — Funding + News Signals
- [ ] Milestone 7 — Cloud + Partnership Signals
- [ ] Milestone 8 — Automation / Scheduling
- [ ] Milestone 9 — Alerts + GTM Output
- [ ] Milestone 10 — Error Handling + Hardening
- [ ] Milestone 11 — Documentation + Demo

## Milestone 0 — Completed

Environment and repository setup completed.

Completed:

- VS Code installed and configured
- Codex desktop app installed
- Git installed and working
- GitHub repository created
- Local repository connected to GitHub
- Python installed
- Python virtual environment created
- `.gitignore` configured
- Initial Git commit created
- Repository renamed to `gtm-signals-intelligence-engine`
- README created
- Project milestone tracker created

## Milestone 1 — Signal Data Model

### Goal

Define the core data structures used by the GTM Signals Intelligence Engine before building scoring or automation.

### Planned V1 Data

The initial version will use:

- 10 sample companies
- 20–30 sample signals
- JSON-based sample data
- No live external APIs yet

### Core Objects

We need to define:

**Company**

Potential fields:

- company name
- domain
- industry
- employee count
- headquarters
- funding stage
- annual revenue
- cloud alignment

**Signal**

Potential fields:

- company
- signal type
- signal subtype
- signal description
- source
- date detected
- confidence
- evidence

The exact schema will be decided during Milestone 1.

### Acceptance Criteria

Milestone 1 is complete when:

- Company schema is defined
- Signal schema is defined
- Sample data exists for 10 companies
- Sample data contains 20–30 signals
- Python can load the sample data
- Data structure is understandable and explainable
- No scoring logic has been implemented yet

## Next Step

Design the Company and Signal schemas, then create the first controlled Codex implementation prompt.

## Open Questions

- Which fields are essential vs optional?
- How should signal types and subtypes be represented?
- How should confidence be represented?
- Should company-level properties and signals live in separate JSON files?
- Which fields will eventually be needed for Marketplace scoring?
- Which fields will eventually be needed for PRM scoring?