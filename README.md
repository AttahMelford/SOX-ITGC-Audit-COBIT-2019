# SOX IT General Controls (ITGC) Audit Using COBIT 2019

## Project Overview

This repository contains a completed simulated, risk-based audit of IT General Controls (ITGCs) supporting Internal Control over Financial Reporting (ICFR) at Apex Financial Services, Inc., a fictional publicly traded U.S. financial services company.

The project documents an end-to-end IT audit process, from risk identification and control mapping through audit sampling, evidence evaluation, control testing, exception identification, findings development, remediation planning, and final reporting.

The audit focuses on three ITGC domains: Access Management, Change Management, and IT Operations. COBIT 2019 was used as a supporting framework for mapping selected IT controls to relevant governance and management objectives. SOX Section 404 and the COSO Internal Control – Integrated Framework provided the broader internal-control context.

| Project Information | Details |
|---|---|
| Project | SOX IT General Controls Audit |
| Organization | Apex Financial Services, Inc. (fictional) |
| Audit Period | January 1 – December 31, 2025 |
| Report Date | January 31, 2026 |
| Audit Type | Simulated risk-based ITGC audit |
| Auditor Role | IT Auditor |
| Primary Framework Reference | COBIT 2019 |
| Regulatory Context | Sarbanes–Oxley Act, Section 404 |
| Supporting Framework | COSO Internal Control – Integrated Framework |
| Project Status | Completed portfolio simulation |

## Business Scenario

Apex Financial Services, Inc. is a fictional financial services organization that relies on financial applications, databases, and supporting IT infrastructure to process transactions and prepare financial reports.

The simulated audit assessed selected IT General Controls that support the reliability, availability, and security of the organization's financial reporting environment.

The audit addressed risks associated with unauthorized access, inappropriate production changes, incomplete processing activities, incident handling, and recovery arrangements.

## Audit Objectives

The audit was designed and documented to:

- Identify IT risks relevant to financial reporting.
- Evaluate selected IT General Controls supporting financial systems.
- Develop a Risk and Control Matrix (RCM).
- Map selected ITGCs to relevant COBIT 2019 objectives.
- Define audit populations and document sample selection.
- Perform simulated operating-effectiveness testing.
- Evaluate supporting audit evidence.
- Identify and document control exceptions.
- Develop preliminary audit findings and recommendations.
- Establish corrective actions, management responses, and validation procedures.
- Communicate the results through a structured audit report.

## Audit Scope

The audit covered 12 selected IT General Controls across three domains.

### 1. Access Management

- New user access authorization.
- Privileged access restrictions and periodic reviews.
- Timely removal of terminated employee access.
- Periodic user access reviews.

### 2. Change Management

- Production change authorization.
- Change testing before production deployment.
- Production deployment access restrictions.
- Emergency change documentation and retrospective review.

### 3. IT Operations

- Backup monitoring and failure resolution.
- Scheduled financial processing job monitoring.
- Financial system incident management.
- Recovery arrangements and testing.

The project assessed IT General Controls only. IT Application Controls (ITACs) were not included in the testing performed.

## Frameworks and Standards

**Sarbanes–Oxley Act (SOX), Section 404**

Provided the regulatory context for evaluating controls relevant to internal control over financial reporting.

**COSO Internal Control – Integrated Framework**

Provided broader internal-control principles for understanding control activities, risk assessment, monitoring, and information and communication.

**COBIT 2019**

Provided governance and management objectives used to support the mapping and assessment of selected IT controls.

The framework mappings in this repository are preliminary objective-level mappings. They are not representations of formal certification or complete practice-level compliance.

## Audit Methodology

The simulated audit followed a risk-based approach that included:

1. Identifying financial reporting-related IT risks.
2. Documenting control objectives and activities in the RCM.
3. Assessing inherent risk using a five-by-five likelihood and impact model.
4. Selecting relevant audit populations and samples.
5. Documenting audit procedures and evidence references.
6. Evaluating simulated operating effectiveness.
7. Recording exceptions and developing preliminary findings.
8. Preparing remediation recommendations and management responses.
9. Reporting results and limitations.

The methodology distinguishes control design effectiveness from operating effectiveness. The documented test results primarily address simulated operating effectiveness and do not establish a complete independent design-effectiveness assessment.

## Audit Results

| Audit Measure | Result |
|---|---:|
| ITGC domains | 3 |
| Controls documented and tested | 12 |
| Total sample items documented | 108 |
| Controls passing sample tests | 6 |
| Controls with exceptions | 6 |
| Preliminary audit findings | 6 |
| Remediation actions | 6 |
| Evidence register entries | 14 |

The results represent the simulated testing documented in the workpapers. They are not statistical projections of the full populations.

## Key Findings

The simulated testing identified exceptions involving:

- Missing documented privileged access reviews.
- Missing application owner sign-off on a quarterly access review.
- Incomplete evidence of production change testing.
- Missing retrospective review of an emergency change.
- Incomplete investigation and resolution evidence for failed financial processing jobs.
- An unresolved recovery-time objective failure identified during recovery testing.

Each finding is linked to its related control and test. The findings log also records preliminary severity, recommendations, and management response status.

The identified exceptions are not automatically classified as significant deficiencies or material weaknesses. Formal SOX deficiency classification requires additional evaluation of likelihood, potential magnitude, financial reporting impact, and relevant compensating controls.

## Repository Structure

```text
sox-itgc-audit-cobit-2019/
│
├── README.md
│
├── docs/
│   ├── audit_scope.md
│   └── audit_methodology.md
│
├── references/
│   ├── framework_mapping.md
│   └── cobit_control_mapping.csv
│
├── risk-control-matrix/
│   └── sox_itgc_rcm.csv
│
├── audit-testing/
│   ├── access_management_testing.csv
│   ├── change_management_testing.csv
│   ├── it_operations_testing.csv
│   └── audit_sampling_summary.csv
│
├── evidence/
│   └── evidence_register.csv
│
├── findings/
│   ├── findings_log.csv
│   ├── remediation_plan.csv
│   └── management_responses.csv
│
└── reports/
    └── final_audit_report.md
```

## Completed Audit Deliverables

The repository includes:

- Audit scope and planning documentation.
- Audit methodology.
- Risk and Control Matrix.
- COBIT 2019 control mapping.
- Three ITGC testing workpapers.
- Audit sampling summary.
- Evidence register.
- Findings and exceptions log.
- Remediation plan.
- Simulated management responses.
- Final simulated audit report.

## Professional Skills Demonstrated

This project demonstrates practical understanding of:

- IT General Controls (ITGCs).
- SOX and internal control over financial reporting.
- IT risk assessment.
- Risk and Control Matrix development.
- COBIT 2019 framework mapping.
- Audit planning and sampling.
- Audit evidence documentation.
- Access management reviews.
- Change management testing.
- IT operations controls.
- Audit findings and remediation tracking.
- Audit reporting and documentation.

These activities are relevant to IT Auditor, SOX IT Controls Analyst, IT Compliance Analyst, IT Risk Analyst, and Governance, Risk, and Compliance (GRC) roles.

## Disclaimer

Apex Financial Services, Inc. is fictional. All organizational information, systems, populations, evidence records, sample selections, test results, findings, management responses, and remediation activities are simulated.

This repository is an educational portfolio project. It does not represent an actual audit engagement, independent audit opinion, certification, or assurance conclusion. It does not establish the compliance status of any real organization under SOX, COBIT, or COSO.
