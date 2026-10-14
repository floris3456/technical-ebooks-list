---
work_id: arpaci-dusseau-operating-systems-three-easy-pieces
title: "Operating Systems: Three Easy Pieces"
authors: ["Remzi H. Arpaci-Dusseau", "Andrea C. Arpaci-Dusseau"]
edition: "Version 1.10; online revisions require separate identification"
publication_year: 2023
isbn_by_format: {}
primary_subject: computer-systems-and-operating-systems
additional_subjects: [concurrency-and-distributed-systems]
concepts: [virtual-memory, scheduling, synchronization, condition-variables, file-systems]
languages: [C]
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: [pdf]
access: unknown
official_url: "https://pages.cs.wisc.edu/~remzi/OSTEP/"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Operating Systems: Three Easy Pieces — Version 1.10

## Recommendation and audience

**Recommend for learning OS mechanisms and concurrency reasoning, not as a current Linux implementation manual.** The official bibliographic entry identifies the two authors, Arpaci-Dusseau Books, and November 2023/version 1.10. Some C background is expected. The intermediate label is our assessment of that prerequisite and the sample code, not a publisher rating. [S1], [S2]

This assessment inspected the official outline, selected chapter material, course use, revision information, and current scheduler documentation. It does not claim a cover-to-cover reading or execution of the exercises.

## Contents and subject fit

The book's three organizing themes are virtualization, concurrency, and persistence. Processes, memory, synchronization, and file systems justify the OS primary subject; its sustained concurrency coverage justifies the secondary subject. It is not automatically classified as a security or cloud book merely because related topics appear. [S1]

Chapter 30 provides a concrete reason to include it: the join example develops a shared completion predicate protected by a mutex, with waiting performed in a loop. This connects an abstract synchronization rule to code and failure reasoning. The inspected example is Figure 30.3, chapter-local page 3, with the surrounding explanation on pages 2–4. [S2]

## Why it remains relevant today

UC San Diego's Fall 2026 CSE 120 explicitly specifies version 1.10. Its October readings cover threads, synchronization, and condition variables; later scheduled material covers memory and file systems. This is evidence of current educational use, not a controlled measure of learning effectiveness or proof that every example is current. [S3]

For implementation-sensitive material, the Linux documentation describes EEVDF rather than treating the CFS case study as a timeless account of current kernels. The transferable lesson is scheduling tradeoffs and resource sharing; actual kernel behavior must be checked against the relevant kernel documentation. [S4], [S6]

## Limitations and alternatives

The title should not be interpreted as requiring no prerequisites. Intermediate C examples and intentionally incomplete examples need the surrounding explanation. Our recommendation is strongest for conceptual OS study supplemented by exercises, rather than copying isolated snippets. [S1], [S2]

Pomona's Spring 2026 systems course recommends both this work and *Computer Systems: A Programmer's Perspective*, explaining that OSTEP goes further into operating systems while CSAPP supports the earlier, broader systems material. That gives a concrete positioning distinction; neither book is declared universally superior. [S5]

## Edition and errata check

Record **1.10**, not a guessed latest edition. The official page identifies that version and distinguishes some older-format editions. Its news/errata page points to revision and typo reporting, but individual reports were not exhaustively adjudicated in this cycle. [S1], [S7]

**Source conflict:** the rendered page 12 of the proportional-share scheduling PDF showed version 1.10 and the older CFS discussion. The text-extraction response for the same URL instead reported version 1.20 and an EEVDF addition. This discrepancy is unresolved: no whole-book 1.20 release or 1.10 EEVDF coverage is asserted. The recommendation rests on the separately identified 1.10 material and current course use; the scheduler caveat remains explicit. [S4], [S6]

## Evidence ledger

All sources below were inspected/accessed **2026-10-14**. Source dates are separate from that access date.

| ID | Source and inspected location | Source date/version |
| --- | --- | --- |
| [S1] | Authors' site: bibliographic block, numbered chapter outline, prerequisites and version labels | Book: November 2023, 1.10; page update date not supplied |
| [S2] | Chapter 30, *Condition Variables*, pp. 2–4 and Figure 30.3; rendered page 3 inspected | PDF displayed 1.10; exact revision date not established |
| [S3] | UCSD CSE 120: Textbook, Course Objectives, October readings, Course Organization | Fall 2026; exact page update date not supplied |
| [S4] | Chapter 9, section 9.7 and section 9.8; rendered page 12 compared with extraction | Conflicting 1.10 rendering / 1.20 extraction; unresolved |
| [S5] | Pomona CS105 Resources, Textbooks comparison | Spring 2026; exact page update date not supplied |
| [S6] | Linux scheduler documentation, EEVDF introduction and eligibility/deadline discussion | Live kernel documentation; exact update date not supplied |
| [S7] | Official news/errata page, version 1.10 announcement and typo-reporting guidance | 1.10 announcement 2023-09-28; not a complete current errata audit |

[S1]: https://pages.cs.wisc.edu/~remzi/OSTEP/
[S2]: https://pages.cs.wisc.edu/~remzi/OSTEP/threads-cv.pdf#page=3
[S3]: https://cseweb.ucsd.edu/classes/fa26/cse120-001/
[S4]: https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-lottery.pdf#page=12
[S5]: https://cs.pomona.edu/classes/cs105/resources.html
[S6]: https://docs.kernel.org/scheduler/sched-eevdf.html
[S7]: https://pages.cs.wisc.edu/~remzi/OSTEP/combined.html

## Next review

Recheck the chapter-version conflict and official release information without inferring dates from copyright footers. Verify source-to-claim fit, assess significant errata, and consider whether the broad concurrency subject remains an adequate browsing route. This record has not yet passed subsequent-run review.
