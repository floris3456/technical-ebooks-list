# Cycle 2026-10-14-10 — source audit

**25 distinct newly documented websites were substantively investigated**, compared with the cited-domain inventory of all 20 canonical records, README, taxonomy and research ledgers at `b02eb3227d76c32381edbed90862b0b2b8d69876`. These are websites, not 25 pages on one website. Counting PragProg and its linked Devtalk community as one publisher ecosystem still leaves **24**, above the required 20.

Each research retrieval batch was recorded in Git before the next batch, including failed fetches and discovery-only results. Files 019–020 and catalog commit `50c8a773af139821e48680cd76015d4fa0f1dda5` appeared at publication rechecks and were inspected/preserved. Logs 021–022 document reconciliation; repeat domains add zero novelty credits. All access dates are **2026-10-14**; dates of books, reviews, documents and revisions remain separately recorded.

## Novelty definition and limits

The [domain baseline](../../SOURCES.md) was checked against the pinned records. No complete log of earlier **unrecorded failed browsing** existed, so this is verified novelty against persisted evidence, not a claim about inaccessible previous execution histories. Author/employer relationships are disclosed. Different `www`, `docs` or `media` hosts on one site count once. A retired document can be a useful inspected source without being current normative guidance.

| # | Website and exact representative source | Visit IDs | What was actually investigated |
| --- | --- | --- | --- |
| 1 | [continuousdelivery.com](https://continuousdelivery.com/) | C10-S01 | Author delivery principles |
| 2 | [logigear.com](https://www.logigear.com/blogs/continuos-delivery-and-devops/Book-Review-Continuous-Delivery-by-Jez-Humble-and-David-Farely) | C10-S02 | Firsthand critical book review |
| 3 | [infrastructure-as-code.com](https://infrastructure-as-code.com/book/) | C10-S03/S06 | Author edition/scope |
| 4 | [opentofu.org](https://opentofu.org/docs/intro/core-workflow/) | C10-S04 | Plan/apply workflow |
| 5 | [jenkins.io](https://www.jenkins.io/doc/book/pipeline/) | C10-S05 | Versioned pipelines |
| 6 | [pulumi.com](https://www.pulumi.com/docs/iac/guides/testing/) | C10-S08 | Mocked vs deployed testing |
| 7 | [fluxcd.io](https://fluxcd.io/flux/concepts/) | C10-S09 | Reconciliation and drift |
| 8 | [tekton.dev](https://tekton.dev/docs/pipelines/pipelines/) | C10-S10 | Dependency/order semantics |
| 9 | [openpolicyagent.org](https://www.openpolicyagent.org/docs/terraform) | C10-S11 | Policy limits; dated example |
| 10 | [slsa.dev](https://slsa.dev/spec/v1.1/levels) | C10-S12 | Retired version identified; current link failed |
| 11 | [sigstore.dev](https://docs.sigstore.dev/cosign/verifying/verify/) | C10-S13 | Identity/issuer/digest verification |
| 12 | [reproducible-builds.org](https://reproducible-builds.org/docs/definition/) | C10-S14 | Specified reproducibility conditions |
| 13 | [in-toto.io](https://in-toto.io/) | C10-S15 | Supply-chain actors/steps |
| 14 | [pragprog.com](https://pragprog.com/titles/mnee2/release-it-second-edition/) | C10-S16/S27 | Publisher and original rendered excerpt |
| 15 | [thoughtworks.com](https://www.thoughtworks.com/insights/podcasts/technology-podcasts/infrastructure-as-code-in-2025) | C10-S17 | Employer/author interview, not independent |
| 16 | [augmentedmind.de](https://www.augmentedmind.de/2023/04/30/release-it-book-summary/) | C10-S18 | Explicit second-edition critical reading |
| 17 | [peterdaugaardrasmussen.com](https://peterdaugaardrasmussen.com/2018/09/18/book-review-release-it-by-michael-t-nygard/) | C10-S19 | Firsthand second-edition assessment |
| 18 | [failsafe.dev](https://failsafe.dev/circuit-breaker/) | C10-S20 | Breaker states and thresholds |
| 19 | [envoyproxy.io](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/upstream/circuit_breaking) | C10-S21 | Resource limits; development version |
| 20 | [istio.io](https://istio.io/latest/docs/tasks/traffic-management/circuit-breaking/) | C10-S22 | Pool limits vs outlier detection |
| 21 | [dapr.io](https://docs.dapr.io/operations/resiliency/policies/circuit-breakers/) | C10-S23 | Open timeout / half-open limits |
| 22 | [buildkite.com](https://buildkite.com/docs/pipelines/configure/artifacts) | C10-S24 | Artifacts and build-origin metadata |
| 23 | [devtalk.com](https://devtalk.com/t/release-it-second-edition-typo-in-client-connection-diagram-page-174/214386) | C10-S36/S39 | Unadjudicated reader correction report |
| 24 | [octopus.com](https://octopus.com/devops/reading-list/continuous-delivery/) | C10-S37 | Dated practitioner reading selection |
| 25 | [matthewskelton.com](https://matthewskelton.com/blog/5-reasons-why-cicdnbspis-a-vital-enabler-for-fast-flow-of-value) | C10-S38 | Expert essay; possible republication caveat |

## Returning sites and unsuccessful work

InformIT, Git, ProGit3, distributed-systems.net, O'Reilly, Youngstown State, Cambridge and Linköping were revisited for depth and review, **not** counted as new websites. Failed redirects, the failed SLSA v1.2 opening, navigation-only initial responses and search-only leads are preserved. An opening became substantive evidence only after its relevant body was read. No unauthorized copy was fetched or linked; book-source retrieval limits did not become selection filters.

The logs assign C10-S01–C10-S39 to identified source documents, with other attempts and search results distinguished. A visit ID or source count is not a quality score. Current vendor documentation validates topic relevance, not independent book evaluation. New recommendations still need a later-run review.

## Chronological records

- [000-start.md](000-start.md)
- [001-discovery.md](001-discovery.md)
- [002-delivery-infrastructure.md](002-delivery-infrastructure.md)
- [003-workflows.md](003-workflows.md)
- [004-modern-delivery-open.md](004-modern-delivery-open.md)
- [005-workflow-findings.md](005-workflow-findings.md)
- [006-supply-chain.md](006-supply-chain.md)
- [007-discovery-and-version-checks.md](007-discovery-and-version-checks.md)
- [008-book-discovery.md](008-book-discovery.md)
- [009-production-design-openings.md](009-production-design-openings.md)
- [010-resilience-assessment.md](010-resilience-assessment.md)
- [011-delivery-original-discovery.md](011-delivery-original-discovery.md)
- [012-original-delivery-and-sample.md](012-original-delivery-and-sample.md)
- [013-rendered-original-and-artifacts.md](013-rendered-original-and-artifacts.md)
- [014-prior-book-review-openings.md](014-prior-book-review-openings.md)
- [015-edition-checks.md](015-edition-checks.md)
- [016-git-review-evidence.md](016-git-review-evidence.md)
- [017-edition-search-and-errata-leads.md](017-edition-search-and-errata-leads.md)
- [018-current-relevance-and-open-corrections.md](018-current-relevance-and-open-corrections.md)
- [019-verified-book-excerpts.md](019-verified-book-excerpts.md)
- [020-review-and-modern-pipeline-checks.md](020-review-and-modern-pipeline-checks.md)
- [021-domain-and-metadata-audit.md](021-domain-and-metadata-audit.md)
- [022-concurrent-commit-and-git-defaults.md](022-concurrent-commit-and-git-defaults.md)

## Research outcomes

Two recommendations: *Continuous Delivery* (2010) and *Release It!* (second edition, 2018). One uncounted candidate: *Infrastructure as Code* (third edition, 2025), missing independent edition-specific assessment. The overlapping catalog commit already added the two recommendations and passed Pro Git and Distributed Systems. Those published passes are preserved with their limitations, including the unresolved Distributed Systems original-prose/errata check. A repeated Git-manual check corrects overbroad default-name wording. No duplicate Continuous Delivery record or additional approval is created. An older Security Engineering errata rotation retained its existing caveats.

See [STATE.md](../../STATE.md) for counts, decisions and resumable gaps. No entire-book reading, executable tutorial testing, exhaustive external-link crawler or final audit is implied.
