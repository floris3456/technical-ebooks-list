# Research checkpoint — 2026-10-16-04

## Starting state and reviewed saved work

Started from live main **e0e6c5543a4af14116361ef9d5cbfca29cb8d19e**, tree c725e269fa76018801afef123634257cb3015650. Reviewed repository state, README, TAXONOMY, BOOK_TEMPLATE, STATE, REJECTIONS, UNSELECTED, current/archived source registries and latest STATE-only commit. The earlier checkpoint is preserved byte-for-byte in [STATE-through-e0e6c55](STATE-through-e0e6c55.md). No unpublished work was assumed.

Observed separate saved source-only branches at9e688a0314536aa22e22370f9fdcf84ead7c38ad (Rust) and5a00d6f9b88aa0835eaf42868553cc9be4c6f88a (curation). Multiple relevant Rust logs were read; changed-file comparisons do not establish that every source-only file was reviewed. They were neither blindly merged nor counted as this invocation's external research. [Current source audit](sources/2026-10-16-04/README.md) records scope, source novelty and retrieval failures.

## Catalog counts and completed curation

| Measure | Count |
| --- | ---: |
| Distinct recommended works | 32 |
| Recommended works with a prior genuine subsequent-run pass | 29 |
| New recommendations pending subsequent-run review | 3 |
| Canonical candidates, uncounted | 2 |
| Active deferred works, including canonical candidates | 6 |
| Retired recommendations | 0 |
| Subject-index appearances, not distinct works | 53 |
| Works cleared by the final completion audit | 0 |
| Target after later review and staged audit | 2,000 |

**This cycle: four strong candidate investigations; three additions; one older-record review annotation; zero removals.** New canonical recommendations: [Bos](../books/bos-rust-atomics-and-locks-1.md), [Gjengset](../books/gjengset-rust-for-rustaceans-1.md), [Palmieri](../books/palmieri-zero-to-production-in-rust-2022.md). All remain pending; no same-invocation self-approval. [Programming Rust3e](../books/blandy-orendorff-tindall-programming-rust-3.md) is a substantive uncounted candidate alongside Morris3e. Bos's previous deferral is retained as superseded, not deleted or counted twice. Five other historical active deferrals plus the new Programming Rust candidate leave six active deferred works.

The older [Systems Performance2e](../books/gregg-systems-performance-2.md) record at the starting commit was reviewed for scope and provenance. Its prior qualified pass is retained, with an annotation that the author's blank, stale errata page is not error-free certification and current scheduler details require primary documentation. The previously inspected book sample and independent translation review were not claimed as newly re-read. Its classification and substantive recommendation are unchanged.

The Linux networking index was corrected from stale pending to its already established canonical pass reviewing521ad153. This is an index reconciliation, not a newly earned review. The topic summary's stale28passed/onepending and deferral wording were also repaired. The revised indexes contain seven additional appearances for three works; candidates remain outside recommendation indexes.

## Evidence and decisions

**27 immediate source logs** retain exact successful/failed/search-only retrievals. **20 new substantive website families** are enumerated with locators, dates and roles against the inspected saved baseline. Related domains, known websites, failed bodies and mere snippets earn no novelty credit. Publication/update dates remain distinct from access2026-10-16. No entire-book reading, executed examples, security certification or exhaustive historical-source audit is claimed.

Bos's actual chapters4/9 now show the targeted guard/counter repairs; blank publisher correction dates did not imply the live text remained unfixed. Printing/build correction identity remains unverified. Gjengset's first edition has documented educational use and original worked material, but material unsafe/FFI errata and post2021 language changes remain explicit. Palmieri has original project/testing evidence, independent production-practitioner counterassessment and course reading use; exact digital build is unspecified and tutorial completion is not a production guarantee. Programming Rust publisher3e identity is separated from2e reviews; original chapter depth, exact-edition independent evidence and errata remain incomplete.

[REJECTIONS](REJECTIONS.md) records R095–R105 and preserves the previous ledger byte-for-byte. [UNSELECTED](UNSELECTED.md) retains active decisions, the superseded Bos deferral and incidental directions separately. Availability was not a filter, and no purchase or unauthorized copy was made.

## Metadata, classification and validation boundaries

Four new canonical files have distinct stable work IDs. The three recommendation scopes are different: advanced language/library practice, concentrated low-level concurrency, and web-backend development. Edition/format variants are not additional works. Verified print identifiers are not reassigned to ebook formats; unknown build/ISBN/access fields remain unknown. Each recommendation maps identity, inspected original material, independent assessment/teaching and current-relevance checks to exact URLs/sections.

Controlled subjects are unchanged: Bos primary concurrency, Gjengset primary programming, Palmieri primary platform-specific development with substantial testing/API secondary indexes. This applies existing taxonomy boundaries rather than inventing a Rust top-level subject. README now explicitly requires four strong research candidates without requiring four approvals. The provisional taxonomy still needs empirical retrieval testing.

Counts reconcile as29 baseline recommended works plus3 unique additions; the two canonical candidates and superseded deferral are excluded. Existing catalog rows and unrelated source history are preserved. Final publication requires a re-fetched main head, self-reviewed changed files and conditional non-force ref update; remote commit verification is reported only after the update succeeds. The subsequent validation record records the actual final checks, not a full audit of every historical claim.

## Next priorities

1. Independently review the three newly published recommendations in a later invocation. For Bos, inspect another original chapter and current platform primitive behavior; retain printing caveats and recheck any Windows-lock claim before asserting it. For Gjengset, deepen unsafe/FFI and another original chapter. For Palmieri, inspect another application chapter, exact version/errata information and a current crate comparison.
2. Close Programming Rust3e's substantive original/independent-edition evidence gap, or select a better-supported earlier edition on its own merits. No automatic newest-edition preference. Separately retain the saved Rust Programming Language third-edition/maintained-online-text distinction; it is a different work, not this candidate.
3. Rotate older recommendations beyond the repeatedly checked systems books. Prioritize Database Internals original chapter evidence, and the unresolved exact-edition gaps for Morris, Python TDD, SRE and Feathers' advertised work. Preserve all earlier checkpoint caveats.
4. Stage final audits: first bibliographic identity and work-level deduplication; then original/independent evidence completeness; then contemporary relevance and errata; then subject/index accuracy and cross-record consistency. Recheck source drift in manageable recorded batches. No stage is cleared collection-wide yet, and removals reopen the target.

## Completion status

**Not complete:32/2,000 recommended,29 later-reviewed, zero final-audit clearances.** The recurring automation was not changed by this invocation. Only at2,000 passing works with no unresolved quality blockers may completion be recorded and an active automation disabled. Quality outranks throughput.
