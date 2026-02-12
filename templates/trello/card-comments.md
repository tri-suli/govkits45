# Trello Card Comment Templates

> **Purpose:** Standardized comment formats for progress updates, escalations, decisions, and status changes across all
> phases.
> **Usage:** Copy the appropriate template, fill in the brackets, and post as a Trello card comment.

---

## Table of Contents

1. [Progress Update Comments](#1-progress-update-comments)
2. [Classification & Decision Comments](#2-classification--decision-comments)
3. [Escalation Comments](#3-escalation-comments)
4. [Rejection & Return Comments](#4-rejection--return-comments)
5. [Approval & Sign-off Comments](#5-approval--sign-off-comments)
6. [Halt & Unblock Comments](#6-halt--unblock-comments)
7. [Closure Comments](#7-closure-comments)

---

## 1. Progress Update Comments

### General Progress Update

```
📌 STATUS UPDATE — [DD Mmm YYYY HH:MM]
Posted by: [ROLE]

Status: [In Progress / Under Review / Awaiting Input]

Progress summary:
[1–2 sentence plain language update on what has been done]

Next step: [WHAT HAPPENS NEXT]
Next step owner: [ROLE]
Expected by: [DD Mmm YYYY]
```

---

### Investigation In Progress (Phase 1 / Phase 2)

```
🔍 INVESTIGATION UPDATE — [DD Mmm YYYY HH:MM]
Posted by: [QA / BA — ROLE]

Investigation status: In Progress

Findings so far:
[BRIEF NON-TECHNICAL SUMMARY — what has been checked, what is still being assessed]

Estimated completion: [DD Mmm YYYY]
Blocking dependencies: [None / Specify]
```

---

### Clarification Session Completed (Phase 3)

```
🗣️ CLARIFICATION SESSION COMPLETED — [DD Mmm YYYY HH:MM]
Posted by: BA

Session date: [DD Mmm YYYY]
Participants: [NAMES / ROLES]

Key outcomes:
- [OUTCOME 1]
- [OUTCOME 2]
- [OUTCOME 3 — if applicable]

Requirements status: [Sufficient to proceed / Requires follow-up session]
Next action: [ACTION] — Owner: [ROLE] — By: [DD Mmm YYYY]
```

---

## 2. Classification & Decision Comments

### Issue Classification by PO (Phase 1)

```
🏷️ CLASSIFICATION DECISION — [DD Mmm YYYY HH:MM]
Posted by: PO

Classification: [Defect / Configuration Gap / Scope Change / Requires Investigation]

Rationale:
[BRIEF EXPLANATION — what criteria led to this classification]

Approved resolution path: [RESOLUTION TYPE]
Resolution owner: [ROLE]
Target resolution date: [DD Mmm YYYY]

Note: [ANY ADDITIONAL GOVERNANCE NOTE — optional]
```

---

### BA Change Classification (Phase 3)

```
📂 CHANGE CLASSIFICATION — [DD Mmm YYYY HH:MM]
Posted by: BA

Change type: [Clarification / Correction / New Scope]

Rationale:
[WHY THIS CLASSIFICATION WAS ASSIGNED — stakeholder input basis]

Action required:
- Clarification / Correction: Proceed to documentation update
- New Scope: ⚠️ PO approval required before proceeding — do not advance card

Submitted to PO: [Yes — DD Mmm YYYY / Pending]
```

---

## 3. Escalation Comments

### Escalation to PO

```
⚠️ ESCALATION TO PO — [DD Mmm YYYY HH:MM]
Posted by: [ROLE]

Escalation reason:
[SPECIFIC TRIGGER — e.g., "scope change detected without PO approval", "conflicting stakeholder input on business intent"]

Impact if unresolved:
[DELIVERY / VALIDATION / CLIENT IMPACT]

Options for resolution:
1. [OPTION A]
2. [OPTION B]

Decision required by: [DD Mmm YYYY]
@[PO NAME] — please review and issue decision as comment on this card.
```

---

### Escalation to DM (Delivery Risk)

```
🚨 DELIVERY RISK ESCALATION — [DD Mmm YYYY HH:MM]
Posted by: [ROLE]

Risk description:
[WHAT IS AT RISK — timeline, capacity, commitment]

Trigger:
[SPECIFIC CONDITION THAT TRIGGERED THIS ESCALATION]

Estimated delivery impact:
[DAYS / SCOPE — be specific]

Proposed mitigation:
[WHAT CAN BE DONE TO REDUCE IMPACT]

@[DM NAME] — action required before [DD Mmm YYYY].
```

---

### Escalation — Unresolved Clarification Beyond SLA

```
⏰ SLA BREACH — CLARIFICATION UNRESOLVED — [DD Mmm YYYY HH:MM]
Posted by: [ROLE]

Original clarification request: [DATE OF ORIGINAL REQUEST]
SLA deadline: [DATE]
Current status: Unresolved — [X] days overdue

Impact on card progress:
[WHAT IS BLOCKED]

Requesting PO/DM intervention to:
[ ] Issue provisional decision
[ ] Formally escalate to stakeholder
[ ] Adjust timeline to accommodate delay

@[DM NAME] @[PO NAME] — response required.
```

---

## 4. Rejection & Return Comments

### QA Validation Rejection

```
❌ VALIDATION REJECTED — [DD Mmm YYYY HH:MM]
Posted by: QA

Rejection reason:
[SPECIFIC DEFICIENCY — reference requirement clause or acceptance criteria section]

Requirement clause violated: [RULE/CLAUSE ID]
Requirement version referenced: [VERSION]

Conditions required for resubmission:
1. [CONDITION 1]
2. [CONDITION 2 — if applicable]

Returned to: BA
Expected resubmission by: [DD Mmm YYYY]

Note: Validation cycle will restart fresh upon resubmission.
```

---

### Requirements Returned to BA (Non-testable)

```
🔁 REQUIREMENTS RETURNED — QA TESTABILITY ISSUE — [DD Mmm YYYY HH:MM]
Posted by: QA

Testability issue identified in:
- Requirement: [REQUIREMENT ID / DESCRIPTION]
- Issue: [NON-TESTABLE CONDITION / CONTRADICTORY CLAUSE]

QA will not proceed with validation planning until this is resolved.

Returned to: BA
Expected resolution by: [DD Mmm YYYY]

@[BA NAME] — please revise and post updated version reference as reply.
```

---

### Design Returned to UI/UX (Incomplete State Coverage)

```
🔁 DESIGN RETURNED — INCOMPLETE STATE COVERAGE — [DD Mmm YYYY HH:MM]
Posted by: BA

State coverage gaps identified:
- [ ] Error state — missing
- [ ] Empty state — missing
- [ ] Edge case: [SPECIFY] — missing

Design cannot proceed to validation until all states are documented.

Returned to: UI/UX
Expected resolution by: [DD Mmm YYYY]

@[UI/UX NAME] — please update design artifact and post new version link.
```

---

## 5. Approval & Sign-off Comments

### PO Scope Approval

```
✅ SCOPE APPROVED — [DD Mmm YYYY HH:MM]
Posted by: PO

Approval scope: [WHAT HAS BEEN APPROVED]
Approval conditions: [ANY CONDITIONS OR CONSTRAINTS — or "None"]
Authorized by: [PO NAME]

Next step: [ROLE] to proceed with [ACTION]
```

---

### QA Validation Sign-off

```
✅ VALIDATION SIGN-OFF — [DD Mmm YYYY HH:MM]
Posted by: QA

Validation result: PASSED
Requirement version validated against: [VERSION]
Criteria version: [VERSION]

All validation items confirmed:
- Business rule consistency: ✅
- Boundary condition handling: ✅
- Exception scenario coverage: ✅

Official sign-off issued. Card may proceed to next stage.
```

---

### PO Feature Roadmap Authorization

```
🗺️ ROADMAP AUTHORIZATION — [DD Mmm YYYY HH:MM]
Posted by: PO

Feature authorized for roadmap: [FEAT TRACKING ID]
Authorization basis:
- Business value: ✅ Justified
- Stakeholder alignment: ✅ Confirmed
- Delivery feasibility: ✅ Confirmed by DM
- Success outcome defined: ✅

Roadmap target: [SPRINT / QUARTER / TBD]
Next action: DM to include in delivery planning.
```

---

## 6. Halt & Unblock Comments

### Execution Halted (Unapproved Scope Expansion)

```
🛑 EXECUTION HALTED — [DD Mmm YYYY HH:MM]
Posted by: DM

Reason: Scope expansion detected without PO approval.

Scope in question: [DESCRIPTION]
Discovery source: [HOW IT WAS DETECTED]

All work on this card is suspended pending governance alignment.

@[PO NAME] — approval or rejection required before execution resumes.
Card will remain halted until PO decision is posted here.
```

---

### Card Unblocked

```
✅ CARD UNBLOCKED — [DD Mmm YYYY HH:MM]
Posted by: [DM / PO — ROLE]

Unblocked reason: [WHAT WAS RESOLVED]
Resolution decision: [BRIEF SUMMARY]
Authorized by: [ROLE — NAME]

Resuming from: [STAGE / STEP]
Next action owner: [ROLE]
Expected by: [DD Mmm YYYY]
```

---

## 7. Closure Comments

### Card Closed — Resolved

```
🏁 CARD CLOSED — [DD Mmm YYYY HH:MM]
Posted by: [DM / BA — ROLE]

Resolution status: ✅ Resolved
Client confirmation received: [Yes — DD Mmm YYYY / Not required]

All checklist items: ✅ Complete
All artifacts linked: ✅ Confirmed

Closed by: [NAME (ROLE)]
Archive reference: [CARD URL / ARCHIVE LOCATION]
```

---

### Card Closed — Deferred

```
🗂️ CARD DEFERRED — [DD Mmm YYYY HH:MM]
Posted by: PO

Deferral reason: [NON-TECHNICAL REASON]
Revisit timeline: [SPRINT / QUARTER / TBD]
Deferred by: [PO NAME]

Outstanding items at time of deferral:
- [ITEM 1 — optional]
- [ITEM 2 — optional]

Card will be reopened with a new cycle ID when revisited.
```

---

*Template: Trello Card Comments | Sonnet 4.5 Governance Kit v1.0*
