---
work_id: reis-housley-fundamentals-of-data-engineering
title: "Fundamentals of Data Engineering: Plan and Build Robust Data Systems"
authors: ["Joe Reis", "Matt Housley"]
edition: "First edition, 2022"
publication_year: 2022
isbn_by_format: {}
primary_subject: data-engineering
additional_subjects: []
concepts: [data-lifecycle, ingestion, storage, transformation, data-serving, governance, data-architecture]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: []
access: unknown
official_url: "https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/ch02.html"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Fundamentals of Data Engineering — First edition (2022)

## Recommendation and audience

**Recommend as a lifecycle-oriented map for engineers and analytics practitioners designing or extending data systems.** It is strongest for organizing decisions across a pipeline, not for learning one tool's commands. Some data/software experience helps; the intermediate label is our audience judgment, not a vendor certification.

The publisher previews identify **Joe Reis and Matt Housley** and a **June 2022** listing. This record evaluates the 2022 work without inferring a later edition from an unrelated recommendation widget. No format-specific ISBN is invented. [S1], [S2]

## Inspected contents and classification

The actual exposed chapter-2 opening frames the lifecycle; chapter 7's opening distinguishes moving data from integrating multiple sources. The detailed publisher contents span generation, storage, ingestion, transformation, serving and cross-cutting concerns. These are **limited original previews**, not full chapters or executed pipelines. [S1], [S2]

Assign **Data Engineering** as primary. Architecture, security and storage are important within that lifecycle but do not automatically make this a separate broad recommendation in every adjacent subject. The classification emphasizes the reader's pipeline-design task.

## Independent evaluation and educational use

Johnny Winter's **2025-04-04** firsthand assessment considers the book from a BI/analytics background, evaluating the lifecycle framework and allocation of technical detail. A separate Xebia reading assessment discusses architecture, technology decisions and security. These are contextual practitioner judgments, not controlled evidence of superior outcomes. [S3], [S4]

The University of Tartu's **2025/26 autumn** course explicitly names Reis/Housley as its main reading and assigns particular chapters throughout the schedule. This establishes actual educational adoption. It is not a Fall 2026 syllabus: a later service banner does not change the academic-year label. [S5]

## Present-day usefulness and limitations

Current Debezium architecture still connects change-capture sources with processing systems. Airbyte's incremental-append documentation describes cursor limitations and duplicate delivery; OpenLineage models dataset, job and run relationships. These substantiate continuing engineering problems addressed by a lifecycle perspective—not the correctness of each book-specific product description. [S6]–[S8]

Our assessment favors this book for orientation, vocabulary and end-to-end tradeoffs. It should be complemented by deeper storage/distributed-systems texts and the actual versioned documentation for an implementation. Product names, configuration examples and vendor comparisons age more quickly than the core design questions. No claim is made that old integrations still run unchanged.

It complements the catalog's [Database System Concepts](silberschatz-korth-sudarshan-database-system-concepts-7.md) rather than replacing a database-theory text. Breadth is valuable only when it matches the reader's task; it is not proof of implementation depth.

## Confirmed corrections and edition limits

The official errata contain substantive corrections: the **p.104 lambda-architecture diagram** needs a batch-processing label; **p.241 Figure 7-4** reverses batch/microbatch frequency; **p.273** incorrectly categorizes UPDATE as DDL rather than DML. The latter two were marked corrected on **2026-03-20**. Check the specific copy rather than assuming every edition/printing incorporates them. [S9]

The unconfirmed-errata view displayed no entries; that does **not** mean the confirmed list is empty or that the book is error-free. No exhaustive printing comparison, complete original-text reading or pipeline execution was performed. [S10]

## Evidence ledger

All accessed **2026-10-14**. Unknown revision dates remain unknown. Exact opening outcomes are retained in the [cycle source log](../research/sources/2026-10-14-12/README.md).

| ID | Exact source and inspected locator | Date / role |
| --- | --- | --- |
| [S1] | [Original ch.2 preview](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/ch02.html), bibliographic header, detailed contents and exposed lifecycle introduction | Publisher June 2022 listing; not a full chapter |
| [S2] | [Original ch.7 preview](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/ch07.html), exposed ingestion/integration opening | 2022 work; preview incomplete |
| [S3] | [Johnny Winter's review](https://greyskullanalytics.com/blog/book-review-fundamentals-of-data-engineering), article and author context | 2025-04-04; firsthand assessment |
| [S4] | [Xebia assessment](https://xebia.com/blog/fundamentals-of-data-engineering/), Good Data Architecture, Choosing Technologies, Security | Exact publication/update date not established |
| [S5] | [Tartu reading schedule](https://courses.cs.ut.ee/2025/dataeng/Main/Links), main text and weekly chapter assignments | 2025/26 autumn; independent educational adoption |
| [S6] | [Debezium architecture](https://debezium.io/documentation/reference/stable/architecture.html), Architecture, Server, Engine | Displayed 3.7; exact update date unknown |
| [S7] | [Airbyte incremental append](https://docs.airbyte.com/platform/using-airbyte/core-concepts/sync-modes/incremental-append), cursor and duplication limitations | Live documentation; exact update unknown |
| [S8] | [OpenLineage](https://openlineage.io/docs/), Design and Scope | Displayed 1.54.0; exact update unknown |
| [S9] | [Confirmed errata](https://www.oreilly.com/catalog/errata.csp?isbn=9781098108304), pp.104,241,273 | Corrections dated 2023-07-28 and 2026-03-20 |
| [S10] | [Unconfirmed errata](https://www.oreilly.com/catalog/errataunconfirmed.csp?isbn=0636920558767), empty displayed queue | Live check; not an error-free claim |

## Next review

**Pending a later run.** Verify the original preview boundaries, exact course term, reviewer/source roles and corrections. Inspect deeper original transformation or serving material and compare a specific pipeline-design task against a focused alternative. Availability, price and publication age had no bearing on selection.
