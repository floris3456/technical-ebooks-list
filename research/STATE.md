# Research checkpoint

## Cycle 2026-10-14-07

Starting/reviewed remote commit: `55a8a4e84730c2843885472e26536526288e9604` (`main`), the prior 14-recommendation cycle. Examined live README, TAXONOMY, book template, research state and rejection ledger, latest commit/diff, both pending canonical records and their topic indexes, plus an older passed DDIA-2 record and its concurrency topic. This is an independent later invocation; no claim of observing another process's unpublished work.

| Measure | Distinct works |
| --- | ---: |
| Recommended after initial research | **16** |
| Passed independent subsequent-run review | **14** |
| Awaiting subsequent-run review | **2** |
| Uncounted canonical candidate files | **0** |
| Removed/retired works this cycle | **0** |
| Completed final collection audit | **0 / 2,000** |

**23 subject-index appearances in 20 populated topic files represent 16 distinct works.** Stable `work_id` deduplicates editions, revisions, languages, formats and overlapping indexes. The 2 just added cannot pass a subsequent-run review in their own creation cycle; the final audit has not begun.

## Review of the previous commit

- [*Database System Concepts*, seventh edition](../books/silberschatz-korth-sudarshan-database-system-concepts-7.md): **passed later-run review**. Reopened original seventh-edition chapter 27 §27.1 existential/universal quantified tuple relational calculus and chapter 32 PostgreSQL internals; Bilkent Fall 2026 independently prescribes exact edition. [PostgreSQL 15 release notes](https://www.postgresql.org/docs/15/release-15.html) directly contradict literal use of the 2019 separate statistics collector, but relational modeling, optimization, indexing and transaction theory remain useful. Keep this explicit caveat and assess further errata later.
- [*The Site Reliability Workbook*](../books/beyer-murphy-rensin-kawahara-thorne-site-reliability-workbook-2018.md): **passed later-run review**. Reopened original Google chapters 2 (SLIs/error budgets), 5 (precision/recall, multiwindow alerts), and 9 (incident coordination), current [Cloud Monitoring](https://docs.cloud.google.com/stackdriver/docs/solutions/slo-monitoring/alerting-on-budget-burn-rate) and [Prometheus practices](https://prometheus.io/docs/practices/alerting/), plus independent System Design Space critique. SLO process remains useful; tools, sample 5xx SLI and large-team operational structures are not universally current.
- Rotating older record [DDIA second edition](../books/kleppmann-riccomini-ddia-2.md) remains passed; its three additional subjects are sustained by contents but deserve retrieval tests. Corrected **stale “Pending”** status in [Concurrency & Distributed Systems index](../topics/concurrency-and-distributed-systems.md). No underlying recertification or new edition is claimed.

## New substantive research and recommendations

- [*Logical Foundations*, *Software Foundations* volume 1, v7.0](../books/pierce-logical-foundations-v7.md): **recommended; pending later-run review**. Inspected original university-hosted [v7.0 preface](https://kodu.ut.ee/~kalmera/sf/lf/Preface.html), [proof by induction](https://kodu.ut.ee/~kalmera/sf/lf/Induction.html), [constructive logic](https://kodu.ut.ee/~kalmera/sf/lf/Logic.html) and contents. Independent [Tartu Spring 2026 course](https://courses.cs.ut.ee/2026/vfa/spring/Main/HomePage) explicitly recommends this book and uses its exercises. Formal reasoning is durable; mirror reports Rocq 9.0.0 tested, whereas course installs 9.1.0—compatibility not asserted. Classified as **Mathematics & Formal Methods**, with no indiscriminate compiler tag.
- [*How to Design Programs*, second edition](../books/felleisen-how-to-design-programs-2.md): **recommended; pending later-run review**. [MIT Press](https://mitpress.mit.edu/9780262534802/how-to-design-programs/) supplies exact authors/2018 second edition and eBook ISBN. Inspected [author-hosted May 28, 2026 second-edition revision](https://htdp.org/2026-5-28/Book/index.html) and [Part I](https://htdp.org/2026-5-28/Book/part_one.html), ch3 design recipe/examples/tests. Independent current use: [Brown Fall 2026](https://cs.brown.edu/courses/cs019/2026/pl2due.html) explicitly assigns second-edition chs 8–9, though a coauthor connection means not an arm's-length review. Modern program-design principles survive historical Racket/integration examples. Primary subject **Programming** only. An author web revision is *not* an added edition count.

Each new recommendation has at least three inspected substantive documents collectively covering edition, contents, educational use, and present-day relevance, with exact URLs and relevant sections and explicit limits in its record. All sources accessed **2026-10-14**; access date ≠ publication date. No complete reading, executed prover scripts, all-exercise test, exhaustively verified errata or complete outbound-link crawler is claimed.

## Curation, corrections, and taxonomy

- Preserved all **7 browsing groups / 23 controlled subjects**. After 16 recommended works a meaningful 25–30 real-edition retrieval pilot spanning all groups is still pending; making structural changes now would outrun evidence.
- No weak works were removed this cycle; excluded overclaims and status corrections are in [REJECTIONS.md](REJECTIONS.md). Availability never entered admission decisions.
- New primary subject indexes for **Mathematics & Formal Methods** and **Programming**; fixed stale DDIA concurrency badge and updated database/reliability indexes and README counts. No duplicate canonical work IDs were introduced.

## Research leads and next-run priorities

1. **FIRST review this published commit**, especially v7.0 *Logical Foundations* and *How to Design Programs* 2e: verify original chapter excerpts, exact edition/version, independent learning value and code/tactic portability. Pass, revise or demote each explicitly; do not self-approve.
2. Continue exact-new-edition evidence for [2026 *Site Reliability Engineering*, second edition](https://www.oreilly.com/library/view/site-reliability-engineering/9798341607675/), including non-author critical reading and deep 2026 chapters. [Google's 2026-10-12 announcement](https://cloud.google.com/blog/products/devops-sre/sre-book-second-edition/) is not independent proof. No candidate count unless a canonical candidate is created.
3. Prioritize underrepresented **DevOps/Cloud, AI/ML, debugging/performance, and dedicated distributed algorithms**, not another cluster of fundamentals. For promising leads seek edition metadata, original material, independent educational/adoption/critical evidence and currency checks before recommendation.
4. Continue older long-term issues: OSTEP PDF version/CFS-EEVDF discrepancy; CLRS printing errata and old preliminary schedule discrepancy; Ousterhout 2e direct original reading; Kurose/Ross 9e current protocol checks, 2020 *Security Engineering* cases and 2017 accessibility practice. Do not equate passing review with complete source validation.
5. Pilot the taxonomy on 25–30 varied real editions (including multi-subject works) before altering category slugs, and develop repeatable QA for book metadata / index links as the collection scales.

## Publication and conflict safety

Re-fetch live `main` before publish. Use the exact observed head as parent, a tree based on its content, and a **conditional non-force** ref update. If concurrent work intervenes, reconcile before committing; never force-push or overwrite history. Verify resulting remote head/changed files. This checkpoint describes the cycle and does not fabricate a circular self-commit hash.
