---
work_id: kleppmann-designing-data-intensive-applications
title: "Designing Data-Intensive Applications"
authors: ["Martin Kleppmann", "Chris Riccomini"]
edition: "Second edition"
publication_year: 2026
isbn_by_format: {}
primary_subject: software-architecture
additional_subjects: [databases-and-data-modeling, concurrency-and-distributed-systems, data-engineering]
concepts: [data-system-tradeoffs, replication, transactions, consensus, batch-processing, stream-processing]
languages: []
technologies: []
difficulty: advanced
focus: [conceptual]
formats: [web]
access: unknown
official_url: "https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/"
last_verified: "2026-10-14"
status: candidate
review_status: pending
reviewed_commit: null
---

# Designing Data-Intensive Applications — Second edition

**Uncounted research candidate, not yet a recommendation.** This is a promising system-design work, but independent evidence inspected in this cycle concerned the first edition. It must not be silently transferred to the revised edition.

## What was established

O'Reilly identifies Martin Kleppmann and Chris Riccomini, the second edition, and February 2026 publication. The inspected contents span architectural tradeoffs, data models, storage, replication, sharding, transactions, distributed faults, consistency/consensus, batch and stream processing, and ethics. Those sustained areas support the provisional architecture primary subject and the three additional subjects. [S1]

The accessible preface paragraphs position the work around comparing data-system approaches, not teaching a single product. Only the exposed preface excerpt and detailed contents were inspected; no full-chapter reading is claimed. The advanced label is a provisional curatorial judgment for readers making data-system decisions. [S1], [S2]

## Relevance evidence and its limits

The PostgreSQL 18 manual's transaction-isolation section still requires reasoning about statement snapshots, isolation guarantees, serialization anomalies, and retries. This directly supports the present-day importance of the book's transaction topics, but does not independently validate its explanations or every product example. [S1], [S4]

Murat Demirbas's first-hand October 2024 critique of the first edition's consistency/consensus chapter questions how much material is compressed into one chapter and calls for deeper protocol study. It is useful as a question to test against the new edition, **not a review of the second edition**. Chapter numbering and organization changed; do not claim that his concerns either persist or were fixed without further inspection. [S1], [S3]

## Missing evidence and next action

Find an independent, substantive second-edition evaluation or clearly identified course use, and inspect representative explanatory material beyond the short preface. Test the treatment of transaction isolation or consensus against primary technical references. Compare its breadth with a focused distributed-systems text instead of assuming that reputation proves suitability. These are evidence gaps, not availability or price filters.

The edition-specific errata page reported no confirmed errata when inspected; that is not evidence that the book contains no errors. [S5]

## Evidence ledger

All listed documents were inspected/accessed **2026-10-14**. The exact page update date was not supplied unless stated below.

| ID | Source and inspected location | Source date/version |
| --- | --- | --- |
| [S1] | O'Reilly second-edition landing page, bibliographic header and complete displayed contents | February 2026 book publication |
| [S2] | Second-edition Preface preview, accessible introductory paragraphs only | Second edition, 2026; preview not a full chapter |
| [S3] | Murat Demirbas, first-edition chapter 9 critique, pedagogical scope and protocol-depth discussion | Published 2024-10-25; first-edition evidence only |
| [S4] | PostgreSQL 18 manual, sections 13.2.1–13.2.3 | Documentation version 18; exact update date not supplied |
| [S5] | O'Reilly errata for Second Edition, confirmed-errata tab | Live check; no confirmed entries displayed |

[S1]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/
[S2]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/preface01.html
[S3]: https://muratbuffalo.blogspot.com/2024/10/ddia-chp-9-consistency-and-consensus.html
[S4]: https://www.postgresql.org/docs/18/transaction-iso.html
[S5]: https://www.oreilly.com/catalog/errata.csp?isbn=0636920632788

No claim is made that other sources do not exist. A potentially relevant 2026 author-interview page could not be fetched in this cycle and was not treated as inspected evidence. Preserve this work identifier across first- and second-edition records so editions cannot inflate the eventual count.
