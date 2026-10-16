---
work_id: sedgewick-wayne-algorithms
title: "Algorithms"
authors: ["Robert Sedgewick", "Kevin Wayne"]
edition: "Fourth edition"
publication_year: 2011
isbn_by_format: {print: "9780321573513"}
primary_subject: algorithms-and-data-structures
additional_subjects: []
concepts: [data-structures, sorting, searching, graph-algorithms, string-algorithms, empirical-analysis]
languages: [Java]
technologies: []
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: [epub, pdf]
access: unknown
official_url: https://www.informit.com/store/algorithms-9780321573513
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# Algorithms — Sedgewick and Wayne, fourth edition

## Decision and audience

**Recommend, with edition-specific source and errata qualifications.** Original author preface and publisher contents describe a second-course approach combining data abstraction, complete Java implementations and empirical performance analysis [W1,W2]. The intended reader already programs and wants to connect a cost model to an implementation, not only memorize interview answers.

Independent exact-edition adoption is strong: TEDU requires4e2011, and San José State's Summer2025 syllabus assigns specific SW chapters [W3,W4]. In cycle11 the authors' complete maintained Java Quick.java was freshly inspected, including shuffle, partition and selection code [W8]. This is a distinct practical teaching role and complements the independent chapter-level course evidence. It does not establish exact agreement with all 2011 printed copies or certify code correctness. A complete errata body was not available [W10]. Availability was irrelevant.

## Contents, fit and present relevance

Publisher contents cover Java fundamentals, union-find, sorting/priority queues, search trees/hash tables, graph traversal/paths/spanning trees, strings/tries/regular expressions/compression, and broader context [W1]. Primary subject is Algorithms & Data Structures. Java is a language facet, not a reason to place this primarily under general Programming.

The author explicitly discusses a scientific approach to performance hypotheses and measurements [W2]. Modern JGraphT still exposes concrete heap choices for Dijkstra, while Sage's all-pairs documentation exposes quadratic memory and finite representation limits [W6]. These are current reasons to learn implementation-aware algorithm analysis, not proof that old Java examples compile unmodified. The Summer2025 syllabus's Java7-or-later wording is not adopted as current toolchain advice [W4].

Compared with CLRS and DPV this is the executable-language route; Skiena instead foregrounds recognition of problem families. That is enough to justify serious separate investigation, but not automatic approval of every overlapping general algorithms text.

## Edition, adoption and errata limits

InformIT identifies **2011-03-24** publication, copyright2011, fourth edition, both authors and print ISBN9780321573513. EPUB/PDF formats are explicitly described without assigning that print identifier to either electronic subtype [W1]. A later storefront refresh is not a fifth edition. No substantiated newer numbered edition was established by the bounded publisher/author checks.

TEDU's document body is **Fall2025–2026**, although its URL upload directory says2026-06 [W3]. San José State's syllabus is Summer2025, modified2025-06-03, with SW§§2.2,2.4,4.1–4.2,2.3 visible in the rendered assignment table [W4]. UNIC labels SW4e as recommended, not required; JUST uses it as a secondary course reference in2024–25 [W5]. These distinctions remain part of the evidence rather than being flattened into a claim of universal required adoption.

Original companion-site and legitimate publisher-sample attempts failed; the exact attempts are retained [W7]. Relevant book errata and Java/runtime compatibility were not audited. Do not interpret unsuccessful retrieval as proof that the book is unavailable, obsolete, error-free or low quality. The unresolved issue is evidence depth, not acquisition.

## Evidence ledger

All access dates **2026-10-16**.

| ID | Exact source and inspected locator | Original date / role |
| --- | --- | --- |
| W1 | https://www.informit.com/store/algorithms-9780321573513 — edition/date/format metadata and complete TOC | 2011-03-24; publisher identity/scope, not independent review. |
| W2 | https://sedgewick.io/books/algorithms/ — author preface and TOC | Fourth-edition2011 work; page revision unstated. Original teaching rationale, not a technical example audit. |
| W3 | https://www.tedu.edu.tr/sites/default/files/2026-06/CMPE224_Syllabus-v1_0.pdf#page=1 — rendered required-text table/objectives | BodyFall2025–26; exact4e required, upload path not a new semester. |
| W4 | https://wwwtest.sjsu.edu/cs/docs/syllabi/summer25/Data_Structures_and_Algorithms_CS_146_Summer_2025.pdf#page=8 — rendered schedule and extracted bibliography/reading policy | Summer2025, modified2025-06-03; explicit chapter use. |
| W5 | https://www.unic.ac.cy/ECTS_Syllabi/COMP-370.pdf#page=4; https://services.just.edu.jo/CourseQA/Uploads/Syllabus/1737840.pdf#page=1 — rendered bibliography tables | UNIC undated; JUST2024–25/printed2024-11-03. Recommended/secondary, not required whole-book study. |
| W6 | https://jgrapht.org/javadoc/org.jgrapht.core/org/jgrapht/alg/shortestpath/DijkstraShortestPath.html; https://doc.sagemath.org/html/en/reference/graphs/sage/graphs/distances_all_pairs.html — heap choice and floyd_warshall warnings/examples | Update dates unstated; contemporary primary implementation context. |
| W7 | ../research/sources/2026-10-16-06/README.md — chronological source attempts | Failures and scope limits retained, no unofficial-copy substitution. |

## Reconsideration

Inspect an original fourth-edition worked implementation, check its significant corrections and compare its assumptions with the current Java/library environment. Determine whether its distinct implementation-centered value warrants recommendation beside the existing algorithm texts. This recommendation is pending later-run review; the former deferral is preserved as superseded in [UNSELECTED](../research/UNSELECTED.md).


## Cycle11 original implementation and edition check — 2026-10-16

Fresh full author-maintained [Quick.java](https://github.com/kevin-wayne/algs4/blob/master/src/main/java/edu/princeton/cs/algs4/Quick.java) was read: shuffle-before-partition, recursive sort, quickselect, in-bounds scans and supporting StdRandom/StdIn dependencies. File copyright2002–2025 explicitly links to fourth edition2011. This is original worked implementation, **not proof all printings are identical or verified correct**. Current [Java25 Comparable](https://docs.oracle.com/en/java/javase/25/docs/api/java.base/java/lang/Comparable.html) requires consistent transitive ordering; raw Comparable code has type/compatibility caveats. Independent required/adopted fourth-edition use remains in W3–W5. Publisher [fourth-printing errata](https://algs4.cs.princeton.edu/errata/errata-printing4.php) yielded selected indexed corrections but direct open was HTTP403; full correction ledger and which printings contain fixes are unknown. The author's [quicksort booksite](https://algs4.cs.princeton.edu/23quicksort/) likewise exposed meaningful search-indexed algorithm explanations but direct open failed. These search snippets are leads, not the substantive original proof used for approval. Technical novelty versus CLRS/DPV/Skiena is the Java implementation-and-measurement pathway, not another format of those works.

**Newly recommended, subsequent-run review pending.** Next review must compare an actual printed chapter with the maintained code, inspect full edition-specific corrections and test one current Java API contract; no same-run pass or final clearance.
