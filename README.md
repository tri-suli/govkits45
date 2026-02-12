# 📦 Sonnet 4.5 — AI-Assisted Project Governance Kit

> Operational governance documentation for AI-assisted project execution.
> Applicable to: **Client Support Handling**, **Reporting Validation**, and **Feature Analysis** phases.

---

## 📋 Table of Contents

1. [Overview](#overview)
2. [Project Scope](#project-scope)
3. [Phase-to-Role Mapping](#phase-to-role-mapping)
4. [Role Documentation](#role-documentation)
5. [Templates](#templates)
   - [WhatsApp Client Support](#whatsapp-client-support)
   - [Trello Card Templates](#trello-card-templates)
6. [Governance Pillars](#governance-pillars)
7. [Escalation Matrix](#escalation-matrix)
8. [File Structure](#file-structure)
9. [Usage Guide](#usage-guide)

---

## Overview

This kit provides structured, role-based operational guidance for teams using AI-assisted project execution. All instructions operate at the **operational governance level** — defining *who decides what under which condition*, not how tasks are executed step by step.

> **Abstraction Principle:**
> ✅ `"PO must approve all scope changes affecting client-facing deliverables before BA proceeds."`
> ❌ `"PO reviews the document, updates JIRA, and sends approval email."` ← too granular
> ❌ `"PO is responsible for scope integrity."` ← too abstract

---

## Project Scope

This documentation applies **only** to the following phases:

| Phase | Name | Description |
|---|---|---|
| Phase 1 | **Client Support Handling** | Managing and classifying inbound client-reported issues |
| Phase 2 | **Reporting Validation** | Verifying that reported outputs meet business rules and acceptance criteria |
| Phase 3 | **Feature Analysis** | Eliciting, defining, and validating new feature requirements |

> ⚠️ **Excluded from scope:** System architecture, implementation logic, database schema, API behavior, and all technical design concerns.

---

## Phase-to-Role Mapping

| Role | Phase 1 (Client Support) | Phase 2 (Reporting Validation) | Phase 3 (Feature Analysis) |
|---|---|---|---|
| Product Owner | 🔵 Primary | 🟡 Supporting | 🟡 Supporting |
| Delivery Manager | 🔵 Primary | 🟡 Supporting | 🟡 Supporting |
| Business Analyst | 🟡 Supporting | 🔵 Primary | 🔵 Primary |
| QA Analyst | 🟡 Supporting | 🔵 Primary | 🟡 Supporting |
| UI/UX Designer | — | 🟡 Supporting | 🔵 Primary |

🔵 = Primary ownership | 🟡 = Supporting role

---

## Role Documentation

Each role has a dedicated `SKILL.md` covering all four governance pillars.

| Role | File |
|---|---|
| 🧑‍💼 Product Owner | [`roles/product-owner/SKILL.md`](roles/product-owner/SKILL.md) |
| 📋 Delivery Manager | [`roles/delivery-manager/SKILL.md`](roles/delivery-manager/SKILL.md) |
| 🔍 Business Analyst | [`roles/business-analyst/SKILL.md`](roles/business-analyst/SKILL.md) |
| ✅ QA Analyst | [`roles/qa-analyst/SKILL.md`](roles/qa-analyst/SKILL.md) |
| 🎨 UI/UX Designer | [`roles/ui-ux/SKILL.md`](roles/ui-ux/SKILL.md) |

---

## Templates

### WhatsApp Client Support

Templates for outbound client communication via WhatsApp.

| Template | Description | File |
|---|---|---|
| Bug Report Response | Response to client-reported bugs | [`templates/whatsapp/bug-response.md`](templates/whatsapp/bug-response.md) |
| Data Issue Response | Response to data discrepancy reports | [`templates/whatsapp/data-response.md`](templates/whatsapp/data-response.md) |
| Feature Request Acknowledgment | Acknowledging a new feature request | [`templates/whatsapp/feature-request.md`](templates/whatsapp/feature-request.md) |

### Trello Card Templates

Standardized Trello card structures for each phase.

| Template | Description | File |
|---|---|---|
| Client Issue Card | Trello card for Phase 1 issues | [`templates/trello/card-client-issue.md`](templates/trello/card-client-issue.md) |
| Reporting Validation Card | Trello card for Phase 2 validation tasks | [`templates/trello/card-reporting-validation.md`](templates/trello/card-reporting-validation.md) |
| Feature Analysis Card | Trello card for Phase 3 feature work | [`templates/trello/card-feature-analysis.md`](templates/trello/card-feature-analysis.md) |
| Card Comment Templates | Standard comment formats for progress updates | [`templates/trello/card-comments.md`](templates/trello/card-comments.md) |

---

## Governance Pillars

All role documentation is structured around four consistent pillars:

| Pillar | Description |
|---|---|
| **Decision Criteria** | What conditions trigger a decision, and who owns it |
| **Validation Standards** | What constitutes an acceptable output or deliverable |
| **Documentation Responsibilities** | What artifacts this role owns or signs off on |
| **Requirement Clarification Control** | How this role manages ambiguity or change requests |

---

## Escalation Matrix

| Trigger Condition | Escalated By | Escalated To | Action Required |
|---|---|---|---|
| Scope change affecting client deliverable | BA / DM | PO | Formal approval before proceeding |
| Delivery risk from requirement ambiguity | BA | DM | Halt scheduling until clarified |
| Unapproved scope expansion detected | DM | PO | Halt execution, restore governance alignment |
| Non-testable or contradictory requirements | QA | BA | Return for refinement before retesting |
| Design-driven scope implication | UI/UX | PO | Review and approval required |
| Business intent conflict between commercial & analytical views | BA | PO | PO resolves as final authority |
| Client issue unresolvable at support level | DM | PO | Escalation with documented risk classification |

---

## File Structure

```
sonnet45-project/
│
├── README.md                          ← You are here
│
├── roles/
│   ├── product-owner/
│   │   └── SKILL.md
│   ├── delivery-manager/
│   │   └── SKILL.md
│   ├── business-analyst/
│   │   └── SKILL.md
│   ├── qa-analyst/
│   │   └── SKILL.md
│   └── ui-ux/
│       └── SKILL.md
│
├── templates/
│   ├── whatsapp/
│   │   ├── bug-response.md
│   │   ├── data-response.md
│   │   └── feature-request.md
│   └── trello/
│       ├── card-client-issue.md
│       ├── card-reporting-validation.md
│       ├── card-feature-analysis.md
│       └── card-comments.md
│
└── docs/
    └── governance-reference.md
```

---

## Usage Guide

**For new team members:**
1. Start with this `README.md` to understand scope and roles
2. Open your role's `SKILL.md` under `roles/`
3. Reference the Escalation Matrix before escalating any issue
4. Use templates in `templates/` for all external and internal communications

**For Product Owners and Delivery Managers:**
- Review the Phase-to-Role Mapping to understand where your primary authority applies
- Use the Escalation Matrix as the canonical reference for governance decisions

**For Business Analysts, QA Analysts, and UI/UX Designers:**
- Your `SKILL.md` defines the boundaries of your clarification authority
- Always escalate business intent changes to PO — do not reinterpret independently

---

*Last updated: 2026 | Project: Sonnet 4.5 | Governance Kit v1.0*
