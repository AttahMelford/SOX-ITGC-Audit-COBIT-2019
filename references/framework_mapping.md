# Framework and Regulatory Mapping

## 1. Introduction

This document describes the regulatory and framework references applied in the simulated SOX IT General Controls (ITGC) audit of Apex Financial Services, Inc.

The project uses the Sarbanes–Oxley Act (SOX), the COSO Internal Control – Integrated Framework, and COBIT 2019 to provide context for evaluating selected IT controls supporting financial reporting.

These references serve different purposes. SOX provides the regulatory context, COSO provides broader internal-control principles, and COBIT 2019 provides governance and management objectives relevant to enterprise information and technology.

## 2. Sarbanes–Oxley Act (SOX)

### Purpose

The Sarbanes–Oxley Act of 2002 established requirements intended to strengthen corporate accountability, financial reporting, and internal controls over financial reporting for applicable public companies.

### Section 404

Section 404 is particularly relevant to internal control over financial reporting.

It addresses management's responsibility for assessing and reporting on internal control over financial reporting and the applicable external auditor attestation requirements.

### Relevance to This Project

The simulated audit focused on IT General Controls that support the reliability of financial reporting systems.

The controls examined included:

- User access authorization.
- Privileged access management.
- Terminated employee access removal.
- Periodic user access reviews.
- Production change authorization.
- Change testing.
- Production deployment restrictions.
- Emergency change reviews.
- Backup monitoring.
- Financial processing job monitoring.
- Incident management.
- Recovery arrangements.

These ITGCs were selected because weaknesses in the supporting technology environment could affect the reliability of financial reporting applications and data.

The project does not provide a legal determination or formal conclusion about SOX compliance.

## 3. COSO Internal Control – Integrated Framework

### Purpose

The COSO Internal Control – Integrated Framework provides principles for designing, implementing, and evaluating internal control systems.

It is organized around five components:

1. Control Environment.
2. Risk Assessment.
3. Control Activities.
4. Information and Communication.
5. Monitoring Activities.

### Relevance to This Project

The COSO framework provides the broader internal-control context for the audit.

| COSO Component | Application in This Project |
|---|---|
| Control Environment | Consideration of accountability, assigned control responsibilities, and management oversight. |
| Risk Assessment | Identification and assessment of IT risks affecting financial reporting. |
| Control Activities | Evaluation of access, change management, and IT operations controls. |
| Information and Communication | Documentation of control evidence, audit findings, and management responses. |
| Monitoring Activities | Consideration of periodic reviews, exception monitoring, remediation, and follow-up validation. |

The mapping is conceptual and does not represent a complete COSO component or principle assessment.

## 4. COBIT 2019

### Purpose

COBIT 2019 provides a framework for the governance and management of enterprise information and technology.

It organizes governance and management activities into objectives that support the alignment of IT with enterprise goals, management of technology-related risks, and delivery of value.

### Relevance to This Project

COBIT 2019 was used to identify preliminary objective-level relationships between the selected ITGCs and relevant governance or management activities.

The selected objectives are listed below.

| COBIT Objective | Objective Name | Relevance to the Audit |
|---|---|---|
| APO07 | Managed Human Resources | Supports personnel-related responsibilities and access processes. |
| APO13 | Managed Security | Supports information security management activities. |
| DSS05 | Managed Security Services | Supports security services and logical access protection. |
| BAI06 | Managed IT Changes | Supports authorization and management of IT changes. |
| BAI07 | Managed IT Change Acceptance and Transitioning | Supports testing, acceptance, and transition of changes. |
| DSS01 | Managed Operations | Supports operational procedures and monitoring. |
| DSS02 | Managed Service Requests and Incidents | Supports incident handling and resolution. |
| DSS04 | Managed Continuity | Supports continuity planning and recovery arrangements. |

## 5. ITGC-to-COBIT Objective Mapping

The following table summarizes the preliminary mapping relationships used in the project.

| ITGC Control | Control Area | COBIT Objective | Mapping Rationale |
|---|---|---|---|
| ITGC-AC-01 | New User Access | DSS05 | Relates to logical access protection and security services. |
| ITGC-AC-02 | Privileged Access | DSS05 | Relates to management of security and privileged access. |
| ITGC-AC-02 | Privileged Access | APO13 | Relates to information security management. |
| ITGC-AC-03 | Terminated User Access | APO07 | Relates to personnel lifecycle responsibilities. |
| ITGC-AC-03 | Terminated User Access | DSS05 | Relates to logical access protection and access revocation. |
| ITGC-AC-04 | User Access Reviews | DSS05 | Relates to ongoing logical access security. |
| ITGC-CH-01 | Change Authorization | BAI06 | Relates to controlled management and authorization of IT changes. |
| ITGC-CH-02 | Change Testing | BAI07 | Relates to testing and acceptance before production transition. |
| ITGC-CH-03 | Production Deployment Access | BAI06 | Relates to controlled implementation of production changes. |
| ITGC-CH-03 | Production Deployment Access | DSS05 | Relates to privileged production access security. |
| ITGC-CH-04 | Emergency Changes | BAI06 | Relates to governance and review of emergency changes. |
| ITGC-OP-01 | Backup Monitoring | DSS01 | Relates to routine operational monitoring. |
| ITGC-OP-01 | Backup Monitoring | DSS04 | Relates to backup and recovery capabilities for continuity. |
| ITGC-OP-02 | Financial Processing Jobs | DSS01 | Relates to monitoring of operational processing activities. |
| ITGC-OP-03 | Incident Management | DSS02 | Relates to incident logging, investigation, and resolution. |
| ITGC-OP-04 | Recovery Arrangements | DSS04 | Relates to business continuity and recovery testing. |

The detailed mapping rationale and validation status are maintained in `cobit_control_mapping.csv`.

## 6. Mapping Limitations

The mappings in this project are preliminary objective-level relationships.

A relationship between an ITGC and a COBIT objective indicates conceptual relevance. It does not demonstrate that the control fully implements the objective or satisfies every related COBIT practice.

A detailed assessment would require review of the applicable COBIT 2019 governance and management practices, associated activities, and enterprise-specific implementation evidence.

The mappings are not a certification, maturity assessment, or formal COBIT compliance determination.

## 7. Relationship Between SOX, COSO, and COBIT

The three references have complementary roles in the simulated audit:

| Reference | Primary Role | Application |
|---|---|---|
| SOX Section 404 | Regulatory context | Internal control over financial reporting. |
| COSO Internal Control – Integrated Framework | Internal-control framework | Broader principles for evaluating internal control. |
| COBIT 2019 | IT governance and management framework | Mapping selected IT controls to relevant IT governance and management objectives. |

Together, these references provide context for the assessment of ITGCs supporting financial reporting.

They are not interchangeable, and the use of one does not establish compliance with the others.

## 8. Conclusion

The project used SOX Section 404 as its regulatory context, COSO as its broader internal-control reference, and COBIT 2019 as its IT governance and management mapping framework.

The resulting mappings connect the 12 selected ITGCs to relevant COBIT objectives while preserving the distinction between conceptual framework alignment and formal compliance assessment.

## 9. References

- Sarbanes–Oxley Act of 2002, Section 404.
- COSO, Internal Control – Integrated Framework.
- ISACA, COBIT 2019 Framework: Introduction and Methodology.
- ISACA, COBIT 2019 Framework: Governance and Management Objectives.

This document supports the educational portfolio simulation and does not constitute an actual audit opinion, certification, or assurance conclusion.
