---
work_id: morris-infrastructure-as-code
title: "Infrastructure as Code"
authors: ["Kief Morris"]
edition: "Third edition, March 2025"
publication_year: 2025
isbn_by_format: {}
primary_subject: devops-cloud-and-infrastructure
additional_subjects: []
concepts: [infrastructure-as-code, infrastructure-components, testing-infrastructure, delivery-pipelines, state-reconciliation]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: []
access: unknown
official_url: "https://www.oreilly.com/library/view/infrastructure-as-code/9781098150341/ch14.html"
last_verified: "2026-10-14"
status: candidate
review_status: pending
reviewed_commit: null
---

# Infrastructure as Code — Third edition (2025), uncounted candidate

## Decision and audience

**Keep as a research candidate, not a recommendation yet.** The edition and infrastructure-design focus are established, but independent **third-edition-specific** expert evaluation or documented educational adoption remains missing. This is an evidence gap, not an availability, price, age or format judgment. No copies were purchased or requested.

O'Reilly identifies Kief Morris, the third edition and March 2025. Its detailed contents and exposed chapter-14 introduction were inspected; the full chapter was not. The author explains that the work assumes infrastructure experience and emphasizes design choices rather than a beginner's tool walkthrough. The intermediate label is provisional. [S1], [S2]

## Verified scope and relevance questions

The author contrasts the third edition's infrastructure approaches with earlier editions. Publisher contents include component design, testing and delivery, governance and managing change. That supports a DevOps/cloud primary classification, but not a claim that those chapters' full technical prose was examined. The author's March 2025 interview discusses cohesive components and design tradeoffs; it is hosted by his employer and does **not** supply arm's-length evaluation. [S1]–[S3]

Current primary documentation offers concrete questions for assessment: OpenTofu distinguishes speculative from final plans; Pulumi separates mocked testing from testing deployed infrastructure; Flux describes desired-state reconciliation and drift. The relevance of these problems does not independently establish this edition's pedagogical quality. [S4]–[S6]

A useful caution arose in the OPA Terraform tutorial: its prerequisites still specify Terraform 0.12.6 and leave newer-version compatibility untested. Even an official page reached today may contain old executable instructions. Compare the candidate's examples against actual versioned references, not access dates. [S7]

## Missing evidence and comparison plan

Find an independent substantive review or explicit course adoption naming this edition, then inspect more original testing/component-design material. Recycled publisher descriptions, interviews with the author and reviews of 2016/2020 editions cannot fill that role. Compare its infrastructure lifecycle focus against *Continuous Delivery*'s application release path before asserting comparative strengths. Unknown ISBNs, file formats and access remain intentionally unfilled.

No exhaustive errata check, full-book reading or code execution occurred. No fourth edition was established by the inspected official sources; avoid claiming globally latest status without a later check.

## Evidence ledger

Accessed **2026-10-14**. All opening outcomes were immediately recorded in [the cycle source log](../research/sources/2026-10-14-10/README.md).

| ID | Exact source / inspected material | Date and limitation |
| --- | --- | --- |
| S1 | [O'Reilly 3e ch.14 preview](https://www.oreilly.com/library/view/infrastructure-as-code/9781098150341/ch14.html), bibliographic block, TOC, exposed opening | March 2025; not full chapter |
| S2 | [Author book site](https://infrastructure-as-code.com/book/), edition changes and intended scope | Update unspecified; author-associated |
| S3 | [Thoughtworks author interview](https://www.thoughtworks.com/insights/podcasts/technology-podcasts/infrastructure-as-code-in-2025), design-pattern focus and small components | 2025-03-20; employer/author, not independent review |
| S4 | [OpenTofu core workflow](https://opentofu.org/docs/intro/core-workflow/), team review, plan and apply | Live documentation; update unknown |
| S5 | [Pulumi testing](https://www.pulumi.com/docs/iac/guides/testing/), unit, property and integration tests | Update unknown |
| S6 | [Flux concepts](https://fluxcd.io/flux/concepts/), reconciliation and Kustomization | Update unknown |
| S7 | [OPA Terraform tutorial](https://www.openpolicyagent.org/docs/terraform), prerequisites and policy limitations | Terraform 0.12.6 example; current compatibility not asserted |

## Next review

Resolve the independent edition-specific assessment gap without treating additional vendor documentation as a substitute. Until then, **candidate remains excluded from all recommendation and target counts**.

[S1]: https://www.oreilly.com/library/view/infrastructure-as-code/9781098150341/ch14.html
[S2]: https://infrastructure-as-code.com/book/
[S3]: https://www.thoughtworks.com/insights/podcasts/technology-podcasts/infrastructure-as-code-in-2025
[S4]: https://opentofu.org/docs/intro/core-workflow/
[S5]: https://www.pulumi.com/docs/iac/guides/testing/
[S6]: https://fluxcd.io/flux/concepts/
[S7]: https://www.openpolicyagent.org/docs/terraform
