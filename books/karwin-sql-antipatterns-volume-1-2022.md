---
work_id: karwin-sql-antipatterns
title: "SQL Antipatterns, Volume 1"
authors: ["Bill Karwin"]
edition: "Revised Volume 1, 2022 release P1.0"
publication_year: 2022
isbn_by_format: {}
primary_subject: databases-and-data-modeling
additional_subjects: [software-design-and-code-quality]
concepts: [sql-antipatterns, schema-design, normalization, null-semantics, referential-integrity]
languages: [SQL]
technologies: [MySQL]
difficulty: intermediate
focus: [practical, conceptual]
formats: [pdf, epub]
access: unknown
official_url: https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# SQL Antipatterns, Volume 1 (2022)

## Recommendation and audience

Recommend this applied relational-design and query-correctness guide to programmers who know SQL and review database schemas. It develops recognized failure patterns, costs and appropriate repairs; some apparent antipatterns have legitimate exceptions. The 2022 revised work follows Karwin's 2010 *SQL Antipatterns*: these editions share **one work identifier**. [A1,A4]

Its primary subject is **Databases & Data Modeling** (relations, data constraints and SQL behavior), with substantial additional **Software Design & Code Quality** (reviewable failure/repair patterns). This is not a general MySQL reference.

## Original worked contents and independent appraisal

Authorized PDF pages were visually inspected: *Jaywalking* pp7/9 analyzes comma-separated foreign IDs and lost declarative integrity [A2]; *31 Flavors* p7 evaluates fixed allowed values, and a NULL excerpt p7 illustrates SQL's three-valued logic [A3]. The full table of contents indicates other design/query patterns, but these excerpt readings are not a whole-book read. Frederic Descamps' firsthand review of the **2022 revision**, published 2023-03-20, independently evaluates the examples from a MySQL specialist's perspective [A4]. It does not guarantee portability or correctness.

## Present-day value and limits

PostgreSQL18 §5.5 still documents key and CHECK constraints and null behavior; Prisma documents explicit relational joins and jOOQ documents IS NULL predicates [A7–A9]. These primary technical sources establish the continuing importance of the book's concepts, **not** that 2022 vendor-specific code runs today. ENUM, array and denormalized choices can be appropriate for specific requirements; diagnose tradeoffs rather than applying categorical bans.

The author confirmed substantive errata: p107 partitioning expression, p176 joining latest dates to product IDs, and p235 duplicate column name [A5–A6]. A 2024 intention to fix p176 in a future printing is not proof an inspected copy was repaired. Recheck examples, release and server dialect. No SQL was executed or benchmarked; no complete errata/printing audit.

Choose *SQL Performance Explained* for index/plan tuning, or *Database System Concepts* for foundations. This volume concentrates on frequent development mistakes. The separately titled sequel is not automatically an edition. Publication 2022 and release P1.0 are verified [A1]; format-specific ISBN unknown. Price/access were never filters.

## Sources and correction scope

**All accesses 2026-10-16; document dates below are separate.**

| ID | URL and precise inspected location | Source date/role |
| --- | --- | --- |
| A1 | https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/ — edition/TOC/exception examples | Original publisher, October2022, release P1.0 2022-11-02. |
| A2 | https://media.pragprog.com/titles/bksap1/jaywalking.pdf#page=8 — PDF pp7–9 | Original 2022 worked example. |
| A3 | https://media.pragprog.com/titles/bksap1/31flavors.pdf#page=8 ; https://media.pragprog.com/titles/bksap1/null.pdf#page=8 — each PDF p7 | Original 2022 excerpts. |
| A4 | https://blogs.oracle.com/mysql/mysql-books-sql-antipatterns-volume-1 — full firsthand assessment | 2023-03-20, independent MySQL specialist. |
| A5 | https://forum.devtalk.com/t/sql-antipatterns-volume-1-join-error-page-176/141945 — author response | 2024-02-02 correction; print implementation unknown. |
| A6 | https://forum.devtalk.com/t/sql-antipatterns-volume-1-bad-column-in-partition-by-example-page-107/81455 ; https://forum.devtalk.com/t/sql-antipatterns-volume-1-duplicate-column-name-in-replace-into-page-235/81716 | Author-confirmed 2022-11-07; full threads inspected in saved branch09, not reopened here. |
| A7 | https://www.postgresql.org/docs/18/ddl-constraints.html — §5.5 | Current primary PG18, revision date unknown. |
| A8 | https://www.prisma.io/docs/orm/prisma-schema/data-model/relations — relations (redirect to data-modeling) | Current primary documentation. |
| A9 | https://www.jooq.org/doc/latest/manual/sql-building/conditional-expressions/null-predicate/ — null predicate | Current primary documentation. |

## Next review

Pending independent later-run pass: read a full further chapter, reconcile corrections by printing and broaden independent non-MySQL expert/classroom evidence. No final audit clearance.
