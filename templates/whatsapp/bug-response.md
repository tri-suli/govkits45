# WhatsApp Template — Bug Report Response

> **Tracking Prefix:** `BUG`
> **Applicable Phase:** Phase 1 — Client Support Handling
> **Sent By:** Delivery Manager / Product Owner (authorized sender only)

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

*Tracking ID:* BUG-[YYYY]-[NNN]
*Re:* [MODULE] - Bug Reports: [SUBJECT BRIEF]

Thank you for contacting us. We have received your report and are in the process of initial investigation.

---

*Detail yang kami terima:*
• Affected modules: [MODULE NAME]
• Short description: [ISSUE BRIEF FROM CLIENT]
• Time the report was received: [TIMESTAMP]

We will provide status updates within *[X business hours]* in the future.

---

Please do not make any changes or workarounds while we are investigating, unless there are specific instructions from our team.

If there is any additional information you need to provide, please reply to this message by including the Tracking ID above.

---

Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Template: Status Update (In Progress)

```
========================================
SENT_AT         : [DD Mmm YYYY | HH:MM — within business hours 09:00–17:00]
SENT_BY         : [Team Name | Delivery Manager]
REPLIED_AT      : [DD] [Mmm] [YYYY] [HH]:[MM]
REPLIED_BY      : [CLIENT NAME (ROLE)]
REPLY_MESSAGE   : [CLIENT'S LAST MESSAGE SUMMARY]
========================================

Hi [CLIENT NAME],

*Tracking ID:* BUG-[YYYY]-[NNN]
*Re:* [MODULE] - Update Status: [SUBJECT BRIEF]

We would like to provide an update on the bug reports we are currently addressing.

---

*Current status:* 🔄 Under Investigation / Being Repaired
*Investigation by:* [TEAM/ROLE]
*Estimated completion:* [DATE/TIME atau "Being confirmed"]

*Provisional findings:*
[BRIEF NON-TECHNICAL SUMMARY OF FINDING — no system architecture or implementation detail]

---

We will inform as soon as there are further developments or when improvements are ready to be verified.

---

Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Template: Resolution Confirmation

```
========================================
SENT_AT         : [DD Mmm YYYY | HH:MM — within business hours 09:00–17:00]
SENT_BY         : [Team Name | Delivery Manager]
REPLIED_AT      : [DD] [Mmm] [YYYY] [HH]:[MM]
REPLIED_BY      : [CLIENT NAME (ROLE)]
REPLY_MESSAGE   : [CLIENT'S LAST MESSAGE SUMMARY]
========================================

Hi [CLIENT NAME],

*Tracking ID:* BUG-[YYYY]-[NNN]
*Re:* [MODULE] - Completion Confirmation: [SUBJECT BRIEF]

We would like to inform you that the fixes for the above bug report have been completed and have gone through an internal validation process.

---

*Status:* ✅ Resolved
*Completion date:* [DD Mmm YYYY]
*Divalidasi oleh:* QA Analyst — [DATE]

*Solution summary:*
[NON-TECHNICAL DESCRIPTION OF WHAT WAS RESOLVED — aligned with client's original report]

---

Please confirm from your side whether the reported issue has been resolved in your ward.
If there are still problems, please inform us by including the same Tracking ID.

We will close this report within *[X business days]* if there is no further response.

---

Regards,
[SENDER NAME]
[ROLE] | [TEAM NAME]
([CONTACT NUMBER])
```

---

## Governance Notes

> - All WhatsApp messages should only be sent during business hours (09:00–17:00)
> - A Tracking ID must be included in every message without exception
> - Must not include technical information (architecture, database, API) in the message content
> - Authorized sender: Delivery Manager or Product Owner only
> - Each message sent must be recorded in the DM's client communication log

---

*Template: Bug Response (WhatsApp) | Sonnet 4.5 Governance Kit v1.0*
