# GTM Signals Intelligence Engine

A Technical GTM portfolio project that identifies and prioritizes companies showing buying or intent signals relevant to cloud Marketplace and PRM / partnerships motions.

## Business Problem

GTM teams often miss high-potential accounts because useful commercial signals are scattered across hiring pages, funding announcements, news, cloud ecosystems, company websites, and partnership activity.

Reps may manually research dozens of companies to determine which ones are actively investing in cloud alliances, marketplaces, partner programs, or ecosystem growth.

The GTM Signals Intelligence Engine is designed to collect, normalize, classify, score, and explain these signals so GTM teams can prioritize the companies showing the strongest evidence of relevant buying intent.

## Core Workflow

Company  
↓  
Signals  
↓  
Normalize  
↓  
Classify  
↓  
Score  
↓  
Explain  
↓  
Rank

## Scoring Modes

### Marketplace Mode

Evaluates whether a company appears likely to invest in or benefit from cloud Marketplace and co-sell motions.

Example signals may include:

- Hiring cloud alliance leaders
- Hiring Marketplace roles
- AWS, Azure, or Google Cloud partnership announcements
- Marketplace launches
- Co-sell activity
- Cloud ecosystem investment
- Recent funding or expansion

### PRM Mode

Evaluates whether a company appears likely to invest in partner relationship management or broader partnership infrastructure.

Example signals may include:

- Hiring partnership leaders
- Hiring Partner Operations roles
- Building channel or reseller programs
- Expanding partner teams
- Launching partner programs
- Strategic partnership announcements
- Ecosystem investment

## V1 Scope

The first version will intentionally use sample data instead of live external sources.

V1 will include:

- 10 sample companies
- 20–30 sample GTM signals
- A normalized signal structure
- Marketplace scoring
- PRM scoring
- Ranked company output
- Human-readable explanations for each score

V1 will NOT yet include:

- Live web monitoring
- LinkedIn scraping
- Salesforce production access
- Slack alerts
- n8n automation
- Clay
- Continuous scheduling
- Autonomous CRM updates

These capabilities may be introduced incrementally after the core data model and scoring logic are proven.

## Development Philosophy

This project follows:

**UNDERSTAND → DESIGN → BUILD → TEST → DEBUG → UNDERSTAND → DOCUMENT → DEMO**

AI coding tools may assist with implementation, but important architecture, business rules, data flow, and technical decisions must be understood and explainable.

## Technical Goals

This project will progressively develop practical skills in:

- Python
- SQL and relational databases
- APIs and HTTP
- Postman
- JSON
- Webhooks
- n8n
- Enrichment workflows
- Git and GitHub
- System architecture
- Error handling
- Automation
- Technical communication

## Project Status

Development is milestone-based.

Current milestone status is tracked in `PROJECT_STATUS.md`.