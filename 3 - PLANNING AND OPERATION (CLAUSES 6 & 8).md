# 3 - PLANNING AND OPERATION (CLAUSES 6 & 8)

# Risk Assessment Methodology

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Risk Assessment Methodology |
| Document ID | DTB-NG-ISMS-RAM-012 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to define a consistent, repeatable, and auditable methodology for identifying, analyzing, evaluating, and documenting information security risks affecting DTB Nigeria’s in-scope operations, in accordance with ISO/IEC 27001:2022 Clause 6.1.2.

This methodology ensures that risk treatment decisions are evidence-based, aligned with regulatory obligations, and appropriate for DTB Nigeria’s banking and cybersecurity risk environment.

## 3. Scope

This methodology applies to all information security risk assessments within DTB Nigeria ISMS certification scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

The methodology covers risks related to:

- Information assets and data categories
- Business processes and services
- People and organizational factors
- Technology platforms and infrastructure
- Third-party/supplier dependencies
- Physical and environmental factors
- Regulatory and legal obligations

Out-of-scope entities (London, Frankfurt, Paris, New York) are excluded from internal risk assessment population, except where interface dependencies create risks to DTB Nigeria operations.

## 4. References

1. ISO/IEC 27001:2022 Clause 6.1.2 (Information security risk assessment)
2. ISO/IEC 27001:2022 Clause 6.1.3 (Information security risk treatment)
3. ISO/IEC 27002:2022
4. DTB-NG-ISMS-INF-008 – Information Security Policy
5. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
6. DTB-NG-ISMS-SCP-004 – ISMS Scope
7. DTB-NG-ISMS-IPR-003 – Interested Parties Register
8. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria (next document)
9. DTB Enterprise Risk Management Framework
10. CBN cybersecurity and risk management expectations
11. NDPA/NDPC obligations relevant to security and data protection risk

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Information Security Risk | Effect of uncertainty on information security objectives, typically expressed as combination of likelihood and impact |
| Risk Scenario | Structured statement describing threat exploiting vulnerability affecting an asset and causing business impact |
| Likelihood | Probability/frequency of risk scenario occurrence |
| Impact | Severity of consequence if risk scenario materializes |
| Inherent Risk | Risk level before considering existing controls |
| Residual Risk | Risk level after considering existing controls and current operating effectiveness |
| Risk Owner | Role accountable for managing and accepting treatment outcome of assigned risk |
| Control Effectiveness | Degree to which existing controls reduce likelihood and/or impact |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns methodology and ensures enterprise-wide ISMS application |
| Enterprise Risk Manager (ERM) | Co-owns risk model calibration, quality assurance, and risk aggregation |
| ISMS Programme Manager | Coordinates assessment cycles, workshop scheduling, and documentation quality |
| Asset/Process Owners | Identify assets, threats, vulnerabilities, impacts, and existing controls |
| ITOPS / SOC / Digital Banking Heads | Provide technical threat, vulnerability, and control evidence inputs |
| Compliance/Legal | Validates legal/regulatory impact dimensions and obligations |
| Data Protection Officer (DPO) | Validates privacy and personal data impact dimensions |
| Procurement/Vendor Management Lead | Provides third-party risk inputs and supplier dependency exposure |
| Branch Operations Managers | Provide branch-specific risk context and control evidence |
| Internal Audit | Independently assesses methodology adherence and risk record reliability |
| CEO (Nigeria) | Approves risk framework and accepts escalated risks per authority limits |

## 7. Policy and Procedure (Risk Assessment Method)

### 7.1 Methodology Principles

DTB Nigeria’s risk assessment method is based on the following principles:

1. **Business-context driven:** Risk assessment reflects banking service criticality and customer trust impact.
2. **Threat-informed:** Uses current threat intelligence, sector trends, and incident lessons learned.
3. **Asset-centric:** Risks are anchored to critical information assets and processes.
4. **Control-aware:** Distinguishes between inherent and residual risk.
5. **Evidence-based:** Ratings require documented assumptions and rationale.
6. **Repeatable and consistent:** Standard scales and criteria are applied across all assessments.
7. **Regulatory-aligned:** Explicitly incorporates CBN, NDPA/NDPC, and legal obligations.
8. **Auditable:** All risk records are version-controlled and traceable to decision owners.

### 7.2 Assessment Frequency and Triggers

#### 7.2.1 Planned Assessment Frequency

| **Assessment Type** | **Frequency** | **Purpose** |
| --- | --- | --- |
| Enterprise ISMS baseline assessment | Annually | Comprehensive refresh of risk universe across all in-scope areas |
| Targeted domain assessments (e.g., IAM, cloud, digital channels, SWIFT interface) | Quarterly (risk-based) | Deep-dive reassessment of high-risk domains |
| Branch-focused control/risk reviews | At least annually per branch | Validate local risk conditions and control effectiveness |
| Supplier-related risk reassessment (critical suppliers) | At least annually or on major change | Revalidate third-party risk posture |

#### 7.2.2 Event-Driven Reassessment Triggers

Risk reassessment must be initiated when any of the following occur:

1. Major security incident or near-miss.
2. Significant change to technology architecture (e.g., platform migration, new critical cloud service).
3. New regulatory/legal requirement affecting security obligations.
4. Material business process change (e.g., new product/channel).
5. Major supplier onboarding, failure, or termination affecting critical services.
6. Significant control failure identified by audit or monitoring.
7. Significant threat intelligence alerts relevant to DTB environment.

### 7.3 Risk Assessment Lifecycle

DTB Nigeria applies a seven-step lifecycle:

1. **Establish Context**
2. **Identify Risks**
3. **Analyze Risks (Inherent)**
4. **Evaluate Existing Controls and Residual Risk**
5. **Evaluate and Prioritize Risks**
6. **Document and Approve Risk Records**
7. **Monitor and Reassess**

### 7.4 Step 1: Establish Context

For each assessment scope, define:

- Business process/service under review
- Asset and data classification context
- Applicable legal/regulatory obligations
- Stakeholders and dependency map
- Risk assumptions and constraints
- Risk criteria reference (from DTB-NG-ISMS-RAC-013)

Context must be documented before scoring begins.

### 7.5 Step 2: Risk Identification

Risk identification shall use multiple input sources:

1. Asset inventory and classification records
2. Threat intelligence (internal SOC and external banking/sector sources)
3. Vulnerability assessments and penetration test results
4. Incident and near-miss records
5. Audit findings and nonconformity records
6. Regulatory findings and compliance reviews
7. Change management records
8. Supplier assurance and SLA performance results
9. Branch operational observations and walkthroughs

Each identified risk shall be documented as a structured scenario:

**Risk Scenario Format:**

Threat actor/event exploits vulnerability in [asset/process] causing [CIA impact] leading to [business/regulatory/financial/reputational consequence].

### 7.6 Step 3: Risk Analysis (Inherent Risk)

#### 7.6.1 Likelihood Scale (5-Point)

| **Score** | **Likelihood Level** | **Criteria (Guidance)** |
| --- | --- | --- |
| 1 | Rare | Highly unlikely; no known comparable event and strong deterrents |
| 2 | Unlikely | Possible but not expected under current conditions |
| 3 | Possible | Could occur under plausible threat/control conditions |
| 4 | Likely | Expected to occur in many plausible scenarios |
| 5 | Almost Certain | Frequent/highly probable based on current exposure and intelligence |

#### 7.6.2 Impact Scale (5-Point)

Impact is assessed as the highest relevant impact across dimensions below:

- Financial loss
- Regulatory/legal exposure
- Customer impact/service disruption
- Reputational impact
- Operational disruption
- Data confidentiality/integrity/availability impact

| **Score** | **Impact Level** | **Criteria (Guidance)** |
| --- | --- | --- |
| 1 | Insignificant | Negligible operational effect; no regulatory/customer impact |
| 2 | Minor | Limited localized impact; manageable within routine operations |
| 3 | Moderate | Noticeable business impact; management attention required |
| 4 | Major | Significant service/regulatory/customer impact; executive oversight required |
| 5 | Severe | Critical business disruption, major regulatory exposure, or severe trust impact |

#### 7.6.3 Inherent Risk Calculation

**Formula:**

Inherent Risk Score = Likelihood x Impact (range: 1–25)

### 7.7 Step 4: Control Evaluation and Residual Risk

Existing controls are evaluated for design and operating effectiveness.

#### 7.7.1 Control Effectiveness Rating

| **Rating** | **Description** |
| --- | --- |
| Effective | Control is designed appropriately and operating consistently with evidence |
| Partially Effective | Control exists but has design or operating gaps |
| Ineffective | Control absent, inadequate, or not operating reliably |

Residual likelihood/impact are then reassessed considering existing controls.

**Formula:**

Residual Risk Score = Residual Likelihood x Residual Impact

Residual scoring rationale must reference evidence (e.g., logs, reports, test results, audit outcomes).

### 7.8 Step 5: Risk Evaluation and Prioritization

Residual risks are mapped to severity bands for decision-making priority.

#### 7.8.1 Residual Risk Banding

| **Score Range** | **Rating** | **Priority** |
| --- | --- | --- |
| 1–4 | Low | Monitor through routine controls |
| 5–9 | Medium | Treat within normal planning cycle |
| 10–16 | High | Prioritized treatment with management oversight |
| 17–25 | Critical | Immediate treatment/escalation; executive attention required |

Detailed acceptance thresholds and authority limits are defined in **DTB-NG-ISMS-RAC-013**.

### 7.9 Step 6: Risk Treatment Linkage

Each risk shall be assigned one treatment decision:

1. **Mitigate** (implement/enhance controls)
2. **Avoid** (discontinue risky activity)
3. **Transfer** (contractual/insurance mechanisms)
4. **Accept** (formally approved residual risk per criteria)

Treatment actions must include:

- Action description
- Control mapping (including Annex A references where applicable)
- Owner
- Target completion date
- Required resources
- Status tracking method

Treatment actions are recorded in Risk Treatment Plan and linked to SoA where relevant.

### 7.10 Step 7: Monitoring, Review, and Reassessment

1. Risk owners must review assigned risks at least quarterly.
2. High/Critical residual risks are reviewed monthly by ISMS Steering Committee.
3. Risk status updates shall include:
    - treatment progress,
    - control effectiveness changes,
    - incident linkage,
    - revised scoring if context changed.
4. Closed risks require documented closure rationale and evidence.
5. Reopened risks must retain original history for traceability.

### 7.11 Risk Assessment Data Model (Mandatory Fields)

Each risk record shall include at minimum:

1. Risk ID
2. Assessment date
3. Assessment scope/domain
4. Asset/process owner
5. Risk scenario statement
6. Threat source/category
7. Vulnerability description
8. Existing controls
9. Inherent likelihood/impact/score
10. Residual likelihood/impact/score
11. Risk rating band (Low/Medium/High/Critical)
12. Regulatory/legal linkage (if applicable)
13. Risk owner
14. Treatment decision and action plan
15. Target date and status
16. Approval/acceptance record
17. Review date and review outcome

### 7.12 Quality Assurance and Challenge Process

To ensure consistency and reliability:

1. ERM and CISO office perform calibration sessions for scoring consistency.
2. High/Critical risks require challenge review by cross-functional panel (CISO, ERM, ITOPS/SOC, COMP/DPO as relevant).
3. Sampling quality checks are performed by ISMS Programme Manager on documented rationale/evidence.
4. Internal Audit independently verifies adherence to methodology and evidence sufficiency.

### 7.13 Integration with ISMS Processes

Risk assessment outputs directly feed:

- Risk Acceptance Criteria application
- Risk Register updates
- Risk Treatment Plan development
- Statement of Applicability control selection
- Information Security Objectives prioritization
- Internal audit planning
- Management review inputs
- Continual improvement actions

### 7.14 Methodology Review and Change Control

This methodology shall be reviewed:

- At least annually, and
- Following significant changes in threat landscape, regulatory requirements, or identified methodology weaknesses.

Any methodology change requires:

1. Impact analysis,
2. CISO and ERM review,
3. CEO approval (for major model/threshold changes),
4. Controlled update communication to risk and control owners.

### 7.15 Assumptions Applied

1. DTB Nigeria maintains an up-to-date asset inventory and classification baseline for meaningful risk analysis.
2. Security telemetry and incident records are sufficiently reliable for evidence-based scoring.
3. Business and technical owners participate in workshops and provide timely input.
4. Risk scoring uses professional judgement within defined criteria; where uncertainty exists, conservative (higher risk) rating is preferred.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Risk Assessment Methodology | CISO Office | Minimum 6 years |
| Risk Assessment Workshop Records | ISMS-PM / ERM | Minimum 6 years |
| Risk Scoring Calibration Records | ERM / CISO Office | Minimum 6 years |
| Risk Register Entries and Updates | ERM / Risk Owners | Minimum 6 years |
| High/Critical Risk Challenge Review Records | CISO Office | Minimum 6 years |
| Methodology Review and Change Records | ISMS-PM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
2. DTB-NG-ISMS-AIN-014 – Asset Inventory
3. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
6. DTB-NG-ISMS-SOA-019 – Statement of Applicability
7. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
8. DTB-NG-ISMS-MRV-058 – Management Review Procedure

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 6.1.3 Information security risk treatment
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.3 Management review
- Clause 10.1 Continual improvement

## 11. Annex A References

- 5.7 Threat intelligence
- 5.8 Information security in project management
- 5.9 Inventory of information and other associated assets
- 5.12 Classification of information
- 5.19 Information security in supplier relationships
- 5.24 Information security incident management planning and preparation
- 5.27 Learning from information security incidents
- 5.30 ICT readiness for business continuity
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.36 Compliance with policies and standards for information security
- 8.8 Management of technical vulnerabilities
- 8.15 Logging
- 8.16 Monitoring activities

## 12. Review Frequency

This methodology shall be reviewed:

- At least annually, and
- When significant changes occur in threat landscape, business model, technology architecture, legal/regulatory requirements, or risk governance expectations.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ERM / ISMS Programme Manager | Initial methodology draft |
| 0.9 | 30 June 2026 | CISO / ERM / COMP / DPO | Refined scoring model and governance controls |
| 1.0 | 01 July 2026 | CISO (Nigeria) | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Risk Acceptance Criteria

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Risk Acceptance Criteria |
| Document ID | DTB-NG-ISMS-RAC-013 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to define formal, auditable criteria for evaluating and accepting information security risk within DTB Nigeria’s ISMS, in accordance with ISO/IEC 27001:2022 Clause 6.1.2 and Clause 6.1.3.

These criteria establish decision thresholds, authority limits, escalation requirements, and documentation rules to ensure that risk acceptance is consistent, justified, and aligned with DTB Nigeria’s regulatory obligations and risk posture.

## 3. Scope

This document applies to all residual information security risks identified in DTB Nigeria’s ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It applies to risks arising from:

- Business processes and operations
- Information assets and data handling
- Technology platforms and infrastructure
- Third-party and supplier dependencies
- Physical and environmental exposures
- Legal, regulatory, and contractual obligations

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded except where interface risks materially affect DTB Nigeria operations.

## 4. References

1. ISO/IEC 27001:2022 Clause 6.1.2 (Information security risk assessment)
2. ISO/IEC 27001:2022 Clause 6.1.3 (Information security risk treatment)
3. ISO/IEC 27002:2022
4. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
5. DTB-NG-ISMS-INF-008 – Information Security Policy
6. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
7. DTB-NG-ISMS-RRG-017 – Risk Register (to be issued)
8. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan (to be issued)
9. DTB Enterprise Risk Management Framework
10. CBN cybersecurity and risk governance obligations
11. NDPA/NDPC obligations relevant to risk handling and data protection

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Risk Acceptance | Informed decision to retain residual risk without additional immediate treatment beyond existing controls and planned safeguards |
| Residual Risk | Remaining risk after considering current control design and operating effectiveness |
| Risk Appetite | Level and type of risk DTB Nigeria is willing to retain in pursuit of business objectives |
| Risk Tolerance | Acceptable variation around risk appetite thresholds for operational management |
| Acceptance Authority | Role with delegated approval power to accept residual risk within defined limits |
| Temporary Acceptance | Time-bound risk acceptance pending completion of planned treatment actions |
| Exception | Approved deviation from policy/control requirement with compensating controls and expiry date |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns risk acceptance framework and ensures consistent application |
| Enterprise Risk Manager (ERM) | Validates risk scoring quality and acceptance recommendation logic |
| Risk Owners | Propose acceptance requests with justification and supporting evidence |
| Control Owners | Provide control status, effectiveness evidence, and compensating control details |
| Compliance/Legal | Reviews regulatory/legal implications of proposed acceptance decisions |
| Data Protection Officer (DPO) | Reviews privacy-related acceptance requests impacting personal data |
| ISMS Steering Committee | Reviews and endorses high-impact acceptance decisions before executive approval where required |
| Managing Director/CEO (Nigeria) | Final approval authority for high-risk acceptance and escalated cases |
| Board Risk & Compliance Committee (Oversight) | Receives oversight reporting on material accepted risk profile |
| Internal Audit | Provides independent assurance on adherence to acceptance criteria and governance controls |

## 7. Policy and Procedure (Risk Acceptance Rules)

### 7.1 Risk Acceptance Principles

DTB Nigeria shall apply the following principles to all risk acceptance decisions:

1. **No implicit acceptance:** Risk is not deemed accepted unless formally documented and approved.
2. **Residual-risk basis:** Acceptance decisions must be based on residual risk, not inherent risk.
3. **Evidence-backed rationale:** Acceptance requires objective justification and control evidence.
4. **Time-bound validity:** Acceptance is valid only for defined review periods and may expire.
5. **Regulatory precedence:** Legal and regulatory obligations override business convenience.
6. **Least exposure:** Acceptance is used only when further treatment is not currently feasible, not cost-effective relative to risk reduction, or pending planned remediation with controls in place.
7. **Accountability:** Each accepted risk has a named risk owner and review date.
8. **Escalation discipline:** Higher risk and compliance-sensitive risks require higher approval authority.

### 7.2 Risk Rating Bands (Residual Risk Basis)

Residual risk scores from DTB-NG-ISMS-RAM-012 are interpreted as follows:

| **Residual Score** | **Rating** | **Interpretation** |
| --- | --- | --- |
| 1–4 | Low | Controlled exposure; generally acceptable with routine monitoring |
| 5–9 | Medium | Manageable exposure; acceptance permitted with documented rationale and tracking |
| 10–16 | High | Significant exposure; acceptance restricted and requires senior governance approval |
| 17–25 | Critical | Severe exposure; acceptance generally prohibited except under exceptional, temporary, executive-approved conditions with immediate treatment plan |

### 7.3 Acceptance Decision Matrix

| **Residual Rating** | **Default Position** | **Acceptance Conditions** | **Minimum Approver** |
| --- | --- | --- | --- |
| Low | Acceptable by default | Risk record completed; owner assigned; monitoring defined | Risk Owner + CISO delegate control |
| Medium | Conditionally acceptable | Business justification, control evidence, review date, no regulatory breach | CISO |
| High | Not normally acceptable without treatment | Must include formal treatment roadmap, compensating controls, and Steering Committee review | CISO + CEO |
| Critical | Generally not acceptable | Only temporary emergency acceptance with documented operational necessity, immediate remediation plan, and heightened monitoring | CEO (mandatory) with BRCC oversight notification |

### 7.4 Mandatory Acceptance Constraints (Non-Negotiable Rules)

Risk **shall not be accepted** if any of the following applies unless explicitly approved under exceptional governance route (Section 7.7):

1. Acceptance would directly violate applicable law/regulation (CBN, NDPA/NDPC, Cybercrimes Act).
2. Control failure materially threatens confidentiality/integrity/availability of critical banking services without compensating controls.
3. Risk could cause unmitigated systemic customer harm with no approved contingency.
4. Risk acceptance bypasses required authority levels.
5. Required risk data/evidence is incomplete or unverifiable.

### 7.5 Risk Acceptance Authority Limits

| **Decision Type** | **Authority** |
| --- | --- |
| Low residual risk acceptance | Assigned Risk Owner (within delegated function) with CISO-office oversight |
| Medium residual risk acceptance | CISO |
| High residual risk acceptance | CISO recommendation + CEO approval |
| Critical residual risk temporary acceptance | CEO approval only, after Steering Committee review; BRCC oversight notification mandatory |
| Privacy-impacting risk acceptance (any rating Medium+) | DPO consultation mandatory before final approval |
| Regulatory/legal impacting risk acceptance (any rating Medium+) | Compliance/Legal consultation mandatory before final approval |

No delegated authority may override mandatory regulatory obligations.

### 7.6 Risk Acceptance Request Minimum Content

Each acceptance request shall include:

1. Risk ID and scenario description
2. Residual risk score and rating
3. Affected assets/processes/services
4. Existing controls and effectiveness assessment
5. Business justification for acceptance
6. Alternative treatment options considered and reasons not selected
7. Compensating controls (if any)
8. Validity period and next review date
9. Monitoring plan and KRI/KPI triggers
10. Risk owner and accountable approver(s)
11. Compliance/Legal and DPO comments (where applicable)
12. Linked treatment actions (if temporary acceptance)

Incomplete submissions shall be rejected.

### 7.7 Temporary and Exceptional Acceptance

#### 7.7.1 Temporary Acceptance

Temporary acceptance is permitted where:

- Treatment is planned and funded but not yet fully implemented,
- Compensating controls reduce immediate exposure,
- Clear expiry date is defined,
- Progress is tracked through governance forums.

**Maximum initial temporary acceptance period:** 90 calendar days (unless CEO authorizes extended period with documented rationale).

#### 7.7.2 Exceptional Acceptance (Critical Risks)

Critical risk acceptance is exceptional and requires:

1. Documented operational necessity (e.g., preventing severe immediate business disruption),
2. Immediate action plan with milestones,
3. Daily/weekly enhanced monitoring depending on risk nature,
4. CEO approval,
5. BRCC oversight notification,
6. Mandatory reassessment at least every 30 days until risk downgraded.

### 7.8 Review and Revalidation of Accepted Risks

| **Residual Rating** | **Mandatory Review Frequency** |
| --- | --- |
| Low | At least annually |
| Medium | Quarterly |
| High | Monthly |
| Critical (temporary only) | At least monthly (or more frequent per decision condition) |

Accepted risks must be revalidated upon:

- Major incident related to the risk,
- Significant control change/failure,
- Regulatory requirement change,
- Material business or technology change.

Expired acceptance automatically triggers escalation and treatment action unless renewed through formal approval.

### 7.9 Risk Escalation Triggers

Immediate escalation is required when:

1. Residual risk increases to a higher rating band.
2. Treatment milestones for temporary acceptance are missed.
3. Compensating controls fail or are withdrawn.
4. Related incident indicates higher-than-assessed impact/likelihood.
5. Regulatory inquiries or audit findings challenge acceptance validity.

Escalations shall be recorded and tracked to closure through ISMS governance forums.

### 7.10 Integration with Risk Treatment and SoA

1. Accepted risks shall be linked to:
    - Risk Register entries,
    - Risk Treatment Plan status,
    - Relevant SoA control decisions (where applicable).
2. Acceptance does not remove obligation to improve controls where feasible.
3. Repeated acceptance of similar risk patterns shall trigger root cause analysis and control strategy review.

### 7.11 Reporting Requirements

The CISO office shall provide periodic accepted-risk reporting including:

- Count and trend by risk rating
- Top accepted High/Critical risks
- Overdue temporary acceptances
- Regulatory/privacy-sensitive accepted risks
- Concentration by domain (e.g., IAM, endpoint, supplier)
- Action status and downgrade trajectory

Reporting cadence:

- Monthly: ISMS Steering Committee
- Quarterly: Executive and BRCC oversight summary
- Annual: Management review inputs

### 7.12 Auditability and Record Integrity

- All acceptance decisions must be traceable and retained as controlled records.
- Acceptance evidence shall include digital approvals, supporting artifacts, and review outcomes.
- Post-dated approvals or undocumented verbal acceptance are prohibited.

### 7.13 Assumptions Applied

1. Residual risk scores are generated using approved DTB-NG-ISMS-RAM-012 methodology.
2. Risk owners and approvers have delegated authority consistent with governance documents.
3. Governance forums meet as scheduled to review high/critical acceptance cases and expiring approvals.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Risk Acceptance Criteria Document | CISO Office | Minimum 6 years |
| Risk Acceptance Requests and Decision Forms | ERM / CISO Office | Minimum 6 years |
| Temporary/Exceptional Acceptance Logs | CISO Office | Minimum 6 years |
| Risk Acceptance Review and Renewal Records | Risk Owners / ERM | Minimum 6 years |
| Governance Minutes with Acceptance Decisions | ISMS Secretariat | Minimum 6 years |
| Escalation and Breach-of-criteria Records | CISO Office | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
2. DTB-NG-ISMS-RRG-017 – Risk Register
3. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
4. DTB-NG-ISMS-SOA-019 – Statement of Applicability
5. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
6. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
7. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
8. DTB-NG-ISMS-MRV-058 – Management Review Procedure
9. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
10. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 6.1.3 Information security risk treatment
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.3 Management review
- Clause 10.2 Nonconformity and corrective action

## 11. Annex A References

- 5.1 Policies for information security
- 5.2 Information security roles and responsibilities
- 5.7 Threat intelligence
- 5.8 Information security in project management
- 5.24 Information security incident management planning and preparation
- 5.25 Assessment and decision on information security events
- 5.27 Learning from information security incidents
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.34 Privacy and protection of PII
- 5.36 Compliance with policies and standards for information security
- 5.37 Documented operating procedures
- 8.8 Management of technical vulnerabilities
- 8.16 Monitoring activities

## 12. Review Frequency

This document shall be reviewed:

- At least annually, and
- Immediately when risk appetite direction, regulatory obligations, or governance authority structures materially change.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ERM / ISMS Programme Manager | Initial acceptance criteria draft |
| 0.9 | 30 June 2026 | CISO / ERM / COMP / DPO | Updated authority thresholds and exceptional acceptance controls |
| 1.0 | 01 July 2026 | CISO (Nigeria) | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Asset Inventory

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Asset Inventory |
| Document ID | DTB-NG-ISMS-AIN-014 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 October 2026 (Quarterly Review Cycle) |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to establish and maintain a structured inventory of information and associated assets within DTB Nigeria’s ISMS scope, including asset ownership, classification, business criticality, location, and control requirements, in alignment with ISO/IEC 27001:2022 and ISO/IEC 27002:2022.

This inventory supports risk assessment, control selection, operational management, incident response, business continuity, and audit evidence requirements.

## 3. Scope

This Asset Inventory applies to all in-scope DTB Nigeria operations:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Asset categories included:

- Information assets and records
- Business process assets
- Applications and software platforms
- Infrastructure and network assets
- Endpoint assets
- Cloud service assets
- Security monitoring and protection assets
- Third-party service dependencies
- Physical and facility-related assets relevant to information processing

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from inventory population except where interface assets impact DTB Nigeria risk and control decisions.

## 4. References

1. ISO/IEC 27001:2022
2. ISO/IEC 27002:2022 (Control themes on asset inventory, ownership, acceptable use, handling, disposal)
3. DTB-NG-ISMS-INF-008 – Information Security Policy
4. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
5. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
6. DTB-NG-ISMS-ICS-015 – Information Classification Scheme (next document)
7. DTB-NG-ISMS-ACP-016 – Asset Classification Policy (to be issued)
8. DTB-NG-ISMS-RRG-017 – Risk Register (to be issued)
9. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan (to be issued)
10. DTB Enterprise Architecture and CMDB/IT asset records (Nigeria scope)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Asset | Anything that has value to DTB Nigeria and supports information processing or service delivery |
| Information Asset | Data or records (electronic/physical) with business, legal, or operational value |
| Asset Owner | Role accountable for proper classification, protection, and lifecycle oversight of an asset |
| Custodian | Role/function responsible for day-to-day management of an asset on behalf of owner |
| Criticality | Importance of an asset to service continuity and business objectives |
| CIA Rating | Confidentiality, Integrity, Availability impact rating for an asset |
| Lifecycle Status | Current asset state (Active, In Transition, Retired, Archived) |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns asset inventory governance requirements and control assurance |
| ISMS Programme Manager | Maintains master inventory register format, review workflow, and evidence |
| Asset Owners | Ensure completeness, classification, criticality rating, and review of assigned assets |
| ITOPS Head | Ensures infrastructure, endpoint, server, and network asset records are maintained |
| SOC Head | Ensures monitoring/security tooling assets and log-source mappings are captured |
| Digital Banking Head | Maintains digital channel application and service asset records |
| Compliance/Legal | Confirms legal/regulatory record categories and retention linkage |
| DPO | Confirms assets containing personal data and privacy obligations |
| Procurement/Vendor Management | Maintains third-party service and supplier-linked asset records |
| Branch Operations Managers | Maintain branch-local asset lists and reconcile with central inventory |
| Internal Audit | Verifies asset inventory accuracy and control effectiveness through audits |

## 7. Policy and Procedure (Asset Inventory Register)

### 7.1 Asset Inventory Governance Rules

1. All in-scope assets shall be uniquely identified and recorded in the inventory register.
2. Every asset must have an assigned **Asset Owner** and, where applicable, **Custodian**.
3. Inventory records must include classification, criticality, and CIA impact ratings.
4. New assets shall be recorded before production use or within 5 business days of onboarding.
5. Retired/decommissioned assets shall be updated in register within 5 business days of status change.
6. Critical asset records shall be reviewed at least quarterly; all other assets at least annually.
7. Asset inventory changes shall trigger risk reassessment where control posture is affected.

### 7.2 Asset Classification for Inventory Purposes

Asset Types used in this register:

- INF – Information/Data Asset
- APP – Application/Software Asset
- SYS – Server/Compute/Platform Asset
- NET – Network/Connectivity Asset
- SEC – Security Tooling Asset
- END – Endpoint/User Device Asset
- CLD – Cloud Service Asset
- VEN – Third-Party/Supplier Service Asset
- PHY – Physical/Facility Asset
- PRC – Business Process/Service Asset

### 7.3 Master Asset Inventory Register (Initial Baseline)

**Note:** This is the controlled initial baseline for certification preparation as of 01 July 2026.

Detailed technical sub-registers (e.g., full server lists, endpoint serial-level records) are maintained in operational repositories and reconciled to this master inventory.

| **Asset ID** | **Asset Name** | **Asset Type** | **Business Function / Service** | **Primary Location** | **Owner Role** | **Custodian Role** | **Information Classification*** | **Criticality** | **CIA (C/I/A)** | **Key Technology / Platform** | **Contains Personal Data** | **Regulatory Relevance** | **Lifecycle Status** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AIN-INF-001 | Core Customer Account Master Data | INF | Retail/Commercial/Core Banking Operations | Lagos DC / DR Replication | Head, Core Banking Operations | Database Administration Lead | Restricted | Critical | H/H/H | Core Banking SQL Databases | Yes | CBN, NDPA/NDPC | Active |
| AIN-INF-002 | Customer Transaction Ledger Data | INF | All Banking Segments | Lagos DC / DR Replication | Head, Finance Control | DBA Lead | Restricted | Critical | H/H/H | Core Banking Platform | Yes | CBN, NDPA/NDPC | Active |
| AIN-INF-003 | Digital Banking User Profile Data | INF | DTB One Mobile + Internet Banking | Lagos / Azure | Head, Digital Banking | Digital Platform Ops Lead | Restricted | High | H/H/M | Mobile & Internet Banking Platforms | Yes | NDPA/NDPC | Active |
| AIN-INF-004 | Corporate Banking Transaction Files | INF | Corporate & Investment Banking | Lagos | Head, Corporate Banking Ops | Corporate Platform Support Lead | Restricted | Critical | H/H/H | Corporate Banking Portal | Yes | CBN, contractual | Active |
| AIN-INF-005 | SWIFT Messaging and Payment Instruction Records | INF | Treasury / International Payments Interface | Lagos | Head, Treasury Operations | SWIFT Operations Custodian | Restricted | Critical | H/H/H | SWIFT Connectivity Stack | Limited PII | CBN, contractual | Active |
| AIN-INF-006 | Security Event and Audit Logs | INF | SOC Monitoring / Incident Response | Lagos / Azure SIEM | SOC Head | SIEM Engineering Lead | Confidential | High | M/H/H | Microsoft Sentinel, Splunk | Possible | Cybercrime evidence, audit | Active |
| AIN-INF-007 | Employee HR Security Records | INF | HR / Joiner-Mover-Leaver | Lagos | HR Director | HR Operations Lead | Confidential | High | H/M/M | HR Systems + Secure File Repositories | Yes | NDPA/NDPC, labor law | Active |
| AIN-INF-008 | Regulatory Reporting and Compliance Records | INF | Compliance / Legal / Audit | Lagos | Head, Compliance/Legal | Compliance Manager | Confidential | High | M/H/M | Compliance Repository | Possible | CBN, NDPC | Active |
| AIN-APP-001 | Core Banking Platform (Nigeria Instance) | APP | Core Transaction Processing | Lagos | Head, Core Banking Technology | Application Support Manager | Restricted | Critical | H/H/H | Core Banking Platform | Yes | CBN | Active |
| AIN-APP-002 | DTB One Mobile Banking Platform | APP | Digital Banking | Lagos / Azure | Head, Digital Banking | Mobile Platform Manager | Restricted | Critical | H/H/H | Mobile Banking Stack | Yes | CBN, NDPA/NDPC | Active |
| AIN-APP-003 | Internet Banking Platform | APP | Digital Banking | Lagos / Azure | Head, Digital Banking | Web Platform Manager | Restricted | Critical | H/H/H | Internet Banking Stack | Yes | CBN, NDPA/NDPC | Active |
| AIN-APP-004 | Corporate Banking Portal | APP | Corporate Banking Services | Lagos | Head, Corporate Banking Technology | Portal Support Lead | Restricted | Critical | H/H/H | Corporate Portal Stack | Yes | CBN, contractual | Active |
| AIN-APP-005 | Microsoft 365 Productivity and Collaboration Services | APP | Enterprise Collaboration | Nigeria-wide | Head, ITOPS | M365 Administrator | Internal | High | M/M/H | Microsoft 365 | Yes | NDPA/NDPC | Active |
| AIN-SYS-001 | Active Directory Domain Services | SYS | Enterprise Identity Backbone | Lagos | Head, ITOPS | Identity Services Lead | Restricted | Critical | H/H/H | Active Directory | Yes (identity attrs) | CBN, NDPA/NDPC | Active |
| AIN-SYS-002 | Microsoft Entra ID Tenant (Nigeria Use) | CLD | Cloud Identity and Access | Azure (tenant) | Head, ITOPS | Cloud Identity Admin Lead | Restricted | Critical | H/H/H | Microsoft Entra ID | Yes | NDPA/NDPC | Active |
| AIN-SYS-003 | Windows Server Estate (In-Scope) | SYS | Application and Infrastructure Hosting | Lagos + Branch Server Rooms | Head, ITOPS | Server Operations Team Lead | Internal/Confidential (by hosted data) | High | M/H/H | Windows Server | Possible | CBN (service continuity) | Active |
| AIN-SYS-004 | Linux Server Estate (In-Scope) | SYS | Application/API/Service Hosting | Lagos + Azure | Head, ITOPS | Linux Platform Lead | Internal/Confidential (by hosted data) | High | M/H/H | Linux Server Platforms | Possible | CBN | Active |
| AIN-NET-001 | Enterprise Firewall Infrastructure | NET | Perimeter and Segmentation Security | Lagos + Branches | Head, ITOPS | Network Security Manager | Internal | Critical | M/H/H | Firewall Platforms | No | CBN cyber resilience | Active |
| AIN-NET-002 | Cisco Network Core and Branch Connectivity | NET | Internal and Inter-Branch Connectivity | Nigeria-wide | Head, ITOPS | Network Operations Lead | Internal | High | M/H/H | Cisco Routing/Switching | No | CBN operational resilience | Active |
| AIN-NET-003 | Remote Access VPN Services | NET | Secure Remote Connectivity | Lagos | Head, ITOPS | Network Security Manager | Confidential | High | M/H/H | Enterprise VPN | Possible (session metadata) | CBN | Active |
| AIN-SEC-001 | Microsoft Sentinel SIEM Platform | SEC | Security Monitoring and Detection | Azure | SOC Head | SIEM Engineering Lead | Confidential | Critical | M/H/H | Microsoft Sentinel | Possible | Cybercrime evidence, CBN | Active |
| AIN-SEC-002 | Splunk Analytics Platform | SEC | Log Correlation / Security Analytics | Lagos | SOC Head | Splunk Platform Engineer | Confidential | High | M/H/H | Splunk | Possible | Audit/evidence | Active |
| AIN-SEC-003 | Microsoft Defender XDR | SEC | Endpoint/Identity/Email Threat Protection | Nigeria-wide | SOC Head | Endpoint Security Lead | Confidential | High | M/H/H | Defender XDR | Possible | CBN cyber controls | Active |
| AIN-SEC-004 | SentinelOne EDR | SEC | Endpoint Detection and Response | Nigeria-wide | SOC Head | Endpoint Security Lead | Confidential | High | M/H/H | SentinelOne | Possible | CBN cyber controls | Active |
| AIN-END-001 | Employee End User Devices (Managed Estate) | END | All Business Units | Nigeria-wide | Head, ITOPS | Endpoint Management Lead | Internal/Confidential (data dependent) | High | M/M/M | Managed Windows Endpoints + Encryption | Possible | NDPA/NDPC | Active |
| AIN-CLD-001 | Microsoft Azure Subscription (Nigeria Workloads) | CLD | Cloud Hosting/Security Services | Azure | Head, ITOPS | Cloud Platform Manager | Confidential/Restricted (workload dependent) | Critical | H/H/H | Azure IaaS/PaaS | Possible | CBN, NDPA/NDPC | Active |
| AIN-SEC-005 | Enterprise Backup Infrastructure | SEC | Backup and Recovery Services | Lagos + Offsite Secure Backup | Head, ITOPS | Backup Administrator | Confidential/Restricted (by backup content) | Critical | H/H/H | Backup Infrastructure | Yes (by included data) | CBN, NDPA/NDPC | Active |
| AIN-VEN-001 | Managed Telecom/MPLS Connectivity Services | VEN | Branch and DC Connectivity | Nigeria-wide | Head, ITOPS | Vendor Service Manager | Internal | High | M/M/H | Telecom Provider Service | No | Contractual/CBN continuity | Active |
| AIN-VEN-002 | Critical Cloud Support Services (Microsoft Enterprise Support) | VEN | Cloud Operations Support | Nigeria / Cloud | Head, ITOPS | Cloud Vendor Manager | Confidential | High | M/H/M | Vendor Support Services | Possible | Contractual, NDPA where relevant | Active |
| AIN-PRC-001 | Retail Banking Operations Process | PRC | Customer Account and Transaction Services | Lagos + Branches | Head, Retail Banking Operations | Branch Ops Managers | Restricted (process outputs include restricted data) | Critical | H/H/H | Process Asset | Yes | CBN, NDPA/NDPC | Active |
| AIN-PRC-002 | Information Security Incident Response Process | PRC | Detection, Response, Recovery | Lagos SOC + Enterprise | CISO | SOC Head | Confidential | Critical | M/H/H | Process Asset | Possible | CBN/Cybercrime compliance | Active |
| AIN-PHY-001 | Lagos Data Center / Server Room Facilities | PHY | Hosting and Physical Safeguards | Lagos | Head, ITOPS | Facilities & DC Operations | Internal | Critical | M/H/H | Physical Security Controls | No | CBN resilience | Active |
| AIN-PHY-002 | Branch Secure Record Storage Areas | PHY | Physical Record Protection | Abuja/PH/Enugu/Calabar/Ibadan | Branch Operations Head | Branch Operations Managers | Confidential | Medium | M/M/M | Controlled Storage | Possible | NDPA/record obligations | Active |
- Final classification labels are governed by DTB-NG-ISMS-ICS-015 and DTB-NG-ISMS-ACP-016.

### 7.4 Asset Ownership and Accountability Rules

1. Asset Owners are accountable for:
    - classification accuracy,
    - risk identification linkage,
    - protection requirements definition,
    - periodic review of asset record completeness.
2. Custodians are responsible for:
- operational maintenance,
- control execution,
- evidence generation.
1. Where multi-function ownership exists, one **Primary Owner** must be designated.
2. Ownership changes must be updated within 5 business days.

### 7.5 CIA and Criticality Determination Guidance

#### 7.5.1 CIA Rating Definitions

- **H (High):** Severe impact if compromised/unavailable
- **M (Medium):** Manageable but material impact
- **L (Low):** Limited impact

#### 7.5.2 Criticality Levels

- **Critical:** Essential to core banking operations/regulatory obligations
- **High:** Important to major business operations
- **Medium:** Operationally relevant with tolerable disruption windows
- **Low:** Limited operational dependence

Asset criticality informs risk scoring, treatment prioritization, and continuity planning.

### 7.6 Asset Lifecycle Status Rules

Lifecycle statuses used in inventory:

- **Active:** Operational and in service
- **In Transition:** Under migration/change with temporary control state
- **Retired:** Decommissioned, no active production use
- **Archived:** Retained for legal/regulatory/historical purposes

Retired/Archived assets must still maintain secure retention/disposal records where data persists.

### 7.7 Inventory Maintenance and Reconciliation Procedure

1. Monthly delta update from IT operations repositories for technology assets.
2. Quarterly reconciliation between:
    - CMDB/technical registers,
    - security tooling inventories,
    - business process and information asset owners,
    - branch-local records.
3. Exception report raised for missing owner, missing classification, or stale records.
4. Reconciliation results reviewed in ISMS Steering Committee (monthly/quarterly reporting cycle).

### 7.8 Mandatory Data Quality Controls

Asset inventory is considered valid only where records contain:

- Unique asset ID
- Named owner
- Classification
- Criticality
- Lifecycle status
- Last review date

Records missing mandatory fields must be corrected within 10 business days.

### 7.9 Linkage to Risk and Control Processes

Asset inventory is a mandatory input to:

- Risk assessment and risk register updates
- Vulnerability management prioritization
- Access control and privileged access governance
- Logging and monitoring scope definitions
- Backup and DR scope definition
- Supplier risk and dependency analysis
- Audit sampling and certification evidence preparation

### 7.10 Assumptions Applied

1. Detailed technical inventories (device-level and server-level) exist in operational tools and are reconciled to this ISMS master register.
2. Asset owners have authority to classify and validate their assigned assets.
3. Shared enterprise services used in Nigeria are represented where they materially impact Nigeria ISMS scope.
4. Baseline reflects in-scope environment as of 01 July 2026.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Asset Inventory (Master Register) | CISO Office / ISMS-PM | Minimum 6 years |
| Quarterly Asset Reconciliation Reports | ISMS-PM / ITOPS | Minimum 6 years |
| Asset Ownership Change Logs | ISMS-PM / HR / ITOPS | Minimum 6 years |
| Asset Classification Review Records | Asset Owners / CISO Office | Minimum 6 years |
| Inventory Data Quality Exception Logs | ISMS-PM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
2. DTB-NG-ISMS-ACP-016 – Asset Classification Policy
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
6. DTB-NG-ISMS-SOA-019 – Statement of Applicability
7. DTB-NG-ISMS-BCP-042 – Business Continuity Policy
8. DTB-NG-ISMS-DRP-043 – Disaster Recovery Procedure
9. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 6.1.3 Information security risk treatment
- Clause 7.5 Documented information
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation

## 11. Annex A References

- 5.9 Inventory of information and other associated assets
- 5.10 Acceptable use of information and other associated assets
- 5.11 Return of assets
- 5.12 Classification of information
- 5.13 Labelling of information
- 5.14 Information transfer
- 5.19 Information security in supplier relationships
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.33 Protection of records
- 8.1 User endpoint devices
- 8.9 Configuration management
- 8.10 Information deletion
- 8.11 Data masking
- 8.12 Data leakage prevention
- 8.13 Information backup
- 8.15 Logging

## 12. Review Frequency

This document shall be reviewed:

- Quarterly (formal reconciliation review), and
- Immediately upon major technology, process, organizational, or regulatory change affecting asset population.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager / ITOPS | Initial asset register baseline draft |
| 0.9 | 30 June 2026 | CISO / ITOPS / SOC / DPO / COMP | Refined ownership, classification, and criticality attributes |
| 1.0 | 01 July 2026 | CISO (Nigeria) | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Information Classification Scheme

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Information Classification Scheme |
| Document ID | DTB-NG-ISMS-ICS-015 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to define DTB Nigeria’s formal information classification scheme, including classification levels, handling rules, labeling requirements, and protection controls for information throughout its lifecycle.

This scheme ensures that information receives protection proportionate to its sensitivity, criticality, legal obligations, and business impact, in alignment with ISO/IEC 27001:2022, ISO/IEC 27002:2022, CBN expectations, and NDPA/NDPC requirements.

## 3. Scope

This scheme applies to all information created, processed, stored, transmitted, or disposed of within DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan
- On-premises systems, cloud services, endpoints, collaboration platforms, backup repositories, and physical records
- Employees, contractors, third parties, and service providers handling DTB Nigeria information assets

Out-of-scope international entities (London, Frankfurt, Paris, New York) are not covered as internal users under this scheme; however, any information transfer between DTB Nigeria and those entities must comply with this scheme at the DTB Nigeria boundary.

## 4. References

1. ISO/IEC 27001:2022
2. ISO/IEC 27002:2022 (Information classification, labeling, transfer, and handling controls)
3. DTB-NG-ISMS-INF-008 – Information Security Policy
4. DTB-NG-ISMS-AIN-014 – Asset Inventory
5. DTB-NG-ISMS-ACP-016 – Asset Classification Policy (next document)
6. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
7. DTB-NG-ISMS-PDP-053 – Privacy and Data Protection Policy (to be issued)
8. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy (to be issued)
9. NDPA and NDPC guidance
10. CBN cybersecurity and information governance expectations

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Information Classification | Categorization of information based on sensitivity and required protection level |
| Information Owner | Role accountable for classifying information and approving handling/access requirements |
| Labeling | Marking information with classification designation |
| Need-to-Know | Access principle restricting data access to users with legitimate business requirement |
| Data Handling | Rules governing storage, access, transmission, copying, retention, and disposal |
| Reclassification | Approved change of classification due to business/legal/operational changes |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns and enforces classification scheme governance |
| Information Owners (Business/Process Owners) | Classify and periodically review information assets |
| Data Protection Officer (DPO) | Ensures personal data classification and handling align with NDPA/NDPC |
| Compliance/Legal | Ensures legal/regulatory handling obligations are reflected in classification rules |
| ITOPS | Implements technical controls for storage, access, encryption, and lifecycle protection |
| SOC | Monitors handling violations and supports incident response |
| Records Management / Process Custodians | Ensure physical/digital record labeling and retention controls |
| HR | Supports awareness and disciplinary enforcement for misuse |
| All Users | Comply with classification labels and handling requirements |
| Internal Audit | Tests adherence to classification scheme and evidence integrity |

## 7. Policy and Procedure (Classification Scheme)

### 7.1 Classification Model Overview

DTB Nigeria adopts a **four-level information classification model**:

1. **Public**
2. **Internal**
3. **Confidential**
4. **Restricted**

Each classification level defines mandatory controls for access, storage, transmission, sharing, retention, and disposal.

### 7.2 Classification Levels and Criteria

| **Classification** | **Definition** | **Typical Impact if Compromised** | **Typical Use Cases** |
| --- | --- | --- | --- |
| Public | Information approved for unrestricted public disclosure | Minimal to no adverse impact | Published product brochures, public website content, approved press releases |
| Internal | Non-public business information intended for DTB internal use | Limited operational/reputational impact | Internal policies, operating procedures, general internal memos |
| Confidential | Sensitive business, customer, employee, or operational information requiring controlled access | Significant operational, financial, legal, or reputational impact | Employee records, internal audit records, non-public financial reports, security logs |
| Restricted | Highly sensitive and critical information requiring strongest protection and strict need-to-know access | Severe impact including regulatory sanctions, major customer harm, critical service impact | Core banking customer data, transaction ledgers, payment instructions, credentials/secrets, high-risk investigation records |

### 7.3 Default Classification Rules

1. All information is **classified at creation or onboarding**.
2. If uncertain, information shall be treated as **Confidential** by default until owner determination.
3. Information containing regulated personal data or high-impact banking records shall be classified at least **Confidential**, and **Restricted** where impact is severe.
4. Credentials, cryptographic key material, privileged access artifacts, and high-value fraud/security investigation records are **Restricted by default**.

### 7.4 Classification Decision Criteria

Information owners shall assess classification based on:

1. **Confidentiality impact** (unauthorized disclosure consequences)
2. **Integrity impact** (unauthorized alteration consequences)
3. **Availability impact** (service/process impact if unavailable)
4. **Regulatory/legal obligations** (CBN, NDPA/NDPC, legal hold)
5. **Contractual obligations** (counterparty, supplier, partner clauses)
6. **Business criticality and customer trust impact**
7. **Data aggregation effect** (combined datasets may require higher classification)

### 7.5 Classification and Labeling Requirements

#### 7.5.1 Standard Labels

Approved labels:

- PUBLIC
- INTERNAL
- CONFIDENTIAL
- RESTRICTED

#### 7.5.2 Label Placement Rules

| **Information Format** | **Labeling Requirement** |
| --- | --- |
| Electronic documents | Classification label in header/footer and metadata where supported |
| Emails | Classification indicator in subject prefix and/or banner where tooling permits |
| Database/data stores | Data set/table classification in data catalog/owner register and access policies |
| File shares/collaboration sites | Folder/library classification tags and access group controls |
| Printed documents | Classification marking on each page or cover page (minimum) |
| Backup media/artifacts | Classification reflected in backup catalog and handling controls |

Unlabeled sensitive data identified during review must be remediated promptly.

### 7.6 Handling Requirements by Classification

| **Control Area** | **Public** | **Internal** | **Confidential** | **Restricted** |
| --- | --- | --- | --- | --- |
| Access Control | Open | DTB personnel/authorized users | Need-to-know; approved role-based access | Strict need-to-know; explicit owner approval; enhanced monitoring |
| Storage | Standard approved repositories | Approved corporate repositories | Approved secure repositories with access restrictions | Hardened repositories; strong access controls; encryption and heightened monitoring |
| Transmission (Internal) | Standard channels | Approved corporate channels | Protected channels; avoid unnecessary broad distribution | Encrypted/protected channels only; recipient validation mandatory |
| Transmission (External) | Allowed if approved | Limited and justified | Contractual/legal basis + secure transfer | Strictly controlled; formal approval + strong encryption + logging |
| Printing | Allowed | Controlled | Minimize; secure collection and disposal | Exceptional-only; explicit approval; strict physical controls |
| Copy/Replication | Allowed | Controlled | Minimize and track where feasible | Minimize strictly; formal justification; controlled copies only |
| Retention | Per business need | Per retention schedule | Per legal/business retention schedule | Minimum necessary with strict legal/regulatory retention controls |
| Disposal | Standard disposal | Controlled disposal | Secure disposal (digital/physical) | Verified secure disposal with evidence and chain-of-custody where required |

### 7.7 Encryption and Protection Requirements

1. **Confidential** and **Restricted** information must be protected in transit using approved secure protocols/channels.
2. **Restricted** information requires encryption at rest in approved storage environments unless formally exempted with compensating controls.
3. Cryptographic key access must be limited to authorized personnel under separation-of-duties principles.
4. Use of personal/unapproved storage or messaging channels for Confidential/Restricted data is prohibited.

### 7.8 Data Sharing and Transfer Controls

Before sharing information outside DTB Nigeria:

1. Confirm classification and transfer necessity.
2. Validate recipient authorization and legal/contractual basis.
3. Apply appropriate transmission protection (encryption, secure channels).
4. Ensure data minimization (only required fields shared).
5. Log/retain evidence for Confidential and Restricted transfers as required.
6. For cross-border interface transfers, ensure DTB Nigeria boundary controls and approvals are applied.

### 7.9 Reclassification and Declassification

1. Reclassification requests must be initiated by information owner (or delegate) with rationale.
2. Compliance/Legal and DPO review is mandatory where legal/privacy impact exists.
3. Reclassification decisions must be documented, approved, and reflected in labels/access rules.
4. Declassification to lower sensitivity requires verification that legal, contractual, and risk constraints no longer apply.

### 7.10 Exceptions

Any exception to classification or handling rules requires:

1. Documented business justification,
2. Risk assessment,
3. Compensating controls,
4. Defined validity period,
5. Approval by CISO and information owner,
6. Compliance/Legal and DPO review where applicable.

Exceptions shall be logged and periodically reviewed.

### 7.11 Awareness and Compliance Monitoring

1. All personnel must complete information classification and handling awareness training.
2. Technical and data-owner roles receive role-specific handling guidance.
3. Compliance is monitored through:
    - access reviews,
    - DLP/security monitoring alerts,
    - audit sampling,
    - incident analysis.
4. Noncompliance may result in disciplinary, contractual, or legal action.

### 7.12 Assumptions Applied

1. Data owners are assigned and available for in-scope information assets.
2. Tooling supports practical implementation of labeling and access controls for major repositories.
3. Supporting policies/procedures (asset classification policy, disposal policy, privacy policy) will remain aligned to this scheme.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Information Classification Scheme | CISO Office | Minimum 6 years |
| Information Classification Register Entries | Information Owners / ISMS-PM | Minimum 6 years |
| Reclassification/Declassification Requests and Approvals | CISO Office / Information Owners | Minimum 6 years |
| Classification Exception Logs | CISO Office | Minimum 6 years |
| Classification Awareness Completion Records | HR / ISMS-PM | Minimum 6 years |
| Monitoring and Violation Reports | SOC / Compliance | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-ACP-016 – Asset Classification Policy
2. DTB-NG-ISMS-AIN-014 – Asset Inventory
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-ACP-027 – Access Control Policy
6. DTB-NG-ISMS-CRY-031 – Cryptographic Controls Policy
7. DTB-NG-ISMS-MHD-051 – Media Handling Procedure
8. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy
9. DTB-NG-ISMS-PDP-053 – Privacy and Data Protection Policy
10. DTB-NG-ISMS-ECP-025 – External Communication Procedure

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 7.3 Awareness
- Clause 7.5 Documented information
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 10.2 Nonconformity and corrective action

## 11. Annex A References

- 5.9 Inventory of information and other associated assets
- 5.10 Acceptable use of information and other associated assets
- 5.12 Classification of information
- 5.13 Labelling of information
- 5.14 Information transfer
- 5.15 Access control
- 5.17 Authentication information
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.33 Protection of records
- 5.34 Privacy and protection of PII
- 8.10 Information deletion
- 8.11 Data masking
- 8.12 Data leakage prevention
- 8.24 Use of cryptography

## 12. Review Frequency

This document shall be reviewed:

- At least annually, and
- On significant changes to legal/regulatory obligations, data processing models, business services, or technology platforms affecting classification/handling requirements.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager / DPO / CISO Office | Initial classification model draft |
| 0.9 | 30 June 2026 | CISO / COMP / DPO / ITOPS / SOC | Updated handling matrix and transfer control requirements |
| 1.0 | 01 July 2026 | CISO (Nigeria) | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Asset Classification Policy

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Asset Classification Policy |
| Document ID | DTB-NG-ISMS-ACP-016 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this policy is to establish mandatory requirements for classifying DTB Nigeria information and associated assets based on sensitivity, business criticality, legal/regulatory obligations, and risk impact, and to ensure that classification results are consistently applied to protection, access, transfer, retention, and disposal controls.

This policy operationalizes DTB’s Information Classification Scheme and supports risk-based information security management in accordance with ISO/IEC 27001:2022 and ISO/IEC 27002:2022.

## 3. Scope

This policy applies to all assets within DTB Nigeria ISMS certification scope, including:

- Information and data assets (structured/unstructured, physical/digital)
- Applications and databases
- Infrastructure and endpoint assets
- Cloud-hosted services and repositories
- Security monitoring records and logs
- Business process assets and records
- Third-party managed assets handling DTB Nigeria information

Applicable locations:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Out-of-scope entities (London, Frankfurt, Paris, New York) are excluded as internal organizational domains under this policy; cross-border exchanges with those entities must still apply DTB Nigeria classification and handling requirements at boundary points.

## 4. References

1. ISO/IEC 27001:2022
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-INF-008 – Information Security Policy
4. DTB-NG-ISMS-AIN-014 – Asset Inventory
5. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
6. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
7. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
8. DTB-NG-ISMS-ACP-027 – Access Control Policy (to be issued)
9. DTB-NG-ISMS-CRY-031 – Cryptographic Controls Policy (to be issued)
10. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy (to be issued)
11. NDPA / NDPC requirements and guidance
12. CBN information security and cyber risk governance requirements

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Asset Classification | Assignment of protection category to an asset based on sensitivity, criticality, and impact |
| Information Owner | Role accountable for classifying information and approving handling controls |
| Asset Owner | Role accountable for protection and lifecycle governance of non-information assets and associated data contexts |
| Classification Label | Approved marker indicating classification level (Public, Internal, Confidential, Restricted) |
| Criticality | Measure of asset importance to business operations and service continuity |
| Reclassification | Approved change to classification level due to business, legal, technical, or risk changes |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Policy owner; ensures classification controls are enforced |
| Information Owners | Determine and approve classification for information assets |
| Asset Owners | Ensure associated non-information assets inherit and enforce required protection levels |
| DPO | Reviews classification decisions involving personal data and privacy obligations |
| Compliance/Legal | Reviews legal/regulatory classification implications |
| ITOPS | Implements technical controls aligned to classification outcomes |
| SOC | Monitors handling violations and supports incident escalation |
| Procurement/Vendor Management | Ensures supplier handling controls align with asset classification requirements |
| Branch Operations Managers | Apply and verify classification controls for branch-held records/assets |
| All Users | Handle assets according to assigned classification and policy requirements |
| Internal Audit | Independently tests compliance with policy and control operation effectiveness |

## 7. Policy Requirements

### 7.1 Classification Obligation

1. All in-scope assets must be classified prior to operational use or as part of formal onboarding.
2. No asset may remain unclassified beyond 5 business days from creation/onboarding.
3. Assets with unknown classification shall be treated as **Confidential** until formally assessed.
4. Classification decisions must be documented in the Asset Inventory and related repositories.

### 7.2 Approved Classification Levels

DTB Nigeria adopts the classification levels defined in DTB-NG-ISMS-ICS-015:

1. **Public**
2. **Internal**
3. **Confidential**
4. **Restricted**

Classification applies to both standalone assets and composite service environments.

### 7.3 Classification Criteria

Asset and information classification shall be based on:

1. Confidentiality impact
2. Integrity impact
3. Availability impact
4. Legal and regulatory obligations
5. Contractual obligations
6. Business criticality and customer impact
7. Aggregation/sensitivity amplification effects

Where classification criteria yield differing levels, the **highest required protection level** shall apply.

### 7.4 Ownership and Approval Rules

1. Every asset must have a named owner accountable for classification accuracy.
2. Initial classification requires owner approval and documentation.
3. For assets processing personal data, DPO consultation is mandatory for Confidential/Restricted determinations.
4. For assets with regulatory implications, Compliance/Legal consultation is mandatory.
5. Classification authority may be delegated for execution, but accountability remains with asset/information owner.

### 7.5 Labeling and Metadata Requirements

1. Classification labels must be applied to digital and physical assets per DTB-NG-ISMS-ICS-015.
2. Systems storing classified information must maintain classification metadata at data store, repository, or dataset level.
3. Email and document systems should enforce visible or metadata labeling where tooling supports.
4. Unlabeled sensitive assets discovered during operations or audits must be remediated promptly and tracked.

### 7.6 Handling Control Alignment

Classification outputs must drive control enforcement in:

- Access control and least privilege assignment
- Encryption and key protection
- Data transfer channel selection
- Backup and restoration handling
- Logging and monitoring priority
- Retention and secure disposal methods
- Third-party sharing and contract controls

Minimum control expectations by classification are defined in DTB-NG-ISMS-ICS-015 and supporting procedures.

### 7.7 Asset Types and Classification Inheritance

1. Applications, databases, and infrastructure assets inherit minimum protection level from highest classified data processed or stored.
2. Backup assets inherit classification of source data.
3. Log repositories inherit classification based on contained event content and sensitivity.
4. Shared platforms hosting mixed classification data must enforce segregation and highest applicable baseline controls where segregation is not feasible.

### 7.8 Reclassification Rules

Reclassification is required when:

1. Business use changes materially,
2. Legal or regulatory obligations change,
3. Data content sensitivity increases/decreases,
4. Asset role in critical services changes,
5. Incident or audit findings indicate misclassification.

Reclassification must be:

- documented,
- approved by owner,
- reviewed by DPO/Compliance where applicable,
- reflected in labels and control settings within defined implementation timelines.

### 7.9 Review Frequency

1. **Restricted and Critical assets:** review at least quarterly.
2. **Confidential assets:** review at least semi-annually.
3. **Internal/Public assets:** review at least annually.
4. Event-driven review is mandatory upon major incidents, architecture changes, or regulatory updates.

### 7.10 Exceptions and Risk Acceptance

Any deviation from this policy requires:

1. Formal exception request,
2. Risk assessment,
3. Compensating controls,
4. Time-bound approval,
5. CISO approval (mandatory),
6. DPO/Compliance review where privacy/legal obligations are involved.

Exceptions must be logged and reviewed periodically.

Unapproved deviations are policy violations.

### 7.11 Third-Party and Supplier Requirements

1. Suppliers handling DTB information must comply with classification-related contractual controls.
2. Confidential/Restricted information sharing requires approved legal/contractual basis and secure transfer controls.
3. Supplier environments handling Restricted data require enhanced assurance checks.
4. Third-party noncompliance must trigger escalation and corrective action per supplier governance procedures.

### 7.12 Compliance Monitoring and Enforcement

Compliance is verified through:

- Asset inventory and metadata reviews,
- Access recertification controls,
- DLP/monitoring alerts,
- Audit sampling,
- Incident trend analysis.

Policy breaches may result in:

- Access suspension/removal,
- Disciplinary action,
- Contractual sanctions,
- Regulatory/legal escalation where required.

### 7.13 Awareness and Training

1. All users must complete mandatory classification and handling awareness training.
2. Asset/information owners require role-specific training on classification decision criteria.
3. Technical custodians require implementation training on labeling, access, encryption, and data lifecycle controls.
4. Training completion is tracked and reported to governance forums.

### 7.14 Assumptions Applied

1. Asset ownership assignment is maintained and current in DTB master inventory.
2. Supporting technical controls exist or are being implemented per ISMS roadmap.
3. Records repositories and collaboration platforms support classification metadata or equivalent control tagging.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Asset Classification Policy | CISO Office | Minimum 6 years |
| Classification Decision Records | Asset/Information Owners | Minimum 6 years |
| Reclassification Request and Approval Records | CISO Office / Owners | Minimum 6 years |
| Classification Exception Logs | CISO Office | Minimum 6 years |
| Classification Review Evidence (periodic) | ISMS-PM / Owners | Minimum 6 years |
| Awareness and Training Completion Logs | HR / ISMS-PM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
2. DTB-NG-ISMS-AIN-014 – Asset Inventory
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-ACP-027 – Access Control Policy
6. DTB-NG-ISMS-CRY-031 – Cryptographic Controls Policy
7. DTB-NG-ISMS-MHD-051 – Media Handling Procedure
8. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy
9. DTB-NG-ISMS-PDP-053 – Privacy and Data Protection Policy
10. DTB-NG-ISMS-SUP-044 – Supplier Security Policy

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 6.1.3 Information security risk treatment
- Clause 7.2 Competence
- Clause 7.3 Awareness
- Clause 7.5 Documented information
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 10.2 Nonconformity and corrective action

## 11. Annex A References

- 5.9 Inventory of information and other associated assets
- 5.10 Acceptable use of information and other associated assets
- 5.12 Classification of information
- 5.13 Labelling of information
- 5.14 Information transfer
- 5.15 Access control
- 5.18 Access rights
- 5.19 Information security in supplier relationships
- 5.20 Addressing information security within supplier agreements
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.33 Protection of records
- 5.34 Privacy and protection of PII
- 5.36 Compliance with policies and standards for information security
- 8.10 Information deletion
- 8.12 Data leakage prevention
- 8.24 Use of cryptography

## 12. Review Frequency

This policy shall be reviewed:

- At least annually, and
- Upon significant legal/regulatory change, business model change, new technology implementation, or major data handling incident.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager / CISO Office | Initial policy draft |
| 0.9 | 30 June 2026 | CISO / DPO / COMP / ITOPS | Updated criteria, ownership, and exception requirements |
| 1.0 | 01 July 2026 | CISO (Nigeria) | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Risk Register

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Risk Register |
| Document ID | DTB-NG-ISMS-RRG-017 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Enterprise Risk Manager (ERM), Nigeria |
| Co-Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 October 2026 (Quarterly Review Cycle) |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this Risk Register is to document, track, and govern information security risks affecting DTB Nigeria’s in-scope operations, including risk ownership, scoring, treatment status, residual exposure, and review decisions, in accordance with ISO/IEC 27001:2022 requirements.

This register is the authoritative record for risk-based decision-making and supports treatment planning, management review, audit readiness, and continual improvement.

## 3. Scope

This register applies to all information security risks within DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Risk categories covered include:

- Governance and compliance risks
- Cybersecurity and technology risks
- Data protection and privacy risks
- Operational and process risks
- Third-party/supplier risks
- Resilience and continuity risks
- Physical/environmental risks related to information security

Out-of-scope international branches (London, Frankfurt, Paris, New York) are excluded except where interface dependencies create risk to DTB Nigeria operations.

## 4. References

1. ISO/IEC 27001:2022 Clauses 6.1.2 and 6.1.3
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
5. DTB-NG-ISMS-AIN-014 – Asset Inventory
6. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
7. DTB-NG-ISMS-ACP-016 – Asset Classification Policy
8. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan (next document)
9. DTB-NG-ISMS-SOA-019 – Statement of Applicability
10. DTB-NG-ISMS-INF-008 – Information Security Policy
11. CBN cybersecurity and risk management obligations
12. NDPA/NDPC obligations relevant to personal data and security risk

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Risk ID | Unique identifier for each risk record |
| Inherent Risk | Risk score before considering existing controls |
| Residual Risk | Risk score after evaluating existing controls and effectiveness |
| Risk Owner | Role accountable for managing assigned risk and treatment outcomes |
| Control Owner | Role accountable for operation and effectiveness of controls linked to the risk |
| Risk Treatment Status | Current state of treatment actions (Open, In Progress, Mitigated, Accepted, Closed) |
| Review Date | Scheduled date for formal reassessment/update of risk record |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| ERM (Nigeria) | Maintains risk register integrity, quality controls, and aggregation reporting |
| CISO (Nigeria) | Ensures security risk governance and escalates high/critical residual risks |
| Risk Owners | Maintain risk records, treatment progress, and review updates |
| Control Owners | Implement and evidence control actions linked to risk reduction |
| Compliance/Legal | Validate regulatory risk impacts and legal obligations |
| DPO | Validate privacy impact and personal data risk handling |
| ISMS Programme Manager | Coordinates review cycles and governance reporting packs |
| ISMS Steering Committee | Reviews high/critical risks and treatment progress monthly |
| CEO (Nigeria) | Approves escalated high/critical risk acceptance decisions |
| Internal Audit | Provides independent assurance on risk governance and record reliability |

## 7. Policy and Procedure (Risk Register Content)

### 7.1 Risk Register Governance Rules

1. Every identified in-scope information security risk shall be recorded in this register.
2. Risk records must follow DTB-NG-ISMS-RAM-012 scoring model and DTB-NG-ISMS-RAC-013 acceptance rules.
3. Each risk must have one named risk owner and at least one review date.
4. High/Critical residual risks must be reported monthly to ISMS Steering Committee.
5. Risk status and treatment fields must be updated at least monthly for High/Critical risks and quarterly for all others.
6. Closed risks must retain closure rationale and evidence for audit traceability.

### 7.2 Risk Register Field Model (Minimum)

Each risk record includes:

- Risk ID
- Risk category/domain
- Risk scenario
- Affected asset/process
- Threat/vulnerability context
- Existing controls
- Inherent likelihood/impact/score
- Residual likelihood/impact/score
- Residual rating (Low/Medium/High/Critical)
- Regulatory/privacy relevance
- Risk owner
- Control owner(s)
- Treatment strategy
- Treatment actions and target date
- Current status
- Acceptance decision (if applicable)
- Last review date / next review date
- Comments/evidence references

### 7.3 DTB Nigeria ISMS Risk Register (Initial Baseline)

**Scoring basis:** 1–5 likelihood x 1–5 impact = 1–25 score

**Rating bands:** Low (1–4), Medium (5–9), High (10–16), Critical (17–25)

| **Risk ID** | **Category** | **Risk Scenario** | **Affected Asset/Process** | **Existing Controls (Summary)** | **Inherent L/I/S** | **Residual L/I/S** | **Residual Rating** | **Regulatory/Privacy Relevance** | **Risk Owner** | **Treatment Strategy** | **Target Date** | **Status** | **Next Review** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RSK-001 | IAM / Access Governance | Delayed deprovisioning of terminated users leads to unauthorized access and potential data exposure | AD/Entra ID, HR JML Process | JML workflow, periodic access reviews, SOC monitoring | 4/4/16 | 3/3/9 | Medium | NDPA/NDPC | Head, ITOPS | Mitigate | 30 Sep 2026 | In Progress | Monthly |
| RSK-002 | Vulnerability Management | Critical vulnerabilities remain unpatched beyond SLA, enabling exploitation of internet-facing systems | Server estate, digital channels | Vulnerability scans, patch cycles, exception process | 5/4/20 | 4/4/16 | High | CBN | Head, ITOPS | Mitigate | 31 Oct 2026 | In Progress | Monthly |
| RSK-003 | Incident Detection | Incomplete SIEM log-source onboarding reduces ability to detect malicious activity in time | Sentinel/Splunk, critical systems | SOC monitoring, existing use cases | 4/4/16 | 3/4/12 | High | CBN, Cybercrime evidence | SOC Head | Mitigate | 31 Dec 2026 | In Progress | Monthly |
| RSK-004 | Data Protection | Inadequate data labeling/handling causes unauthorized sharing of customer personal data | Customer data repositories, email/collab tools | Classification scheme, DLP controls (partial), awareness | 4/5/20 | 3/4/12 | High | NDPA/NDPC | DPO | Mitigate | 30 Nov 2026 | In Progress | Monthly |
| RSK-005 | Third-Party Security | Critical supplier security weaknesses or delayed incident notification impact DTB service and data confidentiality | Supplier-managed connectivity/services | Contract clauses (partial), due diligence process | 4/4/16 | 3/4/12 | High | Contractual/CBN | Procurement Lead | Mitigate | 31 Dec 2026 | In Progress | Monthly |
| RSK-006 | Resilience / Backup | Backup restoration failure for critical systems prolongs service outage during incident | Backup infrastructure, core systems | Daily backup jobs, periodic restore tests | 4/5/20 | 3/4/12 | High | CBN resilience obligations | Head, ITOPS | Mitigate | 31 Jan 2027 | In Progress | Monthly |
| RSK-007 | Endpoint Security | Malware/ransomware infection on endpoints spreads laterally due to inconsistent hardening | End-user devices, internal network | Defender XDR/SentinelOne, AV policies, segmentation | 5/4/20 | 3/4/12 | High | CBN | SOC Head | Mitigate | 30 Nov 2026 | In Progress | Monthly |
| RSK-008 | Regulatory Compliance | Delays in implementing new regulatory security obligations create compliance breaches | Compliance monitoring process | Regulatory tracker, legal review cadence | 3/5/15 | 2/4/8 | Medium | CBN, NDPA/NDPC | Head, Compliance/Legal | Mitigate | 30 Sep 2026 | In Progress | Quarterly |
| RSK-009 | Privileged Access | Excessive privileged accounts and weak recertification increase risk of unauthorized high-impact changes | AD/Server/Admin consoles | PAM controls (partial), periodic review | 4/5/20 | 3/4/12 | High | CBN | Head, ITOPS | Mitigate | 30 Nov 2026 | In Progress | Monthly |
| RSK-010 | Application Security | Security weaknesses in digital channel releases introduce exploitable flaws | Mobile/Internet/Corporate banking apps | Change control, code review, testing (maturity improving) | 4/5/20 | 3/4/12 | High | CBN, NDPA/NDPC | Head, Digital Banking Technology | Mitigate | 31 Dec 2026 | In Progress | Monthly |
| RSK-011 | Logging Integrity | Insufficient log retention/protection undermines forensic investigations and legal defensibility | SIEM, log repositories | Centralized logging, access controls (partial hardening) | 3/4/12 | 2/4/8 | Medium | Cybercrime evidence, audit | SOC Head | Mitigate | 31 Oct 2026 | In Progress | Quarterly |
| RSK-012 | Branch Security Operations | Inconsistent branch control execution (physical access, records handling) exposes sensitive information | Branch operations, physical records | Branch SOPs, awareness, local supervision | 3/4/12 | 2/3/6 | Medium | NDPA/NDPC | Head, Branch Operations | Mitigate | 31 Dec 2026 | In Progress | Quarterly |
| RSK-013 | Configuration Management | Baseline configuration drift in servers/network devices introduces exploitable weaknesses | Windows/Linux servers, firewalls, network devices | Hardening guides, change process, periodic checks | 4/4/16 | 3/3/9 | Medium | CBN | Head, ITOPS | Mitigate | 31 Dec 2026 | In Progress | Quarterly |
| RSK-014 | Business Continuity / DR | DR failover process not sufficiently validated for all critical services | DR planning and exercises | DR plans, selective testing | 4/5/20 | 3/4/12 | High | CBN resilience | Head, ITOPS | Mitigate | 31 Mar 2027 | In Progress | Monthly |
| RSK-015 | Identity Federation / Cloud Misconfig | Misconfiguration in Entra ID or cloud access policies leads to unauthorized access | Entra ID, Azure resources | Conditional access, admin controls, monitoring | 4/5/20 | 3/4/12 | High | NDPA/NDPC, CBN | Head, ITOPS | Mitigate | 30 Nov 2026 | In Progress | Monthly |
| RSK-016 | Data Retention/Disposal | Inadequate disposal of expired records/media results in unauthorized data recovery | Archived data, removable/legacy media | Retention schedule, disposal procedures (partial evidence) | 3/4/12 | 2/3/6 | Medium | NDPA/NDPC | Compliance + DPO | Mitigate | 31 Jan 2027 | In Progress | Quarterly |
| RSK-017 | Fraud / Social Engineering | Phishing and social engineering compromise user credentials and trigger fraudulent transactions | End users, email platform, banking workflows | Awareness training, MFA, SOC monitoring | 5/4/20 | 3/4/12 | High | CBN, customer impact | SOC Head | Mitigate | 31 Oct 2026 | In Progress | Monthly |
| RSK-018 | Supplier Concentration | Overreliance on limited telecom/cloud providers creates single-point operational and security dependency | Network/cloud service dependencies | Vendor management, contracts, contingency planning (limited) | 4/4/16 | 3/3/9 | Medium | CBN continuity | Procurement Lead | Mitigate/Transfer | 31 Mar 2027 | In Progress | Quarterly |
| RSK-019 | Incident Response Readiness | Incomplete incident playbook coverage for some high-risk scenarios delays containment | Incident response process | IR procedure, SOC triage, escalation matrix | 4/4/16 | 3/3/9 | Medium | CBN/Cybercrime | CISO | Mitigate | 31 Oct 2026 | In Progress | Quarterly |
| RSK-020 | Security Awareness Maturity | Low awareness in some functions increases accidental policy/control violations | Workforce security behavior | Mandatory awareness program, phishing simulations | 4/3/12 | 3/3/9 | Medium | NDPA/NDPC (human error) | HR Director | Mitigate | 31 Dec 2026 | In Progress | Quarterly |

### 7.4 High/Critical Risk Focus List (Current)

Current High residual risks requiring monthly governance oversight:

- RSK-002
- RSK-003
- RSK-004
- RSK-005
- RSK-006
- RSK-007
- RSK-009
- RSK-010
- RSK-014
- RSK-015
- RSK-017

No Critical residual risks are approved in this baseline version.

### 7.5 Status Definitions

| **Status** | **Meaning** |
| --- | --- |
| Open | Risk identified and documented; treatment not yet initiated |
| In Progress | Treatment actions underway |
| Mitigated | Planned treatment implemented; awaiting validation or monitoring confirmation |
| Accepted | Residual risk formally accepted per DTB-NG-ISMS-RAC-013 |
| Closed | Risk exposure reduced/removed and closure approved with evidence |
| Escalated | Risk requires higher governance decision due to severity, delay, or impact change |

### 7.6 Review and Update Requirements

1. High/Critical risks: reviewed at least monthly.
2. Medium risks: reviewed at least quarterly.
3. Low risks: reviewed at least annually (or sooner on trigger events).
4. Risk score changes require rationale and evidence update in register.
5. Missed treatment milestones automatically trigger escalation review.

### 7.7 Linkage to Risk Treatment Plan and SoA

1. Each non-closed risk must map to one of:
    - active treatment action in DTB-NG-ISMS-RTP-018,
    - formal acceptance record under DTB-NG-ISMS-RAC-013.
2. Risks linked to control gaps must reference relevant SoA controls and implementation status.
3. Register and RTP shall be reconciled monthly.

### 7.8 Assumptions Applied

1. Baseline register reflects risk posture as of 01 July 2026 based on available assessments and operational evidence.
2. Additional risks may be added as deeper domain/branch assessments continue.
3. Scoring and acceptance decisions follow DTB-approved methodology and criteria documents without exception.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Risk Register | ERM / CISO Office | Minimum 6 years |
| Monthly Risk Review Minutes and Updates | ISMS-PM / ERM | Minimum 6 years |
| High/Critical Risk Escalation Records | CISO Office | Minimum 6 years |
| Risk Score Change Logs | ERM | Minimum 6 years |
| Risk Closure Evidence and Approvals | Risk Owners / ERM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
2. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
3. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
4. DTB-NG-ISMS-SOA-019 – Statement of Applicability
5. DTB-NG-ISMS-AIN-014 – Asset Inventory
6. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
7. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
8. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
9. DTB-NG-ISMS-MRV-058 – Management Review Procedure

## 10. ISO Clause References

- Clause 6.1.2 Information security risk assessment
- Clause 6.1.3 Information security risk treatment
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.3 Management review
- Clause 10.1 Continual improvement

## 11. Annex A References

- 5.7 Threat intelligence
- 5.8 Information security in project management
- 5.9 Inventory of information and other associated assets
- 5.15 Access control
- 5.16 Identity management
- 5.18 Access rights
- 5.19 Information security in supplier relationships
- 5.24 Information security incident management planning and preparation
- 5.26 Response to information security incidents
- 5.27 Learning from information security incidents
- 5.30 ICT readiness for business continuity
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.34 Privacy and protection of PII
- 5.36 Compliance with policies and standards for information security
- 8.8 Management of technical vulnerabilities
- 8.13 Information backup
- 8.15 Logging
- 8.16 Monitoring activities
- 8.24 Use of cryptography

## 12. Review Frequency

This register shall be reviewed:

- Monthly (governance update cycle for high-priority risks),
- Quarterly (full register health review),
- Immediately upon significant incident, control failure, or material business/technology/regulatory change.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ERM / ISMS Programme Manager | Initial risk register draft |
| 0.9 | 30 June 2026 | CISO / ERM / SOC / ITOPS / COMP / DPO | Baseline risks validated and scored |
| 1.0 | 01 July 2026 | ERM / CISO | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Emeka R. Okonkwo | Enterprise Risk Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Risk Treatment Plan

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Risk Treatment Plan |
| Document ID | DTB-NG-ISMS-RTP-018 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Co-Owner | Enterprise Risk Manager (ERM), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 October 2026 (Quarterly Review Cycle) |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this Risk Treatment Plan is to define how DTB Nigeria will address identified information security risks through prioritized treatment actions, assigned ownership, implementation timelines, and measurable outcomes, in accordance with ISO/IEC 27001:2022 Clause 6.1.3.

This plan translates risk register outputs into operationally actionable control improvements and provides traceability from risk to treatment to residual risk decision.

## 3. Scope

This plan applies to all in-scope DTB Nigeria information security risks requiring treatment across:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers treatment activities related to:

- Governance and policy controls
- Technical and operational controls
- Human and process controls
- Supplier and third-party controls
- Resilience and continuity controls
- Regulatory and privacy compliance controls

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded, except for treatment actions involving cross-border interface control at DTB Nigeria boundaries.

## 4. References

1. ISO/IEC 27001:2022 Clause 6.1.3 (Information security risk treatment)
2. ISO/IEC 27001:2022 Clause 8.1 (Operational planning and control)
3. ISO/IEC 27002:2022
4. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
5. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
6. DTB-NG-ISMS-RRG-017 – Risk Register
7. DTB-NG-ISMS-SOA-019 – Statement of Applicability (next document)
8. DTB-NG-ISMS-INF-008 – Information Security Policy
9. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
10. CBN cybersecurity and risk management directives
11. NDPA/NDPC requirements related to security controls

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Risk Treatment | Process of selecting and implementing measures to modify risk |
| Treatment Strategy | Chosen approach to risk: mitigate, avoid, transfer, or accept |
| Treatment Action | Specific planned activity to reduce likelihood/impact of a risk |
| Target Residual Risk | Intended post-treatment risk level |
| Risk Owner | Role accountable for risk outcomes and treatment progress |
| Action Owner | Role accountable for execution of a specific treatment action |
| Due Date | Approved target date for completion of treatment action |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns treatment planning governance and escalates delivery risks |
| ERM (Nigeria) | Maintains risk-to-treatment traceability and progress integrity |
| Risk Owners | Approve treatment strategy and ensure outcomes are achieved |
| Action Owners (ITOPS/SOC/DIGI/COMP/DPO/PROC/HR/Branch Ops) | Implement assigned treatment actions and provide evidence |
| ISMS Programme Manager | Coordinates tracking, dependencies, and reporting cadence |
| Compliance/Legal | Validates legal/regulatory adequacy of treatment actions |
| DPO | Validates privacy protections where personal data risks are involved |
| ISMS Steering Committee | Reviews treatment progress and approves adjustments/escalations |
| CEO (Nigeria) | Approves major resource decisions and escalated acceptance paths |
| Internal Audit | Provides assurance on treatment implementation and effectiveness |

## 7. Policy and Procedure (Treatment Plan)

### 7.1 Treatment Planning Principles

DTB Nigeria shall ensure that risk treatment:

1. Is aligned to approved risk assessment and acceptance criteria.
2. Prioritizes High/Critical residual risks and regulatory-impacting exposures.
3. Assigns clear ownership, deadlines, and measurable success criteria.
4. Includes dependencies, resource requirements, and escalation paths.
5. Is monitored through defined governance reporting cycles.
6. Is evidenced and auditable from planning through closure.

### 7.2 Treatment Strategy Rules

Each risk from the Risk Register shall be assigned one of the following:

- **Mitigate:** implement/enhance controls to reduce risk.
- **Avoid:** discontinue or redesign risky activity.
- **Transfer:** shift components of risk via contractual/insurance mechanisms.
- **Accept:** retain residual risk with formal approval per DTB-NG-ISMS-RAC-013.

For High/Critical risks, mitigation is the expected default unless formally justified otherwise.

### 7.3 Risk-to-Treatment Action Plan Register (Baseline)

**Baseline Date:** 01 July 2026

**Source Risks:** DTB-NG-ISMS-RRG-017 v1.0

| **Treatment ID** | **Linked Risk ID(s)** | **Treatment Objective** | **Key Actions** | **Action Owner** | **Start Date** | **Target Date** | **Priority** | **Success Criteria** | **Target Residual Rating** | **Status** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RTP-001 | RSK-001, RSK-009 | Strengthen IAM and privileged access governance | Automate JML integration, enforce recertification schedule, reduce dormant privileged accounts, implement monthly exception escalation | Head, ITOPS | 01 Jul 2026 | 30 Sep 2026 | High | ≥99% leaver deprovisioning in 24h; ≥98% recertification on time; privileged account reduction plan completed | Medium/Low | In Progress |
| RTP-002 | RSK-002, RSK-013 | Improve vulnerability and secure configuration performance | Implement risk-based patch SLA dashboard, weekly critical vuln review, baseline drift detection, escalation for overdue patches | Head, ITOPS | 01 Jul 2026 | 31 Oct 2026 | High | ≥95% critical vulnerabilities remediated within SLA; monthly baseline compliance ≥95% | Medium | In Progress |
| RTP-003 | RSK-003, RSK-011 | Expand monitoring visibility and detection integrity | Onboard remaining critical log sources, tune SIEM use cases, harden log retention/protection controls, validate forensic readiness | SOC Head | 01 Jul 2026 | 31 Dec 2026 | High | Critical asset log-source coverage ≥97%; MTTD ≤60 mins; log retention meets policy for critical sources | Medium | In Progress |
| RTP-004 | RSK-004, RSK-016 | Improve data protection handling and lifecycle controls | Enforce classification labels in major repositories, strengthen DLP rules, update secure disposal workflow, conduct targeted data handling audits | DPO + Compliance | 01 Jul 2026 | 31 Jan 2027 | High | Labeling compliance ≥95% for sensitive repos; DLP false-negative trend reduced; disposal evidence completeness ≥98% | Medium | In Progress |
| RTP-005 | RSK-005, RSK-018 | Strengthen third-party and concentration risk controls | Complete critical supplier security reassessments, update security clauses, define alternate provider/contingency options for critical services | Procurement Lead | 01 Jul 2026 | 31 Mar 2027 | High | 100% critical suppliers reassessed; 100% critical contracts with required clauses; concentration mitigation roadmap approved | Medium | In Progress |
| RTP-006 | RSK-006, RSK-014 | Improve backup, restoration, and DR readiness | Increase restore testing frequency, expand scenario coverage, execute full-scope DR exercise for critical services, remediate findings | Head, ITOPS | 01 Jul 2026 | 31 Mar 2027 | High | Backup success ≥99.5%; restore success ≥95%; annual DR plan completion 100% with documented lessons | Medium | In Progress |
| RTP-007 | RSK-007, RSK-017 | Reduce malware and social engineering risk | Enhance endpoint hardening, expand phishing simulation campaigns, improve rapid containment playbooks, enforce high-risk user controls | SOC Head + HR Director | 01 Jul 2026 | 30 Nov 2026 | High | Phishing failure rate ≤5%; endpoint control coverage ≥98%; major malware containment SLA achieved | Medium | In Progress |
| RTP-008 | RSK-008 | Strengthen regulatory obligation management | Introduce regulatory change SLA tracker, map obligations to controls/evidence, monthly compliance checkpoint with CISO office | Head, Compliance/Legal | 01 Jul 2026 | 30 Sep 2026 | Medium | ≥98% applicable obligations implemented/evidenced by target cycle | Low/Medium | In Progress |
| RTP-009 | RSK-010 | Improve application security in digital channels | Integrate secure SDLC control gates, enforce pre-release security testing criteria, fix high-risk findings before production release | Head, Digital Banking Technology | 01 Jul 2026 | 31 Dec 2026 | High | 100% major releases pass security gates; no unresolved high findings at go-live without approved exception | Medium | In Progress |
| RTP-010 | RSK-012 | Standardize branch-level security control execution | Branch control checklist harmonization, quarterly compliance walk-throughs, branch evidence quality reviews | Head, Branch Operations | 01 Jul 2026 | 31 Dec 2026 | Medium | 100% branches using standardized checklist; closure of branch control gaps within SLA | Low/Medium | In Progress |
| RTP-011 | RSK-019 | Improve incident playbook coverage and readiness | Expand playbooks for top scenarios (ransomware, identity compromise, data leak), conduct tabletop exercises, update escalation matrices | CISO + SOC Head | 01 Jul 2026 | 31 Oct 2026 | Medium | Playbooks approved for all top scenarios; 2+ exercises completed with action closure tracking | Low/Medium | In Progress |
| RTP-012 | RSK-020 | Raise workforce security maturity | Role-based awareness tracks, executive and high-risk user briefings, monthly behavior metrics reporting | HR Director + CISO | 01 Jul 2026 | 31 Dec 2026 | Medium | Awareness completion ≥99%; repeat policy violations reduced quarter-on-quarter | Low/Medium | In Progress |

### 7.4 Treatment Dependency and Sequencing Notes

1. RTP-001 (IAM improvements) supports risk reduction in RTP-003 and RTP-007 by improving identity telemetry and containment quality.
2. RTP-002 (vulnerability/configuration) is prerequisite to sustained improvement in RTP-009 (application and platform security).
3. RTP-004 (classification/handling) and RTP-008 (regulatory management) are interdependent for NDPA/NDPC and CBN evidence assurance.
4. RTP-006 (resilience) depends on accurate asset criticality and service mapping from Asset Inventory and BIA-aligned continuity planning.

### 7.5 Milestone Governance

Each treatment action with duration > 60 days must define interim milestones.

Minimum milestone structure:

- Design/Planning Complete
- Implementation Started
- Control Validation Complete
- Evidence Pack Complete
- Residual Risk Reassessment Complete

Missed milestones for High-priority actions trigger escalation to ISMS Steering Committee.

### 7.6 Treatment Status Definitions

| **Status** | **Meaning** |
| --- | --- |
| Planned | Action approved but execution not started |
| In Progress | Implementation ongoing |
| Delayed | Milestone or target date at risk or missed |
| Implemented | Action completed; awaiting effectiveness validation |
| Validated | Control effectiveness verified and residual risk rescored |
| Closed | Treatment fully complete and documented |

### 7.7 Success Measurement and KPI Linkage

Treatment effectiveness is measured through linked KPIs from DTB-NG-ISMS-OBJ-009, including:

- Critical vulnerability SLA compliance
- Access recertification completion rates
- MTTD/MTTR improvements
- Monitoring coverage of critical assets
- Backup/restore success rates
- Supplier assurance completion
- Awareness completion and phishing resilience

Each action owner must provide evidence supporting KPI contribution.

### 7.8 Risk Reassessment and Closure Rules

1. On completion of treatment actions, linked risks must be reassessed using DTB-NG-ISMS-RAM-012.
2. Residual risk downgrade must be supported by objective evidence.
3. If target residual rating is not achieved, additional treatment or formal acceptance route is required.
4. Treatment closure requires:
    - action completion evidence,
    - control validation result,
    - updated risk score,
    - owner and governance approval.

### 7.9 Exceptions and Acceptance Linkage

1. If treatment cannot be completed by target date, risk owner must:
- submit delay justification,
- propose interim compensating controls,
- request revised target date or acceptance per DTB-NG-ISMS-RAC-013.
1. High/Critical treatment delays require immediate governance escalation.
2. Temporary acceptance must not replace treatment without formal decision records.

### 7.10 Reporting and Escalation

#### 7.10.1 Reporting Cadence

- Weekly: internal action-owner progress updates for High-priority actions
- Monthly: consolidated RTP dashboard to ISMS Steering Committee
- Quarterly: executive summary for CEO and oversight reporting inputs

#### 7.10.2 Escalation Triggers

- High-priority action delayed > 10 business days
- Critical dependency unresolved > 15 business days
- Budget/resource constraints impacting regulatory-risk treatment
- Residual risk remains High after planned treatment completion

Escalations must include impact analysis and revised action proposal.

### 7.11 Assumptions Applied

1. Treatment action owners have operational authority and capacity to execute assigned actions.
2. Budget and procurement lead times are managed through governance escalation where needed.
3. Existing risk register entries are accurate as treatment baseline inputs.
4. Detailed technical workplans may exist in operational trackers but must remain traceable to this master RTP.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved Risk Treatment Plan | CISO Office / ERM | Minimum 6 years |
| Action Tracker and Milestone Updates | ISMS-PM / Action Owners | Minimum 6 years |
| Treatment Evidence Packs | Control Owners / Action Owners | Minimum 6 years |
| Delay/Exception/Escalation Records | CISO Office | Minimum 6 years |
| Residual Risk Reassessment Records | ERM / Risk Owners | Minimum 6 years |
| Treatment Closure Approvals | CISO / ERM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-RRG-017 – Risk Register
2. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
3. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
4. DTB-NG-ISMS-SOA-019 – Statement of Applicability
5. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
6. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
7. DTB-NG-ISMS-MRV-058 – Management Review Procedure
8. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
9. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure

## 10. ISO Clause References

- Clause 6.1.3 Information security risk treatment
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.3 Management review
- Clause 10.1 Continual improvement
- Clause 10.2 Nonconformity and corrective action

## 11. Annex A References

- 5.1 Policies for information security
- 5.2 Information security roles and responsibilities
- 5.7 Threat intelligence
- 5.8 Information security in project management
- 5.9 Inventory of information and other associated assets
- 5.15 Access control
- 5.16 Identity management
- 5.18 Access rights
- 5.19 Information security in supplier relationships
- 5.20 Addressing information security within supplier agreements
- 5.24 Information security incident management planning and preparation
- 5.26 Response to information security incidents
- 5.27 Learning from information security incidents
- 5.30 ICT readiness for business continuity
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.34 Privacy and protection of PII
- 5.36 Compliance with policies and standards for information security
- 8.8 Management of technical vulnerabilities
- 8.13 Information backup
- 8.15 Logging
- 8.16 Monitoring activities
- 8.24 Use of cryptography

## 12. Review Frequency

This plan shall be reviewed:

- Monthly for progress and milestone performance,
- Quarterly for formal re-baselining,
- Immediately upon major incident, regulatory trigger, or material risk posture change.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ERM / ISMS Programme Manager | Initial treatment action planning draft |
| 0.9 | 30 June 2026 | CISO / ERM / Action Owners | Baseline actions, owners, and deadlines validated |
| 1.0 | 01 July 2026 | CISO / ERM | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Emeka R. Okonkwo | Enterprise Risk Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Statement of Applicability (SoA)

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Statement of Applicability (SoA) |
| Document ID | DTB-NG-ISMS-SOA-019 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | Chief Information Security Officer (CISO), Nigeria |
| Co-Owner | Enterprise Risk Manager (ERM), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 October 2026 (Quarterly Review Cycle) |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this Statement of Applicability (SoA) is to define the set of information security controls selected by DTB Nigeria for its ISMS, including:

- Control applicability decisions,
- Justification for inclusion/exclusion,
- Implementation status,
- Reference to governing documents and control owners.

This document fulfills ISO/IEC 27001:2022 Clause 6.1.3(d) requirement to produce a statement of applicable controls and justification.

## 3. Scope

This SoA applies to DTB Nigeria’s ISMS certification scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers controls applicable to in-scope governance, people, process, technology, and third-party interfaces supporting DTB Nigeria banking services.

Out-of-scope entities (London, Frankfurt, Paris, New York) are excluded as internal scope units; however, controls relevant to interfaces with these entities are included where risk or contractual obligations require.

## 4. References

1. ISO/IEC 27001:2022 Clause 6.1.3
2. ISO/IEC 27002:2022 (Control set and guidance)
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
5. DTB-NG-ISMS-RRG-017 – Risk Register
6. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
7. DTB-NG-ISMS-INF-008 – Information Security Policy
8. DTB-NG-ISMS-AIN-014 – Asset Inventory
9. DTB-NG-ISMS-ICS-015 – Information Classification Scheme
10. Applicable legal/regulatory obligations (CBN, NDPA/NDPC, Cybercrime legal obligations)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Applicable | Control selected for implementation due to risk, legal, regulatory, contractual, or business requirements |
| Not Applicable | Control excluded with documented justification based on scope and risk context |
| Implementation Status | Current implementation state (Implemented, Partially Implemented, Planned) |
| Control Owner | Role accountable for control implementation and effectiveness |
| Justification | Documented rationale for applicability decision |
| Evidence Reference | Document, record, or operational artifact demonstrating control operation |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Owns SoA and control applicability decisions |
| ERM (Nigeria) | Ensures traceability between risk treatment and selected controls |
| Control Owners | Implement and operate assigned controls; provide evidence |
| Compliance/Legal | Confirms legal/regulatory control requirements |
| DPO | Confirms privacy-related control requirements |
| ISMS Programme Manager | Maintains SoA versioning and review records |
| Internal Audit | Tests design and effectiveness of selected controls |
| CEO (Nigeria) | Approves SoA as part of ISMS governance and certification readiness |

## 7. Method for Determining Applicability

DTB Nigeria determines control applicability using:

1. Risk assessment results (DTB-NG-ISMS-RAM-012; Risk Register)
2. Risk treatment requirements (DTB-NG-ISMS-RTP-018)
3. Legal and regulatory obligations (CBN, NDPA/NDPC, Cybercrime obligations)
4. Contractual obligations (customers, counterparties, suppliers)
5. Business continuity and operational resilience needs
6. Information classification and asset criticality requirements

Controls are excluded only where demonstrably irrelevant to scope, architecture, or operating model, and where exclusion does not create unaddressed risk or compliance gaps.

## 8. Control Applicability Register (ISO/IEC 27001:2022 Annex A)

**Status Legend:**

- **Implemented** = control designed and operating with evidence
- **Partially Implemented** = control exists but maturity/evidence gaps remain
- **Planned** = control selected with approved implementation action in RTP
- **N/A** = not applicable (with justification)

### 8.1 Organizational Controls (A.5)

| **Control ID** | **Control Name** | **Applicability** | **Justification** | **Implementation Status** | **Control Owner** | **Key Reference(s)** |
| --- | --- | --- | --- | --- | --- | --- |
| A.5.1 | Policies for information security | Applicable | Foundational ISMS requirement and governance baseline | Implemented | CISO | INF-008 |
| A.5.2 | Information security roles and responsibilities | Applicable | Required for accountability and segregation of duties | Implemented | CISO / HR | ORG-006, RRC-007 |
| A.5.3 | Segregation of duties | Applicable | Banking fraud and privileged misuse risk control | Partially Implemented | ITOPS / CISO | RRG-017, RTP-001 |
| A.5.4 | Management responsibilities | Applicable | Ensures leadership direction and enforcement | Implemented | CEO / CISO | GOV-010, INF-008 |
| A.5.5 | Contact with authorities | Applicable | Required for regulatory and incident escalation obligations | Implemented | Compliance/Legal | COM-011 |
| A.5.6 | Contact with special interest groups | Applicable | Supports threat awareness and sector intelligence | Partially Implemented | SOC | RTP-003 |
| A.5.7 | Threat intelligence | Applicable | High cyber threat environment for Nigerian banking sector | Partially Implemented | SOC | RRG-017, RTP-003 |
| A.5.8 | Information security in project management | Applicable | Needed for secure change and transformation initiatives | Partially Implemented | PMO / CISO | RTP-009 |
| A.5.9 | Inventory of information and other associated assets | Applicable | Mandatory for risk and control coverage | Implemented | CISO / ITOPS | AIN-014 |
| A.5.10 | Acceptable use of information and other associated assets | Applicable | User behavior control to reduce misuse risk | Planned | CISO / HR | AUP-026 (planned) |
| A.5.11 | Return of assets | Applicable | Employee/contractor offboarding risk control | Partially Implemented | HR / ITOPS | RTP-001 |
| A.5.12 | Classification of information | Applicable | Required for proportional protection | Implemented | CISO / DPO | ICS-015, ACP-016 |
| A.5.13 | Labelling of information | Applicable | Required to operationalize classification | Partially Implemented | Information Owners / ITOPS | RTP-004 |
| A.5.14 | Information transfer | Applicable | External/internal transfer risks incl. cross-border interfaces | Partially Implemented | CISO / Compliance | COM-011, ICS-015 |
| A.5.15 | Access control | Applicable | Core preventive control for confidentiality/integrity | Partially Implemented | ITOPS | RTP-001 |
| A.5.16 | Identity management | Applicable | Needed for lifecycle identity governance | Partially Implemented | ITOPS | RTP-001 |
| A.5.17 | Authentication information | Applicable | Credential compromise is key threat vector | Partially Implemented | ITOPS / SOC | RTP-001, RTP-007 |
| A.5.18 | Access rights | Applicable | Privileged/user access governance requirement | Partially Implemented | ITOPS | RTP-001 |
| A.5.19 | Information security in supplier relationships | Applicable | Significant supplier dependency in operations | Partially Implemented | Procurement / CISO | RTP-005 |
| A.5.20 | Addressing information security within supplier agreements | Applicable | Contractual enforcement of supplier controls required | Partially Implemented | Procurement / Compliance | RTP-005 |
| A.5.21 | Managing information security in the ICT supply chain | Applicable | Technology supply-chain risk relevant for critical services | Planned | Procurement / ITOPS | RTP-005 |
| A.5.22 | Monitoring, review and change management of supplier services | Applicable | Ongoing supplier assurance needed for resilience | Partially Implemented | Procurement | RTP-005 |
| A.5.23 | Information security for use of cloud services | Applicable | Azure/M365/Entra are in scope | Partially Implemented | ITOPS | RRG-017, RTP-015 (via RTP-002/003 scope) |
| A.5.24 | Information security incident management planning and preparation | Applicable | Essential for response readiness | Partially Implemented | CISO / SOC | RTP-011 |
| A.5.25 | Assessment and decision on information security events | Applicable | SOC triage/escalation requirement | Implemented | SOC | COM-011, RTP-011 |
| A.5.26 | Response to information security incidents | Applicable | Mandatory operational capability | Partially Implemented | SOC / ITOPS | RTP-011 |
| A.5.27 | Learning from information security incidents | Applicable | Required for continual improvement | Partially Implemented | CISO / SOC | RTP-011 |
| A.5.28 | Collection of evidence | Applicable | Legal and forensic readiness obligations | Partially Implemented | SOC / Compliance | RTP-003, RTP-011 |
| A.5.29 | Information security during disruption | Applicable | Continuity of critical banking services required | Partially Implemented | ITOPS / BCM | RTP-006 |
| A.5.30 | ICT readiness for business continuity | Applicable | DR/backup readiness required by risk/regulation | Partially Implemented | ITOPS | RTP-006 |
| A.5.31 | Legal, statutory, regulatory and contractual requirements | Applicable | Mandatory compliance obligations | Implemented | Compliance/Legal | COM-011, RTP-008 |
| A.5.32 | Intellectual property rights | Applicable | Legal protection obligations apply | Planned | Compliance/Legal | Legal controls roadmap |
| A.5.33 | Protection of records | Applicable | Regulatory/audit evidence and customer records protection | Partially Implemented | Compliance / ITOPS | RTP-004 |
| A.5.34 | Privacy and protection of PII | Applicable | NDPA/NDPC obligations apply | Partially Implemented | DPO | RTP-004, RTP-008 |
| A.5.35 | Independent review of information security | Applicable | Needed for objective assurance | Implemented | Internal Audit | IAP-056 |
| A.5.36 | Compliance with policies and standards for information security | Applicable | Control monitoring and enforcement requirement | Partially Implemented | CISO / Internal Audit | RTP-009, IAP-056 |
| A.5.37 | Documented operating procedures | Applicable | Procedure-driven operations required for consistency | Partially Implemented | ISMS-PM / Control Owners | ISMS roadmap docs |

### 8.2 People Controls (A.6)

| **Control ID** | **Control Name** | **Applicability** | **Justification** | **Implementation Status** | **Control Owner** | **Key Reference(s)** |
| --- | --- | --- | --- | --- | --- | --- |
| A.6.1 | Screening | Applicable | Workforce trust and insider risk mitigation | Partially Implemented | HR | HR process controls |
| A.6.2 | Terms and conditions of employment | Applicable | Security obligations in employment terms | Implemented | HR / Legal | HR policy set |
| A.6.3 | Information security awareness, education and training | Applicable | Human-factor risk is significant | Partially Implemented | HR / CISO | RTP-012 |
| A.6.4 | Disciplinary process | Applicable | Policy enforcement mechanism required | Implemented | HR / Legal | INF-008 |
| A.6.5 | Responsibilities after termination or change of employment | Applicable | Offboarding and role-change risk mitigation | Partially Implemented | HR / ITOPS | RTP-001 |
| A.6.6 | Confidentiality or non-disclosure agreements | Applicable | Protection of sensitive information and contractual assurance | Implemented | HR / Legal / Procurement | Contract templates |
| A.6.7 | Remote working | Applicable | Hybrid/remote access risk control | Partially Implemented | ITOPS / HR | VPN and endpoint controls |
| A.6.8 | Information security event reporting | Applicable | Early incident reporting required | Implemented | SOC / CISO | COM-011, IR process |

### 8.3 Physical Controls (A.7)

| **Control ID** | **Control Name** | **Applicability** | **Justification** | **Implementation Status** | **Control Owner** | **Key Reference(s)** |
| --- | --- | --- | --- | --- | --- | --- |
| A.7.1 | Physical security perimeters | Applicable | DC/office perimeter control for asset protection | Implemented | Facilities / ITOPS | Physical security procedures |
| A.7.2 | Physical entry controls | Applicable | Unauthorized entry risk mitigation | Partially Implemented | Facilities / Branch Ops | Branch control improvement (RTP-010) |
| A.7.3 | Securing offices, rooms and facilities | Applicable | Protection of processing environments and records | Partially Implemented | Facilities / Branch Ops | RTP-010 |
| A.7.4 | Physical security monitoring | Applicable | Surveillance and incident support | Partially Implemented | Facilities / SOC | Physical monitoring logs |
| A.7.5 | Protecting against physical and environmental threats | Applicable | Fire/flood/power and environmental disruption risks | Partially Implemented | ITOPS / Facilities | RTP-006 |
| A.7.6 | Working in secure areas | Applicable | High-sensitivity work area control | Planned | Facilities / CISO | Secure area guidance roadmap |
| A.7.7 | Clear desk and clear screen | Applicable | Prevent unauthorized visual/data exposure | Planned | CISO / HR | Awareness and acceptable use roadmap |
| A.7.8 | Equipment siting and protection | Applicable | Asset protection from damage/tampering | Implemented | ITOPS | Asset standards |
| A.7.9 | Security of assets off-premises | Applicable | Endpoint/laptop mobility risk | Partially Implemented | ITOPS | Endpoint controls, RTP-007 |
| A.7.10 | Storage media | Applicable | Data leakage risk via media | Planned | ITOPS / Compliance | MHD-051 (planned) |
| A.7.11 | Supporting utilities | Applicable | Service availability dependency | Partially Implemented | ITOPS / Facilities | RTP-006 |
| A.7.12 | Cabling security | Applicable | Network/communication integrity | Implemented | ITOPS | Network standards |
| A.7.13 | Equipment maintenance | Applicable | Operational reliability and security integrity | Implemented | ITOPS | Maintenance procedures |
| A.7.14 | Secure disposal or re-use of equipment | Applicable | Data remanence and leakage prevention | Partially Implemented | ITOPS / Compliance | RTP-004, disposal policy roadmap |

### 8.4 Technological Controls (A.8)

| **Control ID** | **Control Name** | **Applicability** | **Justification** | **Implementation Status** | **Control Owner** | **Key Reference(s)** |
| --- | --- | --- | --- | --- | --- | --- |
| A.8.1 | User endpoint devices | Applicable | Endpoint attack surface is high | Partially Implemented | ITOPS / SOC | RTP-007 |
| A.8.2 | Privileged access rights | Applicable | High impact of privileged misuse | Partially Implemented | ITOPS | RTP-001 |
| A.8.3 | Information access restriction | Applicable | Enforces least privilege and segregation | Partially Implemented | ITOPS | RTP-001 |
| A.8.4 | Access to source code | Applicable | Application integrity and insider control | Partially Implemented | DIGI / ITOPS | RTP-009 |
| A.8.5 | Secure authentication | Applicable | Credential theft and account takeover risks | Partially Implemented | ITOPS / DIGI | RTP-001, RTP-009 |
| A.8.6 | Capacity management | Applicable | Availability management for critical services | Partially Implemented | ITOPS | RTP-006 |
| A.8.7 | Protection against malware | Applicable | High malware/ransomware threat | Partially Implemented | SOC | RTP-007 |
| A.8.8 | Management of technical vulnerabilities | Applicable | Direct linkage to major risk items | Partially Implemented | ITOPS / SOC | RTP-002 |
| A.8.9 | Configuration management | Applicable | Baseline drift and hardening risk | Partially Implemented | ITOPS | RTP-002 |
| A.8.10 | Information deletion | Applicable | Data lifecycle and privacy compliance | Partially Implemented | Compliance / ITOPS | RTP-004 |
| A.8.11 | Data masking | Applicable | Sensitive data handling in non-prod/reporting contexts | Planned | DPO / DIGI | Privacy roadmap |
| A.8.12 | Data leakage prevention | Applicable | Prevent unauthorized exfiltration/disclosure | Partially Implemented | SOC / ITOPS | RTP-004 |
| A.8.13 | Information backup | Applicable | Critical availability and recovery dependency | Partially Implemented | ITOPS | RTP-006 |
| A.8.14 | Redundancy of information processing facilities | Applicable | Availability and resilience obligations | Partially Implemented | ITOPS | RTP-006 |
| A.8.15 | Logging | Applicable | Detection, forensic, and compliance needs | Partially Implemented | SOC | RTP-003 |
| A.8.16 | Monitoring activities | Applicable | Threat detection and response capability | Partially Implemented | SOC | RTP-003 |
| A.8.17 | Clock synchronization | Applicable | Event correlation and forensic integrity | Implemented | ITOPS / SOC | Technical standards |
| A.8.18 | Use of privileged utility programs | Applicable | Prevent abuse of high-power tools | Planned | ITOPS | PAM roadmap |
| A.8.19 | Installation of software on operational systems | Applicable | Control unauthorized software risk | Partially Implemented | ITOPS | Endpoint/server controls |
| A.8.20 | Networks security | Applicable | Core enterprise and branch connectivity security | Partially Implemented | ITOPS | RTP-002, network controls |
| A.8.21 | Security of network services | Applicable | Supplier/internal service security assurance | Partially Implemented | ITOPS / Procurement | RTP-005 |
| A.8.22 | Segregation of networks | Applicable | Lateral movement and containment control | Partially Implemented | ITOPS | RTP-007 |
| A.8.23 | Web filtering | Applicable | User-borne threat reduction | Planned | ITOPS / SOC | Security stack roadmap |
| A.8.24 | Use of cryptography | Applicable | Data protection in transit/at rest | Partially Implemented | ITOPS / CISO | CRY-031 (planned), RTP-004 |
| A.8.25 | Secure development life cycle | Applicable | Application risk reduction in digital banking | Partially Implemented | DIGI | RTP-009 |
| A.8.26 | Application security requirements | Applicable | Secure design baseline for business apps | Partially Implemented | DIGI | RTP-009 |
| A.8.27 | Secure system architecture and engineering principles | Applicable | Secure-by-design requirement | Partially Implemented | ITOPS / DIGI | Architecture governance |
| A.8.28 | Secure coding | Applicable | Reduce exploitable coding flaws | Partially Implemented | DIGI | RTP-009 |
| A.8.29 | Security testing in development and acceptance | Applicable | Release assurance for digital channels | Partially Implemented | DIGI | RTP-009 |
| A.8.30 | Outsourced development | Applicable | Third-party development risk governance | Planned | DIGI / Procurement | Supplier controls roadmap |
| A.8.31 | Separation of development, test and production environments | Applicable | Prevent integrity/confidentiality compromise | Partially Implemented | DIGI / ITOPS | RTP-009 |
| A.8.32 | Change management | Applicable | Controlled change is essential for stable security posture | Partially Implemented | ITOPS / DIGI | Change governance, RTP-009 |
| A.8.33 | Test information | Applicable | Protect sensitive data in test environments | Planned | DIGI / DPO | Data masking/testing roadmap |
| A.8.34 | Protection of information systems during audit testing | Applicable | Preserve system integrity during assurance activities | Implemented | ITOPS / IA | Audit procedure alignment |

## 9. Controls Marked Not Applicable (N/A)

At this baseline stage, DTB Nigeria has **not excluded** any Annex A control as universally not applicable across scope.

Where maturity is low or operating model specifics are evolving, controls are marked as **Planned** or **Partially Implemented** rather than N/A to maintain risk treatment traceability.

If future reviews determine any control is not applicable, justification shall be documented here with explicit scope/risk rationale and approval.

## 10. SoA Summary Dashboard

| **Category** | **Total Controls** | **Applicable** | **Not Applicable** | **Implemented** | **Partially Implemented** | **Planned** |
| --- | --- | --- | --- | --- | --- | --- |
| A.5 Organizational | 37 | 37 | 0 | 8 | 23 | 6 |
| A.6 People | 8 | 8 | 0 | 4 | 4 | 0 |
| A.7 Physical | 14 | 14 | 0 | 4 | 7 | 3 |
| A.8 Technological | 34 | 34 | 0 | 2 | 24 | 8 |
| **Total** | **93** | **93** | **0** | **18** | **58** | **17** |

Implementation maturity will be progressively improved through RTP actions and tracked via governance dashboards.

## 11. Implementation Priorities (Next 2 Quarters)

Top priority controls targeted for maturity uplift:

1. A.5.15 / A.5.16 / A.5.18 (Access and identity controls)
2. A.8.8 / A.8.9 (Vulnerability and configuration management)
3. A.8.15 / A.8.16 (Logging and monitoring coverage)
4. A.5.19 / A.5.20 / A.5.22 (Supplier control framework)
5. A.5.24–A.5.28 (Incident readiness and evidence controls)
6. A.5.29 / A.5.30 / A.8.13 / A.8.14 (Resilience and continuity)
7. A.8.25–A.8.33 (Secure SDLC and application assurance)

## 12. SoA Review and Change Rules

1. SoA shall be reviewed at least quarterly and after major risk or scope changes.
2. Any change to applicability decision must reference:
    - updated risk assessment/treatment evidence,
    - legal/regulatory analysis where relevant,
    - control owner recommendation.
3. SoA version updates require CISO approval and controlled document update.
4. Significant applicability changes shall be reported in management review.

## 13. Assumptions Applied

1. Baseline reflects current in-scope DTB Nigeria operating environment as of 01 July 2026.
2. “Partially Implemented” and “Planned” controls are tracked through approved Risk Treatment Plan actions.
3. Supporting standards/procedures referenced as planned documents will be issued in subsequent phases and mapped back to SoA entries.

## 14. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Approved SoA | CISO Office / ISMS-PM | Minimum 6 years |
| SoA Change Log | ISMS-PM | Minimum 6 years |
| Applicability Decision Evidence | ERM / Control Owners | Minimum 6 years |
| Quarterly SoA Review Minutes | ISMS Steering Committee Secretariat | Minimum 6 years |
| Implementation Status Evidence Pack | Control Owners | Minimum 6 years |

## 15. Related Documents

1. DTB-NG-ISMS-RRG-017 – Risk Register
2. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RAC-013 – Risk Acceptance Criteria
5. DTB-NG-ISMS-INF-008 – Information Security Policy
6. DTB-NG-ISMS-OBJ-009 – Information Security Objectives
7. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
8. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
9. DTB-NG-ISMS-MRV-058 – Management Review Procedure

## 16. ISO Clause References

- Clause 6.1.3 Information security risk treatment
- Clause 7.5 Documented information
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.3 Management review
- Clause 10.1 Continual improvement

## 17. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | CISO Office / ERM | Initial applicability mapping draft |
| 0.9 | 30 June 2026 | CISO / ERM / Control Owners | Applicability and status calibration |
| 1.0 | 01 July 2026 | CISO / ERM | First approved issue |

## 18. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Emeka R. Okonkwo | Enterprise Risk Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |