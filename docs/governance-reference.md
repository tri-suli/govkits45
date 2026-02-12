# Governance Reference — Sonnet 4.5

> **Purpose:** Consolidated reference for all governance definitions, standards, and operating principles used across
> the project kit.

---

## Abstraction Level Standard

All governance instructions in this project operate at the **operational governance level**. Use the calibration guide
below when creating or reviewing any governance document.

| Level                   | Definition                                         | Example                                                                                      |
|-------------------------|----------------------------------------------------|----------------------------------------------------------------------------------------------|
| ✅ Governance (correct)  | Defines *who decides what under which condition*   | "PO must approve all scope changes affecting client-facing deliverables before BA proceeds." |
| ❌ Task (too granular)   | Describes *how* an action is executed step by step | "PO reviews document, updates JIRA, sends email to BA."                                      |
| ❌ Policy (too abstract) | States a principle without actionable ownership    | "PO is responsible for scope integrity."                                                     |

---

## Tracking ID Convention

| Prefix          | Phase                     | Issued By |
|-----------------|---------------------------|-----------|
| `BUG-YYYY-NNN`  | Phase 1 — Bug Report      | DM        |
| `DATA-YYYY-NNN` | Phase 1/2 — Data Issue    | DM        |
| `FEAT-YYYY-NNN` | Phase 3 — Feature Request | PO        |

**Format:** `[PREFIX]-[4-DIGIT YEAR]-[3-DIGIT SEQUENCE]`
**Example:** `BUG-2026-001`, `FEAT-2026-012`

---

## Requirement Change Classification

All requirement changes must be classified by BA before reaching PO:

| Classification    | Definition                                                         | Approval Path                                            |
|-------------------|--------------------------------------------------------------------|----------------------------------------------------------|
| **Clarification** | Adds specificity to existing requirement without changing scope    | BA documents, no PO approval needed                      |
| **Correction**    | Fixes a documented requirement that was incorrect or contradictory | BA documents with version update, PO notified            |
| **New Scope**     | Introduces behavior or functionality not currently covered         | Must receive PO formal approval before any work proceeds |

---

## SLA Reference (to be customized per project)

| Activity                            | SLA               | Owner            |
|-------------------------------------|-------------------|------------------|
| Initial WhatsApp acknowledgment     | 1 business day    | DM               |
| Issue classification by PO          | [X hours]         | PO               |
| Reproducibility confirmation by QA  | [X business days] | QA               |
| BA clarification request resolution | [X business days] | BA → stakeholder |
| QA validation cycle                 | [X business days] | QA               |
| PO authorization for roadmap entry  | [X business days] | PO               |

> ⚠️ Replace `[X]` values with project-agreed SLAs before using this kit.

---

## Non-Overlap Ownership Reference

To prevent governance ambiguity, the table below defines the distinct ownership boundary between roles for commonly
shared activities.

| Activity                        | Owner | Other Role's Boundary                                            |
|---------------------------------|-------|------------------------------------------------------------------|
| Requirement elicitation         | BA    | PO approves, QA assesses testability — neither elicits           |
| Scope change approval           | PO    | DM flags, BA submits — neither approves                          |
| Validation sign-off             | QA    | BA confirms criteria completeness — does not sign off            |
| Escalation routing              | DM    | BA/QA raise escalations — DM routes and acts                     |
| Roadmap authorization           | PO    | DM confirms feasibility — does not authorize                     |
| Design-to-requirement alignment | BA    | UI/UX proposes, BA confirms — UI/UX does not align independently |
| Delivery risk assessment        | DM    | All roles flag risk — DM owns the risk record                    |

---

## Escalation Decision Tree

```
ISSUE DETECTED
     │
     ▼
Is this a scope change or business intent question?
     ├── Yes → Escalate to PO
     └── No
          │
          ▼
     Is this a delivery or timeline risk?
          ├── Yes → Escalate to DM
          └── No
               │
               ▼
          Is this a requirement ambiguity or testability issue?
               ├── Yes → BA resolves via stakeholder consultation
               │         If unresolvable → Escalate to PO
               └── No
                    │
                    ▼
               Is this a design-scope conflict?
                    ├── Yes → UI/UX escalates to BA, then PO if scope-impacting
                    └── No → Resolve within role, document outcome
```

---

## Communication Channel Rules

| Channel             | Authorized Senders                                | Content Restrictions                                                          |
|---------------------|---------------------------------------------------|-------------------------------------------------------------------------------|
| **WhatsApp**        | DM (Phase 1), PO (Phase 3), DM+BA draft (Phase 2) | No technical details (architecture, DB, API). Business language only.         |
| **Trello Comments** | All roles                                         | Must use comment templates. All governance decisions must be documented here. |
| **Trello Cards**    | DM (creates Phase 1/2), PO/BA (creates Phase 3)   | Use card templates. No undocumented status changes.                           |

---

## Glossary

| Term                    | Definition                                                                                                       |
|-------------------------|------------------------------------------------------------------------------------------------------------------|
| **Governance Level**    | Operational layer that defines decision ownership, not execution steps                                           |
| **Acceptance Criteria** | Explicitly documented, measurable conditions a deliverable must meet to be accepted                              |
| **Traceability**        | The ability to link a requirement back to its originating stakeholder intent and forward to its validated output |
| **Scope Change**        | Any addition, removal, or modification that changes what is delivered to the client                              |
| **SLA**                 | Service Level Agreement — the agreed timeframe within which a governance action must be completed                |
| **Version Control**     | The practice of assigning version numbers to documents so historical states are preserved and retrievable        |
| **Escalation**          | The formal act of raising an unresolved issue to a higher governance authority, with documented context          |

---

*Governance Reference | Sonnet 4.5 Governance Kit v1.0*
