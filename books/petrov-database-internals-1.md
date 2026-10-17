---
work_id: petrov-database-internals
title: "Database Internals: A Deep Dive into How Distributed Data Systems Work"
authors: ["Alex Petrov"]
edition: "First edition, 2019; publisher-confirmed corrections through 2020 inspected"
publication_year: 2019
isbn_by_format: {}
primary_subject: databases-and-data-modeling
additional_subjects: [concurrency-and-distributed-systems]
concepts: [storage-engines, b-trees, lsm-trees, file-layout, transactions, replication, consensus]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, reference]
formats: []
access: unknown
official_url: "https://www.databass.dev/"
last_verified: "2026-10-17"
status: recommended
review_status: pending
reviewed_commit: null
---

# Database Internals — first edition

## Recommendation and audience

**Recommend for programmers seeking to reason about storage-engine choices and the distributed mechanisms around them.** Data-structure, operating-system and database familiarity will help; this is not a SQL syntax course or an operational runbook. The selection is supported by original author/editor material, explicit independent chapter assignment and current technical context, not author-page testimonials [P1–P6].

The author frames the work across database implementations rather than as a dissection of one product [P1]. That makes it useful as a conceptual bridge between general data structures and engine documentation. No full-book reading, implementation exercise suite or database benchmark was performed.

## Actual contents and distinctive value

Publisher contents and author material identify a storage-engine half and a distributed-systems half [P1,P2]. The former covers page organization, tree and log-structured storage and transaction mechanisms; the latter sustains coordination, replication and consensus topics. **Databases & Data Modeling** is primary, with **Concurrency & Distributed Systems** a substantial secondary subject, not a duplicate recommendation.

The detailed publisher-confirmed corrections expose actual technical content, including index indirection and different leaf/nonleaf split operations [P3]. Those first-party corrections, the chapter map and the independently assigned B-tree chapter jointly support this assessment of contents. The visible chapter3 preview was brief; it was not represented as an inspected full original chapter [P2].

## Independent assessment and evidence limits

MIT's Spring2026 database course explicitly assigns Petrov chapter2 and provides related discussion questions [P4]. This is concrete educational use, not an undated mention or a claim that every chapter is mandatory.

Shion Honda's2025 firsthand review favors the book's low-level depth relative to DDIA and suggests supplementary explanation for some material [P5]. Its technical summary is not adopted as a specification: compressed consistency and protocol descriptions are too weak to establish exact book correctness. The page's shortened retail links also warrant a commercial-link caveat. MIT's assignment, rather than this review alone, anchors the independent evidence.

## Present-day relevance and dated boundaries

Modern engine documentation still requires understanding merging, deletion markers and amplification costs; Tarantool's Vinyl guide illustrates these concerns [P6]. Its vendor comparisons and undated performance assertions are not imported as universal facts. YottaDB's transaction documentation distinguishes rollback from restart and warns about external side effects [P7]. Such contracts show why the book's mechanism-level reasoning remains useful while exact products, defaults and guarantees need separate verification.

This is not a current ranking of database products, a promise that2019 hardware ratios still hold, or an implementation-correctness certificate. Use maintained engine references for an actual deployment. Price, format, purchase links and ability to obtain a copy did not determine selection.

## Limitations and alternatives

Compared with the catalog's Database System Concepts, this assessment emphasizes engine implementation concerns rather than a broad database curriculum; compared with DDIA, it supplies a more concentrated storage-mechanism route rather than general application architecture. Those distinctions are curator judgments from scope and independent teaching, not a comparative full-book reading.

Important inspected corrections include index pointers, leaf/nonleaf splitting, a separator figure, timestamp-order wording and synchronous/asynchronous terminology [P3]. Consult the actual ledger rather than assuming any unidentified copy includes every repair. Further original-example comparison and distributed-protocol scrutiny remain valuable for subsequent and final review.

## Edition and correction boundary

Publisher/author checks establish the2019 first-edition work, with no substantiated newer numbered edition in the bounded recheck [P1,P2]. Specific corrections are dated2020; an access date does not make them newly discovered or prove correction of all formats/builds [P3]. No format-specific ISBN or unknown digital build is invented.

The previous deferral is retained as superseded in UNSELECTED. It was an incomplete evidence assessment, not a supported poor-quality verdict. The accumulated first-party corrections and explicit teaching evidence now fill the required roles without imposing possession of a full copy as an extra eligibility gate. All inspection limits remain visible; recommendation review is **pending**.

## Evidence ledger

All accessed **2026-10-17**. Original source dates remain separate.

| ID | Exact document and inspected locator | Date / role and limitation |
| --- | --- | --- |
| P1 | https://www.databass.dev/ — scope, Storage Engines/Distributed Systems and FAQ | Page update unstated. Author identity/scope; embedded testimonials not independent evidence. |
| P2 | https://www.oreilly.com/library/view/database-internals/9781492040330/ch03.html — identity, full chapter map and brief chapter3 opening | Publisher labels2019. Original preview limited; no full chapter read. |
| P3 | https://www.oreilly.com/catalog/errata.csp?isbn=0636920174462 — confirmed technical rows, especially pp21,39,40,99,190,274 | Corrections2020-01-28,2020-01-29 and2020-09-04. First-party content/correction evidence, not every printing's identity. |
| P4 | https://dsg.csail.mit.edu/6.5830/lectures/lecture5.php — required reading and discussion questions | Spring2026; page update unstated. Independent specific chapter adoption. |
| P5 | https://hippocampus-garden.com/book_review_petrov/ — complete review and current author bio | Review2025-04-27; later bio not a review revision date. Firsthand appraisal with summary-quality and retail-link limits. |
| P6 | https://www.tarantool.io/en/doc/latest/platform/engines/vinyl/ — Filling, Compaction, Search and implementation limits | Current3.x documentation location; narrative date unknown. Primary storage-design context, not new benchmark evidence. |
| P7 | https://docs.yottadb.com/ProgrammersGuide/langfeat.html — Transaction Processing, TP Definitions, Key Considerations | Living primary manual; revision date unstated. Actual transaction-restart boundaries. |
| P8 | ../research/sources/2026-10-17-01/README.md — logs012–013,016–017,022 | Exact attempts, failed guessed errata paths, preserved earlier deferral and decision. Not another independent book review. |

## Next review

Independently inspect this published recommendation, compare a further original algorithm or diagram with the significant corrections, and recheck a specific contemporary engine contract. Separate the reviewer's shorthand from Petrov's actual prose. Do not silently broaden partial inspection into an entire-book or production-safety approval.
