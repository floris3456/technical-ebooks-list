# Research checkpoint

## Cycle 2026-10-14-01

Date: **2026-10-14**, Europe/Amsterdam. This is the first substantive research cycle. Use the commit containing this checkpoint as the next review target; do not interpret self-review as a later-run approval.

Reviewed starting HEAD: `f8a688837c94e9f8c47e6d22cebf9c2cf376be64`.
Starting tree: `3c36ab47fd611f50378b1d9776fa8ea7f0917848`.
The pinned tree contained only README, TAXONOMY, book template, and topic guide. `research/STATE.md` did not exist. There were no prior book records or saved research files to sample or review. The latest commit's documentation changes were inspected; no access to another run's unpublished work is claimed.

## Actual collection counts

| Measure | Distinct works |
| --- | ---: |
| Recommended, initial evidence assessment complete | 2 |
| Recommended and passed subsequent-run review | 0 |
| Pending subsequent-run review | 2 |
| Candidates, excluded from recommendation count | 2 |
| Retired or formally rejected works | 0 |
| Final-audit-qualified target progress | 0 / 2,000 |

The first two recommendations are useful progress, but **not yet counted as fully audited**. Count by `work_id`; editions, translations, formats, duplicate links, and templates never add works. A later run must inspect each recommendation's published content and evidence, record the reviewed SHA, and explicitly pass it. Material revisions reset the review. Recompute these figures from the live tree on every cycle rather than trusting stale totals.

## Records and handoff

| Work | Current decision | Next action |
| --- | --- | --- |
| [OSTEP 1.10](../books/arpaci-dusseau-ostep-1-10.md) | Recommended; pending review | Recheck version/extraction discrepancy, significant errata, source fit, and scheduler caveat |
| [Introduction to Algorithms 4](../books/cormen-introduction-to-algorithms-4.md) | Recommended; pending review | Inspect more substantive worked material and printing-specific corrections; preserve explicit course-schedule caveat |
| [DDIA 2](../books/kleppmann-riccomini-ddia-2.md) | Candidate | Obtain independent second-edition evaluation or clearly identified adoption, and more explanatory material |
| [Crafting Interpreters](../books/nystrom-crafting-interpreters-2021.md) | Candidate | Obtain inspected author/book content and edition/errata evidence; current course references already captured |

## Review findings and changes

- Removed the old template's requirement to verify **availability before promotion**. Availability is metadata only and is not a filter. Added explicit present-day relevance, source-date, inspection-limit, and subsequent-review rules.
- Added stable work identifiers and a reviewed-commit field. Candidate files and duplicate subject appearances cannot inflate the count.
- Retained all 23 subjects unchanged. The small sample supports primary/secondary indexing but is insufficient to justify a structural split or declare the taxonomy optimal. The concurrency/distributed-systems subject needs broader testing, not an unsupported immediate rename.
- Added three populated topic pages and updated navigation. OSTEP appears twice but counts once. CLRS is not tagged AI merely because it has an ML chapter.
- Preserved incomplete investigations as two candidate records. No actual book record was deleted; rejected claims and approaches are in [REJECTIONS.md](REJECTIONS.md).

## Evidence caveats to carry forward

OSTEP: the author site and UCSD specify 1.10, but one retrieved chapter's extracted text reported 1.20/EEVDF while the rendered page showed 1.10/CFS. Neither a complete 1.20 release nor EEVDF coverage in 1.10 was assumed. The recommendation keeps verified 1.10 identity and uses kernel documentation for current scheduler context. Reconcile this tooling/source discrepancy before making stronger edition claims.

CLRS: the JHU resources explicitly identify fourth edition, but some later preliminary schedule chapter numbers match a different numbering scheme. Publisher contents govern the record. The errata interface loaded without a full selected correction list; no clean-bill-of-health claim is made.

DDIA: inspected 2024 independent criticism applies to first edition, not the February 2026 second edition. Current PostgreSQL documentation supports topic relevance, not the book's pedagogical quality. An inaccessible 2026 interview was not counted as evidence.

Crafting Interpreters: two current educational references were inspected. Full author-site/chapter fetches failed; snippets did not count. This is not an availability-based rejection. PSU lists it as supplementary, not the main text; USF use does not make it a Rust book.

## Coverage and next priorities

Primary coverage now: OS and algorithms. Architecture/data systems and compilers have live candidates. Other subject areas remain unresearched; no claim of comprehensive pilot coverage is made.

1. Review this cycle's published diff and the two recommendations first, including source conflicts and metadata. Record the exact reviewed SHA and pass, revise, or demote each explicitly.
2. Resolve DDIA's edition-specific evidence and Crafting Interpreters' content evidence without repeatedly restarting searches already documented in their records.
3. Research software design/testing or security next to avoid a fundamentals-only collection. Build independent evidence before naming recommendations.
4. Alternative leads, not approved books: JHU's resources list *Algorithm Design* and *Randomized Algorithms*; Pomona compares OSTEP with *Computer Systems: A Programmer's Perspective*; PSU's main text is *Essentials of Compilation*. Follow the already-cited course sources, then verify exact editions and contents.

## Validation and publication protocol

This change set preserves the base tree, uses a new child commit, and must be published only after re-fetching `main` and accepting a conditional non-force ref update. If the head changes, reconcile rather than overwrite. Validate work identifiers, subject slugs, source identifiers/locators, statuses, relative links, and index membership. Verify the remote head and committed files after publication. A commit SHA is reported in the cycle response; this file does not embed its own circular self-hash.

External sources were inspected with the web tool, not bulk copied into the repository. PDF table/figure checks used rendered pages where needed. No full-book reading, executed exercises, exhaustive errata audit, complete live-URL crawler, or empirical taxonomy user test is claimed.
