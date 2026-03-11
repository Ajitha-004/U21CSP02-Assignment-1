# Protect, Preserve, and Serve Information Services

## 1. Protect – Confidentiality

**Purpose:** Ensure only authorized users can access data.

### Mechanisms

* Encryption at Rest: Data encrypted when stored
* Encryption in Transit: Data encrypted during transmission
* Access Controls: RBAC, ABAC, ACL
* Authentication: Multi‑factor authentication (MFA)
* Audit Trails: Record all access and modifications

### Implementation Practices

* AES‑256 encryption standard
* TLS 1.2+ for data in transit
* Regular access reviews and cleanup
* Principle of Least Privilege
* Strong password policies

---

## 2. Preserve – Integrity

**Purpose:** Ensure data has not been altered or corrupted.

### Mechanisms

* Checksums and Hash Functions: Detect data changes
* Digital Signatures: Verify authenticity
* WORM (Write Once Read Many): Prevent modification
* Immutable Backups: Read‑only backup copies
* Consistency Checks: Validate stored data

### Implementation Practices

* Regular integrity checks (daily/weekly)
* Separate verification procedures
* Immutable storage for compliance data
* Version control for tracking changes
* Rollback procedures for corruption recovery

---

## 3. Serve – Availability

**Purpose:** Ensure authorized users can access data when needed.

### Mechanisms

* Redundancy: Multiple copies of data
* Disaster Recovery: Recovery procedures for incidents
* High Availability: Failover systems to reduce downtime
* Performance Optimization: Faster response to requests
* Capacity Planning: Ensure sufficient resources

### Implementation Practices

* Regular disaster recovery testing
* Defined RTO and RPO targets
* Continuous system health monitoring
* Graceful degradation under heavy load
* Load balancing across resources

---

## Integration of Security Services

* All three pillars must work together
* Security should not severely affect availability
* Compliance requires confidentiality, integrity, and availability
* Regular assessment of effectiveness

---

### Quick Memory Tip

* Protect → Confidentiality
* Preserve → Integrity
* Serve → Availability
