# False Positives & Validation

## Why false positives happen
- Scan credential issues / partial visibility
- Non-applicable controls for a workload (role mismatch)
- Temporary states (patching windows, maintenance)
- Tool mis-detection

## Validation checklist
- Confirm asset identity (correct hostname, correct OS)
- Confirm control applicability (server role, environment)
- Confirm compensating controls (e.g., MFA via SSO)
- Request supporting evidence from owner if needed
- Document the decision

## Outcomes
- **True finding** → Remediate
- **False positive** → Document and close with rationale
- **Not applicable** → Mark NA with justification
- **Exception** → Risk acceptance workflow
