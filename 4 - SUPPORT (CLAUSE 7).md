# 4 - SUPPORT (CLAUSE 7)

# Document Control Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Document Control Procedure |
| Document ID | DTB-NG-ISMS-DCP-020 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the process for creation, review, approval, issuance, distribution, maintenance, revision, retention, retrieval, archival, and withdrawal of documented information required by the DTB Nigeria ISMS.

This procedure ensures that ISMS documents are:

- accurate and current,
- appropriately approved,
- protected from unauthorized change,
- available where needed,
- traceable for audit and compliance purposes,

in accordance with ISO/IEC 27001:2022 Clause 7.5.

## 3. Scope

This procedure applies to all ISMS documented information within DTB Nigeria certification scope, including:

- Policies, standards, procedures, guidelines, plans, registers, and templates
- Mandatory ISO records and operational evidence documents
- Controlled forms used in ISMS process execution
- Internal and external-origin documents relied on by the ISMS

In-scope locations:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from internal governance under this procedure.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.5 (Documented information)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-INF-008 – Information Security Policy
4. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
5. DTB-NG-ISMS-COM-011 – Communication Plan
6. DTB-NG-ISMS-RCP-021 – Record Control Procedure (next document)
7. DTB-NG-ISMS-SOA-019 – Statement of Applicability
8. DTB Records Retention and Legal Hold requirements (Nigeria operations)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Documented Information | Information required to be controlled and maintained by the ISMS, and the medium on which it is contained |
| Controlled Document | ISMS document subject to formal approval, versioning, and change control |
| Uncontrolled Copy | Copy distributed for reference only and not guaranteed to reflect latest approved version |
| Document Owner | Role accountable for content accuracy and operational suitability |
| Control Owner | Role accountable for governance and compliance of document control process |
| Master Document Register (MDR) | Authoritative index of all controlled ISMS documents and their status |
| Obsolete Document | Superseded/withdrawn document no longer valid for operational use |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| Managing Director/CEO (Nigeria) | Final approval for top-tier governance documents where required |
| CISO (Nigeria) | Governance owner of ISMS documentation framework |
| ISMS Programme Manager | Operates document control process and maintains Master Document Register |
| Document Owner | Drafts/updates documents; ensures technical and operational accuracy |
| Reviewers (SMEs) | Provide cross-functional review and validation comments |
| Approvers | Provide formal authorization before issue/re-issue |
| Compliance/Legal | Reviews documents for regulatory/legal alignment as required |
| DPO | Reviews privacy-impacting documents for NDPA/NDPC alignment |
| Internal Audit | Assesses effectiveness of document control process during audits |
| All Staff/Users | Use current approved versions and follow handling/classification requirements |

## 7. Procedure

### 7.1 Document Lifecycle Overview

DTB Nigeria controls ISMS documents through the following lifecycle stages:

1. Document request/initiation
2. Drafting
3. Review
4. Approval
5. Issuance and communication
6. Periodic review and revision
7. Obsolescence/withdrawal
8. Archival and retention

No document is considered effective until approved and published through controlled channels.

### 7.2 Document Classification and Hierarchy

#### 7.2.1 Document Hierarchy

| **Level** | **Document Type** | **Typical Examples** |
| --- | --- | --- |
| Level 1 | Governance and Direction | Policy, Charter, Scope, SoA |
| Level 2 | Process and Control Procedures | Document control, risk, audit, incident response procedures |
| Level 3 | Standards and Guidelines | Secure configuration standards, technical hardening guides |
| Level 4 | Operational Records/Forms/Registers | Risk register, treatment plan, audit logs, meeting minutes |

#### 7.2.2 Document Sensitivity Classification

All ISMS documents shall be classified at minimum as **Internal – Confidential**, unless explicitly approved otherwise.

### 7.3 Document Identification and Numbering Standard

Each controlled document shall include a unique identifier using this format:

DTB-NG-ISMS-[DOC-TYPE]-[NNN]

Examples:

- DTB-NG-ISMS-INF-008
- DTB-NG-ISMS-RAM-012
- DTB-NG-ISMS-DCP-020

Mandatory metadata in each document:

1. Title
2. Document ID
3. Version
4. Classification
5. Owner
6. Approver
7. Effective date
8. Review date
9. Version history
10. Approval section/sign-off

### 7.4 Drafting and Review Process

1. Document Owner initiates draft based on approved roadmap, regulatory trigger, audit finding, or change request.
2. Draft is prepared using approved template.
3. Required reviewers are assigned based on content domain, including:
    - CISO (security governance relevance),
    - Compliance/Legal (regulatory/legal impact),
    - DPO (privacy impact),
    - Technical/operational SMEs (implementation accuracy).
4. Reviewer comments are consolidated and resolved before approval submission.
5. Review evidence (comments, tracked changes, decision notes) must be retained.

### 7.5 Approval Workflow

Approval authority is determined by document criticality:

| **Document Category** | **Minimum Approval Requirement** |
| --- | --- |
| ISMS Policy / Scope / SoA / Governance Core Docs | CISO + CEO (and Board oversight where applicable) |
| Core ISMS Procedures | CISO + relevant functional owner |
| Operational Standards / Guidelines | Functional owner + CISO delegate |
| Forms / Templates | ISMS Programme Manager + process owner |

Approval must be explicitly recorded (digital workflow, signed approval page, or controlled approval log).

### 7.6 Issuance and Distribution

1. Only approved documents are published to the controlled ISMS repository.
2. Master Document Register is updated at issuance.
3. Communication of new/revised documents follows DTB-NG-ISMS-COM-011.
4. Where mandatory acknowledgment is required, completion evidence must be tracked.
5. Printed copies are discouraged; where needed, they must be marked:
- “Controlled Copy” (if managed), or
- “Uncontrolled if Printed”.

### 7.7 Master Document Register (MDR) Requirements

The ISMS Programme Manager shall maintain MDR with at least:

- Document ID
- Title
- Version
- Owner
- Approver
- Effective date
- Next review date
- Status (Draft/Active/Obsolete)
- Repository location/link
- Last change summary

MDR is the single source of truth for document status.

### 7.8 Change Control and Versioning Rules

#### 7.8.1 Versioning Convention

| **Change Type** | **Version Example** | **Criteria** |
| --- | --- | --- |
| Major | 1.0 → 2.0 | Significant content, scope, control, or governance changes |
| Minor | 1.0 → 1.1 | Limited updates not materially changing control intent |
| Editorial | 1.1 → 1.2 | Typographic/format corrections with no control impact |

#### 7.8.2 Change Rules

1. All changes must be logged in Version History section.
2. Major changes require full review and re-approval cycle.
3. Minor/editorial changes require owner validation and proportionate approval.
4. Superseded versions must be archived and removed from active use areas.

### 7.9 Periodic Review Requirements

1. All controlled ISMS documents must be reviewed at least annually unless shorter interval is specified.
2. Early review is mandatory on:
    - regulatory/legal changes,
    - major incidents,
    - audit findings indicating document weakness,
    - material process/technology changes.
3. If no change is needed, document owner records “reviewed-no-change” evidence.

### 7.10 Obsolete Document Withdrawal and Archival

1. When superseded/withdrawn, documents are marked **Obsolete** in MDR.
2. Obsolete documents must be removed from active repositories/workspaces.
3. Archived versions are retained in secure archive with controlled access.
4. Obsolete documents shall be clearly watermarked/labeled to prevent unintended use.
5. Retention/disposal follows DTB-NG-ISMS-RCP-021 and legal hold rules.

### 7.11 External-Origin Documents

External documents (e.g., regulations, standards, contractual templates) used by ISMS must be controlled by:

1. Source identification and ownership assignment,
2. Version/date tracking,
3. Relevance and applicability review,
4. Access and distribution controls.

Outdated external references must be replaced or flagged with action owner and timeline.

### 7.12 Access and Protection Controls

1. ISMS repositories shall enforce role-based access.
2. Editing rights limited to authorized owners/administrators.
3. Approval records protected from unauthorized modification.
4. Backup and recovery controls shall apply to document repositories.
5. Document integrity checks should be performed periodically for critical records.

### 7.13 Nonconformities and Corrective Actions

Any document control breach (e.g., use of obsolete version, missing approval, uncontrolled modification) shall be:

1. logged as nonconformity/deviation,
2. risk-assessed for impact,
3. corrected with containment actions,
4. analyzed for root cause where material/recurrent,
5. tracked to closure under corrective action process.

### 7.14 Monitoring and KPI Indicators

Document control effectiveness is monitored through:

- % of active documents reviewed by due date
- % of documents with complete metadata
- number of obsolete documents found in active use
- average approval cycle turnaround time
- number of document control nonconformities per quarter

Results are reported through ISMS governance forums.

### 7.15 Assumptions Applied

1. DTB Nigeria maintains a central controlled repository for ISMS documentation.
2. Digital approval workflows are available and auditable.
3. Document owners have delegated authority and functional support for timely updates.
4. Supporting record retention controls are governed by DTB-NG-ISMS-RCP-021.

## 8. Records Generated

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Master Document Register (MDR) | ISMS Programme Manager | Minimum 6 years |
| Draft Review Comment Logs | Document Owner / ISMS-PM | Minimum 6 years |
| Approval Records (digital/sign-off) | ISMS-PM / Document Owner | Minimum 6 years |
| Document Change Logs / Version Histories | Document Owner | Minimum 6 years |
| Obsolete Document Archive Index | ISMS-PM | Minimum 6 years |
| Review Due-Date Tracking Reports | ISMS-PM | Minimum 6 years |
| Document Control Nonconformity Logs | CISO Office / ISMS-PM | Minimum 6 years |

## 9. Related Documents

1. DTB-NG-ISMS-RCP-021 – Record Control Procedure
2. DTB-NG-ISMS-COM-011 – Communication Plan
3. DTB-NG-ISMS-GOV-010 – ISMS Governance Structure
4. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
5. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
6. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
7. DTB-NG-ISMS-MRV-058 – Management Review Procedure

## 10. ISO Clause References

- Clause 7.5 Documented information
- Clause 7.4 Communication
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.2 Internal audit
- Clause 10.2 Nonconformity and corrective action

## 11. Annex A References

- 5.1 Policies for information security
- 5.2 Information security roles and responsibilities
- 5.33 Protection of records
- 5.36 Compliance with policies and standards for information security
- 5.37 Documented operating procedures
- 8.15 Logging
- 8.16 Monitoring activities

## 12. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon major ISMS structure/process changes, audit findings, regulatory updates, or repository/tooling changes affecting document governance.

## 13. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / Compliance / DPO | Updated approval workflow, MDR requirements, and control rules |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 14. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Record Control Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Record Control Procedure |
| Document ID | DTB-NG-ISMS-RCP-021 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define requirements for identification, creation, collection, indexing, storage, protection, retrieval, retention, disposition, and disposal of ISMS records to ensure their integrity, confidentiality, availability, and evidential value.

This procedure ensures DTB Nigeria maintains reliable records demonstrating ISMS conformity, operational effectiveness, legal/regulatory compliance, and audit readiness in alignment with ISO/IEC 27001:2022 Clause 7.5.

## 3. Scope

This procedure applies to all ISMS records generated, received, or maintained within DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers records in all formats, including:

- Electronic records (systems, logs, trackers, tickets, dashboards, approvals)
- Physical records (signed approvals, controlled printed forms, meeting files)
- Audio/visual records where used as ISMS evidence
- Third-party supplied assurance records and attestations

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from internal record ownership under this procedure, except for interface-related records retained by DTB Nigeria.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.5 (Documented information)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-DCP-020 – Document Control Procedure
4. DTB-NG-ISMS-COM-011 – Communication Plan
5. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
6. DTB-NG-ISMS-RRG-017 – Risk Register
7. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
8. DTB-NG-ISMS-SOA-019 – Statement of Applicability
9. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
10. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
11. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
12. Applicable legal hold, regulatory retention, and evidentiary requirements (Nigeria)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Record | Evidence of performed activity, decision, transaction, event, or result retained for operational, legal, regulatory, or audit purposes |
| Record Owner | Role accountable for accuracy, completeness, and control of a specific record set |
| Record Custodian | Role responsible for storage, technical administration, and retrieval support |
| Retention Period | Minimum period a record must be preserved before disposition |
| Disposition | Authorized action on records at end of retention (archive extension, secure destruction, transfer under legal hold) |
| Legal Hold | Suspension of normal disposition/destruction due to legal, regulatory, investigative, or audit requirements |
| Record Register | Controlled index of record categories, owners, location, retention, and disposition rules |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Governance accountability for ISMS evidence and record integrity |
| ISMS Programme Manager | Maintains ISMS Record Register and retention oversight |
| Record Owners (process/control owners) | Ensure records are generated, accurate, and retained per requirements |
| Record Custodians (ITOPS/system admins) | Ensure secure storage, backup, access control, and retrievability |
| Compliance/Legal | Defines legal/regulatory retention and legal hold obligations |
| DPO | Ensures privacy-related record handling aligns with NDPA/NDPC |
| Internal Audit | Verifies record adequacy, traceability, and retention control effectiveness |
| HR / Procurement / Branch Ops (as applicable) | Maintain domain-specific ISMS records under this procedure |
| All staff/users | Create and handle records in line with approved controls |

## 7. Procedure

### 7.1 Record Lifecycle Management

ISMS records shall be managed through the following lifecycle:

1. Record creation/capture
2. Classification and indexing
3. Storage and protection
4. Access and retrieval
5. Retention monitoring
6. Legal hold handling (if applicable)
7. Disposition and secure destruction/archival extension

Each lifecycle stage must preserve record authenticity, integrity, and usability.

### 7.2 Record Identification and Minimum Metadata

All controlled ISMS records must include, where applicable:

- Record title/type
- Record ID/reference (if assigned)
- Owner
- Creation date/time
- Source system/location
- Classification level
- Retention period
- Disposition due date
- Version/revision marker (if mutable record type)
- Approval/evidence linkage (where relevant)

Unidentified or orphan records are not acceptable for auditable ISMS evidence.

### 7.3 ISMS Record Register Requirements

The ISMS Programme Manager shall maintain a Record Register containing at least:

1. Record category
2. Description/purpose
3. Owner role
4. Storage location/system
5. Classification
6. Retention period
7. Disposal method
8. Legal/regulatory basis (if applicable)
9. Backup requirement
10. Access control profile

Record Register shall be reviewed at least quarterly.

### 7.4 Record Categories (Minimum Mandatory Set)

DTB Nigeria shall maintain records for, at minimum:

- ISMS governance and meeting records
- Policy/procedure approvals and revisions
- Risk assessment and risk treatment records
- SoA applicability and control status evidence
- Asset inventory and classification records
- Access control approvals and recertifications
- Vulnerability/patch and configuration records
- Logging/monitoring and incident response records
- Supplier due diligence and monitoring records
- Awareness/training completion records
- Internal audit plans, findings, and closures
- Nonconformity and corrective action records
- Management review inputs/outputs
- Regulatory communication and compliance evidence

### 7.5 Storage and Protection Controls

1. Records shall be stored in approved repositories only.
2. Access shall be role-based and least-privilege.
3. Confidential/Restricted records require enhanced protection (encryption/access restrictions).
4. Storage repositories must be included in backup and recovery scope.
5. Integrity safeguards (e.g., audit trail, version history, immutable logging where applicable) shall be enabled for critical records.
6. Physical records must be stored in access-controlled locations.

### 7.6 Record Retrieval and Availability

1. Records must be retrievable within acceptable business/audit timelines.
2. Record owners must be able to produce requested evidence during audits, incidents, or regulatory reviews.
3. Retrieval requests and responses for sensitive records should be logged.
4. If record retrieval fails, incident/deviation shall be raised and addressed.

### 7.7 Retention Schedule Rules

1. Minimum default retention for ISMS records: **6 years**, unless legal/regulatory/contractual requirements mandate longer periods.
2. Where multiple retention requirements apply, the longest period prevails.
3. Retention start point shall be clearly defined (e.g., date of creation, closure date, end of contract, end of incident).
4. Retention rules must be documented in the Record Register.

### 7.8 Legal Hold and Investigation Preservation

1. Compliance/Legal may issue legal hold notices affecting relevant record sets.
2. Upon legal hold:
    - disposition/destruction is suspended,
    - affected records are flagged and preserved,
    - access and chain-of-custody controls are strengthened.
3. Legal hold release must be documented before normal disposition resumes.

### 7.9 Record Disposition and Secure Destruction

1. At retention expiry, records shall be dispositioned per approved method:
    - secure destruction, or
    - archival extension (with justification), or
    - transfer under legal/regulatory instruction.
2. Disposal of Confidential/Restricted records must ensure non-recoverability.
3. Disposal actions must be logged with:
    - record category,
    - date,
    - method,
    - authorizing role,
    - executor/custodian evidence.
4. Unauthorized disposal is a serious control breach.

### 7.10 Handling Mutable vs Immutable Records

- **Mutable records** (working trackers, draft operational logs) must preserve revision history/audit trail.
- **Immutable records** (approved evidence snapshots, signed approvals, finalized reports) must be protected from alteration.
- Where systems permit, finalized evidence should be locked/read-only after closure.

### 7.11 Third-Party Records

1. Records received from suppliers/auditors/regulators shall be validated, classified, and stored in controlled repositories.
2. Contractual rights should ensure availability of supplier evidence for agreed periods.
3. Critical supplier assurance evidence must be indexed in Record Register with owner and retrieval path.

### 7.12 Record Quality Controls

Record owners shall ensure records are:

- Complete (all mandatory fields/evidence present),
- Accurate (factually correct and attributable),
- Timely (created/updated within required timeframe),
- Legible and usable (human-readable and technically accessible),
- Traceable (linked to decisions/events/processes).

Quality issues must trigger corrective action where material.

### 7.13 Monitoring and KPIs

Record control effectiveness shall be measured using indicators such as:

1. % required ISMS records available during audit sampling
2. % records with complete metadata
3. % overdue retention reviews
4. number of record retrieval failures
5. number of unauthorized record changes or deletions
6. number of legal hold breaches (target: zero)

Metrics are reported through ISMS governance channels.

### 7.14 Nonconformities and Escalation

The following require immediate escalation:

- Missing mandatory records for critical controls
- Evidence tampering/unauthorized modification
- Unauthorized deletion or premature destruction
- Legal hold noncompliance
- Repeated retrieval failures impacting audit/regulatory response

Incidents/nonconformities shall be logged and managed under NCP/CAP procedures.

### 7.15 Assumptions Applied

1. DTB Nigeria has approved repositories capable of access control, backup, and audit logging.
2. Process owners can identify mandatory records within their control domains.
3. Record retention obligations are periodically validated by Compliance/Legal.

## 8. ISMS Record Retention Matrix (Baseline)

| **Record Category** | **Owner** | **Minimum Retention** | **Storage Location Type** | **Disposal Method** |
| --- | --- | --- | --- | --- |
| ISMS Policies/Procedures Approval Records | ISMS-PM / CISO Office | 6 years | Controlled ISMS repository | Secure digital destruction after expiry |
| Risk Assessments and Risk Register History | ERM / CISO Office | 6 years | GRC/risk repository | Secure digital destruction |
| Risk Treatment and SoA Evidence | CISO / Control Owners | 6 years | ISMS evidence repository | Secure digital destruction |
| Incident Records and Investigation Artifacts | SOC / CISO | 6 years (or longer if legal case) | Incident management platform + evidence vault | Secure destruction post-clearance |
| Access Reviews and IAM Approval Logs | ITOPS | 6 years | IAM system / evidence repository | Secure digital destruction |
| Vulnerability/Patch/Config Compliance Reports | ITOPS / SOC | 6 years | Security operations repositories | Secure digital destruction |
| Supplier Security Due Diligence Records | Procurement / Compliance | 6 years after contract end (minimum) | Vendor governance repository | Secure destruction |
| Awareness and Training Records | HR / CISO Office | 6 years | LMS/HR repository | Secure digital destruction |
| Internal Audit Files and NC/CAPA Records | Internal Audit / ISMS-PM | 6 years | Audit repository | Secure destruction |
| Management Review Minutes and Decisions | CISO Office | 6 years | Governance repository | Secure destruction |
| Regulatory Communication Records | Compliance/Legal / DPO | 6 years minimum (or per legal requirement) | Compliance repository | Per legal direction |
| Legal Hold Registers and Notices | Compliance/Legal | Duration of hold + 6 years | Legal repository | Per legal direction |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| ISMS Record Register | ISMS Programme Manager | Minimum 6 years |
| Record Access/Retrieval Logs (where applicable) | Record Custodians | Minimum 6 years |
| Retention Review Reports | ISMS-PM / Compliance | Minimum 6 years |
| Disposition Authorization and Destruction Logs | Record Owners / Custodians | Minimum 6 years |
| Legal Hold Notices and Release Records | Compliance/Legal | Duration of hold + 6 years |
| Record Control Nonconformity Logs | CISO Office / ISMS-PM | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-DCP-020 – Document Control Procedure
2. DTB-NG-ISMS-COM-011 – Communication Plan
3. DTB-NG-ISMS-RAM-012 – Risk Assessment Methodology
4. DTB-NG-ISMS-RRG-017 – Risk Register
5. DTB-NG-ISMS-RTP-018 – Risk Treatment Plan
6. DTB-NG-ISMS-SOA-019 – Statement of Applicability
7. DTB-NG-ISMS-IAP-056 – Internal Audit Procedure
8. DTB-NG-ISMS-NCP-061 – Nonconformity Procedure
9. DTB-NG-ISMS-CAP-062 – Corrective Action Procedure
10. DTB-NG-ISMS-DSP-052 – Data Retention and Secure Disposal Policy (to be issued)

## 11. ISO Clause References

- Clause 7.5 Documented information
- Clause 8.1 Operational planning and control
- Clause 9.1 Monitoring, measurement, analysis and evaluation
- Clause 9.2 Internal audit
- Clause 9.3 Management review
- Clause 10.2 Nonconformity and corrective action

## 12. Annex A References

- 5.1 Policies for information security
- 5.2 Information security roles and responsibilities
- 5.31 Legal, statutory, regulatory and contractual requirements
- 5.33 Protection of records
- 5.34 Privacy and protection of PII
- 5.36 Compliance with policies and standards for information security
- 5.37 Documented operating procedures
- 8.10 Information deletion
- 8.13 Information backup
- 8.15 Logging
- 8.16 Monitoring activities

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon significant legal/regulatory retention changes, audit findings, major incident learnings, or repository architecture/tooling changes affecting record controls.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / Compliance / DPO | Updated retention/legal hold/disposition controls |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Competence Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Competence Procedure |
| Document ID | DTB-NG-ISMS-CMP-022 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the process for determining the necessary competence of persons doing work under the control of DTB Nigeria that affects its information security performance. It ensures that personnel are competent on the basis of appropriate education, training, or experience, and outlines the steps to acquire and evaluate necessary competencies.

This procedure ensures DTB Nigeria maintains reliable human resource controls demonstrating ISMS conformity, operational effectiveness, and audit readiness in alignment with ISO/IEC 27001:2022 Clause 7.2.

## 3. Scope

This procedure applies to all employees, contractors, consultants, and relevant third-party personnel working within the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers competence requirements in all formats, including:

- Formal education and professional certifications
- Internal and external security training
- Information security awareness programs
- Technical and operational security experience

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from internal competence management under this procedure, except for interface-related personnel requiring specific security competencies to interact with DTB Nigeria.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.2 (Competence)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-POL-008 – Information Security Policy
4. DTB-NG-ISMS-RACI-007 – Roles and Responsibilities Matrix (RACI)
5. DTB-NG-ISMS-RCP-021 – Record Control Procedure
6. Applicable regulatory requirements (e.g., CBN IT Standards, NDPA/NDPC)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Competence | The ability to apply knowledge and skills to achieve intended results, specifically regarding information security. |
| Action to Acquire Competence | Provision of training, mentoring, reassignment of currently employed persons, or hiring/contracting of competent persons. |
| Evaluation of Effectiveness | The process of verifying that an action taken to acquire competence has successfully imparted the required knowledge or skills. |
| Role Profile | A documented description of the responsibilities, accountabilities, and required competencies for a specific job function. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Defines specific information security competence requirements for ISMS roles and assesses effectiveness of specialized security training. |
| ISMS Programme Manager | Maintains oversight of ISMS competence gaps and ensures alignment with ISMS objectives. |
| Human Resources (HR) | Coordinates training programs, maintains personnel records, and facilitates the performance evaluation and recruitment processes. |
| Line Managers (Process Owners) | Identify competence gaps within their teams, recommend appropriate training, and evaluate effectiveness of actions taken. |
| All staff/users | Attend required training, apply learned skills, and provide evidence of qualifications and experience. |

## 7. Procedure

### 7.1 Determining Competence Requirements

1. HR, in consultation with the CISO and relevant Line Managers, shall define the specific competencies required for each role within DTB Nigeria that affects information security performance.
2. These requirements must be documented in formal Job Descriptions and/or Role Profiles.
3. Competency requirements shall be based on:
    - Formal education and academic qualifications.
    - Professional certifications (e.g., ISO/IEC 27001 Lead Implementer/Auditor, CISSP, CISM).
    - Relevant industry, banking, and technical experience.
    - Required technical and soft skills.

### 7.2 Assessing Current Competence

1. During the recruitment and onboarding process, HR and the hiring manager shall assess candidate qualifications against documented competence requirements. This includes verification of educational certificates, reference checks, and technical interviews.
2. For existing employees, Line Managers shall review competence at least annually during standard performance appraisals.
3. Competence must also be re-assessed when an employee changes roles or is assigned new responsibilities impacting information security.
4. The CISO may periodically conduct skills assessments to ensure baseline information security competencies are maintained across the organization.

### 7.3 Acquiring Competence

1. Where a gap in competence is identified, appropriate actions must be taken to ensure the individual acquires the necessary skills or knowledge.
2. Actions to acquire competence may include, but are not limited to:
    - Formal internal or external training courses.
    - Mentoring, coaching, or job-shadowing by experienced personnel.
    - Provision of targeted information security awareness materials.
    - Reassignment of tasks to currently competent personnel.
    - Hiring or contracting competent external resources.
3. Training and development plans must be documented and approved by the respective Line Manager and HR.

### 7.4 Evaluating Effectiveness of Actions Taken

1. Following the completion of any training or action taken to acquire competence, the Line Manager must evaluate its effectiveness.
2. The evaluation shall occur within an appropriate timeframe (e.g., 1 to 3 months post-training) to allow the individual to demonstrate newly acquired skills in an operational setting.
3. Methods for evaluating effectiveness include:
    - Post-training assessments or certification exams.
    - Observation of the employee's performance in applying the new skills.
    - Review of relevant key performance indicators (KPIs) or reduction in error rates.
    - Feedback from peers, supervisors, or internal audit results.
4. If the action taken is deemed ineffective, the Line Manager and HR shall determine further appropriate remedial actions.

### 7.5 Documenting and Maintaining Evidence

1. Documented information must be retained as evidence of competence.
2. Verified copies of certifications, degrees, and training attendance must be securely stored in the employee's HR file.
3. Records of performance appraisals, competence assessments, and evaluations of training effectiveness must be maintained.
4. All competence evidence is subject to the DTB-NG-ISMS-RCP-021 Record Control Procedure.

### 7.6 Assumptions Applied

1. DTB Nigeria maintains an active, centralized HR repository capable of tracking employee training and certifications.
2. Line Managers are adequately trained to assess technical and behavioral competencies within their domains.
3. Training budgets are allocated annually to address identified competence gaps.

## 8. ISMS Competence Requirements Matrix (Baseline)

| **Role Category** | **Minimum Required Competence** | **Evaluation Method** |
| --- | --- | --- |
| ISMS Governance (CISO, ISMS-PM) | Advanced ISMS framework knowledge, risk management, relevant certification (e.g., ISO 27001 Lead Implementer/CISM). | Certificate verification, performance review, audit results. |
| IT Operations & Security | Technical security controls, network architecture, secure configuration, incident response. | Technical interview, certificate verification, incident handling observation. |
| General Employees | Basic information security awareness, acceptable use, phishing recognition, physical security rules. | Onboarding assessment, annual awareness quiz, phishing simulation results. |
| Internal Auditors | Audit principles, ISO 27001 requirements, objective evidence gathering. | ISO 27001 Internal Auditor certification, audit report quality review. |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Job Descriptions / Role Profiles | HR | Duration of employment + 6 years |
| Training Attendance Logs and Certificates | HR / CISO Office | Minimum 6 years |
| Employee Qualifications and Resumes | HR | Duration of employment + 6 years |
| Performance Appraisals & Competence Reviews | Line Managers / HR | Minimum 6 years |
| Post-Training Effectiveness Evaluations | Line Managers / HR | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-RACI-007 – Roles and Responsibilities Matrix (RACI)
3. DTB-NG-ISMS-RCP-021 – Record Control Procedure
4. DTB Nigeria Annual Training Plan (HR)
5. DTB Nigeria Employee Performance Appraisal Forms

## 11. ISO Clause References

- Clause 7.2 Competence
- Clause 7.3 Awareness
- Clause 7.5 Documented information

## 12. Annex A References

- 5.2 Information security roles and responsibilities
- 6.3 Information security awareness, education and training

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon significant organizational restructuring, changes to regulatory competence requirements, or identification of systemic competence failures during internal audits.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / HR | Updated competence evaluation methods and matrix |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Security Awareness Programme

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Security Awareness Programme |
| Document ID | DTB-NG-ISMS-SAP-023 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this document is to define the Information Security Awareness Programme for DTB Nigeria. This programme ensures that all relevant personnel are aware of the Information Security Policy, their contribution to the effectiveness of the Information Security Management System (ISMS), the benefits of improved information security performance, and the implications of not conforming to ISMS requirements.

This procedure ensures DTB Nigeria maintains reliable awareness controls demonstrating ISMS conformity, operational effectiveness, and audit readiness in alignment with ISO/IEC 27001:2022 Clause 7.3.

## 3. Scope

This procedure applies to all employees, contractors, consultants, and relevant third-party personnel working within the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers awareness activities in all formats, including:

- New hire orientation and onboarding
- Annual refresher training
- Phishing simulations and social engineering tests
- Periodic newsletters, alerts, and executive communications

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from this specific internal awareness programme, except where their personnel directly access DTB Nigeria systems and require local orientation.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.3 (Awareness)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-ISP-008 – Information Security Policy
4. DTB-NG-ISMS-RRM-007 – Roles and Responsibilities Matrix (RACI)
5. DTB-NG-ISMS-CMP-022 – Competence Procedure
6. DTB-NG-ISMS-RCP-021 – Record Control Procedure
7. Applicable regulatory requirements (e.g., CBN IT Standards, NDPA/NDPC)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Security Awareness | The knowledge and attitude members of an organization possess regarding the protection of the physical and informational assets of that organization. |
| Phishing Simulation | A controlled, internal exercise simulating a malicious email attack to test and educate employees on identifying social engineering threats. |
| Remedial Training | Additional targeted training assigned to individuals who demonstrate a lack of understanding or fail security assessments (e.g., failing a phishing simulation). |
| Social Engineering | Psychological manipulation of people into performing actions or divulging confidential information. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Designs, implements, and continually improves the Security Awareness Programme based on the organizational risk assessment and threat landscape. |
| ISMS Programme Manager | Tracks awareness completion metrics and ensures alignment with ISMS objectives. |
| Human Resources (HR) | Integrates security awareness into the employee onboarding process and tracks completion in personnel files. |
| Line Managers (Process Owners) | Ensure all personnel within their teams complete mandatory training and apply security best practices. |
| All staff/users | Participate in the awareness programme, understand the material provided, and apply the principles in daily activities. |

## 7. Procedure

### 7.1 Programme Development and Topic Selection

1. The CISO shall conduct an annual assessment to determine the key information security topics to be covered in the awareness programme.
2. Topic selection shall be informed by the current Risk Register (DTB-NG-ISMS-RRG-017), recent internal/external security incidents, audit findings, and changes in the threat landscape.
3. Core topics to be covered shall include, but are not limited to:
    - The Information Security Policy and individual responsibilities.
    - Password management and authentication best practices.
    - Recognizing and reporting phishing and social engineering.
    - Physical security, including visitor management and tailgating.
    - Clean Desk and Clear Screen principles.
    - Data protection, privacy, and secure data handling.
    - Information security incident reporting procedures.

### 7.2 New Hire Onboarding

1. Information security awareness training is mandatory for all new hires.
2. HR shall ensure that new employees, contractors, and relevant third parties complete the baseline security awareness training within the first 30 days of their employment or contract start date.
3. IT Operations (ITOPS) may restrict or revoke system access if the onboarding security training is not completed within the mandated timeframe.

### 7.3 Ongoing Awareness and Delivery Methods

1. **Annual Refresher Training:** All personnel must complete a comprehensive security awareness refresher course at least once every 12 months.
2. **Targeted Training:** Specialized awareness training shall be provided to personnel in high-risk roles (e.g., ITOPS, HR, Finance, and Customer Service) addressing threats specific to their functions.
3. **Continuous Communication:** The CISO and ISMS Programme Manager shall utilize various delivery methods to maintain continuous awareness, including:
    - Monthly or quarterly security newsletters.
    - Internal portal (intranet) announcements.
    - Screen savers and physical posters placed in DTB Nigeria offices.
    - Briefings during departmental or town-hall meetings.

### 7.4 Phishing Simulations

1. The Information Security department shall conduct periodic, unannounced phishing simulations across the organization.
2. The results of these simulations shall be used strictly for educational purposes and to measure the effectiveness of the awareness programme.
3. Personnel who repeatedly fail phishing simulations will be required to undergo mandatory supplementary remedial training and may be reported to their Line Manager.

### 7.5 Evaluation and Improvement

1. The CISO shall evaluate the effectiveness of the Security Awareness Programme at least annually.
2. Metrics for evaluation shall include:
    - Training completion rates across departments.
    - Click rates and reporting rates from phishing simulations.
    - Number of security incidents caused by human error versus those reported proactively by personnel.
3. The results of this evaluation shall be presented during Management Reviews to improve the programme for the following year.

### 7.6 Assumptions Applied

1. DTB Nigeria utilizes a Learning Management System (LMS) or equivalent platform to track and record training completion.
2. The organization has the technical capability to safely conduct internal phishing simulations.
3. Executive management actively supports and participates in the awareness programme, setting a "tone at the top."

## 8. ISMS Security Awareness Matrix (Baseline)

| **Audience** | **Activity** | **Frequency** | **Delivery Method** |
| --- | --- | --- | --- |
| All New Hires | Baseline Security Induction | Within 30 days of joining | E-learning / Instructor-led |
| All Personnel | Annual Security Refresher | Annually | E-learning platform |
| All Personnel | Phishing Simulations | At least quarterly | Simulated email campaigns |
| High-Risk Roles | Targeted Threat Awareness | Bi-annually | Workshop / Specialized module |
| All Personnel | General Security Communications | Monthly | Newsletters, Intranet, Posters |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Awareness Training Attendance/Completion Logs | HR / ISMS-PM | Minimum 6 years |
| Phishing Simulation Campaign Reports | CISO Office | Minimum 6 years |
| Remedial Training Records | HR / ISMS-PM | Minimum 6 years |
| Security Newsletters and Broadcast Archives | CISO Office | Minimum 6 years |
| Annual Awareness Programme Evaluation Report | CISO Office | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-ISP-008 – Information Security Policy
2. DTB-NG-ISMS-RRM-007 – Roles and Responsibilities Matrix (RACI)
3. DTB-NG-ISMS-CMP-022 – Competence Procedure
4. DTB-NG-ISMS-RCP-021 – Record Control Procedure
5. DTB-NG-ISMS-ICP-024 – Internal Communication Procedure (to be issued)

## 11. ISO Clause References

- Clause 7.2 Competence
- Clause 7.3 Awareness
- Clause 7.4 Communication
- Clause 7.5 Documented information

## 12. Annex A References

- 5.24 Information security incident management planning and preparation
- 6.3 Information security awareness, education and training

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon significant shifts in the cyber threat landscape, recurring incident trends indicating an awareness gap, or changes to internal policies affecting staff responsibilities.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / HR | Updated phishing simulation and remedial training rules |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# Internal Communication Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | Internal Communication Procedure |
| Document ID | DTB-NG-ISMS-ICP-024 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the process for internal communication relevant to the Information Security Management System (ISMS) at DTB Nigeria. It ensures that the organization systematically determines what to communicate, when to communicate, with whom to communicate, how to communicate, and who communicates.

This procedure ensures DTB Nigeria maintains reliable internal communication controls demonstrating ISMS conformity, operational effectiveness, and alignment with ISO/IEC 27001:2022 Clause 7.4.

## 3. Scope

This procedure applies to all internal communications regarding information security directed at employees, contractors, consultants, and relevant internal stakeholders working within the DTB Nigeria ISMS scope:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

It covers all internal communication channels, including:

- Broadcast emails and organizational announcements
- Intranet portals and collaborative platforms (e.g., Microsoft Teams)
- Management and departmental meetings
- Visual aids (e.g., posters, digital signage)

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from this internal communication procedure, except where shared security bulletins apply directly to interface personnel.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.4 (Communication)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-POL-008 – Information Security Policy
4. DTB-NG-ISMS-COM-011 – Communication Plan
5. DTB-NG-ISMS-SAP-023 – Security Awareness Programme
6. DTB-NG-ISMS-RCP-021 – Record Control Procedure

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| Internal Communication | The exchange of information and messages regarding the ISMS between the organization and its internal stakeholders. |
| Broadcast | A wide-scale distribution of information, typically via email or intranet, intended for all or a large segment of DTB Nigeria personnel. |
| ISMC | Information Security Management Committee. |
| Ad-hoc Communication | Unplanned communications triggered by specific events, such as security incidents or urgent threat intelligence. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| CISO (Nigeria) | Determines the technical accuracy and necessity of information security communications and authorizes the release of security alerts. |
| Corporate Communications | Formats, reviews, and distributes internal communications to ensure alignment with DTB Nigeria’s internal branding guidelines. |
| ISMS Programme Manager | Ensures planned ISMS communications (e.g., policy updates, objectives) are executed according to the ISMS schedule. |
| Line Managers (Process Owners) | Reinforce internal communications within their departments and ensure their teams understand the distributed messages. |
| All staff/users | Read, acknowledge (where required), and act upon internal security communications. |

## 7. Procedure

### 7.1 What to Communicate

DTB Nigeria shall communicate relevant information security matters to internal stakeholders. The content of these communications shall include, but is not limited to:

- The Information Security Policy and any significant policy or procedural updates.
- Information security objectives and performance against these objectives.
- The individual’s contribution to the effectiveness of the ISMS.
- The implications of not conforming to ISMS requirements.
- Changes to the ISMS, including new security tools, processes, or controls.
- Security alerts, threat intelligence warnings, and internal incident notifications.
- Feedback from internal audits, management reviews, and continuous improvement initiatives.

### 7.2 When to Communicate

Internal communications shall occur at appropriate intervals, defined as:

- **Upon Onboarding:** Introduction to security policies for all new personnel.
- **Periodically:** Regular updates as defined in the Communication Plan (e.g., monthly newsletters, quarterly performance dashboards).
- **Ad-hoc / Event-Driven:** Immediately upon the occurrence of significant events, such as urgent security alerts, active zero-day vulnerabilities, or ongoing internal security incidents affecting business operations.
- **Annually:** Reiteration of the Information Security Policy and annual objectives.

### 7.3 With Whom to Communicate

The target audience for internal communications shall be identified based on the relevance of the message:

- **All Personnel:** For general awareness, policy updates, and widespread threat alerts (e.g., phishing campaigns).
- **Executive Management / ISMC:** For strategic updates, risk metrics, audit results, and incident reports.
- **Specific Departments / Teams:** For targeted communications (e.g., secure coding practices for IT Development, data handling rules for HR).

### 7.4 How to Communicate

The organization shall utilize approved internal channels to deliver communications effectively:

- **Email Broadcasts:** For urgent alerts, policy distributions, and formal announcements.
- **Intranet Portal:** As a centralized repository for policies, procedures, and ongoing security news.
- **Meetings and Briefings:** Town halls, departmental meetings, and ISMC meetings for interactive communication and feedback.
- **Visual Aids:** Posters, digital signage, and screensavers deployed within DTB Nigeria facilities.
- **Collaboration Tools:** Approved internal messaging platforms for quick updates and team-specific guidance.

### 7.5 Who Communicates

Authority to issue internal information security communications is defined as follows:

- The **CISO** or designated Information Security team members shall initiate and draft technical alerts, awareness content, and policy updates.
- The **Corporate Communications Department** shall broadcast organization-wide messages on behalf of the Information Security department.
- **Executive Management** or the **ISMC Chair** shall communicate strategic changes, high-level objectives, and major organizational impacts.
- **Line Managers** shall handle specific, localized communications within their respective teams.

### 7.6 Assumptions Applied

1. DTB Nigeria utilizes a centrally managed corporate email and intranet system capable of reaching all in-scope employees and contractors.
2. The Corporate Communications department has established Service Level Agreements (SLAs) with the Information Security team to prioritize urgent security broadcasts.
3. Personnel have access to the required communication channels to receive updates promptly.

## 8. ISMS Internal Communication Matrix (Baseline)

| **Communication Topic** | **Audience** | **Frequency / Trigger** | **Initiator / Approver** | **Delivery Channel** |
| --- | --- | --- | --- | --- |
| Information Security Policy Updates | All Personnel | Annually / Upon major revision | CISO / Exec Management | Broadcast Email & Intranet |
| Security Alerts (e.g., Active Phishing) | All Personnel | Ad-hoc / Event-driven | CISO | Broadcast Email |
| ISMS Performance & Audit Results | ISMC / Exec Mgmt | Quarterly / Annually | ISMS Programme Manager | ISMC Meeting / Report |
| Monthly Security Newsletter | All Personnel | Monthly | Corporate Communications | Email & Intranet |
| Targeted Process Changes (e.g., new IAM tool) | IT / Specific Depts | Prior to rollout | CISO / Line Managers | Collaboration Tools & Meetings |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Email Broadcast Archives | Corporate Communications | Minimum 6 years |
| Published Intranet Articles/Newsletters | Corporate Communications | Minimum 6 years |
| ISMC and Town Hall Meeting Minutes | ISMS-PM / CISO Office | Minimum 6 years |
| Policy Acknowledgment Receipts | HR / ISMS-PM | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-COM-011 – Communication Plan
3. DTB-NG-ISMS-SAP-023 – Security Awareness Programme
4. DTB-NG-ISMS-RCP-021 – Record Control Procedure
5. DTB-NG-ISMS-ECP-025 – External Communication Procedure (to be issued)

## 11. ISO Clause References

- Clause 7.4 Communication
- Clause 7.5 Documented information

## 12. Annex A References

- 5.24 Information security incident management planning and preparation
- 6.3 Information security awareness, education and training

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon implementation of new corporate communication platforms, significant organizational restructuring, or identified failures in communication channels during an incident.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / Corporate Comm. | Aligned communication channels and approval matrix |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |

# External Communication Procedure

## 1. Document Control Information

| **Field** | **Details** |
| --- | --- |
| Document Title | External Communication Procedure |
| Document ID | DTB-NG-ISMS-ECP-025 |
| Version | 1.0 |
| Classification | Internal – Confidential |
| Process Owner | ISMS Programme Manager, DTB Nigeria |
| Control Owner | Chief Information Security Officer (CISO), Nigeria |
| Approved By | Managing Director/CEO (Nigeria Operations) |
| Effective Date | 01 July 2026 |
| Next Review Date | 01 July 2027 |
| Applicability | Digho Trust Bank (DTB) Nigeria ISMS Certification Scope |

## 2. Purpose

The purpose of this procedure is to define the process for external communication relevant to the Information Security Management System (ISMS) at DTB Nigeria. It ensures that the organization systematically determines what to communicate, when to communicate, with whom to communicate, how to communicate, and who communicates with external parties.

This procedure ensures DTB Nigeria maintains reliable external communication controls demonstrating ISMS conformity, legal and regulatory compliance, and alignment with ISO/IEC 27001:2022 Clause 7.4.

## 3. Scope

This procedure applies to all external communications regarding information security, security incidents, and the ISMS posture of DTB Nigeria:

- Head Office: Lagos
- Branches: Abuja, Port Harcourt, Enugu, Calabar, Ibadan

Target audiences include:

- Regulatory bodies (e.g., Central Bank of Nigeria [CBN], Nigeria Data Protection Commission [NDPC])
- Law enforcement agencies (e.g., Nigeria Police Force, Cybercrime units)
- Customers and clients
- Suppliers, vendors, and strategic partners
- Media and the general public
- Special interest groups and professional cybersecurity associations

Out-of-scope international entities (London, Frankfurt, Paris, New York) are excluded from this procedure, except where DTB Nigeria is required to report local incidents or compliance statuses to global headquarters.

## 4. References

1. ISO/IEC 27001:2022 Clause 7.4 (Communication)
2. ISO/IEC 27002:2022
3. DTB-NG-ISMS-POL-008 – Information Security Policy
4. DTB-NG-ISMS-COM-011 – Communication Plan
5. DTB-NG-ISMS-ICP-024 – Internal Communication Procedure
6. DTB-NG-ISMS-RCP-021 – Record Control Procedure
7. Applicable regulatory requirements (e.g., CBN IT Standards, NDPA/NDPC)

## 5. Definitions

| **Term** | **Definition** |
| --- | --- |
| External Communication | The exchange of information and messages between DTB Nigeria and external entities or the general public regarding information security. |
| External Party | Any individual, organization, or regulatory body outside the direct employment and structural control of DTB Nigeria. |
| Special Interest Group (SIG) | External forums, industry bodies, or professional networks focused on cybersecurity and threat intelligence sharing. |
| Incident Notification | Formal communication to external parties regarding a confirmed information security event that impacts their data or services. |

## 6. Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| Managing Director/CEO | Authorizes major external communications, especially those regarding significant information security incidents or public statements. |
| CISO (Nigeria) | Determines technical accuracy of external information, acts as a liaison with SIGs, and ensures regulatory security reporting requirements are met. |
| Corporate Communications | Manages all media relations, drafts external public statements, and ensures consistent messaging aligned with DTB Nigeria’s corporate image. |
| Legal and Compliance | Reviews external communications to ensure alignment with legal obligations, privacy laws (e.g., NDPA), and regulatory mandates. |
| All staff/users | Strictly prohibited from making unauthorized statements to the media, external parties, or on public forums regarding the bank’s information security. |

## 7. Procedure

### 7.1 What to Communicate

DTB Nigeria shall communicate relevant information security matters to external parties as necessary. The content of these communications may include:

- Information security incident notifications (e.g., data breaches, extended service outages) affecting customers or third parties.
- Mandatory reporting of security incidents or vulnerabilities to regulatory and law enforcement authorities.
- Verification of ISMS certification status, executive summaries, or the Statement of Applicability (SoA) to prospective clients or partners.
- Responses to external audits, customer due diligence questionnaires, or regulatory inquiries.
- Coordinated vulnerability disclosures or threat intelligence sharing with trusted industry groups.

### 7.2 When to Communicate

External communications shall occur based on specific triggers and regulatory timelines:

- **Incident-Driven:** In the event of a significant security breach, notifications must be made to regulatory authorities within legally mandated timeframes (e.g., within 72 hours for data breaches under the NDPC, or as stipulated by the CBN).
- **Customer Impact:** Customers must be notified as soon as practically possible if an incident compromises their sensitive personal data or severely impacts banking services.
- **Periodic/Routine:** Submission of mandatory compliance reports, audit summaries, and security posture updates to regulators as defined by industry schedules.
- **On-Demand:** Responding to media inquiries or partner security questionnaires within an appropriate timeframe determined by the CISO and Corporate Communications.

### 7.3 With Whom to Communicate

The organization shall identify the appropriate external stakeholders for specific communications, including:

- **Regulatory Authorities:** CBN, NDPC, and other relevant Nigerian statutory bodies.
- **Law Enforcement:** Nigerian Police Force, Economic and Financial Crimes Commission (EFCC), and national cyber emergency response teams (CERTs).
- **Customers and Clients:** Retail, corporate, and institutional banking clients.
- **Suppliers and Partners:** Third-party vendors, managed service providers, and strategic partners.
- **Media and Public:** News outlets, social media platforms, and the general public.
- **Special Interest Groups:** Industry forums (e.g., Committee of CISOs of Nigerian Banks), cybersecurity information sharing groups, and professional associations.

### 7.4 How to Communicate

Approved channels must be used to deliver external communications securely and effectively:

- **Regulatory Portals:** Official submission portals or secured channels mandated by regulators.
- **Formal Written Correspondence:** Official letters on DTB Nigeria letterhead, signed by authorized executives.
- **Press Releases:** Official statements published via the Corporate Communications department.
- **Encrypted Email:** Used when transmitting sensitive technical details, audit reports, or incident data to external partners or authorities.
- **Bank Website and Social Media:** Verified corporate accounts for widespread customer service announcements or outage notifications.

### 7.5 Who Communicates

Authority to issue external information security communications is strictly controlled:

- The **Corporate Communications Department**, in conjunction with the **Managing Director/CEO**, are the sole authorized bodies to issue press releases or speak to the media.
- The **CISO** and the **Legal and Compliance Department** are authorized to communicate directly with regulatory authorities and law enforcement regarding security matters.
- **Relationship Managers** or **Customer Support** may communicate with specific customers only using approved scripts provided by the CISO and Corporate Communications.

### 7.6 Assumptions Applied

1. DTB Nigeria maintains an updated contact list for all relevant regulatory bodies, law enforcement agencies, and special interest groups.
2. The Legal and Compliance department is actively monitoring changes to CBN and NDPC reporting timelines to ensure this procedure remains legally compliant.
3. Media inquiries are automatically routed to Corporate Communications by all DTB Nigeria staff without providing unauthorized technical comments.

## 8. ISMS External Communication Matrix (Baseline)

| **Communication Topic** | **Target Audience** | **Trigger / Frequency** | **Authorized Communicator** | **Delivery Channel** |
| --- | --- | --- | --- | --- |
| Major Security Incident / Data Breach | Regulators (CBN, NDPC) | Within 72 hours of confirmation | CISO / Legal & Compliance | Secure Portal / Formal Letter |
| Public Incident Notification | Customers / General Public | Upon MD/CEO approval | Corporate Communications | Website / Press Release / Email |
| ISMS Audit Responses & Questionnaires | Third-Party Partners / Clients | On-Demand (Due Diligence) | CISO Office | Encrypted Email |
| Threat Intelligence Sharing | Special Interest Groups | Ad-hoc / Event-driven | CISO | Secure Industry Forums |
| Media Inquiries regarding Security | News Outlets / Journalists | On-Demand | Corporate Communications | Press Release / Briefing |

## 9. Records Generated by this Procedure

| **Record** | **Owner** | **Retention** |
| --- | --- | --- |
| Copies of Regulatory Reports & Breach Notifications | Compliance / CISO | Minimum 6 years |
| Press Releases and Media Statements | Corporate Communications | Minimum 6 years |
| Formal Correspondence with Law Enforcement/SIGs | CISO / Legal | Minimum 6 years |
| Legal/Exec Approvals for External Releases | Corporate Communications | Minimum 6 years |
| Completed External Security Questionnaires | CISO Office | Minimum 6 years |

## 10. Related Documents

1. DTB-NG-ISMS-POL-008 – Information Security Policy
2. DTB-NG-ISMS-COM-011 – Communication Plan
3. DTB-NG-ISMS-ICP-024 – Internal Communication Procedure
4. DTB-NG-ISMS-RCP-021 – Record Control Procedure
5. DTB-NG-ISMS-IRP-039 – Information Security Incident Response Procedure (to be issued)

## 11. ISO Clause References

- Clause 7.4 Communication
- Clause 7.5 Documented information

## 12. Annex A References

- 5.6 Contact with special interest groups
- 5.24 Information security incident management planning and preparation
- 5.31 Legal, statutory, regulatory and contractual requirements

## 13. Review Frequency

This procedure shall be reviewed:

- At least annually, and
- Upon significant changes to regulatory reporting mandates (e.g., CBN frameworks, NDPA updates), organizational restructuring, or following a major incident requiring external communication.

## 14. Version History

| **Version** | **Date** | **Author** | **Description of Change** |
| --- | --- | --- | --- |
| 0.1 | 29 June 2026 | ISMS Programme Manager | Initial draft |
| 0.9 | 30 June 2026 | CISO / Corporate Comm / Legal | Aligned regulatory reporting timelines and media authorization |
| 1.0 | 01 July 2026 | ISMS Programme Manager | First approved issue |

## 15. Approval Section

| **Name** | **Role** | **Decision** | **Date** | **Signature** |
| --- | --- | --- | --- | --- |
| Nneka I. Okafor | ISMS Programme Manager, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Chioma N. Eze | Chief Information Security Officer, DTB Nigeria | Approved | 01 July 2026 | __________________ |
| Adewale O. Adebayo | Managing Director/CEO, DTB Nigeria | Approved | 01 July 2026 | __________________ |