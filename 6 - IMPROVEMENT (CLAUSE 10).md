# 6 - IMPROVEMENT (CLAUSE 10)

# Nonconformity Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Nonconformity Procedure |
| Document ID | DTB-NG-ISMS-NCP-061 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the process for identifying, reporting, and initially reacting to nonconformities within the Information Security Management System (ISMS) at DTB Nigeria. It ensures that when a nonconformity occurs, the organization reacts appropriately to control and correct it, and deals with the consequences in alignment with ISO/IEC 27001:2022 Clause 10.2.

This procedure acts as the first phase of the continual improvement lifecycle, seamlessly integrating with the Corrective Action Procedure (DTB-NG-ISMS-CAP-062) to prevent recurrence.

## 3. Scope

This procedure applies to all nonconformities related to the ISMS policies, procedures, controls, and ISO/IEC 27001:2022 requirements within the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Sources of nonconformities covered by this procedure include, but are not limited to:

- Internal and external audit findings.
- Information security incidents and breaches.
- Management review outputs.
- Key Performance Indicator (KPI) and metric failures.
- Regulatory compliance failures or gap assessments.
- Routine operational monitoring and employee observations.

Out-of-scope international entities are excluded unless their activities directly result in a nonconformity within the DTB Nigeria ISMS scope.

## 4. References

1. ISO/IEC 27001:2022 Clause 10.2 (Nonconformity and corrective action)
2. DTB-NG-ISMS-POL-008 – Information Security Policy
3. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
4. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
5. DTB-NG-ISMS-RCP-021 – Record Control Procedure

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Nonconformity (NC) | The non-fulfillment of a specified requirement (e.g., failure to follow a policy, malfunctioning of a security control, or missing ISMS documentation). |
| Correction | Immediate action taken to eliminate a detected nonconformity or contain its immediate impact (e.g., isolating a compromised server or restoring a deleted file). |
| Corrective Action | Action taken to eliminate the *root cause* of a nonconformity to prevent it from recurring. |
| Major Nonconformity | A total breakdown of a system requirement, absence of a required control, or a risk situation that threatens the integrity of the ISMS. |
| Minor Nonconformity | An isolated incident, minor lapse in discipline, or a partial fulfillment of a requirement that does not immediately threaten the ISMS. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| All staff/users | Identify and promptly report suspected nonconformities or deviations from approved security policies to their Line Manager or the Information Security team. |
| ISMS Programme Manager | Manages the central Nonconformity Register, tracks reported NCs, and coordinates the initial evaluation and assignment of the NC. |
| Control / Process Owners | Take immediate correction/containment actions when an NC is identified within their domain and participate in the subsequent corrective action process. |
| CISO (Nigeria) | Evaluates the severity of identified nonconformities, approves immediate containment strategies for critical NCs, and reports significant NCs to the ISMC. |
| Internal Audit | Identifies and formally reports nonconformities discovered during planned audit activities. |

## 7. Procedure

### 7.1 Identification and Reporting

1. A nonconformity can be identified by any employee, contractor, auditor, or via automated monitoring systems.
2. Upon identification, the nonconformity must be reported to the ISMS Programme Manager or the IT Service Desk. If identified during an audit, it is reported via the formal Internal Audit Report.
3. The report must include factual, objective evidence of the non-fulfillment of the requirement (e.g., screenshot, log extract, specific policy clause violated).

### 7.2 Immediate Reaction and Correction (Containment)

1. Upon validation of the nonconformity, the relevant Control Owner must immediately assess if the NC poses an active threat to DTB Nigeria’s information assets.
2. If an active threat exists (e.g., an unauthorized open firewall port), the Control Owner must take immediate **Correction** to contain the issue, minimize impact, and deal with the consequences.
3. If the nonconformity constitutes an active security breach, the Information Security Incident Response Procedure (DTB-NG-ISMS-IRP-039) must be triggered immediately.
4. Immediate corrections must be documented, including who authorized the action and what steps were taken.

### 7.3 Logging and Categorization

1. The ISMS Programme Manager shall record the nonconformity in the central ISMS Nonconformity Register.
2. The NC shall be categorized by severity:
    - **Major:** Requires immediate management escalation, urgent containment, and comprehensive corrective action.
    - **Minor:** Requires standard correction and scheduled root cause analysis.
    - **Observation / Opportunity for Improvement (OFI):** Not a strict violation, but a potential weakness that should be proactively addressed.
3. The record must map the NC to the specific ISO 27001 clause, Annex A control, or internal DTB document that was breached.

### 7.4 Evaluation of the Need for Corrective Action

1. Once the immediate correction is applied and the situation is stable, the ISMS Programme Manager and the CISO shall evaluate the NC to determine if a formal Corrective Action is required to prevent recurrence.
2. Formal Corrective Action is mandatory for all Major Nonconformities, repetitive Minor Nonconformities, and audit findings.
3. If formal Corrective Action is deemed necessary, the process transitions to the Corrective Action Procedure (DTB-NG-ISMS-CAP-062).
4. If the NC was an isolated, low-risk human error successfully corrected without systemic implications, it may be closed in the register with a justification, without triggering a full Corrective Action process.

### 7.5 Assumptions Applied

1. DTB Nigeria fosters a "blame-free" reporting culture to encourage the proactive identification of nonconformities.
2. An integrated IT Service Management (ITSM) or Governance, Risk, and Compliance (GRC) tool is used to effectively log and route nonconformities.
3. Control Owners have the necessary authority to enact immediate, emergency corrections to contain severe nonconformities.

## 8. ISMS Nonconformity Workflow Matrix (Baseline)

| **Phase** | **Action** | **Responsible Role** | **Target Timeline** |
| --- | --- | --- | --- |
| **Identification** | Detect and report the NC | Any Staff / Auditor | Immediately |
| **Logging** | Enter NC into central register | ISMS-PM | Within 24 Hours of report |
| **Correction** | Execute immediate containment actions | Control Owner | < 24 Hours (if Major) |
| **Categorization** | Assign severity (Major, Minor, OFI) | CISO / ISMS-PM | Within 48 Hours |
| **Handoff** | Initiate Corrective Action Procedure | ISMS-PM | Within 3 Days of categorization |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| ISMS Nonconformity Register | ISMS Programme Manager | Minimum 6 years |
| Audit Nonconformity Reports | Internal Audit | Minimum 6 years |
| Initial Correction / Containment Logs | Control Owners | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
3. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
4. DTB-NG-ISMS-RCP-021 – Record Control Procedure
5. DTB-NG-ISMS-IRP-039 – Information Security Incident Response Procedure (to be issued)

## 11. ISO Clause References

- Clause 10.1 Continual improvement
- Clause 10.2 Nonconformity and corrective action

## 12. Annex A References

- N/A (Applies to failures in any Annex A control).

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Following any major external audit where the auditor identifies weaknesses in the bank's internal nonconformity management process.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / Chief Internal Auditor | Defined severity categories and containment responsibilities |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Corrective Action Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Corrective Action Procedure |
| Document ID | DTB-NG-ISMS-CAP-062 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the methodology for identifying the root causes of recognized nonconformities and implementing corrective actions to prevent their recurrence within the Information Security Management System (ISMS) at DTB Nigeria.

This procedure ensures DTB Nigeria effectively reviews nonconformities, determines their causes, evaluates the need for action, implements the required actions, and reviews the effectiveness of those actions, in strict compliance with ISO/IEC 27001:2022 Clause 10.2.

## 3. Scope

This procedure applies to all corrective actions initiated within the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

This procedure is triggered following the formal identification and initial containment of a nonconformity under the Nonconformity Procedure (DTB-NG-ISMS-NCP-061). It applies to root causes originating from internal audits, external audits, security incidents, risk assessments, or management reviews. Out-of-scope international entities are excluded unless their actions are identified as the root cause of a local nonconformity.

## 4. References

1. ISO/IEC 27001:2022 Clause 10.2 (Nonconformity and corrective action)
2. DTB-NG-ISMS-POL-008 – Information Security Policy
3. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
4. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
5. DTB-NG-ISMS-RRG-017 – Risk Register
6. DTB-NG-ISMS-RCP-021 – Record Control Procedure

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Corrective Action (CA) | Action taken to eliminate the *root cause* of a detected nonconformity or other undesirable situation to prevent recurrence. |
| Root Cause Analysis (RCA) | A systematic process for identifying the underlying, systemic reasons why a nonconformity or incident occurred. |
| Nonconformity | The non-fulfillment of a specified requirement. |
| Verification | The objective confirmation that a corrective action has been implemented and successfully eliminated the root cause without introducing new, unmitigated risks. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| ISMS Programme Manager | Manages the Corrective Action Plan (CAP) register, coordinates RCA activities, and monitors the timely implementation of approved actions. |
| Control / Process Owners | Conduct Root Cause Analysis for nonconformities within their domain, develop the corrective action plan, and execute the required remediation steps. |
| CISO (Nigeria) | Approves proposed corrective actions, ensures adequate resources are allocated for remediation, and authorizes risk register updates if necessary. |
| Internal Audit | Verifies the effectiveness of implemented corrective actions during follow-up audits before formally closing the nonconformity. |

## 7. Procedure

### 7.1 Reviewing the Nonconformity

1. Once a nonconformity is handed over from the Nonconformity Procedure (DTB-NG-ISMS-NCP-061), the assigned Control Owner must conduct a formal review.
2. The review must ensure that the initial correction (containment) was successful and that the scope of the nonconformity is fully understood.
3. The Control Owner must determine if similar nonconformities exist elsewhere in the organization or could potentially occur.

### 7.2 Root Cause Analysis (RCA)

1. The Control Owner, in collaboration with relevant subject matter experts, must conduct a Root Cause Analysis.
2. Acceptable RCA methodologies include, but are not limited to:
    - "5 Whys" (iterative interrogative technique).
    - Fishbone (Ishikawa) diagrams.
    - Fault Tree Analysis.
3. The RCA must identify the systemic failure (e.g., lack of training, process flaw, resource shortage, technology failure) rather than just the immediate symptom or human error.
4. The findings of the RCA must be documented in the Corrective Action Plan (CAP).

### 7.3 Determining and Implementing Corrective Action

1. Based on the RCA, the Control Owner must determine the corrective actions needed to eliminate the root cause and prevent recurrence.
2. The proposed actions must be proportionate to the effects and risks of the nonconformities encountered.
3. The Control Owner shall draft a Corrective Action Plan (CAP) detailing:
- The specific tasks to be executed.
- Resource requirements (budget, tools, personnel).
- Assigned task owners.
- Target completion dates.
1. The CISO must review and approve the CAP before implementation begins.
2. The task owners shall implement the corrective actions according to the approved timeline.

### 7.4 Reviewing the Effectiveness of Corrective Actions

1. Upon completion of the corrective action, the Control Owner must notify the ISMS Programme Manager.
2. The corrective action must operate for a sufficient period (e.g., 30 to 90 days) to generate objective evidence of its effectiveness.
3. Internal Audit or the ISMS Programme Manager shall conduct a formal verification review to confirm:
- The root cause has been eliminated.
- The nonconformity has not recurred.
- The action did not introduce new, unmitigated risks to the ISMS.
1. If the action is deemed effective, the CAP is formally closed. If ineffective, a new RCA must be conducted, and the cycle repeats.

### 7.5 Updating the ISMS and Risk Register

1. If the root cause analysis or the corrective action reveals previously unidentified risks or alters the risk landscape, the CISO shall ensure the ISMS Risk Register (DTB-NG-ISMS-RRG-017) is updated.
2. If the corrective action requires changes to ISMS policies, procedures, or the Statement of Applicability (SoA), the ISMS Programme Manager shall initiate those updates under the Document Control Procedure (DTB-NG-ISMS-DCP-020).

### 7.6 Assumptions Applied

1. DTB Nigeria allocates sufficient time and resources for process owners to conduct thorough Root Cause Analysis rather than rushing to apply superficial fixes.
2. Management supports structural or procedural changes if they are identified as necessary corrective actions.

## 8. ISMS Corrective Action Workflow Matrix (Baseline)

| **Phase** | **Action** | **Responsible Role** | **Target Timeline** |
| --- | --- | --- | --- |
| **Review** | Review NC and evaluate scope | Control Owner | Within 3 days of NC handover |
| **Analysis** | Conduct Root Cause Analysis (RCA) | Control Owner / Experts | Within 7 days of NC handover |
| **Planning** | Draft and approve Corrective Action Plan | Control Owner / CISO | Within 14 days of NC handover |
| **Execution** | Implement approved corrective actions | Task Owners | As defined in the approved CAP |
| **Verification** | Review effectiveness of the action taken | Internal Audit / ISMS-PM | 30-90 days post-implementation |
| **Closure** | Formally close the NC/CAP record | ISMS-PM | Upon successful verification |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Root Cause Analysis (RCA) Reports | Control Owners | Minimum 6 years |
| Corrective Action Plans (CAPs) | ISMS Programme Manager | Minimum 6 years |
| Verification / Effectiveness Review Reports | Internal Audit / ISMS-PM | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
3. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-RCP-021 – Record Control Procedure

## 11. ISO Clause References

- Clause 10.1 Continual improvement
- Clause 10.2 Nonconformity and corrective action

## 12. Annex A References

- N/A

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- If recurring nonconformities indicate that the Root Cause Analysis methodology currently in use is ineffective.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO | Added integration with Risk Register updates |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Continual Improvement Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Continual Improvement Procedure |
| Document ID | DTB-NG-ISMS-CIP-063 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the methodology for identifying, evaluating, implementing, and tracking opportunities to continually improve the suitability, adequacy, and effectiveness of the Information Security Management System (ISMS) at DTB Nigeria.

This procedure ensures DTB Nigeria proactively enhances its information security posture and maintains strict alignment with ISO/IEC 27001:2022 Clause 10.1.

## 3. Scope

This procedure applies to all continual improvement activities and initiatives related to the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers improvements derived from reactive sources (such as nonconformities and incidents) as well as proactive sources (such as threat intelligence, employee suggestions, and management reviews). Out-of-scope international entities are excluded from this specific procedure unless global initiatives are adopted locally by DTB Nigeria.

## 4. References

1. ISO/IEC 27001:2022 Clause 10.1 (Continual improvement)
2. DTB-NG-ISMS-POL-008 – Information Security Policy
3. DTB-NG-ISMS-MRP-058 – Management Review Procedure
4. DTB-NG-ISMS-MKF-060 – ISMS Metrics and KPI Framework
5. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
6. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Continual Improvement | A recurring activity to enhance performance, resulting in a more suitable, adequate, and effective ISMS. |
| Opportunity for Improvement (OFI) | A potential enhancement identified within the ISMS that is not a strict nonconformity but could increase security, efficiency, or compliance. |
| ISMC | Information Security Management Committee. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| Information Security Management Committee (ISMC) | Reviews high-impact continual improvement proposals, approves required resources, and sets the strategic direction for ISMS maturity. |
| CISO (Nigeria) | Evaluates and prioritizes OFIs, ensuring they align with the bank's risk appetite and strategic objectives. |
| ISMS Programme Manager | Maintains the Continual Improvement Register, tracks the implementation of approved initiatives, and measures their effectiveness. |
| Control / Process Owners | Identify OFIs within their operational domains and execute approved improvement initiatives. |
| All staff/users | Actively participate in the ISMS by submitting suggestions and feedback for security process enhancements. |

## 7. Procedure

### 7.1 Identifying Opportunities for Improvement

1. Opportunities for Improvement (OFIs) shall be systematically gathered from multiple sources to ensure a comprehensive approach to continual improvement.
2. Reactive sources include:
    - Root cause analysis from the Corrective Action Procedure (DTB-NG-ISMS-CAP-062).
    - Post-incident reviews and lessons learned.
    - Identified trends in security metrics failing to meet targets.
3. Proactive sources include:
- Outputs and decisions from the Management Review.
- Internal and external audit recommendations (formal OFIs).
- Evolving cyber threat intelligence and changes to the regulatory landscape (e.g., CBN directives).
- Employee feedback and suggestions for process efficiency.
- Technological advancements and the introduction of new security tools.

### 7.2 Logging and Evaluation

1. All identified OFIs must be submitted to the ISMS Programme Manager.
2. The ISMS Programme Manager shall record the proposed improvements in the central ISMS Continual Improvement Register.
3. The CISO and the ISMS Programme Manager shall conduct an initial evaluation of each logged OFI based on:
- Potential impact on risk reduction.
- Resource requirements (cost, time, personnel).
- Strategic alignment with ISMS objectives.

### 7.3 Prioritization and Approval

1. OFIs that require minimal resources and offer immediate "quick wins" may be approved directly by the CISO or the respective Control Owner.
2. Major improvement initiatives requiring significant capital expenditure, structural changes, or cross-departmental resources must be formalized into a proposal.
3. Major proposals shall be presented to the ISMC during Management Review meetings (or ad-hoc sessions) for prioritization and formal approval.
4. Approved initiatives shall be assigned to a specific task owner with a defined target completion date.

### 7.4 Implementation and Tracking

1. Task owners are responsible for integrating the approved continual improvement initiatives into their operational workflows.
2. The ISMS Programme Manager shall monitor the progress of all open initiatives within the Continual Improvement Register.
3. Status updates on major improvement projects shall be reported monthly to the CISO and summarized for the ISMC.

### 7.5 Measurement of Effectiveness

1. Following the implementation of an improvement initiative, its effectiveness must be measured.
2. The ISMS Programme Manager and the relevant Control Owner shall review the targeted metrics defined in the ISMS Metrics and KPI Framework (DTB-NG-ISMS-MKF-060) to confirm that the change produced the intended enhancement.
3. If the initiative did not yield the expected results, it shall be reassessed for further modification or closure.
4. Successful improvements that mandate changes to existing documentation shall be processed through the Document Control Procedure (DTB-NG-ISMS-DCP-020).

### 7.6 Assumptions Applied

1. DTB Nigeria fosters a culture that encourages employees at all levels to suggest security and process improvements without fear of reprisal.
2. Executive management commits necessary budgetary and personnel resources to realize approved improvement initiatives.

## 8. ISMS Continual Improvement Workflow Matrix (Baseline)

| **Phase** | **Action** | **Responsible Role** | **Target Timeline** |
| --- | --- | --- | --- |
| **Identification** | Submit OFI or suggestion | Any Staff / Auditor | Ongoing |
| **Logging** | Enter into Continual Improvement Register | ISMS-PM | Within 7 days of submission |
| **Evaluation** | Assess risk, cost, and benefit | CISO / ISMS-PM | Monthly review cycle |
| **Approval** | Approve resources and timeline | CISO / ISMC | Varies based on complexity |
| **Execution** | Implement the improvement | Assigned Task Owner | As per approved plan |
| **Verification** | Review effectiveness post-implementation | ISMS-PM / CISO | 30-90 days post-completion |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| ISMS Continual Improvement Register | ISMS Programme Manager | Minimum 6 years |
| Improvement Project Proposals & Business Cases | CISO Office | Minimum 6 years |
| Post-Implementation Effectiveness Reviews | ISMS Programme Manager | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-MRP-058 – Management Review Procedure
3. DTB-NG-ISMS-MKF-060 – ISMS Metrics and KPI Framework
4. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
5. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure

## 11. ISO Clause References

- Clause 10.1 Continual improvement
- Clause 9.3 Management review (Outputs)

## 12. Annex A References

- N/A

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- If the organization fails to demonstrate maturity growth or continual improvement during external surveillance audits.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO | Refined the approval thresholds for major vs. minor OFIs |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Certification Readiness Checklist

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Certification Readiness Checklist |
| Document ID | DTB-NG-ISMS-CRC-064 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to provide a comprehensive checklist to verify Digho Trust Bank (DTB) Nigeria's readiness for the initial ISO/IEC 27001:2022 Stage 1 (Documentation) and Stage 2 (Implementation) external certification audits.

This checklist ensures that all mandatory management system requirements, documentation, operational records, and Annex A controls are fully implemented, functional, and supported by objective evidence prior to engaging the external Certification Body (CB).

## 3. Scope

This checklist applies to the entire Information Security Management System (ISMS) scope of DTB Nigeria:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers all mandatory clauses (4.0 to 10.0) of the ISO/IEC 27001:2022 standard and the associated Annex A controls selected within the Statement of Applicability (SoA). Out-of-scope international entities are excluded from this checklist.

## 4. References

1. ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection — ISMS Requirements
2. ISO/IEC 27002:2022 Information security controls
3. DTB-NG-ISMS-SOA-019 – Statement of Applicability
4. All approved DTB Nigeria ISMS Policies, Procedures, and Records (Documents 001 through 063)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Stage 1 Audit | The external auditor's review of the ISMS documentation to ensure the system design meets the ISO 27001 standard. |
| Stage 2 Audit | The external auditor's on-site evaluation of the implementation and effectiveness of the ISMS against the documentation and the standard. |
| Objective Evidence | Documented proof (records, logs, approved policies, meeting minutes) demonstrating that an ISMS requirement is fulfilled. |
| Certification Body (CB) | The accredited independent organization performing the external audit. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Reviews the completed checklist, ensures resources are allocated to close any identified gaps, and signs off on the final certification readiness. |
| ISMS Programme Manager | Responsible for actively completing this checklist, gathering evidence links, coordinating with Control Owners, and tracking gap remediation. |
| Control / Process Owners | Provide the required objective evidence, records, and demonstrations of control effectiveness for their respective domains. |
| Internal Audit | Reviews the checklist as part of the final pre-certification readiness assessment. |

## 7. Instructions for Use

1. The ISMS Programme Manager shall conduct a readiness review using this checklist approximately 4 to 6 weeks prior to the scheduled Stage 1 external audit.
2. For each requirement, the ISMS Programme Manager must verify the status and select:
    - **Yes (Y):** Requirement is fully met, and objective evidence is available and verified.
    - **Partial (P):** Requirement is partially met (e.g., policy approved but not fully rolled out, or records are incomplete).
    - **No (N):** Requirement is not met.
3. In the "Evidence Reference / Link" column, provide the exact Document ID or repository location of the evidence.
4. Any item marked "Partial" or "No" must immediately be logged as a Nonconformity (DTB-NG-ISMS-NCP-061) and undergo Corrective Action before the external audit.
5. The completed checklist must be signed by the CISO and MD/CEO to officially declare DTB Nigeria ready for the external certification audit.

## 8. Certification Readiness Checklist Matrix

### 8.1 Context of the Organization (Clause 4)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 4.1 | 4.1 | Are internal and external issues relevant to the ISMS identified and documented? |  |  |  |
| 4.2 | 4.2 | Are the interested parties and their relevant requirements identified? |  |  |  |
| 4.3 | 4.3 | Is the scope of the ISMS clearly defined, documented, and justified (including exclusions)? |  |  |  |
| 4.4 | 4.4 | Is the ISMS established, implemented, maintained, and continually improved? |  |  |  |

### 8.2 Leadership (Clause 5)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 5.1 | 5.1 | Can top management demonstrate leadership and commitment to the ISMS? |  |  |  |
| 5.2 | 5.2 | Is the Information Security Policy established, approved by top management, and communicated? |  |  |  |
| 5.3 | 5.3 | Are organizational roles, responsibilities, and authorities (RACI) assigned and communicated? |  |  |  |

### 8.3 Planning (Clause 6)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 6.1 | 6.1.1 | Have risks and opportunities related to the ISMS context been determined? |  |  |  |
| 6.2 | 6.1.2 | Is the Information Security Risk Assessment methodology defined and approved? |  |  |  |
| 6.3 | 6.1.2 | Has a comprehensive risk assessment been conducted and a Risk Register produced? |  |  |  |
| 6.4 | 6.1.3 | Is there a Risk Treatment Plan formulated and approved by risk owners? |  |  |  |
| 6.5 | 6.1.3 | Has a Statement of Applicability (SoA) been produced, justifying inclusions and exclusions? |  |  |  |
| 6.6 | 6.2 | Are measurable Information Security Objectives established at relevant functions and levels? |  |  |  |

### 8.4 Support (Clause 7)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 7.1 | 7.1 | Are sufficient resources determined and provided for the ISMS? |  |  |  |
| 7.2 | 7.2 | Is the necessary competence of persons doing ISMS-related work determined and evidenced? |  |  |  |
| 7.3 | 7.3 | Have all relevant personnel undergone Information Security Awareness training? |  |  |  |
| 7.4 | 7.4 | Are internal and external communication procedures defined and active? |  |  |  |
| 7.5 | 7.5.1 | Are all mandatory documents required by ISO 27001 created and approved? |  |  |  |
| 7.6 | 7.5.3 | Are documents and records controlled securely (versioning, access, retention)? |  |  |  |

### 8.5 Operation (Clause 8)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 8.1 | 8.1 | Are operational processes planned, implemented, and controlled to meet requirements? |  |  |  |
| 8.2 | 8.2 | Are information security risk assessments performed at planned intervals (or upon major changes)? |  |  |  |
| 8.3 | 8.3 | Is the Risk Treatment Plan actively implemented with verifiable progress? |  |  |  |

### 8.6 Performance Evaluation (Clause 9)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 9.1 | 9.1 | Are ISMS metrics and KPIs defined, monitored, measured, and analyzed? |  |  |  |
| 9.2 | 9.2 | Has a full cycle Internal Audit been planned, conducted, and reported? |  |  |  |
| 9.3 | 9.3 | Has Top Management conducted at least one formal Management Review of the ISMS? |  |  |  |
| 9.4 | 9.3 | Are Management Review minutes documented with clear output actions? |  |  |  |

### 8.7 Improvement (Clause 10)

| **Req. #** | **ISO Clause** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| 10.1 | 10.1 | Is there a process for logging and acting upon opportunities for continual improvement? |  |  |  |
| 10.2 | 10.2 | Are nonconformities (from audits, incidents) formally logged and investigated? |  |  |  |
| 10.3 | 10.2 | Are corrective actions implemented, with root cause analysis and effectiveness verification recorded? |  |  |  |

### 8.8 Annex A Controls (Implementation Evidence Verification)

*Ensure all policies mapped in the SoA are operational and generating auditable records.*

| **Req. #** | **Annex A Area** | **Requirement Description** | **Status (Y/P/N)** | **Evidence Reference / Link** | **Gap / Action Required** |
| --- | --- | --- | --- | --- | --- |
| A.1 | Org Controls | Policies, Threat Intel, Asset Inventory, Access Control, Cloud, Supplier Security operational? |  |  |  |
| A.2 | People Controls | Screening, Terms of Employment, Awareness, Disciplinary, Termination procedures active? |  |  |  |
| A.3 | Physical Controls | Perimeters, Entry Controls, Clear Desk/Screen, Equipment Siting/Maintenance verified? |  |  |  |
| A.4 | Tech Controls | Endpoint Security, Cryptography, Logging, Network Security, Secure Dev, BCDR functional? |  |  |  |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Completed Certification Readiness Checklist | ISMS Programme Manager | Minimum 6 years |
| Pre-Audit Corrective Action Plans (if gaps identified) | ISMS Programme Manager | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-SOA-019 – Statement of Applicability
2. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
3. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
4. All foundational ISMS Phase 1 through Phase 7 documentation.

## 11. ISO Clause References

- Clauses 4.0 through 10.0 (Comprehensive Readiness)
- Annex A Controls (Comprehensive Readiness)

## 12. Annex A References

- All applicable Annex A controls as defined in the Statement of Applicability.

## 13. Review Frequency

This checklist shall be reviewed and utilized:

- Prior to the Initial Certification Audits (Stage 1 and Stage 2).
- Prior to Annual Surveillance Audits.
- Prior to the Triennial Recertification Audit.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft of readiness checklist |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section (Readiness Sign-Off)

*Signing this document indicates that DTB Nigeria has successfully completed the readiness assessment and is formally prepared to engage the external Certification Body.*

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |