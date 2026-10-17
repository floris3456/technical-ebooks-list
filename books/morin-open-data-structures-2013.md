---
work_id: morin-open-data-structures
title: "Open Data Structures: An Introduction"
authors: ["Pat Morin"]
edition: "Athabasca University Press, 2013; Java text"
publication_year: 2013
isbn_by_format: {paperback: "9781927356388", pdf: "9781927356395"}
primary_subject: algorithms-and-data-structures
additional_subjects: []
concepts: [data-structures, dynamic-arrays, amortized-analysis, hashing, search-trees, external-memory]
languages: [Java]
technologies: []
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: [pdf]
access: unknown
official_url: "https://www.aupress.ca/books/120226-open-data-structures/"
last_verified: "2026-10-17"
status: recommended
review_status: pending
reviewed_commit: null
---

# Open Data Structures — 2013 Java text

## Recommendation and audience

**Recommend for programmers who want to connect data-structure implementations with mathematical cost arguments.** Basic programming, recursion and comfort with proofs are useful prerequisites. This is not an introductory Java syntax course. The independent teaching reviews support that placement while identifying preparation and navigation difficulties [M3]. This assessment selects the publisher's Java text; related language versions are neither additional works nor silently equivalent editions [M1,M4].

## Original contents and subject fit

The publisher identifies August2013, 336 pages and coverage from array lists through hashing, trees, graphs, integer structures and external memory [M1]. The inspected original §2.1.2–2.1.3 presents resizing code and its aggregate-cost proof. Crucially, the bound on total resizing does not eliminate the separate cost of shifting indexed elements [M2]. The connection between representation, operation and proof is the concrete strength of this recommendation.

**Algorithms & Data Structures** is the sole subject. Java is an implementation facet, not grounds to classify this as a general language handbook. Only the recorded original pages were examined closely; no full chapter corpus, executable example suite or C++ variant was tested.

## Independent assessment

The Open Textbook Library contains four signed faculty evaluations. Cory Scott's February2026 account reports years of course use; other reviewers identify proof-preparation needs, dependency between chapters and unfamiliar terminology. Andrew Black supplies specific critical observations rather than an unqualified endorsement [M3]. These are teaching experiences, not measured superiority or proof that every algorithm is correct. Ratings were not used as the evidence gate.

## Present-day usefulness and limitations

The abstract distinction between amortized cost and individual operation cost remains relevant. Java SE26's ArrayList contract promises amortized append without fixing a growth policy [M5]. Therefore the book's resizing thresholds are a teaching design, not the JDK's implementation guarantee. In current OpenBSD tree interfaces, even a lookup may write when the tree splays; traversal/removal also has explicit safety rules [M6]. A familiar operation name alone does not establish mutation, lifetime or cost semantics.

The book's mathematical focus may be demanding without discrete-mathematics preparation. It should not be treated as a production-library, persistent-data-structure or concurrent-container certification. The inspected mutable-array argument is not automatically an amortization proof for a branched persistent history; that gap motivated a separate, uncounted Okasaki investigation [M7].

Relative to CLRS and DPV, this is a more focused representation-and-implementation route; relative to Sedgewick–Wayne, its differentiator here is explicit data-structure analysis rather than a larger program-oriented survey of algorithms. These are curator scope judgments, not claims of comparative learning trials.

## Edition, corrections and provenance

The publisher and rendered copyright/CIP page establish the2013 Java edition and distinct paperback/PDF identifiers [M1,M2]. The author HTML identifies version0.1G and separately labels a C++ beta [M4]. This record does not certify their equality to the publisher PDF. Bounded publisher/author checks did not establish a newer numbered edition or a consolidated correction map; the attempted issue-ledger retrieval failed [M8]. That is an inspection limit, not evidence of an error-free book or a negative availability criterion.

The same stable ID and filename were already present in saved branch11 at `c4a99c0c0fad674fec7cbd9891b2d051c68db317`. That unmerged assessment remains preserved. This freshly sourced, narrower Java record does not count a second work or import uninspected language variants. No purchase, unauthorized copy or book-code execution occurred.

## Evidence ledger

All access dates **2026-10-17**; source dates below are separate.

| ID | Exact document and inspected locator | Date / role and limits |
| --- | --- | --- |
| M1 | https://www.aupress.ca/books/120226-open-data-structures/ — metadata and contents | Work August2013; page update unstated. Publisher identity, not independent praise. |
| M2 | https://www.aupress.ca/app/uploads/120226_99Z_Morin_2013-Open_Data_Structures.pdf#page=4 and #page=47 — rendered PDFp4 and pp47–49, printed33–35 | Copyright2013; PDF revision unstated. Original code/proof and identifiers, not whole-book review. |
| M3 | https://open.umn.edu/opentextbooks/textbooks/171 — all four signed reviews | Cory Scott2026-02-11; Joseph Jess2020-01-14; Breeann Flesch2019-02-25; Andrew Black2016-08-21. Independent teaching/appraisal. |
| M4 | https://opendatastructures.org/ and https://opendatastructures.org/ods-java/ — version and variant notices | Java0.1G; calendar revision unknown. Version boundary only. |
| M5 | https://docs.oracle.com/en/java/javase/26/docs/api/java.base/java/util/ArrayList.html — class cost/growth contract | Explicit SE26, update unstated; not asserted latest release. |
| M6 | https://man.openbsd.org/tree.3 — Splay Trees, comparator and traversal Notes | Manual2025-06-13, OpenBSD-current. Primary implementation countercheck. |
| M7 | https://www.cs.cmu.edu/~rwh/students/okasaki.pdf#page=31 — §3.2, printed19 | Thesis September1996. Original persistence counterexample, not independent review of Morin. |
| M8 | ../research/sources/2026-10-17-01/README.md — logs005–009,011,018,020 | Exact retrieval history including failed issue request and saved-version review. |

## Next review

A later invocation must inspect this published recommendation, a second original proof or representation and any significant version/correction differences. Keep Java2013 separate from HTML0.1G and C++ beta claims. Approval remains **pending** and final-audit clearance is absent.
