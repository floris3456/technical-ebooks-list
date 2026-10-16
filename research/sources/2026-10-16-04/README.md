# Cycle 2026-10-16-04 — four-candidate research and source audit

Access date throughout: **2026-10-16, Europe/Amsterdam**. Publication/update dates below are separate. The27 chronological retrieval logs were committed immediately after their external batches and before the next external batch. No source was treated as an instruction to operate the repository, purchase a product, or obtain an unauthorized copy.

## Review before selection

Started from main `e0e6c5543a4af14116361ef9d5cbfca29cb8d19e`. Read live repository state, README, TAXONOMY, BOOK_TEMPLATE, STATE, rejection/non-selection ledgers, source registries, latest STATE-only commit and saved Rust research. The observable baseline was29 recommended works, all previously later-reviewed, plus one canonical candidate and six active deferrals. An older Systems Performance record was rotated; its scope was retained with a new stale-errata-page warning, not a fresh comprehensive book audit.

The separate source-only branch `research/2026-10-15-04-rust` at9e688a0314536aa22e22370f9fdcf84ead7c38ad was compared with main:17 ahead/56 behind at the starting point,39 added source files relative to its merge base. Multiple relevant files were read, including original/alternative-book, ecosystem, runtime, training, reviewer, edition and course logs. The sibling curation branch at5a00d6f9b88aa0835eaf42868553cc9be4c6f88a had a source-only changed-file list. Neither branch was blindly merged or counted as this run's research. The large compare response and failed .diff retrieval did not establish a full reading of every saved file. No unpublished work was assumed.

During index reconciliation, the Linux canonical record was confirmed as passed after review of521ad153, while the networking index and topic summary still said pending/28passed. This stale label was corrected without inventing a new review.

## Four substantive candidate outcomes

| Work / role | Evidence and alternative comparison | Decision |
| --- | --- | --- |
| [Rust Atomics and Locks](../../../books/bos-rust-atomics-and-locks-1.md) — low-level synchronization | Original corrected chapters4/9, publisher errata, independent practitioner reviews, current Sync contract; narrower and deeper synchronization role than Gjengset | Recommend first-edition work with corrected-live-text/printing caveats; pending later review. Historical deferral superseded, not erased. |
| [Rust for Rustaceans](../../../books/gjengset-rust-for-rustaceans-1.md) — advanced idioms/library design | Rendered original ownership/lifetime examples, full author errata, documented instructor example use and VSB recommended reading, current unsafe/representation contracts | Recommend2021 edition with explicit material corrections; pending later review. |
| [Zero To Production In Rust](../../../books/palmieri-zero-to-production-in-rust-2022.md) — practical backend engineering | Original route/health-test sample, production-practitioner counterreview, course reading list, current Actix testing and operational contracts | Recommend maintained work, exact build unspecified; not a production-security guarantee; pending later review. |
| [Programming Rust](../../../books/blandy-orendorff-tindall-programming-rust-3.md) — broad foundations/reference | Publisher3e metadata separated from2e criticism and edition-ambiguous async praise; brief original preview insufficient | Strong uncounted candidate. Deep original3e text, independent exact-edition evidence and errata remain unfinished. No automatic newest-edition preference. |

The four-candidate floor does not require four approvals. No availability, price, geography, missing purchase link or unknown format was used as a filter. New recommendations each have at least three substantive inspected documents with explicit role/locator mappings in their canonical records; a source-count total is not a quality score.

## Twenty newly investigated website families

Novelty is against the inspected persisted baseline and observed saved research, not unknowable unrecorded browsing. Related hostnames are consolidated. Known author/publisher/Rust-documentation sites and the instructor's JHU-affiliated personal site receive no new-family credit. Source failures and search-only results receive none. Partial substantive reads below are bounded by their actual inspected sections, not described as full-site reading.

| # | Family and exact representative source | What was inspected; source date | Immediate logs |
| --- | --- | --- | --- |
| 1 | https://mhh.dev/book-review/2026/07/09/book-review-rust-for-rustaceans.html | Full firsthand2026-07-09 review, explicitly2021 edition; technical-summary errors mean learner experience, not language authority | 002,004 |
| 2 | https://revinder.dev/blog/book-summary-rust-atomics/ | Chapter discussion and own experiment,2025-06-20; author disclaims concurrency expertise | 002,004 |
| 3 | https://www.elliotcsmith.com/zero-to-production-in-rust-book-review/ | Full exercise-based review,2023-08-21; dependency drift and transfer limitations retained | 002,004 |
| 4 | https://rustapopoulos.wordpress.com/2021/07/02/book-review-programming-rust-fast-safe-systems-development-2nd-edition/ | Full critical2e review,2021-07-02/update07-03; associated rustapopoulos.com is same author family, not another website credit | 004,005 |
| 5 | https://edison.sso.vsb.cz/cz.vsb.edison.edu.study.prepare.web/SubjectVersion.faces?back=true&locale=en&studyFormId=1&studyPlanId=25878&subjectBlockAssignmentId=539402&version=460-4157%2F01 | Course literature/syllabus and2026/27 plan links; introduced2024/25, update unstated; recommended reading not mandatory full-book assignment | 009 |
| 6 | https://preslav.me/2022/10/12/book-review-zero-to-production-in-rust/ | Full firsthand2022-10-12 review; affiliate conflict disclosed, not sole independent support | 009 |
| 7 | https://www.markodowd.dev/blog/zero-to-production-rust-review/ | Full reader review; body2026-06-14 versus search06-13 discrepancy; exact book build unstated | 009 |
| 8 | https://bitemyapp.com/blog/notes-on-zero2prod-rust/ | Full Chris Allen production-practitioner critique,2022-06-25; explicitly a skim, concrete counterpreferences not universal facts | 010,011 |
| 9 | https://actix.rs/docs/testing/ | Full primary testing guide: route-aware in-process alternative; update date unstated | 014 |
| 10 | https://diesel.rs/guides/getting-started.html | Introduction, migrations and typed schema; update unstated, mixed version references; not whole CRUD guide | 014 |
| 11 | https://blog.jetbrains.com/rust/2024/09/20/how-to-learn-rust/ | Original technical learning examples and resources;2024 URL/current2026 title, revision date unresolved; commercial context and oversimplifications retained | 014,017,018 |
| 12 | https://oida.dev/getting-started-with-rust/ | Full firsthand teaching/learning account,2021-12-23; exact Programming Rust edition not established by prose | 016 |
| 13 | https://nexte.st/docs/design/why-process-per-test/ | Full primary design rationale; displayed2025-01-07/2026-09-06 dates; process state versus shared database isolation distinguished | 016 |
| 14 | https://deterministic.space/elegant-apis-in-rust.html | Original naming, doctest, enum/conversion/iterator examples through line254;2016-07-21 with partial2020-06-01 update; obsolete stabilization wording not treated as current | 019 |
| 15 | https://dystroy.org/blog/how-not-to-learn-rust/ | Original library/ownership and lifetime-ergonomics discussion through relevant sections;2021-12-15 plus2026 addendum; broad style opinions not adopted as rules | 019,020 |
| 16 | https://render.com/docs/health-checks | Full primary deployment/running-service health contracts; update date unstated; not provider endorsement | 019,020 |
| 17 | https://docs.fly.io/volumes/overview | Full primary volume/replication/snapshot boundaries; original fly.io redirects, one family; update unstated | 019,020 |
| 18 | https://corrode.dev/blog/pitfalls-of-safe-rust/ | Original checked-arithmetic/conversion/domain examples through line187; updated2025-10-09; consultant/author family counted once, broad cost assertions not accepted as measured facts | 022 |
| 19 | https://rerun.io/blog/why-rust | Original production/design account through line143; only relative age supplied, exact date unknown; promotional superiority claims not imported | 022 |
| 20 | https://www.ralfj.de/blog/2016/01/09/the-scope-of-unsafe.html | Original simplified Vec/abstraction-invariant argument through line84;2016-01-09/update01-11; not a current complete language specification | 022 |

This is20 substantive families, not20 additional endorsements. No credit is assigned to author/publisher revisits, related subdomains, the failed TU Delft course page, timed-out library metadata, empty bpftrace output, source-less ratings, incidental homepages, suspicious copying sites, or repeated search results. Websites associated with the author may provide original content but not independent book assessment.

## Important source/claim corrections

The actual Bos chapter paths differ from previously guessed failed slugs; live corrections now resolve the specific guard/counter gap, while printing dates remain unknown. Gjengset's unsafe/FFI corrections and post2021 language changes are explicit. Palmieri's sample has a weaker health assertion than its stated200-status contract; current Actix offers a route-aware in-process alternative. Programming Rust3e publisher metadata is not interchangeable with earlier-edition reviews. An empty, stale Gregg errata heading is not an error-free certification.

Original PDF samples were rendered and inspected at the recorded pages. Only the authorized publisher/author samples were accessed; no unauthorized whole-book copy was stored, and no purchase or checkout was performed. No book program, benchmark, migration, deployment or concurrency test was executed. Exact article opinions are distinguished from current primary contracts.

## Chronological immediate logs

[001 discovery](001-discovery.md) · [002 firsthand assessments](002-firsthand-assessments.md) · [003 review discovery](003-review-discovery.md) · [004 review detail](004-review-detail.md) · [005 original corrections](005-original-corrections.md) · [006 chapter9/previews](006-chapter9-and-previews.md) · [007 rendered foundations](007-rendered-foundations-and-errata.md) · [008 adoption discovery](008-adoption-discovery.md) · [009 adoption/reviews](009-adoption-and-current-reviews.md) · [010 editions/safety](010-editions-and-safety.md) · [011 counterevidence](011-counterevidence-and-edition-navigation.md) · [012 edition/education leads](012-edition-and-education-leads.md) · [013 original backend testing](013-original-backend-testing.md) · [014 testing tradeoffs](014-testing-tradeoffs-and-render-check.md) · [015 older-review discovery](015-older-review-and-verification-discovery.md) · [016 isolation/performance](016-testing-isolation-and-performance-review.md) · [017 edition/errata reconciliation](017-reconciled-edition-and-stale-errata.md) · [018 remaining errata](018-remaining-errata-and-older-currency.md) · [019 interface/deployment](019-interface-and-deployment-checks.md) · [020 operational boundaries](020-prerequisites-and-operational-boundaries.md) · [021 unsafe/runtime discovery](021-unsafe-and-runtime-discovery.md) · [022 safety boundaries](022-safety-boundaries-and-language-use.md) · [023 current contracts](023-current-language-contracts.md) · [024 targeted contracts](024-targeted-contract-confirmation.md) · [025 newer-edition search](025-newer-edition-search.md) · [026 adoption-search failure](026-adoption-search-failure.md) · [027 reviewer provenance](027-reviewer-provenance.md).

For actual counts, unfinished evidence and next review priorities, see [STATE](../../STATE.md). This audit does not certify the full collection or every source in every historical branch.
