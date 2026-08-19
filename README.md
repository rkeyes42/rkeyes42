# Robert Thomas Keyes

**Healthcare Data Systems Architect · T-SQL & PL/SQL Developer**

Thirty-one years of parsing and merging in the healthcare industry — eligibility, enrollment, claims, remittance, utilization and care management. I build the systems that decide who is covered, and I repair them when they stop telling the truth.

### → **[Healthcare Eligibility Decoded](https://rkeyes42.github.io/)**

An interactive technical portfolio. A live X12 834 segment decoder, the nine-relationship coverage span reconciliation taxonomy, a row-to-English narrative generator with column tracing, a lineage tracer, and sixty diagnostic queries organised by presenting symptom.

---

## Where to start

|                                                              |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **[The portfolio](https://rkeyes42.github.io/eligibility-decoded.html)** | The 834, the merge, span reconciliation, lineage, and the incidents that taught me each of them |
| **[The console](https://rkeyes42.github.io/console.html)**   | A simulated nightly run — five feeds parsed, staged and merged, with every step, drop and warning in the log |
| **[Applications](https://rkeyes42.github.io/applications.html)** | Five single-file demonstration apps: provider network, quality and HEDIS, LTSS waiver, dual eligibility and TPL, narrative generation |
| **[Glossary](https://rkeyes42.github.io/glossary.html)**     | 834, 837, 835, loops, qualifiers, spans, fan-out, TPL and the rest — in plain language |
| **[The Central series](https://github.com/rkeyes42/central)** | Fifty single-file Medicaid eligibility models, one per state, each planted with the same six business questions so answers can be compared across states |
| **[Resume](https://rkeyes42.github.io/resume.html)**         | Thirty-one years, in detail                                  |

---

## What I do

- **Enrollment and eligibility pipelines** — X12 834 end to end: parsing, staging, deterministic deduplication, reference resolution, idempotent merge, and daily reconciliation against the source
- **Remediation** — duplicate and fan-out incidents, parser defects, semantic inversions, retroactive change
- **Coverage reconciliation** — gaps, overlaps, contained windows, concurrent lines, retroactive terminations, and the claims exposure each one creates
- **Lineage and provenance** — column-level lineage held as queryable data rather than drawn in a diagram that goes stale
- **UM and CM data models** — authorization clocks with pause and resume, assessments, level of care, care plans, and the audit trail that defends them

**Stack:** SQL Server and T-SQL, Oracle and PL/SQL · X12 837/835/834/270/271/278/999 · HL7 2.x, C-CDA · PowerShell · Python, TypeScript

Author of *Medicaid Eligibility Processing: A Comprehensive Guide*, and *Fifty States, One Statute: A Field Guide to Medicaid Eligibility Data* (forthcoming). Active HL7 balloting and voting member.

---

### A note on provenance

The healthcare systems behind this work were **written by hand** across three decades — HL7 extraction from VAX/VMS lab systems in the late nineteen-nineties, HIPAA transaction parsers and serializers through the 4010 era, and the SQL Server merge and eligibility architecture of the last decade. Source files still carry their original timestamps.

The **web presentation** of the portfolio — page layout and the interactive screen mockups — was built with AI assistance, and it would be dishonest to imply otherwise. The mockups demonstrate the systems; they are not the systems.

Every record, identifier and code shown anywhere in these repositories is **synthetic**. No protected health information appears in any of it.

---

📧 **rkeyes42@yahoo.com** · 💼 **[LinkedIn](https://www.linkedin.com/in/robert-keyes-3b0b3059/)**

*Available for independent Medicaid and healthcare data consulting.*
