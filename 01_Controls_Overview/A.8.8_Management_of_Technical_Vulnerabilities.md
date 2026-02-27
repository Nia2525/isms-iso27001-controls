# A.8.8 Management of Technical Vulnerabilities

## Objective

Identify, assess, prioritize, and remediate vulnerabilities in a timely and risk-based manner.

## Implementation Guidance

- Conduct regular vulnerability scans (e.g., Nessus, Qualys, OpenVAS) on servers, endpoints, and cloud assets.
- Maintain a documented vulnerability and patch management process.
- Prioritize vulnerabilities based on CVSS score, asset criticality, exposure, and business impact.
- Track remediation through a ticketing or ITSM system with defined SLAs.
- Define patching timelines (e.g., critical within 7 days, high within 30 days).
- Document and approve risk acceptances and exceptions.

## Audit Criteria

- Is there a documented vulnerability management policy and procedure?
- Are scans performed regularly and comprehensively (including cloud and remote assets)?
- Are vulnerabilities risk-rated and prioritized?
- Are patches and mitigations applied within defined SLAs?
- Are exceptions and risk acceptances documented, justified, and approved?

## Evidence Examples

- Vulnerability scan reports
- Patch deployment logs
- Remediation tickets with status and dates
- Risk acceptance forms
- Asset inventory aligned with scan scope

## Typical Findings

- Missing scans for certain networks, cloud environments, or remote devices
- Critical vulnerabilities open beyond SLA
- No clear link between asset inventory and scan targets
- No formal tracking of remediation or risk acceptance

## Maturity Indicators

- Level 1: Reactive patching after incidents
- Level 2: Regular scanning but inconsistent remediation
- Level 3: SLA-based remediation with tracking
- Level 4: Automated patching and continuous scanning
- Level 5: Integrated risk-based vulnerability management with business context

## Related Controls

- A.5.14 Change Management
- A.8.9 Configuration Management

**Benefits:** Minimizes exposure to known vulnerabilities and supports regulatory and contractual compliance.
