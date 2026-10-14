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
review_status: passed
reviewed_commit: "b02eb3227d76c32381edbed90862b0b2b8d69876"
---

# Pro Git — Second edition (2014; maintained web text)

## Recommendation and audience

**Recommend for programmers and teams learning version-control concepts and collaborative workflows.** Scott Chacon and Ben Straub's completed second edition is distinct from the still-in-progress third edition. The latter's discussion of future Git changes is not evidence those changes have shipped. This is a narrated conceptual/practical reference, not an authoritative guide to every current hosting interface. [S1], [S7]

## Inspected contents and subject fit

Earlier inspection covered original §§3.1–3.2 on branches, HEAD, divergence and merging, and §7.1 on revision selection. The later-run review inspected **§10.2, Git Objects**, including Tree Objects and Commit Objects. It distinguishes content objects from trees recording names/modes and commits connecting trees, history and metadata. Sample hashes depend on details and are not test results from this research. [S2]–[S4], [S9]

The main teaching purpose is working with version history, so **Software Engineering Practices & Collaboration** remains primary. Git's distributed workflow is not equivalent to a book teaching distributed consensus or cloud infrastructure.

## Current relevance and independent educational use

Youngstown State's **Fall 2026 CSCI 5802** lists *Pro Git* as required reading and assigns chapters **1–3, 7 and 10** in its August 31 module. That was reopened in this review. Cornell's separately documented Fall 2026 guide is supplementary evidence from the preceding run, not falsely counted as a new source inspection here. Educational use supports applicability, not measured superiority. [S5], [S6]

Current command documentation qualifies older examples. The rechecked `git-init` manual explicitly lists SHA-1 as its default object format and `master` as the current fallback initial branch, with configuration overrides and a future Git 3.0 change. Thus the overlapping review's blanket claim that these are no longer current defaults was too broad. Upstream defaults, hosting conventions and future plans are different. Likewise, `git switch` offers a contemporary command reference alongside older `checkout` examples. The book's graph/object reasoning survives these version-specific differences. [S8], [S10]

## Limitations and alternatives

The text is not a modern GitHub Actions or organizational security handbook. Historical branch examples and hosting screenshots can age; use official manuals for the exact installed version. Compared with *Software Engineering at Google*, its value is focused tool literacy rather than broad engineering-over-time practices. No commands, exercises or full-version compatibility suite were executed; no complete book reading or comprehensive errata audit is claimed. Maintained web corrections do not prove every printing is identical. [S1], [S7], [S8], [S10]

## Subsequent-run review — 2026-10-14

**Passed after reviewing the published record at `b02eb3227d76c32381edbed90862b0b2b8d69876`.** The original internals chapter, current `git-init` details, draft status and explicit current course assignments corroborate the recommendation while preserving the existing version/UI caveats. The overlapping commit `50c8a773af139821e48680cd76015d4fa0f1dda5` already recorded this pass. This reconciliation preserves it while correcting that commit's overbroad default-name statement against the official manual. It is not another approval or another work. It is not final collection-audit clearance. [S5], [S7], [S9], [S10]

## Evidence ledger

Accessed **2026-10-14**. S9–S10 were added by this review; S5/S7 were reopened. Other evidence and limits are retained from the prior published record. Exact visit outcomes are in [cycle logs](../research/sources/2026-10-14-10/README.md).

| ID | Exact source and locator | Source date/version |
| --- | --- | --- |
| S1 | [Official book](https://git-scm.com/book/en/v2), authors, edition and chapter map | Second edition 2014; web update unknown |
| S2 | [Original §3.1](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell), branch/HEAD model | Maintained 2e; section date unknown |
| S3 | [Original §3.2](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging), divergence and merges | Maintained 2e; section date unknown |
| S4 | [Original §7.1](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection), selectors and ancestors | Maintained 2e; section date unknown |
| S5 | [YSU Fall 2026 syllabus](https://catalog.ysu.edu/syllabi/2026-fall/csci-5802-01-44236/), Course Readings and August 31 assignments | Fall 2026; revision unknown |
| S6 | [Cornell Fall 2026 guide](https://courses.cs.cornell.edu/cs3410/2026fa/rsrc/git.html), further reading | Prior-run inspection, Fall 2026 |
| S7 | [Third-edition draft](https://progit3.com/), in-progress notice | Blog dates August 2026; overall revision unknown |
| S8 | [Git switch](https://git-scm.com/docs/git-switch), command reference | Prior-run check noted 2.55.0, 2026-06-29 |
| S9 | [Original §10.2](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects), Tree Objects and Commit Objects | Maintained second-edition text; date unknown |
| S10 | [Git init](https://git-scm.com/docs/git-init), object-format and initial-branch options | Last listed substantive change 2.54.0, 2026-04-20 |

## Next review

For final audit, examine version-pinned corrections and test representative commands in an identified environment. Revisit third-edition completion later without counting another edition as another work. Availability remains irrelevant to selection.

[S1]: https://git-scm.com/book/en/v2
[S2]: https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell
[S3]: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
[S4]: https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection
[S5]: https://catalog.ysu.edu/syllabi/2026-fall/csci-5802-01-44236/
[S6]: https://courses.cs.cornell.edu/cs3410/2026fa/rsrc/git.html
[S7]: https://progit3.com/
[S8]: https://git-scm.com/docs/git-switch
[S9]: https://git-scm.com/book/en/v2/Git-Internals-Git-Objects
[S10]: https://git-scm.com/docs/git-init
