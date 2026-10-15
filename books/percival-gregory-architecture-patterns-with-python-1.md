---
work_id: percival-gregory-architecture-patterns-with-python
title: "Architecture Patterns with Python: Enabling Test-Driven Development, Domain-Driven Design, and Event-Driven Microservices"
authors: ["Harry J. W. Percival", "Bob Gregory"]
edition: "First O'Reilly edition (March 2020); author-hosted online text"
publication_year: 2020
isbn_by_format: {}
primary_subject: software-architecture
additional_subjects: [software-design-and-code-quality, software-testing-and-quality-assurance]
concepts: [domain-driven-design, hexagonal-architecture, dependency-inversion, repository-pattern, unit-of-work, event-driven-architecture, test-doubles]
languages: [Python]
technologies: [SQLAlchemy, Flask, Redis]
difficulty: intermediate
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://www.cosmicpython.com/book/preface"
last_verified: "2026-10-15"
status: recommended
review_status: passed
reviewed_commit: "dca423978a1a7ab5a5e491eca1c2f59d499b75ea"
---

# Architecture Patterns with Python — first edition

## Recommendation and audience

**Recommend for experienced Python developers designing applications with growing domain complexity and dependencies.** It teaches how to separate business decisions from database, HTTP and messaging mechanisms so the core can be tested and changed. Know ordinary Python classes, automated tests, SQL and HTTP basics; the architecture and DDD vocabulary is not taught from absolute zero. O'Reilly identifies **Harry Percival and Bob Gregory**, a **March 2020** first-edition work and its chapter sequence. Its online catalog identifier is not assigned to an unverified individual ebook format. [S1], [S2]

This assessment read substantial author-hosted prose (preface, repository and external-events chapters), the publisher's limited chapter-one preview, a dated independent critical review and versioned current platform documentation. It did **not** read every chapter, implement the inventory service, or execute code. Availability, price, format and publication age were not selection criteria.

## Technical contents and subject fit

The original **chapter 2, Repository Pattern**, makes the dependency-inversion tradeoff concrete. A domain model is mapped without ORM-defined domain classes; the persistence adapter implements a narrow repository interface. A fake repository makes service tests simpler, but the extra abstraction incurs implementation effort. The text includes an old SQLAlchemy imperative-mapping API and considers the cost of extra layers rather than prescribing repositories for every small script. [S3]

The original **chapter 11, Event-Driven Architecture: Using Events to Integrate Microservices**, introduces asynchronous publishing and consuming to reduce temporal coupling, with Redis pub/sub and end-to-end verification. Its example is an instructional integration slice, not a complete durable-delivery system. Publisher contents substantiate sustained treatment of domain models, service layer, unit of work, aggregates, consistency boundaries, event buses, commands, CQRS and dependency injection. [S1], [S4]

**Software Architecture** is primary: it organizes system boundaries and cross-component tradeoffs. **Software Design & Code Quality** is justified by detailed dependency inversion, code-level repository and aggregate patterns; **Software Testing & Quality Assurance** by the book's sustained high/low gear TDD, fake adapters and test-pyramid techniques, not merely one testing mention. A few Redis examples do not automatically make it a distributed-algorithms or message-broker manual. [S1]–[S4]

## Independent critical assessment and contemporary applicability

Roland Buresund's original **2022-03-13** independent reading gives the work a **6/10**: a fairly good explanation of large-scale Python patterns, but dry, narrow in its furniture/business use case and Flask/Redis stack, and demanding prior TDD, event-driven and DDD familiarity. This is real negative evidence, not an endorsement inflated from publisher prose. For an intermediate reader with a complex existing codebase, the inspected dependency-inversion and testability exercises still provide concrete value despite these shortcomings; a novice wanting a Python or Flask introduction should choose another book. [S5], [S3]

Current **SQLAlchemy 2.0** mapping documentation explains that the standalone `sqlalchemy.orm.mapper()` function used in the 2020 chapter was removed. The equivalent imperative mapping is now `registry.map_imperatively()`. Therefore **the old sample is not drop-in runnable on SQLAlchemy 2.x**; learn the boundary first, then port concrete APIs against versioned manuals. [S3], [S6]

The transactional-outbox pattern documents a failure mode omitted by simplistic publish-after-commit integrations: synchronizing stored state with message publication can require an outbox and relay, which may publish duplicates. RabbitMQ and NATS documentation demonstrate distinct delivery choices; an abstract event bus or transient Redis pub/sub does not itself promise exactly-once processing, replay or durable recovery. Those modern checks support *why* explicit service boundaries and failure thinking remain useful, **not** that the book's exact code or recommendations implement modern broker guarantees. [S4], [S7], [S8], [S9]

## Boundaries and alternatives

The book concentrates on a single business-oriented Python example. Extra abstractions can burden small systems, and an unchanged Flask/SQLAlchemy/Redis setup is not today's framework migration recipe. A database-specific migration, security and SRE program needs additional guidance. For team-wide process, choose the catalog's [Software Engineering at Google](winters-manshreck-wright-software-engineering-at-google-2020.md); for extensive practical legacy characterization techniques, [Working Effectively with Legacy Code](feathers-working-effectively-with-legacy-code-1.md) is deeper in that task. These complement the book rather than establish a measured hierarchy. [S5], [S6], [S7]

The publisher's errata endpoint returned an error during this cycle, so a comprehensive correction/printing check was **not** possible. The original sources establish this first edition; no later edition is asserted from incomplete searches. Unknown format-specific ISBNs are left blank rather than inferred. [S1], [S10]

## Evidence ledger

All documents attempted/accessed **2026-10-15**; source dates below are independent and are not inferred from access. A restricted or failed response is labelled, not upgraded into evidence.

| ID | Exact URL and inspected locator | Source publication/update / evidence role |
| --- | --- | --- |
| S1 | [O'Reilly bibliographic page / contents](https://www.oreilly.com/library/view/architecture-patterns-with/9781492052197/ch01.html), header, Part I chs.1–7, Part II chs.8–13, exposed *What Is a Domain Model?* | **March 2020** first edition; identity/actual scope, limited publisher preview |
| S2 | [Authors' original preface](https://www.cosmicpython.com/book/preface), *Managing Complexity*, *Who Should Read This Book*, Parts I–II | Original book 2020; page footer updated 2023-11-24; author viewpoint, not independent review |
| S3 | [Authors' chapter 2](https://www.cosmicpython.com/book/chapter_02_repository), *Applying DIP*, *Inverting the Dependency*, *Fake Repository*, *Trade-Off* | Original 2020 web text; chapter revision date unknown |
| S4 | [Authors' chapter 11](https://www.cosmicpython.com/book/chapter_11_external_events.html), *Temporal Decoupling*, *Using a Redis Pub/Sub Channel*, integration tests | Original 2020 web text; revision unspecified |
| S5 | [Roland Buresund's firsthand critique](https://www.buresund.se/books/architecture-patterns-with-python/), *Reviews / Opinion* | Review **2022-03-13**; different site metadata 2021-04-01 |
| S6 | [SQLAlchemy 2.0 class-mapping API](https://docs.sqlalchemy.org/en/20/orm/mapping_api.html), *Mapper*, *registry.map_imperatively* | Displayed release **2.0.54 / 2026-09-15**; implementation-specific authoritative API |
| S7 | [Transactional Outbox](https://microservices.io/patterns/data/transactional-outbox.html), Problem, Solution, Resulting Context | Exact publication/update unknown; current delivery tradeoff pattern, not book appraisal |
| S8 | [RabbitMQ Python tutorial](https://www.rabbitmq.com/tutorials/tutorial-one-python), publisher/consumer/queue scope | Live project documentation, update unknown |
| S9 | [NATS overview](https://docs.nats.io/concepts/what-is-nats), core messaging/JetStream distinction | Live project documentation, update unknown |
| S10 | [O'Reilly errata attempt](https://www.oreilly.com/catalog/errata.csp?isbn=9781492052203), failed retrieval | No errata body inspected; not a zero-errors finding |

## Next review

**Passed a qualified later-run assessment**; further review should execute a declared-version fake-versus-real test, check exact SQLAlchemy 2.1 mapping ports and source-level migration, resolve significant edition-specific errata, and investigate additional independent criticism. No full program execution or final collection audit is claimed.

## Independent subsequent-run review — 2026-10-15

Reviewed the published recommendation from **`dca423978a1a7ab5a5e491eca1c2f59d499b75ea`**, not a change created in this same run. Reopened full original [chapter 2](https://www.cosmicpython.com/book/chapter_02_repository) and [chapter 6, Unit of Work](https://www.cosmicpython.com/book/chapter_06_uow). In chapter 6's *Fake Unit of Work for Testing* example, the fake merely sets a **committed flag** while rollback is a no-op; successful fake tests **do not demonstrate real database atomicity or rollback correctness**. The authors themselves acknowledge a SQLAlchemy Session already provides unit-of-work behavior and discuss abstraction cost. This qualifies, rather than undermines, the architectural teaching: complement isolated service tests with real-DB integration checks. [S3], [S11]

The independently critical [Buresund review, 2022-03-13](https://www.buresund.se/books/architecture-patterns-with-python/) was reopened in full. Its **6/10**, dry exposition, narrow business setting, and assumed knowledge remain limiting evidence, not proof of universal superiority. [S5] Current [SQLAlchemy 2.0 migration notes](https://docs.sqlalchemy.org/en/20/changelog/migration_20.html) confirm `mapper()` moved to `registry.map_imperatively()`, while direct string execution through `Connection.execute()` needs `text()` or driver-specific execution. SQLAlchemy **2.0.54 (2026-09-15)** is marked legacy relative to **2.1**, so **no unchanged modern compatibility claim** is warranted. [S12] Preserve the event-delivery and correction gaps in the original assessment. The **Architecture** primary, **Design** and **Testing** secondaries remain supported by substantial chapters and exercises, not incidental keywords. No code was executed or comprehensive errata verified.

| Additional evidence | Locator / original source date | Access date |
| --- | --- | --- |
| [S11] [Author's Unit of Work chapter](https://www.cosmicpython.com/book/chapter_06_uow) | *Fake Unit of Work for Testing*, *Explicit Tests for Commit/Rollback Behavior*, *Wrap-Up*; 2020 text, site footer 2023-11-24 | 2026-10-15 |
| [S12] [SQLAlchemy migration 1.4→2.0](https://docs.sqlalchemy.org/en/20/changelog/migration_20.html) | *execute() method more strict* and *original mapper() function renamed*; displayed 2.0.54 release 2026-09-15 | 2026-10-15 |
