---
work_id: winand-sql-performance-explained
title: "SQL Performance Explained"
authors: ["Markus Winand"]
edition: "2012 original English-language work; author-maintained online chapters checked separately"
publication_year: 2012
isbn_by_format: {paperback: "9783950307825"}
primary_subject: debugging-and-performance-engineering
additional_subjects: [databases-and-data-modeling]
concepts: [query-optimization, b-tree-indexes, execution-plans, composite-indexes, pagination, sql-tuning]
languages: [SQL]
technologies: [PostgreSQL, Oracle, MySQL, "SQL Server"]
difficulty: intermediate
focus: [practical, conceptual, reference]
formats: [web, pdf]
access: unknown
official_url: https://sql-performance-explained.com/
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# SQL Performance Explained — Markus Winand

## Recommendation, audience and scope

Recommend for application developers and database engineers who already know SELECT, joins and basic SQL but do not yet reason about index structure, predicate selectivity and execution plans. It is a focused query-performance book, not a SQL syntax primer or general DBMS theory textbook. The original author's English contents and technical web chapters establish the intended path from B-tree pages and filtered predicates through joins, indexed sorting, pagination and plans [W1–W3].

**Debugging & Performance Engineering** is primary because the user's main task is diagnosing and improving query execution; **Databases & Data Modeling** is substantial secondary coverage because index design and physical access paths dominate the work. An independent 2013 technical review by PostgreSQL specialist Pavel Stěhule explains why developer-facing, cross-database indexing knowledge mattered in practice, and critically situates it against general database books [W4]. A full independent 2019 reader analysis discusses its index-seek and ORM guidance [W5]. Those appraisals do not demonstrate that every vendor-specific recipe is correct today.

## Inspected original instruction

The English online original *Anatomy of an Index* explains why indexes duplicate data, how clustered/index-organized storage changes that abstraction, and why ordered leaves plus a balanced search tree support access and update [W2]. The author chapter *Fetching the Next Page* develops pagination as an execution-cost/design choice rather than just attaching LIMIT to a SELECT; its original SQL examples compare offset and seek-style retrieval [W3]. These are original readable explanations, not merely advertising or a table of contents; only the identified chapters, not every page of the physical book, were inspected. The author explicitly describes the online text as an authorized way to read the same intellectual work [W1].

The 2024 University of Tübingen DB2 course lists a **German-language** ISBN, not the English paperback; and Kannur University's curriculum lists *SQL Performance Explained* among essential database readings with an unknown syllabus year [W6–W7]. Those establish related work-level educational use, **not** an exact English-printing assignment or current 2026 semester.

## Why it remains applicable in 2026

Modern PostgreSQL 18 still documents composite B-tree index leading-key selectivity, covering and partial-index tradeoffs, cost-based EXPLAIN and the need for stable ordering when applying LIMIT/OFFSET [W8–W10]. That directly supports the value of understanding index layout and plan inspection. **Qualification:** PostgreSQL 18 also documents conditional *skip scan* on composite indexes even with absent equality on a leading key, so an absolute rule that such indexes can never help later-column predicates would be wrong [W8]. Optimizers and support across Oracle, SQL Server, MySQL, PostgreSQL and contemporary columnar/search engines vary. Do not copy 2012 version-dependent execution-plan commands or performance advice without checking the actual engine/version, data distribution and measurement.

## Alternatives, edition and evidence boundaries

Choose *Database System Concepts* for relational theory, transactions and DBMS architecture; choose this for application-facing query diagnosis. *SQL Antipatterns* addresses erroneous schema/query patterns rather than concentrated tuning, and Petrov's deferred *Database Internals* studies storage engines and coordination more deeply. Those are scope comparisons, not a controlled learning trial. No database workload was benchmarked, no SQL executed and no full print edition/errata register was audited.

The independent 2013 English review gives ISBN **9783950307825**, 204 pages and 2012 publication; the **German edition** has ISBN **9783950307818**, demonstrated by its original cover, and must not be assigned to the English file [W4,W6]. The author site does not establish a stable dated digital build or a complete correction history. Formats web and PDF refer to advertised text availability, not separately counted works or a verified PDF ISBN. Missing format-specific metadata and purchasing availability played no role.

## Claim-to-source ledger

All inspected on **2026-10-16** or separately noted saved earlier source readings; document publication dates are distinct from access. Original saved research did not establish all source page revisions.

| Key | Exact inspected URL and section | Publication/update and role |
| --- | --- | --- |
| W1 | https://sql-performance-explained.com/ — About the Author, Table of Contents and downloadable-PDF statement | Original work 2012; page revision unstated. Author identity/scope, not independent praise. |
| W2 | https://use-the-index-luke.com/sql/anatomy — Anatomy/Clustered Indexes, leaves/B-tree discussion | Original author technical text; web page revision unstated, site copyright2010–2026 is not a revision date. |
| W3 | https://use-the-index-luke.com/sql/partial-results/fetch-next-page — offset versus keyset-style pagination and SQL examples | Original worked technical chapter; web revision unknown. |
| W4 | https://www.root.cz/clanky/markus-winand-sql-performance-explained/ — Pavel Stěhule complete specialist review | 2013-07-08, independent English-edition assessment and ISBN. |
| W5 | https://planspace.org/20190727-sql_performance_explained_by_winand/ — original reader notes on leaf/seek and ORM claims | 2019-07-27, independent supplement; previously persisted branch08 read, not silently claimed newly reopened. |
| W6 | https://db.cs.uni-tuebingen.de/teaching/ss24/db2/ and https://sql-performance-explained.de/img/9783950307818_preview.pdf#page=2 — course ISBN and original German cover | Summer2024 university course; German2012 edition, **not English** print. Saved branch09 inspection. |
| W7 | https://www.kannuruniversity.ac.in/media/documents/Computer_Science.pdf#page=179 — essential reading list | Curriculum date not established; prior rendered p178–179, not recent use claim. |
| W8 | https://www.postgresql.org/docs/18/indexes-multicolumn.html — §11.3 composite leading keys and skip scan | PostgreSQL18 current as of access, update date unstated. |
| W9 | https://www.postgresql.org/docs/18/using-explain.html — §14.1 estimated and actual plans | PostgreSQL18 primary guide; update date unstated. |
| W10 | https://www.postgresql.org/docs/18/queries-limit.html — §7.6 ordering and offset | PostgreSQL18 primary guide; update date unstated. |

## Later-run review

Pending: inspect a new author technical chapter, another independent exact-English-edition assessment and the status of significant corrections; test one current plan example with a controlled dataset if possible. Confirm the scope/metadata against newer edition announcements without mistaking later online revisions or translations for distinct works. This cycle's review is not a final-audit clearance.
