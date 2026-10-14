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
status: recommended
review_status: passed
reviewed_commit: "c1251db102898b3acc3c8ffec259153ae2dc0711"
---

# Designing Data-Intensive Applications — Second edition

**Recommend for experienced backend/data engineers** needing to reason through competing storage and distributed-systems guarantees. This second edition now has independent edition-specific evaluation and explicit Fall 2026 course adoption; first-edition criticism stays separate.

## What was established

O'Reilly identifies Martin Kleppmann and Chris Riccomini, the second edition, and February 2026 publication. The inspected contents span architectural tradeoffs, data models, storage, replication, sharding, transactions, distributed faults, consistency/consensus, batch and stream processing, and ethics. Those sustained areas support the provisional architecture primary subject and the three additional subjects. [S1]

The accessible preface paragraphs position the work around comparing data-system approaches, not teaching a single product. Only the exposed preface excerpt and detailed contents were inspected; no full-chapter reading is claimed. The advanced label is a provisional curatorial judgment for readers making data-system decisions. [S1], [S2]

## Relevance evidence and its limits

The PostgreSQL 18 manual's transaction-isolation section still requires reasoning about statement snapshots, isolation guarantees, serialization anomalies, and retries. This directly supports the present-day importance of the book's transaction topics, but does not independently validate its explanations or every product example. [S1], [S4]

Murat Demirbas's first-hand October 2024 critique of the first edition's consistency/consensus chapter questions how much material is compressed into one chapter and calls for deeper protocol study. It is useful as a question to test against the new edition, **not a review of the second edition**. Chapter numbering and organization changed; do not claim that his concerns either persist or were fixed without further inspection. [S1], [S3]

## Second-edition independent evidence (2026-10-14)

Waterloo Fall 2026 CS431 explicitly names Kleppmann and Riccomini's **second edition** and assigns chapter 1 and selected portions of chapters 3–7, including replication, sharding and encoding. A March 30, 2026 independent second-edition review describes the strengths of architectural tradeoff reasoning and cautions that it assumes some service-engineering experience. O'Reilly's accessible chapter 1 and 6 introductions corroborate actual edition-specific contents. PostgreSQL 18 documentation (current on this check date) demonstrates that transaction-isolation anomalies and retry behavior remain live engineering topics. This supports a recommendation for conceptual architectural design, not the validity of every vendor-specific example. [S1], [S2], [S6], [S7], [S8], [S9]

The broad system tradeoff focus supports Software Architecture primary; sustained data modeling, distributed coordination and batch/stream topics justify the three additional subjects. Source and price availability are not admission criteria.

## Residual checks

Independent second-edition evaluation and use are now documented; a later run must independently review the published record, inspect deeper examples if possible, and evaluate the breadth of secondary classification. Test the treatment of transaction isolation or consensus against primary technical references. Compare its breadth with a focused distributed-systems text instead of assuming that reputation proves suitability. These are evidence gaps, not availability or price filters.

The edition-specific errata page reported no confirmed errata when inspected; that is not evidence that the book contains no errors. [S5]

## Evidence ledger

All documents below were inspected/accessed **2026-10-14**. The exact page update date was not supplied unless stated below.

| ID | Source and inspected location | Source date/version |
| --- | --- | --- |
| [S1] | O'Reilly second-edition landing page, bibliographic header and complete displayed contents | February 2026 book publication |
| [S2] | Second-edition Preface preview, accessible introductory paragraphs only | Second edition, 2026; preview not a full chapter |
| [S3] | Murat Demirbas, first-edition chapter 9 critique, pedagogical scope and protocol-depth discussion | Published 2024-10-25; first-edition evidence only |
| [S4] | PostgreSQL 18 manual, sections 13.2.1–13.2.3 | Documentation version 18; exact update date not supplied |
| [S5] | O'Reilly errata for Second Edition, confirmed-errata tab | Live check; no confirmed entries displayed |
| [S6] | Waterloo Fall 2026 CS431 Organization / Course Materials | Fall 2026 |
| [S7] | Waterloo CS431 Syllabus, week 1–3 book chapter/section assignments | Fall 2026 |
| [S8] | slaptijack second-edition review, audience and tradeoffs | Published 2026-03-30 |
| [S9] | O'Reilly second-edition chapters 1 and 6, accessible introductory paragraphs | February 2026 edition |

[S1]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/
[S2]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/preface01.html
[S3]: https://muratbuffalo.blogspot.com/2024/10/ddia-chp-9-consistency-and-consensus.html
[S4]: https://www.postgresql.org/docs/18/transaction-iso.html
[S5]: https://www.oreilly.com/catalog/errata.csp?isbn=0636920632788

No claim is made that other sources do not exist. A potentially relevant 2026 author-interview page could not be fetched in this cycle and was not treated as inspected evidence. Preserve this work identifier across first- and second-edition records so editions cannot inflate the eventual count.

[S6]: https://lintool.github.io/cs431-2026f/organization.html
[S7]: https://lintool.github.io/cs431-2026f/syllabus.html
[S8]: https://slaptijack.com/articles/designing-data-intensive-applications-2nd-edition-review.html
[S9]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/ch06.html
[S9-ch1]: https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/ch01.html

## Subsequent-run review (2026-10-14)

Reviewed the actual published 2026 second-edition promotion in `c1251db102898b3acc3c8ffec259153ae2dc0711`. O'Reilly's chapter 1 and 6 intros directly confirm the second-edition architecture, replication and tradeoff discussion. Waterloo Fall 2026 CS431 explicitly prescribes this **second edition** and assigns chapters 1 and 3–7, while the March 30, 2026 independent second-edition review assesses its assumptions and architectural value. PostgreSQL 18's isolation documentation confirms that transactions and anomalies remain a live engineering challenge, not that every book example is error-free. The 2024 first-edition critique does not transfer automatically. The broad database, distributed-system and data-engineering secondary tags are supported by substantial listed material but remain open to retrieval-pilot evaluation. **Decision: pass, with depth and errata caveats.** [S1], [S4], [S6], [S7], [S8], [S9]

## Next review

Check deeper consensus and transaction examples, source-specific errata, the justification for each secondary index, and comparison with a focused distributed-systems title. Subsequent review passed; the final collection audit has not.
