---
work_id: nygard-release-it
title: "Release It!: Design and Deploy Production-Ready Software"
authors: ["Michael Nygard"]
edition: "Second edition (P1.0)"
publication_year: 2018
isbn_by_format: {}
primary_subject: software-architecture
additional_subjects: [reliability-and-observability]
concepts: [failure-modes, circuit-breakers, bulkheads, timeouts, back-pressure, service-coupling]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: [pdf, epub, mobi]
access: unknown
official_url: "https://pragprog.com/titles/mnee2/release-it-second-edition/"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Release It! — second edition (2018)

## Recommendation and audience

**Recommend to software engineers, production architects and reliability-minded developers designing systems that contain failures**, rather than a current cloud-provider cookbook. Prior experience with services, deployment and production incidents improves the book's use, despite the publisher claiming no prerequisites. [S1] The publisher identifies Michael Nygard, *Release It! Second Edition*, January 2018 and first printing P1.0 dated 2018-01-09. Sidebar says 'Edition 1' but the title and original excerpt copyright explicitly establish the second edition; preserve that metadata conflict rather than misclassify the work. Publisher ISBN 9781680502398 is not assigned to an unverified ebook format. [S1][S2]

## Contents and classification

Part *Create Stability* covers integration points, chain reactions, capacity and back-pressure, circuit breakers and bulkheads. Later parts cover production architecture, versioned deployment and systemic problems. The primary category **Software Architecture** represents failure isolation and dependency design; **Reliability & Observability** captures substantial operations and degradation/recovery treatment. The original chapter 4 excerpt, PDF pages 5–8, explains dense integration coupling and depicts alternative service dependency graphs; the diagrams are primary material inspected visually, not a claim to have read the whole book. [S1][S2]

## Current usefulness

The lasting insight is to expect partial failure, bound consumption, prevent cascading load and observe failure modes. Current [Dapr resiliency policy docs](https://docs.dapr.io/operations/resiliency/policies/circuit-breakers/) describe open and half-open transitions; [Envoy circuit breaking](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/upstream/circuit_breaking) describes request/connection/retry resource limits (its viewed page was marked **1.41.0-dev**, not a stable-release guarantee). Implementations differ: the book's named pattern is not an API contract. [S5][S6]

## Independent evaluation and limitations

A 2023 firsthand **second-edition** evaluation particularly recommends fault taxonomy, stability patterns, deployment and API versioning while criticizing manual networking/server practices, limited chaos/security depth, and obsolete **OWASP 2017** coverage. A separate 2018 second-edition review values concrete incident stories and stability techniques. Neither is a controlled study, but they provide independent judgment on the actual edition. [S3][S4] The chapter does not replace live OWASP, Envoy, Kubernetes or library specifications. In particular, an old diagram or cloud assumption must not dictate today's configurations.

Compared with *Continuous Delivery*, this work centers on what breaks **in production**, not pipeline design. Compared with *The Site Reliability Workbook*, it emphasizes application/system failure containment more than SLO operations and on-call processes. No universal superiority asserted. A 2025 reader-reported p.174 DNS/request-IP diagram discrepancy has not been adjudicated by the author; label it unresolved, not a confirmed erratum. [S7] No full-book read, experiment or release upgrade was performed.

## Evidence ledger

All sources accessed 2026-10-14; access dates do not imply the source was newly published.

| ID | Exact document and section/page | Publication/update |
| --- | --- | --- |
| [S1] | [Pragmatic publisher](https://pragprog.com/titles/mnee2/release-it-second-edition/), edition heading, P1.0 release log, contents/chapters 4–17 and format labels | January 2018; P1.0 2018-01-09; page update unspecified |
| [S2] | [Publisher's original chapter 4 excerpt](https://media.pragprog.com/titles/mnee2/antipatterns.pdf#page=8), PDF pp.4–8, especially integration-point illustrations and publisher version label | P1.0 January 2018 |
| [S3] | [Marius second-edition firsthand review](https://www.augmentedmind.de/2023/04/30/release-it-book-summary/), *Key topics* and *Conclusion* | 2023-04-30/05-01 (site shows both) |
| [S4] | [Peter Daugaard Rasmussen second-edition review](https://peterdaugaardrasmussen.com/2018/09/18/book-review-release-it-by-michael-t-nygard/), stability patterns, architecture and operations | 2018-09-18 |
| [S5] | [Dapr circuit breaker](https://docs.dapr.io/operations/resiliency/policies/circuit-breakers/), half-open/open policy configuration | v1.18 docs; date of each technical claim unverified |
| [S6] | [Envoy circuit breaking](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/upstream/circuit_breaking), upstream request/connection/retry limits | Viewed version 1.41.0-dev; page update unspecified |
| [S7] | [Reader erratum report](https://devtalk.com/t/release-it-second-edition-typo-in-client-connection-diagram-page-174/214386), p.174 alleged mismatch | 2025-09-11, unverified report |

## Edition and next review

Only this **2018 second edition** is recommended, with its print-versus-web sidebar ambiguity recorded and old OWASP/config examples caveated. Validate another original chapter, source errata resolution and current chaos/back-pressure standards in the next run. **Pending subsequent-run review.**
