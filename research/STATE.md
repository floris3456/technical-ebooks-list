# Research checkpoint

## Cycle 2026-10-15-03 — published catalog assessment

**Starting main:** `d727213e25261b11384c9d6cf625cd2ea30761e8` (tree `1ebe84945e6ada3d68739de206c1ebc387c262f4`). Reviewed live README, TAXONOMY, book template, this STATE, SOURCES, REJECTIONS, UNSELECTED, latest source-only commit and observable cycle-02 WIP batches 001–012. The prior STATE remains verbatim in [STATE-through-d727213.md](STATE-through-d727213.md). No access to unpublished research is claimed. Reopened both pending catalog records and their original sources; rotated older Database System Concepts 7e, with an inspection of original rendered PostgreSQL chapter and release/current monitoring notes.

## Recount after this change set

| Measure | Distinct works |
| --- | ---: |
| **Recommended** | **27** |
| **Passed genuine subsequent-run review** | **26** |
| **Pending subsequent-run review** | **1** |
| **Canonical uncounted candidate** | **1** |
| **Retained deferred works, including candidate** | **5** |
| **Completed final collection audit** | **0 / 2,000** |

**41 topic-index appearances represent 27 distinct recommended work IDs**, not edition/format/translation copies. All 23 controlled subjects have at least one primary record, but coverage depth and retrieval are not empirically validated. This cycle: **1 recommendation added; 2 previously pending reviewed and qualified; 0 removals; 1 deferred non-selection added; no category rename or reclassification**. Neither the new book nor a source-only commit can self-certify its own later-run review.

## Review-first and correction decisions

- [Eloquent JavaScript, fourth edition](../books/haverbeke-eloquent-javascript-4.md): **passed qualified later-run review of published commit `3c0c9d505e77a0d99bb5cb641b20d54da9df715c`**. Original async and DOM teaching remains practical. Re-rendered the Spring 2026 course document pp.1/5/11, verified fourth-edition requirement and assignments; preserved conflicting PDF metadata saying Spring 2025. Added an explicit correction: chapter 14's “inline style always wins” shortcut fails for other cascade origins/important layers; async functions returning Promises are not ordinary async generator iterators. Publisher reviews of third edition still not used for fourth-edition endorsement; author corrections remain open for printings.
- [Web Browser Engineering](../books/panchekha-harrelson-web-browser-engineering.md): **passed qualified later-run review of the same previously published commit**, principally the **author-hosted online work**. Original task queues, acknowledged shortcuts, omissions and independent UW Spring 2023 online-work course use checked. Oxford electronic 2024 / print 2025 bibliographic identity is retained, **not** claim of identical complete Oxford text or post-publication print adoption. No implication the teaching browser is suitable for hostile pages, security, JS conformance or actual shipping.
- Rotating [Database System Concepts 7e](../books/silberschatz-korth-sudarshan-database-system-concepts-7.md): reopened original author's PostgreSQL chapter 32, §32.3 on heap pages/tablespaces (rendered PDF p.5), compared PostgreSQL 15 (2022-10-13) release note removing the separate statistics collector and current monitoring documentation. Existing qualified pass retained; neither a new approval nor full chapter audit is claimed.

## New recommendation — pending subsequent-run assessment

- [Architecture Patterns with Python — first edition](../books/percival-gregory-architecture-patterns-with-python-1.md), authors Harry Percival and Bob Gregory, **March 2020**. Original preface, repository and external event chapters were inspected, plus publisher exact table of contents, independent Roland Buresund **2022-03-13 6/10** critique, and current ORM/messaging documentation. Its enduring dependency inversion, domain modeling and fake-adapter lessons are valuable for experienced Python teams, but reviewer concerns about dryness, narrow business domain and prior knowledge remain explicit. The original `sqlalchemy.orm.mapper()` API was removed in SQLAlchemy 2.0; `registry.map_imperatively()` now replaces it. Example Redis pub/sub is not automatically durable or exactly-once; pair with transactional-outbox and broker current docs. The new record has three controlled subject links and **review_status: pending**, not prematurely passed.

## Retained uncounted work

- **Database Internals** by Alex Petrov (2019 first edition, publisher's additional release revisions to 2020) is now separately retained in [UNSELECTED.md](UNSELECTED.md) as **deferred evidence**: original publisher scope, individual February 2026 chapter notes and a Spring 2026 course listing among multiple titles are insufficient to claim a substantively inspected original chapter and strong independent expert appraisal/explicit exact work adoption. Modern storage manuals affirm topic relevance without proving book quality. No age, price, paywall or format criterion applied. Previous four deferred works retain original reasons; none retired.

## Source investigation and dates

The [cycle exact-source audit](sources/2026-10-15-03/README.md) has **22 new substantively inspected website families** under conservative domain consolidation; chronology is in committed 000–015 batch logs. The SQLAlchemy 2.0.54 reference explicitly displays a 2026-09-15 release label; Buresund's review was 2022-03-13; original book March 2020; rendered course Spring 2026; our access date 2026-10-15. Dates remain distinct. Tool failures, search results and original-preview boundaries were retained rather than turned into reading or correctness claims. Prior cycle-02 source-only efforts are saved elsewhere and earned **zero** new credit here.

## Unfinished quality questions and next work

1. In a genuinely later run, independently review **Architecture Patterns with Python** against a concrete fake-versus-real test and the verified SQLAlchemy mapping-port; inspect significant errata or document why unresolved. No same-run review pass.
2. Find credible original chapter depth, independent expert critique and exact course assignments for **Database Internals** before promotion. Do not use vendor popularity or access status as proxies; compare narrower storage books.
3. Continue deeper final-audit checks for Eloquent JavaScript's CSS shortcut, print/web differences, and browser-book Oxford/author-hosted revision correspondence, runtime/security/conformance limits and more recent independent assessment. The later-run passes are not final-audit clearance.
4. Revisit open older OSTEP extraction/version, CLRS printing corrections, Logical Foundations 7.0/7.1 boundary, Security Engineering errata and current infrastructure code examples; sample older records across groups rather than only latest additions.
5. Stress-test subject retrieval and precision against real reader tasks, not just alphabetical coverage; retain rejected/retired records with stable IDs and exact evidence. Maintain 20 genuinely novel substantive website investigations per cycle and immediately committed attempted source logs.

## Validation, review and publication limits

Verified record status/slug/schema changes and category membership against the 23-subject taxonomy and prior canonical work set; **one new stable work ID**, no title/edition duplicate, two later-review transitions and **3 new topic appearances** (2→3 architecture, 1→2 design, 4→5 testing) yield 41. Browser and JavaScript remain on existing indexes; their statuses change to Passed. Final publication must preserve all source-log commits and unrelated main history, re-fetch the remote head, reconcile concurrent work, and use non-force conditional update or expected-head normal merge. Verify the resulting main head and counts. No full book reading, executed full example suite, comprehensive external-link or errata crawl, empirical taxonomy test, or completed final catalog audit. No automation settings changed.
