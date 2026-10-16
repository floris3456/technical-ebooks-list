---
work_id: blandy-orendorff-tindall-programming-rust
title: "Programming Rust: Fast, Safe Systems Development"
authors: ["Jim Blandy", "Jason Orendorff", "Leonora F. S. Tindall"]
edition: "Third edition, publisher-listed October 2026; exact release day not established"
publication_year: 2026
isbn_by_format: {}
primary_subject: programming
additional_subjects: []
concepts: [systems-programming, ownership, borrowing, asynchronous-programming, unsafe-rust]
languages: [Rust]
technologies: []
difficulty: mixed
focus: [conceptual, practical, reference]
formats: []
access: unknown
official_url: https://www.oreilly.com/library/view/programming-rust-3rd/9781098176228/
last_verified: "2026-10-16"
status: candidate
review_status: pending
reviewed_commit: null
---

# Programming Rust — Edition Comparison and Uncounted Candidate

## Decision and likely audience

**Strong candidate, not a recommendation and not counted.** The intended niche is a substantial foundations-to-reference treatment for programmers moving into systems-oriented Rust. The original contents and independent earlier-edition reading experiences make this a worthwhile fourth candidate in this cycle, distinct from the advanced-interface, synchronization and backend-project books [R1–R4]. They do not yet substantiate this exact third edition to the catalog's standard.

The missing evidence is substantive original third-edition chapter inspection and independent edition-specific assessment or educational use, with relevant corrections. Neither availability, price, unverified ebook subtype nor the age of an alternative edition is a negative criterion.

## Verified identity and edition separation

The directly inspected publisher record lists **October2026**,730 pages and authors **Jim Blandy, Jason Orendorff and Leonora F. S. Tindall** for the third edition [R1]. A previous search lead suggesting July2026/690 pages is not preferred over the original publisher record. The exact release day and correspondence between earlier preview builds and the listed edition were not established.

The second-edition publisher record identifies June2021 and738 pages with the same three authors [R2]. Its original chapter4 preview exposes ownership/deallocation goals but not enough substantive text to claim a deep original chapter read. An early-release two-author attribution must not replace the final three-author metadata. Publisher platform identifiers9781098176228 and9781492052586 are not assigned to unverified ebook-format ISBN fields.

A newer edition is not automatically better, and its existence does not make useful second-edition teaching obsolete. The next review should compare actual changes and learning roles rather than default to the newest cover. Editions remain one intellectual work under this stable work identifier.

## Potential value, reservations and alternatives

The contents suggest broad coverage of ownership/references, collections, iterators, errors, concurrency, async and unsafe/foreign interfaces [R1–R2]. This warrants **Programming** primary; merely listing several topics is not sufficient reason to add every possible secondary subject.

John West's explicitly second-edition review finds useful material but reports a demanding C/C++-oriented presentation, distracting complex-number/fractal examples and less web coverage than he wanted [R3]. His experience is relevant audience counterevidence; unlocated error allegations and speculation about author/publisher motives are not accepted as verified facts. Stefan Baumgartner's first-person learning article praises a self-contained Programming Rust async chapter, but the article's prose does not establish an exact edition [R4]. Neither assessment is a third-edition endorsement.

The two accounts suggest that a broad reference may suit some experienced programmers better than a guided beginner sequence. Compared with [Rust for Rustaceans](gjengset-rust-for-rustaceans-1.md), this candidate appears broader in foundations; compared with [Zero To Production](palmieri-zero-to-production-in-rust-2022.md), it is not principally a sustained web-backend build. Those are provisional scope comparisons, not a completed comparative book test.

## Currency and errata work still required

Current Rust documentation confirms that ownership-related unsafe contracts and trait-object limitations require precise treatment [R5–R6]. These references establish relevant questions, not that the third edition answers them correctly. Check the third-edition treatment of newer async features, unsafe-operation scope and library APIs against the current primary contracts.

An attempted publisher errata navigation failed before returning a resolved URL; no comprehensive second- or third-edition errata audit was completed. A short original preview is not a full chapter, and a contents page is not correctness evidence. No code was run. Do not promote until these evidence gaps are closed; do not require purchase or access-format research first.

## Evidence and leads

All accessed **2026-10-16**. The following ledger intentionally does not satisfy the complete recommendation gate.

| ID | Exact source / inspected locator | Source date and limitation |
| --- | --- | --- |
| R1 | https://www.oreilly.com/library/view/programming-rust-3rd/9781098176228/ — identity, overview and contents through chapter17 | Publisher-listed October2026. Original metadata/scope, not substantive chapter correctness or independent evaluation. |
| R2 | https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/ and https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/ch04.html — identity/contents and brief chapter4 opening | June2021. Second edition, preview too short for deep contents substantiation. |
| R3 | https://rustapopoulos.wordpress.com/2021/07/02/book-review-programming-rust-fast-safe-systems-development-2nd-edition/ — full critical firsthand review | Published2021-07-02, updated07-03. Explicit2e, not3e. |
| R4 | https://oida.dev/getting-started-with-rust/ — full learning/teaching account | 2021-12-23. Relevant firsthand chapter experience; edition not pinned by inspected prose. |
| R5 | https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html — migration/lint behavior | Current guide, update date unstated. Technical comparison question, not book endorsement. |
| R6 | https://doc.rust-lang.org/reference/items/traits.html#dyn-compatibility — dispatchable-method restrictions | Current Reference, update date unstated. Technical comparison question. |
| R7 | ../research/sources/2026-10-16-04/017-reconciled-edition-and-stale-errata.md | Exact edition reconciliation and unsuccessful earlier retrievals. |

## Next decision

Inspect a substantive legitimate original chapter from the third edition, seek an independent exact-edition assessment or explicit teaching assignment, and verify relevant errata. Alternatively reassess a well-supported earlier edition on its own merits. Retain this decision in [UNSELECTED](../research/UNSELECTED.md); no edition, format or translation can inflate the work count.
