# WhatsApp Template — Data Issue Response

> **Tracking Prefix:** `DATA`
> **Applicable Phase:** Phase 2 — Reporting Validation
> **Sent By:** Business Analyst (draft) → Delivery Manager (authorized sender)

---

## Template Structure Reference

```
========================================
SENT_AT         : [Send during business hours 9 AM - 5 PM]
SENT_BY         : [TEAM NAME | ROLE NAME]
REPLIED_AT      : [DD] [Mmm] [YYYY] [HH]:[MM]
REPLIED_BY      : [CLIENT NAME (ROLE)]
REPLY_MESSAGE   : [CLIENT MESSAGE]
========================================
```

---

## Template: Initial Acknowledgment

```
========================================
SENT_AT         : [DD Mmm YYYY | HH:MM — within business hours 09:00–17:00]
SENT_BY         : [Team Name | Delivery Manager]
REPLIED_AT      : -
REPLIED_BY      : -
REPLY_MESSAGE   : -
========================================

Hi [CLIENT NAME],

*Tracking ID:* DATA-[YYYY]-[NNN]
*Re:* [MODULE] - [SUBMODULE if any] - Data Report: [SUBJECT BRIEF]

Thank you for your report. We have noted any data discrepancies you reported and will investigate immediately.

---

*Information we receive:*
• Affected reports/modules: [REPORT/MODULE NAME]
• Description of non-conformity: [BRIEF DESCRIPTION FROM CLIENT]
• Data period in question: [DATE RANGE if relevant]

Our team will conduct a search of applicable business rules and validation criteria to determine the source of these nonconformities.

---

Estimasi waktu investigasi awal: *[X jam kerja]*

During the investigation process, please do not use the reported data as a reference for operational decisions until we provide further confirmation.

---

Best Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Template: Clarification Request (Requesting Additional Information)

```
========================================
SENT_AT         : [DD Mmm YYYY | HH:MM — within business hours 09:00–17:00]
SENT_BY         : [Team Name | Business Analyst via Delivery Manager]
REPLIED_AT      : [DD] [Mmm] [YYYY] [HH]:[MM]
REPLIED_BY      : [CLIENT NAME (ROLE)]
REPLY_MESSAGE   : [CLIENT'S LAST MESSAGE SUMMARY]
========================================

Halo [CLIENT NAME],

*Tracking ID:* DATA-[YYYY]-[NNN]
*Re:* [MODULE] - [SUBMODULE] - Request for Clarification: [SUBJECT BRIEF]

In order to expedite the process of investigating the data you report, we need some additional information to ensure the analysis we are conducting is in line with your expectations.

---

*Information we need:*

1. [CLARIFICATION QUESTION 1 — specific, non-technical, business-context only]
2. [CLARIFICATION QUESTION 2]
3. [CLARIFICATION QUESTION 3 — if applicable]

---

Please provide the above information before *[DD Mmm YYYY]* so that the investigation process is not further delayed.

If there are relevant document references or screenshots, you can attach them in the reply to this message.

---

Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Template: Resolution — Data Discrepancy Explained

```
========================================
SENT_AT         : [DD Mmm YYYY | HH:MM — within business hours 09:00–17:00]
SENT_BY         : [Team Name | Delivery Manager]
REPLIED_AT      : [DD] [Mmm] [YYYY] [HH]:[MM]
REPLIED_BY      : [CLIENT NAME (ROLE)]
REPLY_MESSAGE   : [CLIENT'S LAST MESSAGE SUMMARY]
========================================

Halo [CLIENT NAME],

*Tracking ID:* DATA-[YYYY]-[NNN]
*Re:* [MODULE] - [SUBMODULE] - Penjelasan Hasil Investigasi: [SUBJECT BRIEF]

The investigation of the data report you submitted has been completed. Here is a summary of our findings.

---

*Status:* ✅ Investigasi Selesai
*Classification of findings:* [Business Rule Inconsistency / Interpretation Differences / Scope Gap / More]
*Validated by:* QA Analyst & Business Analyst — [DATE]

*Summary of findings (non-technical):*
[PLAIN LANGUAGE EXPLANATION aligned with business rule — no technical implementation detail]

*Actions that have been/will be taken:*
[ACTION TAKEN or TO BE TAKEN — framed as outcome, not process]

---

[IF THERE IS A SCOPE GAP THAT NEEDS TO BE ACTED UPON:]
We also note that this report indicates a need that is not currently covered.
Our team will follow up on this through a separate Feature Analysis process.
You will get a new Tracking ID for the process.

---

Please confirm whether this explanation answers your report.
If there is any ambiguity, please convey it through this message reply.

---

Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Governance Notes

> - Draft message created by BA, approved and sent by DM
> - No technical content (calculation rules, system logic, queries) should be delivered via WhatsApp
> - If the findings lead to a scope gap, BA is required to create a separate Trello card Feature Analysis before the confirmation message is sent
> - All messages must be sent within business hours (09:00–17:00)
> - The PO must approve the confirmation message if the findings impact the scope or commitment of the contract

---

*Template: Data Issue Response (WhatsApp) | Sonnet 4.5 Governance Kit v1.0*
