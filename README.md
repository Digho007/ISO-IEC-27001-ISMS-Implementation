# ISO/IEC 27001:2022 ISMS Implementation

**A full Information Security Management System (ISMS) built end-to-end and aligned to ISO/IEC 27001:2022, using a simulated Nigerian bank ("Digho Trust Bank") as the operating context.**

> **Disclaimer:** This is a self-directed training project. Digho Trust Bank is a fictional entity created for practice purposes. No real organization, client, or confidential data is represented in this repository. Document IDs, names, and approvers are illustrative.

## About this project

I built this to practice translating ISO/IEC 27001:2022 requirements into a working, cross-referenced ISMS document set, the way it would need to exist inside a regulated financial institution — not just isolated templates.

The scope simulates a bank with a Lagos head office and five branches (Abuja, Port Harcourt, Enugu, Calabar, Ibadan), running a Microsoft-centric security stack (Entra ID, Defender XDR, Sentinel) alongside core banking and digital banking platforms. Documents are layered against Central Bank of Nigeria (CBN) cybersecurity guidance, the Nigeria Data Protection Act (NDPA), and the Cybercrimes Act, in addition to the ISO 27001/27002 standards themselves.

## Structure

The documentation follows the ISO/IEC 27001:2022 clause structure:

| Folder / Section | ISO Clause | Core Document |
|---|---|---|
| `1-project-initiation` | Clause 4 | ISMS Project Charter |
| `2-leadership` | Clause 5 | Information Security Policy |
| `3-planning-and-operation` | Clauses 6 & 8 | Risk Assessment Methodology |
| `4-support` | Clause 7 | Document Control Procedure |
| `5-performance-evaluation` | Clause 9 | Internal Audit Procedure |
| `6-improvement` | Clause 10 | Nonconformity Procedure |

Each document includes standard document control metadata (ID, version, classification, process owner, approval chain, review dates), a defined scope with explicit in-scope/out-of-scope boundaries, references to the standard and related internal documents, and defined roles and responsibilities — built to be internally cross-referenced rather than standalone.

## What this demonstrates

- Translating ISO/IEC 27001:2022 clauses into a working, cross-referenced document set (policies, procedures, registers)
- Scoping discipline — consistent in-scope/out-of-scope boundaries applied across every document
- Regulatory fluency beyond the ISO standard: CBN cybersecurity guidance, NDPA/NDPC, and Nigeria's Cybercrimes Act layered onto the ISMS
- End-to-end clause coverage: governance, risk methodology, document control, internal audit, and nonconformity/corrective action
