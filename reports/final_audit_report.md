# Apex Financial Services, Inc.
# SOX IT General Controls (ITGC) Audit Report

**Audit Period:** January 1 – December 31, 2025  
**Report Date:** January 31, 2026  
**Prepared By:** IT Audit Function  
**Audit Type:** Simulated Risk-Based SOX ITGC Audit  
**Framework References:** SOX Section 404, COSO Internal Control – Integrated Framework, COBIT 2019

---

## 1. Executive Summary

This report presents the results of a simulated risk-based audit of Information Technology General Controls (ITGCs) at Apex Financial Services, Inc., a fictional publicly traded U.S. financial services company.

The audit was designed to evaluate whether selected IT controls supporting financial reporting were appropriately designed and operating effectively during the period January 1 through December 31, 2025.

The assessment covered three primary ITGC domains:

- Access Management
- Change Management
- IT Operations

A total of 12 controls were included in the Risk and Control Matrix (RCM). Audit procedures were documented for all 12 controls, using a combined sample of 108 test items across the three domains.

Based on the simulated test results:

- 6 controls passed the documented sample tests.
- 6 controls had exceptions and were classified as failed.
- 6 preliminary audit findings were documented.
- 6 remediation actions were proposed.

The exceptions primarily involved incomplete privileged access reviews, insufficient change testing documentation, missing emergency change reviews, incomplete investigation of failed processing jobs, and an unresolved recovery-time objective failure.

These results indicate opportunities to strengthen control execution, evidence retention, monitoring, and remediation oversight.

The findings are preliminary. Their severity and potential financial reporting implications require further assessment before any conclusion about significant deficiencies or material weaknesses could be reached.

## 2. Background and Business Scenario

Apex Financial Services, Inc. is a fictional financial services organization operating in the United States.

For this engagement, the organization is assumed to rely on financial applications, databases, infrastructure, and supporting IT services to process, maintain, and report financial information.

Because these systems support financial reporting, weaknesses in access security, production change management, or IT operations could affect the reliability, completeness, or accuracy of financial information.

The audit scenario was developed to demonstrate how an IT auditor can assess ITGCs using a structured, risk-based approach.

All company information, systems, employees, evidence, audit samples, results, findings, and remediation activities in this project are simulated.

## 3. Audit Objectives

The primary objectives were to:

1. Assess whether access to financial systems was authorized, appropriate, and periodically reviewed.
2. Determine whether production changes were authorized, tested, and appropriately controlled.
3. Evaluate whether critical IT operations were monitored and exceptions were investigated.
4. Identify control weaknesses that could affect systems supporting financial reporting.
5. Document control exceptions and their potential business and financial reporting implications.
6. Recommend corrective actions to strengthen the IT control environment.

## 4. Audit Scope

The audit covered selected ITGCs supporting financial reporting during the 2025 audit period.

### 4.1 Access Management

The assessment covered:

- New user access authorization.
- Privileged account restrictions and periodic reviews.
- Timely removal of terminated employee access.
- Periodic user access reviews.

### 4.2 Change Management

The assessment covered:

- Authorization of production changes.
- Testing and approval before deployment.
- Restrictions on production deployment privileges.
- Documentation and retrospective review of emergency changes.

### 4.3 IT Operations

The assessment covered:

- Monitoring of financial system backups.
- Monitoring of scheduled financial processing jobs.
- Incident management.
- Business continuity and recovery testing.

### 4.4 Out of Scope

The engagement did not constitute a complete financial statement audit, enterprise-wide cybersecurity assessment, penetration test, or independent evaluation of every IT system and application.

The assessment also did not independently determine the organization's overall SOX compliance status.

## 5. Frameworks and Audit Criteria

The assessment referenced the following frameworks and regulatory requirements.

**Sarbanes-Oxley Act (SOX), Section 404**

Provided the regulatory context for evaluating internal control over financial reporting.

**COSO Internal Control – Integrated Framework**

Provided a broader internal control perspective, including control activities, risk assessment, monitoring, information and communication, and the control environment.

**COBIT 2019**

Provided governance and management objectives supporting the assessment of IT processes, including:

- APO07 – Managed Human Resources
- DSS01 – Managed Operations
- DSS02 – Managed Service Requests and Incidents
- DSS04 – Managed Continuity
- DSS05 – Managed Security Services
- BAI06 – Managed IT Changes
- BAI07 – Managed IT Change Acceptance and Transitioning

The COBIT mappings in this project are preliminary objective-level mappings. They are supporting references, not a substitute for applicable SOX requirements or a validated practice-level control crosswalk.

## 6. Audit Methodology

A risk-based audit methodology was used.

### 6.1 Risk Assessment

Risks were evaluated using two factors:

- Likelihood: rated from 1 to 5.
- Impact: rated from 1 to 5.

The inherent risk score was calculated as:

**Inherent Risk Score = Likelihood × Impact**

Risk ratings were assigned as follows:

| Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

### 6.2 Control Assessment

The audit considered whether controls were appropriately designed to address identified risks and whether evidence demonstrated that they operated as intended.

Design effectiveness and operating effectiveness are separate assessment considerations. The documented sample results primarily demonstrate simulated operating-effectiveness testing. A complete design-effectiveness conclusion would require additional documented evaluation.

### 6.3 Sample Selection

Samples were selected using risk-based selection, coverage across the audit period, or complete-population testing where appropriate.

The audit workpapers document the relevant populations, sample sizes, selection approaches, evidence reviewed, and conclusions.

The results should not be interpreted as statistical projections to the entire population.

### 6.4 Evidence Evaluation

Evidence was assessed based on relevance, completeness, reliability, and its ability to support the audit procedure.

Evidence references were recorded in the Audit Evidence Register.

## 7. Audit Testing Summary

The engagement documented 12 control tests across the three ITGC domains.

| ITGC Domain | Controls Tested | Passed | Failed |
|---|---:|---:|---:|
| Access Management | 4 | 2 | 2 |
| Change Management | 4 | 2 | 2 |
| IT Operations | 4 | 2 | 2 |
| **Total** | **12** | **6** | **6** |

A combined total of 108 sample items was documented across the workpapers.

### 7.1 Access Management Results

Two of the four access management controls passed their sample tests.

The audit identified:

- Two privileged accounts without documented quarterly access review evidence.
- One quarterly user access review without documented application owner sign-off.

The testing highlighted weaknesses in review documentation and oversight of user privileges.

### 7.2 Change Management Results

Two of the four change management controls passed their sample tests.

The audit identified:

- Two production changes without documented evidence of completed testing before deployment.
- One emergency change without documented retrospective review.

These exceptions indicate weaknesses in change testing documentation and emergency change governance.

### 7.3 IT Operations Results

Two of the four IT operations controls passed their sample tests.

The audit identified:

- Two failed financial processing job executions without documented investigation and resolution evidence.
- One recovery test that identified an unresolved recovery-time objective failure.

These exceptions could affect the availability, completeness, and reliability of systems supporting financial reporting.

## 8. Summary of Audit Findings

Six preliminary findings were documented.

| Finding ID | Finding | Domain | Preliminary Severity |
|---|---|---|---|
| F-001 | Incomplete Privileged Access Reviews | Access Management | High |
| F-002 | Missing Application Owner Review Sign-off | Access Management | Moderate |
| F-003 | Insufficient Evidence of Change Testing | Change Management | High |
| F-004 | Missing Emergency Change Retrospective Review | Change Management | Moderate |
| F-005 | Incomplete Investigation of Failed Financial Processing Jobs | IT Operations | High |
| F-006 | Unresolved Recovery-Time Objective Failure | IT Operations | High |

### 8.1 F-001: Incomplete Privileged Access Reviews

**Condition:** Two privileged accounts lacked documented evidence of quarterly access review.

**Risk:** Excessive or inappropriate privileged access could remain undetected, increasing the possibility of unauthorized changes to financial systems or data.

**Recommendation:** Implement documented quarterly privileged access reviews, require reviewer sign-off, and track identified exceptions through remediation.

**Severity:** High (preliminary).

### 8.2 F-002: Missing Application Owner Review Sign-off

**Condition:** One quarterly user access review lacked documented application owner sign-off.

**Risk:** Inappropriate user permissions may remain undetected.

**Recommendation:** Require application owners to formally approve periodic access reviews and retain supporting evidence.

**Severity:** Moderate (preliminary).

### 8.3 F-003: Insufficient Evidence of Change Testing

**Condition:** Two sampled production changes lacked documented evidence of completed testing before deployment.

**Risk:** Untested changes may introduce errors into financial reporting applications.

**Recommendation:** Enforce documented testing, review, and approval requirements before production deployment.

**Severity:** High (preliminary).

### 8.4 F-004: Missing Emergency Change Retrospective Review

**Condition:** One sampled emergency change lacked documented retrospective review evidence.

**Risk:** Emergency changes may introduce unauthorized or untested modifications without appropriate oversight.

**Recommendation:** Establish mandatory retrospective review requirements, defined completion timelines, and escalation for overdue reviews.

**Severity:** Moderate (preliminary).

### 8.5 F-005: Incomplete Investigation of Failed Financial Processing Jobs

**Condition:** Two sampled failed processing job executions lacked documented investigation and resolution evidence.

**Risk:** Incomplete processing could result in missing or inaccurate financial information.

**Recommendation:** Implement exception tracking, assign investigation owners, and require documented resolution before closure.

**Severity:** High (preliminary).

### 8.6 F-006: Unresolved Recovery-Time Objective Failure

**Condition:** One recovery test identified a recovery-time objective failure that remained unresolved at year-end.

**Risk:** Extended system downtime could disrupt financial reporting activities and delay access to critical financial data.

**Recommendation:** Develop a corrective action plan, address identified recovery gaps, and conduct a successful follow-up recovery test.

**Severity:** High (preliminary).

## 9. Remediation and Corrective Action Plan

A remediation plan was developed for all six findings.

| Finding ID | Responsible Owner | Target Completion |
|---|---|---|
| F-001 | IT Security Manager | March 31, 2026 |
| F-002 | Application Owner | February 28, 2026 |
| F-003 | Application Development Manager | April 15, 2026 |
| F-004 | IT Change Manager | March 15, 2026 |
| F-005 | Application Operations Manager | April 30, 2026 |
| F-006 | IT Disaster Recovery Manager | May 31, 2026 |

The remediation plan includes corrective actions, accountable owners, supporting teams, milestones, closure evidence, and validation procedures.

All remediation statuses are recorded as Open in the simulated plan. No remediation should be considered complete until supporting evidence has been reviewed and the relevant control has been retested.

## 10. Overall Audit Assessment

The simulated assessment identified control exceptions across all three ITGC domains.

The results suggest that Apex Financial Services should strengthen:

- Privileged access governance and periodic access reviews.
- Documentation of change testing and emergency change approvals.
- Investigation and resolution of failed financial processing jobs.
- Recovery testing and follow-up of identified continuity issues.

The six findings require management attention and documented corrective action.

The assessment does not establish that the fictional company has a material weakness, significant deficiency, or actual SOX noncompliance. Such determinations require additional analysis of the likelihood and potential magnitude of financial statement misstatement, relevant compensating controls, and applicable reporting requirements.

## 11. Audit Limitations

This is an educational and portfolio-based simulation.

The following limitations apply:

1. Apex Financial Services, Inc. is fictional.
2. All audit populations, samples, evidence records, test results, findings, and remediation plans are simulated.
3. No actual company systems, employees, or financial records were examined.
4. No independent external audit or assurance engagement was performed.
5. Sample results do not provide statistical assurance about an entire population.
6. Preliminary COBIT mappings require further validation at the relevant practice level.
7. No formal opinion on SOX compliance or internal control effectiveness is expressed.

## 12. Conclusion

This simulated audit demonstrates a structured approach to assessing IT General Controls that support financial reporting.

Through risk identification, control mapping, audit testing, evidence documentation, exception analysis, and remediation planning, the project illustrates how an IT auditor can evaluate selected controls and communicate potential weaknesses to management.

The completed workpapers provide a traceable foundation for further audit procedures, management responses, remediation monitoring, and follow-up testing.

---

## 13. Supporting Audit Workpapers

The following repository artifacts support this report:

| Artifact | Repository Location |
|---|---|
| Audit Scope | `docs/audit_scope.md` |
| Audit Methodology | `docs/audit_methodology.md` |
| Framework Mapping | `references/framework_mapping.md` |
| COBIT Control Mapping | `references/cobit_control_mapping.csv` |
| SOX ITGC Risk and Control Matrix | `risk-control-matrix/sox_itgc_rcm.csv` |
| Access Management Testing | `audit-testing/access_management_testing.csv` |
| Change Management Testing | `audit-testing/change_management_testing.csv` |
| IT Operations Testing | `audit-testing/it_operations_testing.csv` |
| Audit Evidence Register | `evidence/evidence_register.csv` |
| Audit Findings Log | `findings/findings_log.csv` |
| Remediation Plan | `findings/remediation_plan.csv` |

**End of Report**

*Prepared for educational and professional portfolio demonstration purposes only.*
