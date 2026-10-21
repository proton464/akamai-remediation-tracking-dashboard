# Findings Register Guidance

Build this in Microsoft Excel or Google Sheets.

## Recommended Columns
- Finding ID
- Title / Short Description
- Related Control (SOC 2 / ISO 27001 reference)
- Severity (Critical / High / Medium / Low)
- Source (Internal Test, External Audit, Self-Identified)
- Description
- Remediation Recommendation
- Owner (System / Engineering Owner)
- Identified Date
- Target Due Date
- Status (Open / In Progress / Pending Verification / Closed)
- Aging (Days)
- Evidence of Closure Link / Notes
- Re-test Result
- Closed Date

## Dashboard / Summary Views to Build
- Count of findings by status
- Count by severity
- Aging buckets (0–30, 31–60, 61–90, 90+ days)
- Findings by owner
- Closure rate over time (simple chart)
- Open high/critical items highlighted

## Sample Finding Ideas (10–15 total)
- MFA not enforced on privileged cloud roles
- Encryption at rest not enabled on a storage bucket
- Logging retention below policy requirement
- Missing change approval evidence
- Vulnerability scan findings older than SLA
- Incomplete access review documentation
- Publicly exposed security group rule
- Missing encryption in transit on an internal endpoint

## Tips
- Use data validation and conditional formatting (red for overdue high/critical).
- Add a formula for Aging = TODAY() - Identified Date.
- Create a pivot or summary tab for the dashboard.
- Keep sample data realistic but fictional.
