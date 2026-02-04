# Prioritization Model (Risk-based)

A simple scoring approach for CIS deviations.

## Inputs (example)
- Asset criticality: 1–5
- Exposure: 1–5
- Control severity: 1–5
- Compliance urgency/SLA: 1–3

## Example formula
Priority Score = (Criticality + Exposure + Severity) × SLA

## Practical guidance
- Fix highest scores first
- Batch remediation where possible (same control across many hosts)
- Escalate if overdue on Tier-0/Tier-1 assets
