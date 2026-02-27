# A.8.9 Configuration Management

## Objective

Ensure systems are securely configured, maintained, and changed in a controlled and consistent manner.

## Implementation Guidance

- Define secure baseline configurations (e.g., CIS Benchmarks, vendor best practices).
- Use configuration management tools (e.g., Ansible, Puppet, Chef, Group Policy).
- Enforce change management with approvals, testing, and rollback plans.
- Maintain configuration documentation and version control (e.g., Git).
- Conduct periodic configuration reviews and compliance checks.
- Monitor and alert on deviations from approved baselines.

## Audit Criteria

- Are secure configuration baselines documented and approved?
- Are changes logged, reviewed, and approved before implementation?
- Are configuration management tools used consistently across environments?
- Are deviations from baselines detected, investigated, and corrected?
- Are configuration reviews performed regularly and documented?

## Evidence Examples

- Baseline configuration documents
- Change tickets and approval records
- Version control logs (e.g., Git commits)
- Configuration compliance reports
- Audit reports on configuration reviews

## Typical Findings

- No defined or documented baselines
- Unauthorized or emergency changes not documented
- Manual configuration without version control
- No regular review of configuration compliance

## Maturity Indicators

- Level 1: Manual, undocumented configuration
- Level 2: Basic baselines for some systems
- Level 3: Formal change management and documented baselines
- Level 4: Automated configuration enforcement and monitoring
- Level 5: Continuous compliance with real-time reporting

## Related Controls

- A.5.14 Change Management
- A.8.8 Management of Technical Vulnerabilities

**Benefits:** Reduces misconfigurations, improves stability, and lowers the risk of security incidents caused by human error.
