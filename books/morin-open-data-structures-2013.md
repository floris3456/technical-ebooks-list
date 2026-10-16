---
work_id: morin-open-data-structures
title: "Open Data Structures: An Introduction"
authors: ["Pat Morin"]
edition: "2013 Athabasca University Press work; author online Java text 0.1G separately inspected"
publication_year: 2013
isbn_by_format: {paperback: "9781927356388", pdf: "9781927356395"}
primary_subject: algorithms-and-data-structures
additional_subjects: []
concepts: [dynamic-arrays, amortized-analysis, hashing, linear-probing, binary-search-trees, graph-algorithms, data-structure-invariants]
languages: [Java, "C++"]
technologies: []
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: [pdf, web]
access: unknown
official_url: https://www.aupress.ca/books/120226-open-data-structures/
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# Open Data Structures — Pat Morin

## Recommendation and audience

**Recommend a focused, mathematically reasoned introduction to implementing and analyzing data structures.** The reader should know a programming language, recursion and basic proofs; this is not a beginner's first syntax tutorial. The publisher identifies Pat Morin and a 2013 volume, while the author-maintained Java text exposes actual worked representations and invariants [M1–M4]. Independent instructors/reviewers report useful classroom adoption, including a detailed 2026-02-11 instructor assessment [M5]. Those accounts describe experience, not a controlled comparative learning trial.

## Inspected content and subject fit

In original author Java §§2.1, 5.2, 6.2, an array-backed list grows/shrinks using amortized reasoning, an open-addressing hash table distinguishes active entries and tombstones while bounding occupancy, and an unbalanced binary-search tree enforces ordered traversal and replacement invariants [M2–M4]. These are **substantive original explanations with code**, not merely a catalog or publisher promise. Full chapter sets, other language versions and a complete run of the source code were not inspected.

**Algorithms & Data Structures** is the sole subject. The book teaches concrete representations, costs and tradeoffs with Java and C++ language variants; this does not make it a general Java/C++ handbook or concurrency reference. A C++ beta0.1G copy is named in a Fall2026 course, whereas an independent Spring2026 syllabus recommends the Java version [M6–M7]. Those are work-level teaching endorsements, not proof their binaries match the 2013 publisher PDF or our inspected Java online page.

## Enduring principles versus contemporary implementations

Geometric array growth/shrinkage, load-factor tradeoffs, probing/tombstone handling and search-tree order constraints remain useful in 2026. The 2026 Abseil guide distinguishes flat Swiss-table storage from node tables and warns that rehash invalidates pointers for flat tables [M8]. Boost's current unordered-container guide also distinguishes flat open addressing and pointer stability [M9]. These modern primary technical contracts validate the underlying need to reason about layout, cost and invalidation; they **do not** certify Morin's particular resize thresholds, Java version compatibility or benchmark performance. Likewise C++ standard-library references distinguish iterator from pointer invalidation on rehash [M10]. The book's simple hash representation is an instructional model, **not** a contemporary drop-in replacement for a mature library. No experiments, benchmark runs or full proof audit were performed.

## Limitations and alternatives

The mathematical presentation expects comfort with asymptotics and proofs. Reviewer Andrew Black identifies unfamiliar USet/SSet naming and some omissions in treatment of quicksort, while other education reviews praise clarity and breadth [M5]. We retain that criticism rather than universalizing a favorable average score. Each Java/C++ text has implementation-language and version assumptions; consult current standard libraries for API guarantees [M8–M10].

CLRS is a much broader reference and DPV a compact **algorithm-design** course, while Morin emphasizes the mechanics of concrete data structures. Skiena foregrounds technique recognition, and Sedgewick–Wayne fourth edition combines complete Java programs with algorithms across sorting/graphs/strings; **neither similar topics nor multiple author variants imply duplicate works**. This is a subject-role comparison of inspected sources, not a claim to have read every page.

## Identity, edition and correction boundary

Athabasca University Press identifies August 2013, 336 pages and separate paperback/PDF ISBNs [M1]. The author site labels its Java HTML **edition 0.1G** and maintains related C++/pseudocode variants; an archive lists versions through 0.1g but directory timestamps do not certify release dates or edition equivalence [M2]. **Do not silently treat the online revision, 2013 PDF and translated edition as identical files or separate recommendations.** The publisher and author domains show different permissions descriptions; no copyrighted binary is reproduced. No authoritative consolidated work-specific errata, precise corrected-printing map or demonstrably newer numbered edition was established in this bounded review. Absence of a found errata list is not a claim of zero errors. Price/format/access were never selection gates.

## Evidence ledger

**All accessed 2026-10-16.** Publication/source update dates are stated separately and left unknown where missing.

| ID | Exact inspected document and section | Source date and evidentiary limit |
| --- | --- | --- |
| M1 | https://www.aupress.ca/books/120226-open-data-structures/ — title, author, publication, formats/identifiers and TOC | 2013-08 work; site revision unstated. Primary bibliographic evidence. |
| M2 | https://opendatastructures.org/ods-java/ and https://opendatastructures.org/versions/ — cover/TOC and online version index | Java edition 0.1G; version timestamps through 2014, individual page update unstated. Online author representation only. |
| M3 | https://opendatastructures.org/ods-java/2_1_ArrayStack_Fast_Stack_O.html — §2.1 resizing and cost analysis | Original author example, site revision unknown; sampled not compiled. |
| M4 | https://opendatastructures.org/ods-java/5_2_LinearHashTable_Linear_.html — §5.2, and https://opendatastructures.org/ods-java/6_2_BinarySearchTree_Unbala.html — §6.2 | Original probing/tree invariants and pseudocode, revisions unknown; not complete book. |
| M5 | https://open.umn.edu/opentextbooks/textbooks/171 — full named educator reviews; Cory Scott and Andrew Black sections | Scott 2026-02-11, Black 2016-08-21; other reviews 2019/2020. Independent appraisal and caveats, not mathematical proof. |
| M6 | https://ccom.uprrp.edu/~humberto/pages/teaching/ccom3034-f2026.html — course textbook and assessed topics | Fall2026, C++ beta0.1G; page update date unstated. Work-level actual teaching. |
| M7 | https://teachingexcellence.syr.edu/wp-content/uploads/2026/02/CIS-351-Data-Structures-Spring-2026.pdf#page=1 — course materials and projects | Spring2026; recommends Java work, not required. Extracted PDF text only; attempted rendering failed. |
| M8 | https://abseil.io/docs/cpp/guides/container — Hash Tables, Flat/Node guarantees, iteration instability | Maintained provider technical documentation; update date unstated. Not book review. |
| M9 | https://www.boost.org/latest/libs/unordered/doc/html/unordered/compliance.html — Open-addressing and Concurrent Containers | Current primary library guide; update date unstated. Returning previously known family. |
| M10 | https://en.cppreference.com/cpp/container/unordered_map — Iterator invalidation, complexity | Current C++ community reference, page date unknown; not official ISO specification or author's implementation. |

## Next review

A **subsequent invocation** must independently inspect this committed recommendation, more of the original 2013 PDF or reliably corresponding author version, any significant errata/version differences, a second worked proof and relevant current data-structure contracts. Check exact teaching-edition match before making course-copy claims. Until then **pending**, not final-audit cleared.
