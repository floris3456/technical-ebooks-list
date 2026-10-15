# Research checkpoint

## Cycle 2026-10-15-05 — review, systems research, and pending recommendation

**Starting main:** `982ba88e4d8ab0b1489bd41fb91271f5f52f22db` (tree `6db65e09150f63230b6dc802ec8204db1c5e4287`). Read live README, TAXONOMY, book template, this STATE, source baseline, REJECTIONS, UNSELECTED, latest commit and observable cycle-04 saved logs 001–002. Latest main commit at the start only saved an **incomplete, one-line source placeholder** for six prior visits; their unspecified source URLs are unknown, not reconstructed. Previous full checkpoint is archived verbatim at [STATE-through-982ba88.md](STATE-through-982ba88.md). Only observable saved WIP was reviewed. Separate research on main must be preserved through merge.

## Recomputed catalog after this change

| Measure | Distinct works |
| --- | ---: |
| Recommended | **28** |
| Passed genuine subsequent-run review | **27** |
| Awaiting subsequent-run review | **1** |
| Canonical candidates not counted | **1** |
| Retained deferred non-selections, including that candidate | **5** |
| Completed final collection audit | **0 / 2,000** |

**43 subject-index appearances = 28 distinct recommended work IDs** (not editions/formats/translations). Controlled taxonomy remains **7 groups / 23 subjects**. All subjects have at least one primary recommendation but representation depth and browsing retrieval are not formally tested. Net: **1 recommendation, 1 qualified review pass, 0 removals, 0 status-based promotions of deferred works, 0 subject reclassifications, two subject links for the new work**. The new work remains pending; it cannot approve itself.

## Subsequent-run review of the previously published record

[Architecture Patterns with Python](../books/percival-gregory-architecture-patterns-with-python-1.md) by Harry Percival / Bob Gregory: **passed qualified later-run review of published `dca423978a1a7ab5a5e491eca1c2f59d499b75ea`**. The original full Unit of Work chapter shows that a fake's committed flag and no-op rollback are not real database transaction tests, and discusses added abstraction cost. Reopened Buresund's 2022-03-13 critical 6/10 judgment (dry style, narrow business examples, assumed prior patterns knowledge). SQLAlchemy 2.0.54 **2026-09-15 is explicitly legacy** against 2.1 in its migration docs; original standalone `mapper()` and string-based `Connection.execute()` need migration (registry and SQL text handling). This does **not** invalidate stable dependency inversion, service boundary and testing principles. Architecture primary, testing and component design additional still match substantive scope. Did not execute full example or clear the errata endpoint; review pass not final audit.

Rotating older [Operating Systems: Three Easy Pieces 1.10](../books/arpaci-dusseau-ostep-1-10.md): reopened author condition-variable chapter, visually inspected the mutex-protected predicate/while-loop join example. Its 1.10-versus-1.20 scheduler extraction conflict remains unresolved; the short returned EEVDF page this run was insufficient to settle it. Kept its prior qualified pass; this is **not** a new approval or full errata audit. Older [Security Engineering 3e](../books/anderson-security-engineering-3.md) was also metadata/claim-scanned for errata and current-source gaps, without claiming a fresh exhaustive book review.

## New work — pending review

[Computer Systems: A Programmer's Perspective, North American third edition](../books/bryant-ohallaron-computer-systems-programmers-perspective-3.md), Randal E. Bryant and David R. O'Hallaron: original 2015 publication/2016 copyright. Complete accessible original 36-page preface/TOC (selected rendered pages), cache blocking/SIMD author Web Asides, extensive author errata updated 2025-06-25, and independently inspected **Harvard CS61 2026** and **Harvey Mudd Fall 2026** instructional use establish identity/contents/adoption. Also verified Fall 2020 Wellesley and Fall 2025 UMD (recommended, not required). The original authors' June **2026** notice describes a **fourth edition in development for estimated spring 2027** with third author Brian P. Railing, **not an available fourth edition**.

Strength: C-to-machine mental model, memory hierarchy and measured optimization still teach useful principles. Caveats: dated SSE/AVX2/GCC and Linux examples, **Harvard's specific warning of inaccurate C signed-overflow/undefined-behavior explanations**, extensive correction list, and different error-prone international problem set versus US printed exercises. Harvard calls some international editions usable for reading, while original authors warn about assignments; preserve this distinction, never price or geography as admission filters. CSAPP's `computer-systems-and-operating-systems` primary and substantial `debugging-and-performance-engineering` additional are warranted by authored chapters, not just keyword mentions. No full-text reading or benchmark execution. **Pending genuine later-run assessment.**

## Inspected source breadth and retention

[Exact visit registry](sources/2026-10-15-05/README.md): **26 newly directly visited website families**, of which **at least 22 conservatively substantively inspected** after excluding thin metadata/index-only families. Each external retrieval batch has immediate committed exact URLs, relevant sections, failures and search-only leads; repeated sites receive zero novelty credit. CMU and author's blog are grouped within the existing author ecosystem, not new-site credits. Date of source publication/update and access date **2026-10-15** are separate. 26 families is **not** proof of 26 independent book endorsements; technical manuals assess topic currency and alternatives.

All five previously deferred works in [UNSELECTED.md](UNSELECTED.md)—IaC3e, SRE2e, Brutal Refactoring, Python TDD3e and Database Internals—remain separate, uncounted and unchanged because no new book-specific independent evidence removed their blockers. Nothing was retired or rejected because of cost, access, age or format. Source-only search hits are not invented book evaluations.

## Quality blockers / next priorities

1. **Subsequent-run review of CSAPP3e:** carefully check official 2025 errata and Harvard's undefined-behavior counterexamples against original printed chapter; assess Global exercises separately. Reverify 4e status and whether broad systems/performance classifications aid retrieval; no same-run pass.
2. **Python Architecture and OSTEP:** independently execute a real-database versus fake UoW rollback test, update SQLAlchemy 2.1 adapters and errata. Reconcile OSTEP 1.10 vs 1.20 extracted/rendered chapter mismatch against official release sources.
3. **Other candidates:** obtain an original substantive chapter and independent expert appraisal or explicit assignment before promoting Database Internals; seek exact-edition external appraisal for IaC3e, SRE2e and Python TDD3e. Retain every unsuccessful investigated work in UNSELECTED.
4. **Staged older audit:** CLRS printing corrections, Logical Foundations 7.0 vs 7.1, Security Engineering 3e errata, Eloquent JavaScript CSS/edition divergences, and browser Oxford-online correspondence. Passing a later-run review never equals final collection audit.
5. Stress test taxonomy with realistic user retrieval scenarios, deduplicate titles/editions against stable IDs, and deepen thin subject coverage. Future cycles should log **20 different newly investigated websites** plus deeper returning primary/expert sources without padding.

## Validation and publication

Metadata and controlled slugs have been checked against 23 subjects; the new work ID is not among the starting 27. Topic changes are OS 2→3 and performance 1→2, so 41→43 appearances; previously pending Architecture transitions on all three indexes to passed, making 27 passed / 1 pending at 28. Relative book/topic paths and source evidence IDs should be validated against the final tree. Before publication **re-fetch main, reconcile all intervening saved work, self-review changed diff, use expected-head conditional non-force operations or an expected-head ordinary merge, and verify final remote state**. Do not overwrite concurrent cycle-04 research logs.

No complete-book reading, full executed lab suite, all-printings errata resolution, empirical taxonomy study, automated comprehensive link crawler, or final 2,000-item audit is claimed. Automation settings unchanged.
