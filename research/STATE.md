# Research checkpoint — 2026-10-16-06

## Starting state and reviewed work

Started from live main **f164164656102f2381ad7548993f616b13792774**, with32 recommended works,29 prior subsequent-run passes,3 pending recommendations,2 canonical candidates and6 active deferrals. Read README, TAXONOMY, BOOK_TEMPLATE, STATE, source/rejection history, pending Bos/Gjengset/Palmieri records and older CLRS4e. Latest initial commit was validation-only; reviewed the underlying catalog at **ba27c63a3dbc093ceb91dc96a529f8fae76fd059**. The [previous checkpoint](STATE-through-f164164.md), source/rejection ledgers and non-selection list are preserved using their exact original Git blobs.

Observed cycle05 saved WIP at0d4441ac7793388c7304252cd6fc09673415db66, not unpublished work. Rechecking main found **b1f414261241f2540ceefe559ee201a793a43295**, eight commits ahead, all eight added files under research/sources/2026-10-16-05 and no catalog changes. Read the saved logs and preserve every blob and both histories in reconciliation. Their external sources were not re-opened in this cycle and are not claimed as new evidence reads here. Publication must still use a fresh conditional non-force head check; remote success is reported only after verification.

## Catalog counts and decisions

| Measure | Count |
| --- | ---: |
| Distinct recommended works | 34 |
| Passed genuine subsequent-run review | 30 |
| Recommendations awaiting subsequent-run review | 4 |
| Canonical candidates, uncounted | 4 |
| Active deferred works, including canonical candidates | 8 |
| Retired recommendations | 0 |
| Subject-index appearances, not works | 55 |
| Final-audit clearances | 0 |
| Target after review and final audit | 2,000 |

**Cycle06: four strong candidate investigations, two additions, two uncounted canonical candidates, one qualified later-run pass, one older-record annotation, zero removals or reclassifications.** Taxonomy remains23 controlled subjects in7 navigation groups; no automatic additional subjects for incidental chapters or implementation language.

New recommendations: [DPV Algorithms](../books/dasgupta-papadimitriou-vazirani-algorithms-2006.md) and [Skiena3e](../books/skiena-algorithm-design-manual-3.md). Both are **pending**, not same-invocation approved. DPV is specifically the inspected July2006 author electronic text of the first-edition work, not a certified latest print build. Skiena's third-edition sample and independent supplementary-course evidence are explicitly limited. Distinct author/work IDs, not matching title strings, control deduplication.

New candidates: [Kleinberg–Tardos1e](../books/kleinberg-tardos-algorithm-design-1.md) and [Sedgewick–Wayne4e](../books/sedgewick-wayne-algorithms-4.md). Both have substantial identity/scope/adoption evidence but lack sufficient original worked-example and correction inspection. They join Morris and Programming Rust as the four canonical candidates; no candidate appears in recommendation indexes. [UNSELECTED](UNSELECTED.md) retains all eight active deferrals and the superseded historical Bos row.

## Subsequent and rotating review

[Bos](../books/bos-rust-atomics-and-locks-1.md) passes a **qualified subsequent-run review** of published catalogba27c63a3dbc093ceb91dc96a529f8fae76fd059. Fresh ch4/ch9 reads confirm targeted guard/counter fixes; fresh ch3 memory-ordering sections, current Sync/Ordering/Rust2024 contracts and a full re-read of Westbrook's2024 critique support the unchanged core recommendation. The `static mut DATA` method-call example requires Rust2024 migration; unknown printing repair dates, unsafe invariants and unresolved OS-primitive details remain explicit. No concurrency program was executed or certified.

[CLRS4e](../books/cormen-introduction-to-algorithms-4.md) was rotated beyond the frequently reviewed systems books. Re-rendered the original binary-search solution, inspected a newly found exact4e JUST syllabus with its actual2024–25 date, and compared all four algorithm-candidate scopes. The errata interface still does not expose a complete selected correction list; JHU reopening failed. Its earlier qualified pass remains, not a new approval or complete errata audit.

Gjengset and Palmieri remain **pending**. Intervening [saved correction research](sources/2026-10-16-05/003-errata-and-edition-corrections.md) flags Gjengset p207 `c_void` and p235 `DropGuard` issues requiring primary recheck; saved third-edition Programming Rust preview is explicitly early-release. [Saved Petrov research](sources/2026-10-16-05/004-database-book-evidence.md) documents a specific MIT chapter assignment and a critical review, improving the prior adoption gap but leaving original chapter depth unfinished. These are retained, observable leads—not silently promoted source-only findings.

## Evidence and corrected claims

[Cycle source audit](sources/2026-10-16-06/README.md) contains the exact representative/locator table for **20 conservatively new substantive website families**, plus links to initial review and **26 immediate external retrieval logs**. Source publication/update dates remain separate from access2026-10-16. Failed opens, irrelevant search collisions, uncertain-provenance copy leads and partial excerpts are retained but not counted as substantive reads. Related institutional/author ecosystems and ambiguous additional sites are withheld conservatively.

Important distinctions: DPV author-text and printed-errata pagination are not interchangeable; work-level2026 course adoption does not establish assignment of the2006 draft. The signed-product DP aside has a concrete counterexample without domain restrictions. Skiena's significant pseudocode corrections remain explicit, and loose wording on undated author-site LP/shortest-path excerpts is not attributed to a3e print page without comparison. Pearson product refreshes and later paperback dates do not create new works. Current graph/solver/geometry contracts establish present applicability and limitations, not book endorsements. [R106–R115](REJECTIONS.md) record decisions with evidence.

## Counts, taxonomy and validation boundaries

The32-work baseline is preserved; two distinct new recommendations yield34, one genuine Bos pass raises29 to30, and remaining pending count is4. Four candidate files and eight active deferrals are excluded. Two algorithms-primary additions raise53 subject appearances to55. Bos's two recommendation-index labels are updated consistently; CLRS keeps its old reviewed_commit. No primary/secondary classifications of old works changed. Price, formats, geography and access did not govern selection.

Final validation must compare the reconciled commit with the latest observed main, inspect changed-file scope, verify archive/WIP blob preservation, metadata/work-ID uniqueness and all affected index counts, then re-fetch main for conditional publication. The validation record states which checks were actually completed; these structural checks are not a fresh evidence audit of every old record. No book code, solver, test suite, benchmark or deployment was executed.

## Next priorities

1. Independently review DPV and Skiena after publication. For DPV inspect another substantive original section and map draft/print corrections; challenge whether work-level adoption adequately supports the explicitly scoped version. For Skiena inspect a longer original3e worked section and compare it with the correction ledger and undated web excerpts. Keep both pending until that review.
2. Complete Gjengset and Palmieri later-run reviews. Prioritize Gjengset's saved p207/p235 safety corrections and another original chapter; for Palmieri inspect another application chapter, version/change information and one current crate contract. Do not claim unsupported production readiness.
3. Close KT/SW original worked-example and errata gaps; resolve Programming Rust3e early-release vs final-text evidence; use the improved Petrov adoption lead to target its remaining original-content gap. Preserve all Morris, PythonTDD, SRE and Feathers evidence deferrals.
4. Stage the final audit: work/edition identity and deduplication, then original/independent evidence, then present-day relevance/errata, then subject/index consistency. Cycle-level structural checks do not clear any stage collection-wide. Continue rotating older records and test taxonomy retrieval choices before large-scale expansion.

## Completion

**Not complete:34/2,000 recommended works,30 subsequently reviewed, zero final-audit clearances.** No automation setting changed. Completion requires2,000 passing distinct works with no unresolved quality blockers; removals reopen the target.
