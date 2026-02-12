# Trello Card Template — Client Issue (Phase 1)

> **Phase:** Phase 1 — Client Support Handling
> **Card Owner:** Delivery Manager
> **Tracking Prefix:** `BUG` | `DATA`

---

## Card Title Format

```
[BUG|DATA]-[YYYY]-[NNN] | [MODULE(: SUBMODULE)] — [SUBJECT BRIEF]
```

**Example:**

```
BUG-2026-001 | Payment Module — Failed Transactions Not Updated in the Dashboard
```

---

## Card Description Template

```markdown
## 📋 Issue Overview

| Field | Value |
|---|---|
| **Tracking ID** | BUG/DATA-[YYYY]-[NNN] |
| **Reported By** | [CLIENT NAME (ROLE)] |
| **Reported Via** | WhatsApp |
| **Received At** | [DD Mmm YYYY HH:MM] |
| **Module** | [MODULE NAME] |
| **Submodule** | [SUBMODULE — if applicable] |
| **Phase** | Phase 1 — Client Support Handling |

---

## 📝 Client Report Summary

> [VERBATIM OR CLOSE PARAPHRASE OF CLIENT'S ORIGINAL MESSAGE]

---

## 🔍 Initial Classification

> **To be completed by PO within [X hours] of card creation**

- [ ] Defect
- [ ] Configuration Gap
- [ ] Scope Change
- [ ] Requires Further Investigation

**Classification Rationale:**
[TO BE FILLED BY PO]

---

## ✅ Reproducibility Status

> **To be confirmed by QA**

- [ ] Reproduced — conditions documented below
- [ ] Not Reproduced — details documented below
- [ ] Pending

**Reproduction Notes:**
[TO BE FILLED BY QA]

---

## 📌 Resolution Path

> **To be decided by DM after classification**

- [ ] Internal resolution (team handles)
- [ ] Requires cross-functional coordination
- [ ] Requires PO escalation
- [ ] Reclassified → Feature Analysis (new FEAT card required)

**Resolution Owner:** [ROLE]
**Target Resolution Date:** [DD Mmm YYYY]

---

## 📎 Attachments & References

- WhatsApp log: [link or "attached"]
- Screenshot from client: [link or "none"]
- Related card: [card link or "none"]

---

## 🔄 Status Log

| Date | Updated By | Status | Note |
|---|---|---|---|
| [DD Mmm YYYY] | [ROLE] | Created | Initial card creation |
| | | | |
```

---

## Labels (Recommended)

| Label Color | Meaning                                |
|-------------|----------------------------------------|
| 🔴 Red      | High urgency / Contractual risk        |
| 🟡 Yellow   | Medium urgency / Under investigation   |
| 🟢 Green    | Resolved / Pending client confirmation |
| 🔵 Blue     | Awaiting client clarification          |
| 🟣 Purple   | Reclassified to Feature Analysis       |
| ⚫ Black     | On hold / Blocked                      |

---

## Checklist Template

```
[ ] Tracking ID assigned
[ ] Client notified via WhatsApp (Acknowledgment sent)
[ ] Initial classification by PO completed
[ ] Reproducibility confirmed by QA
[ ] Resolution path decided by DM
[ ] Resolution delivered and internally validated
[ ] Client notified of resolution
[ ] Client confirmation received
[ ] Card closed and archived
```

---

## Trello List Flow

```
📥 Incoming → 🔍 Under Investigation → 🔄 In Resolution → ✅ Awaiting Client Confirmation → 🏁 Closed
```

---

*Template: Trello Card — Client Issue | Sonnet 4.5 Governance Kit v1.0*
