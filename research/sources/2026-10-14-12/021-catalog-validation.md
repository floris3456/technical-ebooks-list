# C12 catalog validation and review boundary

Starting snapshot: `fc4e04d125275b9ca8880d61e453a36656a12ce2`. Metadata from all 23 canonical book files was fetched through the authorized GitHub connector, alongside the complete tree, README, taxonomy, template, source registry and relevant topic pages. Canonical documents inspected substantively: the two pending recommendations and IaC candidate; older rotation: Software Engineering at Google plus its original chapter 13. Other header reads are not new substantive reviews.

## Local recount

A local Python check used transcribed canonical work IDs, primary/additional subjects and review states. Before changes: **22 unique recommendations, 20 passed, two pending**, plus one distinct candidate. Every primary/additional slug was checked against the 23-subject vocabulary; no duplicate additional subject or repeated primary was accepted.

After proposed decisions: **24 unique recommendations, 22 passed, two pending**, one canonical candidate. **35 subject appearances across 23 indexes**; 22 primary subjects. Platform-specific development remains secondary-only. The three retained deferred rows include the one canonical candidate and are not three extra canonical recommendations.

## Changed index membership

| Subject | Expected recommendations after update |
| --- | ---: |
| Data Engineering | 2 |
| Software Maintenance & Legacy Systems | 2 |
| Software Testing & Quality Assurance | 4 |
| DevOps, Cloud & Infrastructure | 1 |
| Software Architecture | 2 |
| Reliability & Observability | 2 |

New Feathers and Reis/Housley records must remain pending; CD and Release It review fields point to the already published starting snapshot. Candidate and deferred rows must never appear as approved index additions. Existing 20 passed records are retained, not counted as new approvals.

## Preservation and publication checks

The main branch was re-fetched at `b2381fa9f2277d8476faa37ed3d351f39da2a068` (tree `5f3bc9c458ae544a217d0647ba5a747824ee32b9`) after all external-source log commits. Staged trees use that base rather than constructing a replacement repository. Prior STATE and SOURCES are copied by their exact blob SHAs into same-directory archives; historical rejections are preserved. Relative links, source-ID/ledger mappings and changed-file scope must be checked on the prepared commit before a conditional non-force ref update. Re-fetch and reconcile any intervening head rather than overwrite it.

This is a structural/count validation, not proof of all source claims, full external-link availability, executable examples, complete errata clearance or empirical taxonomy optimality. Final remote verification is reported in the cycle response; this file does not contain its own circular commit hash.
