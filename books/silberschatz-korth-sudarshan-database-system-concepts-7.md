---
work_id: silberschatz-korth-sudarshan-database-system-concepts
title: "Database System Concepts"
authors: ["Avi Silberschatz", "Henry F. Korth", "S. Sudarshan"]
edition: "Seventh edition"
publication_year: 2019
isbn_by_format: {}
primary_subject: databases-and-data-modeling
additional_subjects: []
concepts: [relational-model, normalization, indexing, query-optimization, transactions, concurrency-control, recovery]
languages: [SQL]
technologies: [PostgreSQL]
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: []
access: unknown
official_url: "https://db-book.com/index.html"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Database System Concepts — Seventh Edition

## Recommendation, audience and edition

**Recommend as a serious reference on relational data modeling and database implementation**, for programmers and advanced students comfortable with programming, basic math and data structures. The [authors' official website](https://db-book.com/index.html) identifies Silberschatz, Korth and Sudarshan, McGraw-Hill and **March 2019** publication. The original [preface, pp.xv–xx](https://db-book.com/preface-dir/preface.pdf#page=1) describes senior-undergraduate/early-graduate audiences. ISBN 9780078022159 on that site is **not presumed to be an ebook-format-specific identifier**. [S1], [S3]

## Actual technical material and subject assignment

The [official contents](https://db-book.com/toc-dir/toc.pdf#page=4) covers data models, SQL, normalization (ch.7), storage/indexing (ch.14), processing/optimization (chs.15–16), transaction processing, concurrency control and recovery (chs.17–19), and distributed DBMS processing (ch.23). More than a contents page was inspected: original [chapter 27, *Formal Relational Query Languages*](https://db-book.com/online-chapters-dir/27.pdf#page=2) presents quantified tuple relational calculus examples; original [chapter 32, *PostgreSQL*](https://db-book.com/online-chapters-dir/32.pdf#page=4) illustrates database execution and MVCC internals. This supports **Databases & Data Modeling**, not blanket membership in every subject mentioned by a chapter. These were samples, not complete book reading. [S2], [S4], [S5]

## Present-day use and important obsolete content

Bilkent's **Fall 2026 CS353** explicitly [requires this exact seventh edition](https://www.cs.bilkent.edu.tr/~dibeklioglu/teaching/cs353/) for SQL, relational design, indexing, query plans and transactions; a separate [Summer 2026 course](https://www.cs.bilkent.edu.tr/~oulusoy/cs353-summer.html) also requires it. These are direct independent examples of continuing educational relevance. [S6], [S7]

**Do not copy its 2019 PostgreSQL details as current operations guidance:** original ch32 discusses a **separate statistics collector**, whereas PostgreSQL's official [version 15 release notes, monitoring §E.20.3.1.5](https://www.postgresql.org/docs/15/release-15.html) explicitly state that this collector was removed and statistics moved into shared memory. The [current indexing reference](https://www.postgresql.org/docs/current/indexes-types.html) supports living relevance of B-tree/index topics without endorsing every example in 2019 text. Relational design, transaction isolation and cost-based optimization remain useful regardless of age. [S5], [S8], [S9]

## Limitations and comparisons

Breadth and mathematical detail make it valuable for foundations and later reference but potentially overwhelming for a simple SQL tutorial. PostgreSQL case-study specifics, old XML/web technologies, and chapter 26 blockchain examples are time-bound. Bilkent also lists Ramakrishnan/Gehrke and Garcia-Molina/Ullman/Widom as possible comparison texts, not yet approved recommendations. An exhaustive errata/edition audit and exercise execution were not performed. Availability, price, format or geography played no role in selection.

## Evidence ledger

**Accessed 2026-10-14; source dates below are independent of access time.**

| ID | Inspected document and locator | Source date |
| --- | --- | --- |
| [S1] | [Official edition site](https://db-book.com/index.html), authors/release | March 2019; web update unknown |
| [S2] | [Original edition contents](https://db-book.com/toc-dir/toc.pdf#page=4), chs.7,14–19,23 | 2019 |
| [S3] | [Original preface](https://db-book.com/preface-dir/preface.pdf#page=1), pedagogical audience | 2019 |
| [S4] | [Original ch27](https://db-book.com/online-chapters-dir/27.pdf#page=2), tuple calculus | Updated 2019-01-20 |
| [S5] | [Original ch32](https://db-book.com/online-chapters-dir/32.pdf#page=4), PostgreSQL internals | Updated 2019-09-27 |
| [S6] | [Bilkent Fall 2026 syllabus](https://www.cs.bilkent.edu.tr/~dibeklioglu/teaching/cs353/), required text | Fall 2026 |
| [S7] | [Bilkent Summer 2026 syllabus](https://www.cs.bilkent.edu.tr/~oulusoy/cs353-summer.html), required text | Summer 2026 |
| [S8] | [PostgreSQL 15 official release](https://www.postgresql.org/docs/15/release-15.html), removed statistics collector | 2022 release |
| [S9] | [Current PostgreSQL index methods](https://www.postgresql.org/docs/current/indexes-types.html), access types | Live; revision unknown |

## Next review

**Pending independent later-run assessment** of original chapter claims, exact edition course use, significant errata and competing texts. Preserve the explicit outdated PostgreSQL case-study warning.
