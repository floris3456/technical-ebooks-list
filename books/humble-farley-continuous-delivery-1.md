---
work_id: humble-farley-continuous-delivery
title: "Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation"
authors: ["Jez Humble", "David Farley"]
edition: "First edition"
publication_year: 2010
isbn_by_format: {ebook-unspecified: "9780321770424"}
primary_subject: devops-cloud-and-infrastructure
additional_subjects: [software-testing-and-quality-assurance]
concepts: [continuous-delivery, continuous-integration, deployment-pipelines, build-artifacts, acceptance-testing]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: [epub, pdf]
access: unknown
official_url: "https://www.informit.com/store/continuous-delivery-reliable-software-releases-through-9780321770424"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "fc4e04d125275b9ca8880d61e453a36656a12ce2"
---

# Continuous Delivery — first edition (2010)

## Recommendation and audience

**Recommend for intermediate developers, testers and platform engineers learning reproducible, testable release pipelines**, not as a contemporary manual for a specific CI plug-in. Publisher InformIT identifies Jez Humble and David Farley, first edition 2010-07-27 (copyright 2011) and electronic ISBN 9780321770424 covering PDF/EPUB. No format-specific ISBN is invented. [S1] This assessment inspected original chapter 5 and the complete chapter outline, not the whole book or executed deployments.

## Contents and subject fit

Parts I–III cover configuration management, integration, test strategy, automated acceptance/capacity testing, release stages, infrastructure, data migration, version control and governance. The central pipeline/deployment objective makes **DevOps, Cloud & Infrastructure** primary; several substantial testing chapters justify **Software Testing & QA** secondarily. Original chapter 5, web page 3/10, describes promoting the same tested binary, recording artifact hashes and source revision, separating environment configuration and smoke-testing deployments. Those are inspected technical mechanisms rather than publisher hype. [S1][S2]

## Present-day relevance and limitations

The durable lesson is to build and trace **one tested artifact** through review, acceptance and deployment, obtaining rapid feedback rather than rebuilding unverified variants. Current [Buildkite artifact guidance](https://buildkite.com/docs/pipelines/configure/artifacts) tracks build and step scope plus hashes; [Jenkins Pipeline documentation](https://www.jenkins.io/doc/book/pipeline/) supports pipelines as code and staged approvals. Neither proves the book's old examples run unchanged. [S4][S5] A 2026 practitioner comparison still distinguishes this wide-ranging 2010 book from narrower pipeline guides. [S6]

Independent reviewer Bas Vodde reports strong test-data treatment and explicit pipeline tradeoffs, but criticizes repetition, brief management advice and occasional contradictory project-language. His review date is unspecified; a website footer is not an article date. [S3] Old virtualization and configuration specifics, old tool screenshots and approaches to secrets are not authoritative for 2026 infrastructure or software-supply-chain security. Compare with *Release It!* for failure-resistant production design and *The Site Reliability Workbook* for SLOs and incidents. This book is strongest for delivery process and testing gates, not those other specialties.

## Edition, errata and research limits

The researched **first edition** was published in 2010; no completed replacement edition was established. Publisher Updates supplies errata submission but not a full resolved correction ledger. No full-book reading, tool execution, comparative effectiveness study or availability condition is claimed.

## Evidence ledger

All accessed 2026-10-14, with source dates separately identified.

| ID | Exact document and inspected location | Publication/update |
| --- | --- | --- |
| [S1] | [InformIT](https://www.informit.com/store/continuous-delivery-reliable-software-releases-through-9780321770424), edition, authors, ebook ISBN, TOC Parts I–III, Updates | 2010-07-27; page update unspecified |
| [S2] | [Original chapter 5, page 3](https://www.informit.com/articles/article.aspx?p=1621865&seqNum=3), *Only Build Your Binaries Once*, *Deploy the Same Way*, *Smoke-Test Your Deployments* | 2010-09-07 |
| [S3] | [Bas Vodde's firsthand review](https://www.logigear.com/blogs/continuos-delivery-and-devops/Book-Review-Continuous-Delivery-by-Jez-Humble-and-David-Farely), strengths/criticisms | Date unknown; website spelling error not author's metadata |
| [S4] | [Buildkite artifacts](https://buildkite.com/docs/pipelines/configure/artifacts), integrity and upload/download | Live docs; update date unspecified |
| [S5] | [Jenkins Pipeline](https://www.jenkins.io/doc/book/pipeline/), Jenkinsfile/stages | Live docs; update date unspecified |
| [S6] | [Steve Fenton](https://octopus.com/devops/reading-list/continuous-delivery/), scope comparison | 2026-02-06 |
| [S7] | [OWASP Secrets Management](https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html), CI/CD sections 3.1–3.3 | Live guidance; update unspecified; inspected 2026-10-14 |

## Subsequent-run review — cycle 2026-10-14-12

**Passed**, reviewing the published record at `fc4e04d125275b9ca8880d61e453a36656a12ce2`. Reopened original chapter 5 and Bas Vodde's critical reading; neither popularity nor publication age determined the decision. [S2], [S3] OWASP's current CI/CD guidance makes the existing configuration caveat concrete: versioning ordinary configuration is not permission to commit plaintext credentials. [S7] The pipeline/testing classification remains appropriate. No full errata clearance, modern deployment execution or final collection audit is claimed.

## Next review

Passed later-run assessment with the limitations above. Inspect original configuration/data-migration chapters, printing-specific corrections and a representative current implementation. Preserve the distinction between reusable delivery principles and current secrets/provenance controls.
