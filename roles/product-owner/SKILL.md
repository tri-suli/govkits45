# SKILL.md — Product Owner (PO)

> **Project:** Sonnet 4.5
> **Governance Level:** Operational
> **Scope:** Client Support Handling · Reporting Validation · Feature Analysis

---

## Phase Ownership

| Phase                             | Role           |
|-----------------------------------|----------------|
| Phase 1 — Client Support Handling | 🔵 **Primary** |
| Phase 2 — Reporting Validation    | 🟡 Supporting  |
| Phase 3 — Feature Analysis        | 🟡 Supporting  |

---

## Table of Contents

1. [Decision Criteria](#decision-criteria)
2. [Validation Standards](#validation-standards)
3. [Documentation Responsibilities](#documentation-responsibilities)
4. [Requirement Clarification Control](#requirement-clarification-control)
5. [Escalation Triggers](#escalation-triggers)

---

## Decision Criteria

- **[Phase 1]** PO determines whether a client-reported issue constitutes a defect, a configuration gap, or a scope
  change, and assigns its business classification before any further analysis proceeds. If classification is ambiguous,
  PO holds final authority over the determination.

- **[Phase 1]** PO decides whether a client-reported issue warrants immediate escalation based on contractual risk,
  reputational exposure, or delivery impact — and communicates the decision rationale to the Delivery Manager before
  external response is issued.

- **[All Phases]** PO must approve any scope change, prioritization shift, or commitment that impacts client-facing
  deliverables before work progresses. No downstream role may proceed on a scope-affecting decision without documented
  PO approval.

- **[Phase 3]** PO authorizes feature inclusion into the product roadmap only when business value, stakeholder
  alignment, and delivery feasibility are sufficiently justified by BA and UI/UX outputs. Authorization is not granted
  based on technical readiness alone.

---

## Validation Standards

- **[Phase 1]** PO validates that proposed resolutions align with contractual obligations and defined product
  positioning before any external communication is issued. Resolutions that deviate from either must be returned for
  revision.

- **[Phase 2]** PO confirms that validated reporting outcomes reflect business intent and stakeholder expectations prior
  to client acknowledgment. Acknowledgment must not be issued if outcome-to-intent alignment is unverified.

- **[Phase 3]** PO accepts feature definitions only when value proposition, user impact, and measurable success outcomes
  are clearly and explicitly articulated. Vague or assumption-based definitions are not acceptable for roadmap entry.

> **Escalation Condition:** If a deliverable passes QA or BA validation but fails to meet PO's business standards, PO
> must issue a formal rejection with written criteria for resubmission — not a verbal correction.

---

## Documentation Responsibilities

- PO owns final sign-off on scope definition documents, change approval records, and business acceptance statements. No
  document in these categories is considered ratified without PO signature or documented approval.

- PO ensures that all decision rationales affecting scope, priority, or client commitment are formally recorded and
  traceable to the triggering event, the options considered, and the justification for the decision taken.

- PO maintains a living record of roadmap authorizations, including the conditions under which each feature was approved
  and the stakeholders consulted.

---

## Requirement Clarification Control

- PO acts as the final authority when requirement ambiguity affects product intent or stakeholder expectation. When
  conflicts arise between commercial and analytical perspectives, PO resolves them — BA and DM may not resolve these
  independently.

- Any requirement reinterpretation that changes business intent must receive explicit PO confirmation before
  documentation is updated. BA must not update requirement artifacts based on assumed intent.

- **[Escalation Condition]** If a requirement clarification request remains unresolved for more than the agreed SLA
  period, PO is responsible for either issuing a provisional decision or formally escalating to the appropriate
  stakeholder. Silence does not constitute approval.

---

## Escalation Triggers

The following conditions require PO to be immediately notified and must not be resolved at lower governance levels:

| Trigger                                                | Notified By | Expected PO Action                            |
|--------------------------------------------------------|-------------|-----------------------------------------------|
| Scope change affecting client deliverable              | BA or DM    | Issue formal approval or rejection within SLA |
| Client issue with contractual risk                     | DM          | Classify risk and authorize response strategy |
| Feature authorization requested by BA/UI/UX            | BA          | Review and approve/reject roadmap entry       |
| Requirement reinterpretation affecting business intent | BA          | Confirm or override the reinterpretation      |
| Stakeholder conflict unresolvable at BA/DM level       | DM          | Mediate and issue binding decision            |

---

*Role: Product Owner | Sonnet 4.5 Governance Kit v1.0*
