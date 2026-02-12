# Trello Card Template — Reporting Validation (Phase 2)

> **Phase:** Phase 2 — Reporting Validation
> **Card Owner:** Business Analyst (Primary) · QA Analyst (Primary)
> **Tracking Prefix:** `DATA`

---

## Card Title Format

```
[DATA]-[YYYY]-[NNN] | [REPORT/MODULE] — [VALIDATION SUBJECT]
```

**Example:**

```
DATA-2026-012 | Monthly Sales Report — Validation of Q1 Total Revenue Non-Conformance
```

---

## Card Description Template

```markdown
## 📋 Validation Overview

| Field | Value |
|---|---|
| **Tracking ID** | DATA-[YYYY]-[NNN] |
| **Validation Requested By** | [ROLE] |
| **Source** | [Client Report / Internal Finding / Scheduled Validation] |
| **Received At** | [DD Mmm YYYY HH:MM] |
| **Report / Module** | [REPORT NAME] |
| **Submodule / Dimension** | [SUBMODULE — if applicable] |
| **Data Period** | [DATE RANGE of affected data] |
| **Phase** | Phase 2 — Reporting Validation |

---

## 📝 Discrepancy Description

> [CLEAR DESCRIPTION OF WHAT WAS REPORTED OR OBSERVED — no technical detail]

**Expected Outcome:**
[WHAT SHOULD HAVE BEEN THE CORRECT OUTPUT — based on business rules]

**Actual Outcome:**
[WHAT WAS OBSERVED]

---

## 📐 Acceptance Criteria Reference

> **To be confirmed by BA before validation begins**

- **Business Rule Reference:** [RULE ID / DOCUMENT VERSION]
- **Acceptance Criteria Version:** [VERSION]
- **Criteria Status:** [ ] Complete  [ ] Incomplete — validation blocked

**If criteria are incomplete or ambiguous:**
> ⚠️ Validation must NOT proceed. Return to BA for criteria completion.

---

## 🔍 BA Root Cause Classification

> **To be completed by BA**

- [ ] Requirement Misinterpretation
- [ ] Business Rule Misalignment
- [ ] Stakeholder Misunderstanding
- [ ] Data Source Issue (outside scope — escalate)
- [ ] Pending Classification

**Classification Rationale:**
[TO BE FILLED BY BA]

**Escalation Required:**

- [ ] No escalation needed
- [ ] Escalate to PO (business intent conflict)
- [ ] Escalate to DM (delivery/timeline risk)

---

## ✅ QA Validation Record

> **To be completed by QA against approved criteria only**

| Validation Item | Criteria Ref | Result | Notes |
|---|---|---|---|
| Business rule consistency | [RULE ID] | Pass / Fail / N/A | |
| Boundary condition handling | [RULE ID] | Pass / Fail / N/A | |
| Exception scenario coverage | [RULE ID] | Pass / Fail / N/A | |

**Overall Validation Status:**

- [ ] ✅ Passed — sign-off issued
- [ ] ❌ Rejected — see deficiency statement below
- [ ] ⏸ Blocked — criteria incomplete

**Deficiency Statement (if rejected):**
[SPECIFIC DEFICIENCY — requirement clause, condition unmet]

**Requirement Version Used:** [VERSION]

---

## 📎 Documentation & References

- Requirement spec: [link or version reference]
- Acceptance criteria doc: [link or version reference]
- Client WhatsApp log: [link or "N/A"]
- Previous related card: [link or "none"]

---

## 🔄 Status Log

| Date | Updated By | Status | Note |
|---|---|---|---|
| [DD Mmm YYYY] | [ROLE] | Created | Validation task initiated |
| | | | |

---

## ✔️ Checklist

```markdown

[ ] Tracking ID assigned
[ ] Acceptance criteria confirmed complete by BA
[ ] Root cause classification completed by BA
[ ] QA validation performed against approved criteria
[ ] Validation record completed with version reference
[ ] PO confirmation of business intent alignment (if required)
[ ] Resolution or finding communicated to client (if originated from client report)
[ ] DM informed if delivery/timeline impact exists
[ ] Card closed with all artifacts linked

```

---

## Labels (Recommended)

| Label Color | Meaning |
|---|---|
| 🔴 Red | Validation blocked / Criteria incomplete |
| 🟡 Yellow | In validation / Awaiting QA |
| 🟢 Green | Validated & Passed |
| 🔵 Blue | Awaiting BA classification |
| 🟣 Purple | Escalated to PO |
| ⚫ Black | On hold / Blocked externally |

---

## Trello List Flow

```

📥 Backlog → 📐 Criteria Confirmation → 🔍 BA Classification → ✅ QA Validation → 📣 Communication → 🏁 Closed

```

---

*Template: Trello Card — Reporting Validation | Sonnet 4.5 Governance Kit v1.0*
