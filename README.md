# Darwin-GRC-PCI-DSS-Compliance-Gap-Assessment

## Project Overview

This project simulates a PCI DSS compliance gap assessment for a fictional e-commerce company called **CloudNova Commerce**.

The goal is to evaluate payment-card security controls, identify compliance gaps, assess risk, document evidence, and develop remediation recommendations aligned with PCI DSS requirements.

This project demonstrates practical GRC skills including:

- PCI DSS compliance assessment
- Control review
- Gap analysis
- Risk identification
- Risk scoring
- Evidence tracking
- Remediation planning
- Security governance
- Compliance documentation
- Audit readiness

## Business Scenario

CloudNova Commerce is a fictional online retailer that processes customer payment-card transactions.

The organization uses:

- E-commerce payment processing
- Cloud-hosted systems
- Firewalls
- Endpoint protection
- Multi-Factor Authentication
- Centralized logging
- Vulnerability scanning
- Security awareness training
- Third-party payment providers

Because payment-card data is involved, the organization must maintain security controls that reduce the risk of unauthorized access, malware, data exposure, and insecure payment environments.

## Assessment Scope

The assessment focuses on PCI DSS control areas including:

- Network Security
- Secure Configuration
- Account Protection
- Access Control
- Logging and Monitoring
- Vulnerability Management
- Malware Protection
- Security Testing
- Security Awareness
- Incident Response
- Third-Party Risk
- Data Protection

## Assessment Method

Each control is evaluated using:

1. PCI DSS Requirement
2. Control Objective
3. Current State
4. Compliance Status
5. Risk Level
6. Evidence Available
7. Gap Identified
8. Remediation Recommendation

## Compliance Status Ratings

- Compliant
- Partially Compliant
- Non-Compliant
- Not Tested

## Key Findings

| Control Area | Status | Risk |
|---|---|---|
| Firewall Rule Reviews | Partially Compliant | Medium |
| Default Account Removal | Compliant | Low |
| MFA for Administrative Access | Partially Compliant | High |
| Quarterly Vulnerability Scanning | Compliant | Low |
| Critical Vulnerability Remediation | Partially Compliant | High |
| Centralized Security Logging | Compliant | Low |
| Daily Log Review | Partially Compliant | Medium |
| Security Awareness Training | Compliant | Low |
| Incident Response Testing | Non-Compliant | High |
| Third-Party Security Review | Partially Compliant | Medium |
| Cardholder Data Retention | Partially Compliant | High |
| Penetration Testing | Partially Compliant | Medium |

## Risk Assessment Method

Risk is calculated using:

Risk Score = Likelihood × Impact

### Risk Ratings

- 1–4 = Low
- 5–10 = Medium
- 11–15 = High
- 16–25 = Critical

## Example Risks

| Risk | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| Administrator account compromise | 3 | 5 | 15 | High |
| Cardholder data exposure | 3 | 5 | 15 | High |
| Unpatched critical vulnerability | 3 | 5 | 15 | High |
| Delayed incident response | 3 | 5 | 15 | High |
| Incomplete log monitoring | 2 | 4 | 8 | Medium |
| Third-party compromise | 3 | 4 | 12 | High |

## Example Gap

### MFA for Administrative Access

**Current State:**  
MFA is enabled for some administrative accounts but is not consistently enforced.

**Compliance Status:**  
Partially Compliant

**Risk Level:**  
High

**Gap:**  
Administrative access is not fully protected by strong authentication.

**Recommendation:**  
Require MFA for all administrator accounts and document approved exceptions.

## Evidence Examples

Supporting evidence may include:

- Firewall configuration screenshots
- Access control policies
- MFA configuration
- Vulnerability scan reports
- Patch remediation tickets
- Security logging screenshots
- Security awareness records
- Incident response procedures
- Penetration test reports
- Vendor security questionnaires
- Data retention documentation

## Remediation Priorities

1. Enforce MFA for all administrative access
2. Improve cardholder data retention controls
3. Conduct incident response testing
4. Remediate critical vulnerabilities within defined timelines
5. Improve daily security-log review documentation
6. Formalize third-party security assessments
7. Perform recurring penetration testing
8. Document firewall rule reviews

## Repository Structure

Darwin-GRC-PCI-DSS-Compliance-Gap-Assessment/
│
├── README.md
├── pci_dss_control_matrix.csv
├── pci_dss_gap_assessment.csv
├── pci_dss_risk_register.csv
├── remediation_plan.md
├── evidence_log.csv
└── evidence/

## Skills Demonstrated

- PCI DSS
- Governance, Risk, and Compliance
- Compliance Assessment
- Control Testing
- Gap Analysis
- Risk Assessment
- Risk Registers
- Audit Evidence
- Remediation Planning
- Security Governance
- Third-Party Risk Management
- Vulnerability Management
- Access Control
- Compliance Documentation

## Project Goal

The goal of this project is to demonstrate practical PCI DSS compliance work by evaluating security controls, identifying gaps, assessing risk, documenting evidence, and developing remediation recommendations for a simulated payment-card environment.
