---
work_id: bos-rust-atomics-and-locks
title: "Rust Atomics and Locks: Low-Level Concurrency in Practice"
authors: [Mara Bos]
edition: "1st; corrected author-maintained web text inspected 2026-10-16"
publication_year: 2023
isbn_by_format: {}
primary_subject: concurrency-and-distributed-systems
additional_subjects: [programming]
concepts: [atomics, memory-ordering, synchronization, lock-guards, unsafe-rust]
languages: [Rust]
technologies: [atomic-wait]
difficulty: advanced
focus: [conceptual, practical, reference]
formats: [web]
access: unknown
official_url: https://mara.nl/atomics/
last_verified: 2026-10-16
status: recommended
review_status: pending
reviewed_commit: null
---

# Rust Atomics and Locks

## Audience and prerequisites

For programmers comfortable with Rust ownership, references, traits and ordinary threads who want to understand synchronization below a library's public API. Not a first programming book or a substitute for learning safe Rust. Familiarity with unsafe contracts is important when following the construction exercises. The author contents and worked chapters support this placement [B1–B3]; independent reader assessments distinguish the conceptual introduction from the more specialized later material [B5–B7].

## Strengths, coverage and subject fit

The distinctive teaching method is to construct small primitives and expose the obligations hidden by a polished library. Comparing a raw lock with a guarded interface makes synchronization and safe data access separate design questions. The later blocking-lock treatment connects those questions to wait/wake behavior [B2–B3]. This is primarily **Concurrency & Distributed Systems**, despite having little distributed-system material; Rust interface construction supports **Programming** as a secondary subject. Language and library names remain facets, not new subjects.

The independent case is not a publisher endorsement: Westbrook provides a chapter-specific critical appraisal and describes concrete Rust programming experience; Budilovsky adds a shorter Linux/systems-developer assessment [B5–B6]. Revinder's project-based response is useful learner evidence, not proof of algorithm correctness [B7].

## Present-day value and corrections

Recommend the first-edition work **with its errata and corrected live text**, not every example from an unidentified printing. The previously deferred guard-bound and reader-count issues are now visibly addressed in author chapters4 and9 [B2–B4]. Current `Sync` documentation supplies the relevant shared-reference contract [B8]. This clears the specific missing-live-correction evidence gap; the date each web repair appeared and which downloadable/printed copies include it remain unknown.

Those qualifications do not erase the value of learning memory-ordering and abstraction invariants. They do mean that a pedagogical implementation is not a production-ready replacement for maintained synchronization libraries. No code, stress test or formal proof was executed during this review. A successful example run would not prove concurrency correctness [B3, B9].

## Limitations and alternatives

Later processor/OS details are implementation examples, not permanent platform guarantees. The chapter9 dependency assumes atomic-wait major1; do not transplant that setup unchanged into another release [B3]. Westbrook finds later reference-like chapters repetitive and gives a more qualified assessment than the author blurb [B5].

Compared with **Rust for Rustaceans**, this book earns a separate place through concentrated low-level synchronization, rather than broad library/API and project practices. It is not an alternative to **Zero To Production in Rust** for building a backend application. The latter comparisons are curator judgments from inspected scopes, not claims of reading every page of all three works.

## Bibliographic identity and edition checks

Author landing identifies January2023 and ISBN9781098119447 [B1]. The identifier is retained here without assigning an unverified ebook-format ISBN. The online text is a format of this work, not a second counted recommendation. Official-domain newer-edition search found no substantiated replacement; absence from that bounded search is not proof none exists [B10]. Availability, price and format completeness did not determine selection.

## Claim-to-source ledger

All access dates: **2026-10-16**. Unknown update dates remain unknown.

| ID | Exact source and inspected locator | Document date / role and boundary |
| --- | --- | --- |
| B1 | https://mara.nl/atomics/ — identity and contents | Work January2023; web update unstated. Original metadata/scope, not independent quality evidence. |
| B2 | https://mara.nl/atomics/building-spinlock.html — safe guard interface, especially Send/Sync discussion | 2023 work, repair date unstated. Substantive original chapter sections inspected. |
| B3 | https://mara.nl/atomics/building-locks.html — Mutex/RwLock guard and counter conditions; testing and atomic-wait caveats | 2023 work, live revision unstated. Selected sections, not entire chapter. |
| B4 | https://www.oreilly.com/catalog/errata.csp?isbn=0636920635048 — confirmed ch4/ch9, p54/p68/p76/p209 entries | Reports/corrections2023; some correction dates blank. Entire confirmed ledger inspected. |
| B5 | https://bwestbro.com/blogs/br-rust-atomics.html — full firsthand review; https://bwestbro.com/ — reviewer background | Review2024-09-02; biography undated. Independent software-practitioner assessment, not safety certification. |
| B6 | https://budevg.github.io/posts/2023-01-20-book-review-rust-atomics-and-locks.html and https://budevg.github.io/ — full short review and background | Review2023-01-20; biography undated. Supplementary low-level developer assessment. |
| B7 | https://revinder.dev/blog/book-summary-rust-atomics/ — chapter discussion and own experiment | 2025-06-20. Independent learner, explicitly not a concurrency expert. |
| B8 | https://doc.rust-lang.org/std/marker/trait.Sync.html — definition and reference relationships | Current rustdoc header1.99.1/build2026-10-13 when inspected; not a book update date. |
| B9 | https://www.ralfj.de/blog/2016/01/09/the-scope-of-unsafe.html — representation invariants/abstraction boundary | 2016-01-09, update01-11. Original researcher argument, not today's complete Rust specification. |
| B10 | ../research/sources/2026-10-16-04/025-newer-edition-search.md | Dated search trace, not substantive recommendation evidence. |

## Subsequent-run review required

Independently recheck corrected original guards and the meaningful errata; examine a fresh original chapter and a current platform primitive contract. Do not reinstate the disproved assumption that blank correction dates imply the live text is still unfixed. Do not silently drop printing/version caveats. Historical deferral remains in [UNSELECTED](../research/UNSELECTED.md) and [REJECTIONS](../research/REJECTIONS.md).
