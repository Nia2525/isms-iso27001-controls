# A.8.10 Information Deletion

## Objective

Ensure information is securely deleted when no longer required, preventing unauthorized recovery and reducing legal and compliance risks.

## Implementation Guidance

- Define data retention and deletion policies aligned with legal, regulatory, and business requirements (e.g., GDPR).
- Use secure deletion methods (e.g., cryptographic erasure, secure wipe tools, storage encryption with key destruction).
- Ensure deletion processes cover production systems, backups, logs, and cloud storage.
- Maintain records of deletion activities for auditability.
- Test deletion processes periodically to verify that data cannot be recovered.
- Integrate deletion into offboarding, decommissioning, and lifecycle management processes.

## Audit Criteria

- Are retention and deletion policies documented, approved, and communicated?
- Are secure deletion tools and methods defined and used consistently?
- Are deletion logs or records maintained and reviewed?
- Are backups and replicas included in deletion procedures?
- Are deletion processes tested and validated?

## Evidence Examples

- Data retention and deletion policies
- Deletion logs and reports
- Backup deletion or retention procedures
- Tool configuration screenshots or documentation
- Test reports showing successful non-recoverability

## Typical Findings

- Data retained longer than necessary without justification
- No deletion process for backups or cloud storage
- Incomplete or missing deletion logs
- Manual deletion without verification

## Maturity Indicators

- Level 1: Ad-hoc manual deletion
- Level 2: Basic retention policy, limited enforcement
- Level 3: Defined secure deletion processes and tools
- Level 4: Automated deletion workflows integrated with systems
- Level 5: Full data lifecycle governance with continuous monitoring

## Related Controls

- A.5.32 Information Retention
- A.5.34 Privacy and Protection of PII

**Benefits:** Reduces exposure of obsolete data, supports privacy compliance, and limits impact in case of breaches.
