---
work_id: chacon-straub-pro-git
title: "Pro Git"
authors: ["Scott Chacon", "Ben Straub"]
edition: "Second edition (2014), collaboratively corrected online text"
publication_year: 2014
isbn_by_format: {}
primary_subject: software-engineering-practices-and-collaboration
additional_subjects: []
concepts: [version-control, commits, branching, merging, distributed-workflows, git-internals]
languages: []
technologies: [Git]
difficulty: mixed
focus: [conceptual, practical, reference]
formats: [web]
access: unknown
official_url: "https://git-scm.com/book/en/v2"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Pro Git — Second edition (2014; corrected online text)

## Recommendation and audience

**Recommend for students, programmers, and engineering teams learning how Git represents history and enables collaboration**, rather than for unqualified 2026 hosting-platform screenshots or a step-by-step manual of future Git defaults. The [official Git project publication](https://git-scm.com/book/en/v2) credits Scott Chacon and Ben Straub, Apress, and **second edition (2014)**, with subsequent corrections from many contributors. A [third edition is publicly in progress](https://progit3.com/) in August 2026 but is **not** a verified completed replacement. The year alone is not a quality filter. [S1], [S7]

## Inspected content and subject fit

Original [§3.1, Branches in a Nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell), explains how branch names reference commit history, how HEAD tracks the current checkout, and why moving a branch pointer is inexpensive. Original [§3.2, Basic Branching and Merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging), traces divergence, fast-forward and merge conflict resolution. Original [§7.1, Revision Selection](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection), details identifying and traversing commits. The [full chapter map](https://git-scm.com/book/en/v2) covers staging, local and remote history, distributed collaboration, internals, and hooks; contents establish breadth, while inspected chapters substantiate the mechanics. These are version-control collaboration practices, so **Software Engineering Practices & Collaboration** is primary. Git's references and branching do not make the book primarily a compiler, cloud, or distributed-consensus text. [S1]–[S4]

## Independent educational use and present-day relevance

[Youngstown State University's Fall 2026 CSCI 5802 syllabus](https://catalog.ysu.edu/syllabi/2026-fall/csci-5802-01-44236/) lists *Pro Git* as a **required reading** and assigns **chapters 1–3, 7 and 10** in the August 31 module on Git as a database, workflow and communication medium. [Cornell CS3410 Fall 2026](https://courses.cs.cornell.edu/cs3410/2026fa/rsrc/git.html) separately recommends the book to learn fundamentals. These support contemporary instructional applicability, not an experimentally demonstrated superiority over alternatives. [S5], [S6]

Git's graph-of-commits, merge and history concepts are still useful; users must check the live [git-switch manual](https://git-scm.com/docs/git-switch) rather than assuming older `git checkout` examples are the only current workflow. The manual identifies changes up to Git **2.55.0 (2026-06-29)**. The older book uses `master` as a branch example and includes time-specific GitHub interface instructions; these should **not** be mistaken for universal current defaults or UI guidance. The third-edition work-in-progress advertises further default/object-format changes; such plans are **not** treated as already-released stable behavior. [S1], [S7], [S8]

## Limitations, comparisons, edition and errata

Best for conceptual and practical Git literacy, not as a focused guide to GitHub Actions, modern organizational security controls, or an authoritative manual for a specific future release. Compared with official command reference pages, it supplies mental models and narrated workflows; the official manuals remain authoritative for exact flags and current behavior. Compared with *Software Engineering at Google*, it focuses narrowly on a version-control tool rather than the broader long-term practices of large engineering teams. The Git project says this web edition incorporates corrections, but a full version-pinned errata audit has **not** been performed. No commands, exercises, or complete Git-version compatibility suite were executed.

## Evidence ledger

**Inspected/accessed 2026-10-14**. A current access date is not a source publication date.

| ID | Document and precise location | Source publication/update |
| --- | --- | --- |
| [S1] | [Git book home](https://git-scm.com/book/en/v2), second-edition label, authors, chapters 2–10, corrections notice | Second edition 2014; web revision date not specified |
| [S2] | [Original §3.1](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell), branch and HEAD pointer model | Second-edition maintained web text; section revision date not provided |
| [S3] | [Original §3.2](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging), divergence and merges | Same; revision date not provided |
| [S4] | [Original §7.1](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection), commit selectors and ancestor syntax | Same; revision date not provided |
| [S5] | [Youngstown State Fall 2026](https://catalog.ysu.edu/syllabi/2026-fall/csci-5802-01-44236/), *Course Readings* and Aug 31 schedule | Fall 2026; exact page revision unknown |
| [S6] | [Cornell Fall 2026 Git guide](https://courses.cs.cornell.edu/cs3410/2026fa/rsrc/git.html), recommended Pro Git introduction | Fall 2026; exact update unknown |
| [S7] | [Third-edition draft site](https://progit3.com/), in-progress status and dated Aug 2026 blog entries | Dated 2026-08-02 and 2026-08-04 |
| [S8] | [Official Git switch manual](https://git-scm.com/docs/git-switch), version history and synopsis | Git 2.55.0 update 2026-06-29 |

## Next review

**Pending subsequent-run review** of this commit. Reopen at least one original deep-internals chapter, verify the completed-vs-draft edition boundary and default-branch examples, review Git commands against current docs, and compare a narrower Git-learning alternative. Availability and ebook price played no role.
