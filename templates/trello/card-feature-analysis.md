# Trello Card Template — Feature Analysis (Phase 3)

> **Phase:** Phase 3 — Feature Analysis
> **Card Owner:** Business Analyst (Primary) · UI/UX Designer (Primary)
> **Tracking Prefix:** `FEAT`

---

## Card Title Format

```
[FEAT]-[YYYY]-[NNN] | [MODULE] — [FEATURE NAME]
```

**Example:**

```
FEAT-2026-005 | Dashboard Module — Dynamic filters by user segment
```

---

## Card Description Template

```markdown
## 📋 Feature Overview

| Field | Value |
|---|---|
| **Tracking ID** | FEAT-[YYYY]-[NNN] |
| **Requested By** | [CLIENT NAME / INTERNAL TEAM] |
| **Source** | [WhatsApp Request / Internal Discovery / Phase 1 Reclassification] |
| **Received At** | [DD Mmm YYYY] |
| **Module** | [MODULE NAME] |
| **Submodule** | [SUBMODULE — if applicable] |
| **Phase** | Phase 3 — Feature Analysis |
| **PO Authorization** | [ ] Pending  [ ] Approved  [ ] Deferred |

---

## 📝 Feature Request Summary

> [PLAIN LANGUAGE DESCRIPTION OF WHAT THE CLIENT/STAKEHOLDER WANTS]

**Business Motivation:**
[WHY THIS FEATURE IS NEEDED — business value, user pain point, or strategic intent]

---

## 🎯 BA Requirement Analysis

> **Primary: Business Analyst**

### Elicitation Status

- [ ] Initial stakeholder consultation completed
- [ ] Clarification session conducted (date: [DD Mmm YYYY])
- [ ] Requirements sufficiently defined and testable
- [ ] Requirements submitted for QA testability review

### Change Classification

- [ ] Clarification (no scope impact)
- [ ] Correction (fixes existing documented requirement)
- [ ] New Scope (requires PO approval before proceeding)

**Classification Rationale:**
[TO BE FILLED BY BA]

### Requirement Completeness

- [ ] Measurable and unambiguous
- [ ] Traceable to stakeholder intent
- [ ] Acceptance criteria defined
- [ ] Business rule reference documented

**Requirement Document Version:** [VERSION]
**Acceptance Criteria Version:** [VERSION]

---

## 🎨 UI/UX Design Analysis

> **Primary: UI/UX Designer**

### Design Readiness

- [ ] User journey map created
- [ ] Interaction flows defined
- [ ] State coverage complete (normal, error, empty, loading, edge cases)
- [ ] Consistency with existing patterns confirmed
- [ ] Design assumptions documented and shared with BA

### Scope Implication Check

- [ ] No scope implications identified
- [ ] Scope implication found — escalated to PO ([DD Mmm YYYY])
- [ ] Usability risk identified — escalated to BA ([DD Mmm YYYY])

**Design Artifact Version:** [VERSION]
**Design Assumptions Log:** [link or "attached"]

---

## ✅ QA Testability Review

> **Supporting: QA Analyst**

- [ ] Requirements reviewed for testability
- [ ] All requirements testable — proceed
- [ ] Non-testable requirements found — returned to BA (see notes)

**Non-testable Items (if any):**
[DESCRIPTION — returned to BA for refinement]

---

## 🏁 PO Authorization

> **Required before roadmap entry**

| Item | Status |
|---|---|
| Business value justified | [ ] Yes  [ ] No |
| Stakeholder alignment confirmed | [ ] Yes  [ ] No |
| Delivery feasibility confirmed by DM | [ ] Yes  [ ] No |
| Measurable success outcome defined | [ ] Yes  [ ] No |

**PO Decision:** [ ] Approved for Roadmap  [ ] Deferred  [ ] Requires More Analysis
**Authorization Date:** [DD Mmm YYYY]
**Roadmap Target:** [SPRINT / QUARTER / TBD]

---

## 📎 Documentation & References

- Requirement specification: [link or version]
- Acceptance criteria: [link or version]
- Design artifacts: [link]
- Design assumptions log: [link or "attached"]
- Stakeholder consultation notes: [link or "attached"]
- Originating card (if reclassified): [link or "N/A"]

---

## 🔄 Status Log

| Date | Updated By | Status | Note |
|---|---|---|---|
| [DD Mmm YYYY] | [ROLE] | Created | Feature analysis initiated |
| | | | |

---

## ✔️ Checklist

```markdown

[ ] Tracking ID assigned
[ ] Client/stakeholder acknowledged (WhatsApp FEAT template sent)
[ ] Change classification completed by BA
[ ] BA clarification session conducted
[ ] Requirements defined as measurable and testable
[ ] UI/UX interaction flows and state coverage completed
[ ] Design assumptions documented and confirmed with BA
[ ] QA testability review passed
[ ] Scope implications reviewed by PO (if any)
[ ] PO authorization for roadmap entry obtained
[ ] DM confirms delivery feasibility
[ ] Client notified of analysis outcome
[ ] Card archived with all artifacts linked

```

---

## Labels (Recommended)

| Label Color | Meaning                                                     |
|-------------|-------------------------------------------------------------|
| 🔴 Red      | Blocked — awaiting PO decision or unresolved scope conflict |
| 🟡 Yellow   | In analysis — BA or UI/UX working                           |
| 🟢 Green    | PO authorized — in roadmap                                  |
| 🔵 Blue     | Awaiting clarification from client/stakeholder              |
| 🟣 Purple   | Deferred — revisit in next cycle                            |
| 🟠 Orange   | QA testability issue — returned to BA                       |

---

## Trello List Flow

```

📥 Backlog → 📝 BA Analysis → 🎨 UI/UX Design → ✅ QA Testability → 🏁 PO Authorization → 📣 Client Communication → 🗂 Archived

```

---

*Template: Trello Card — Feature Analysis | Sonnet 4.5 Governance Kit v1.0*
