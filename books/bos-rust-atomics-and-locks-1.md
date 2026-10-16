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
review_status: passed
reviewed_commit: "ba27c63a3dbc093ceb91dc96a529f8fae76fd059"
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

All access dates: **2026-10-16**. Unknown update dates remain unknown. Rows B1–B10 preserve initial-research evidence; the later-run section identifies which sources were freshly reopened.

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
| B11 | https://mara.nl/atomics/memory-ordering.html — More Formally and Example: Locking, through lazy-initialization introduction | Original2023 chapter; live update unstated. Fresh later-run ordering and static-mut example inspection, not full chapter. |
| B12 | https://doc.rust-lang.org/edition-guide/rust-2024/static-mut-references.html — Summary, Details and Alternatives through OnceLock/LazyLock | Current edition guide; page revision unstated. Migration boundary, not a blanket data-race claim. |
| B13 | https://doc.rust-lang.org/std/sync/atomic/enum.Ordering.html — variant contracts through SeqCst | Rust1.99.1/build2026-10-13; modern API contract, not a complete book correctness proof. |

## Subsequent-run review — 2026-10-16, cycle06

**Qualified pass of the recommendation published in `ba27c63a3dbc093ceb91dc96a529f8fae76fd059`, observed on main at `f164164656102f2381ad7548993f616b13792774`.** This is a later invocation than initial selection. The audience, work identity and core recommendation remain unchanged; the prior version/printing warning is made concrete below.

Fresh original ch4/ch9 inspection confirms the distinction between `T: Send` for the lock and `T: Sync` for sharing its guard, plus the corrected reader-counter condition `s < u32::MAX - 2` [B2–B3,B8]. The deliberately unsafe raw-unlock stage in ch4 is not its final safe interface. These checks resolve specific corrections, not every interleaving, liveness property or implementation defect. The confirmed errata table still does not identify correction dates for all copies; p54's explicit second-printing note must not be transferred to unrelated entries [B4].

A fresh reading of ch3's release-ordering/try-lock sections adds original material beyond the previous guard/counter sample [B11]. **Its `static mut DATA` method-call example is not a drop-in Rust2024 example:** that edition denies `static_mut_refs` by default, including implicit references [B12]. This is a migration boundary, not evidence that the intended synchronized access was necessarily racy. Prefer locally reasoned encapsulation; disabling a lint alone is not a safety argument. Current ordering contracts continue to support the central Acquire/Release teaching [B13].

Westbrook's full2024 review was reopened and its criticism of the later reference-like chapters retained [B5]. His casual discussion of adding an unsafe `Sync` implementation is not accepted as general permission without representation-invariant reasoning [B8–B9]. No code was compiled, no concurrency test was run and no complete platform-primitive audit was performed. Exact retrievals and failures are in [cycle06 logs022–026](../research/sources/2026-10-16-06/README.md).

## Next review

Retain all printing, Rust2024 and unsafe-invariant qualifications. Check an actual current OS wait/wake implementation against the corresponding author chapter; earlier Windows/SRWLock leads are not verified facts here. Broaden original-chapter and correction coverage before final-audit clearance. A qualified subsequent-run pass is not a production-library endorsement. Historical deferral remains in [UNSELECTED](../research/UNSELECTED.md) and [REJECTIONS](../research/REJECTIONS.md).
