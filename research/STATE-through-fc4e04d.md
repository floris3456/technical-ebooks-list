# Research checkpoint

## Cycle 2026-10-14-10 — reconciled publication

Starting catalog reviewed: `b02eb3227d76c32381edbed90862b0b2b8d69876`, tree `9e201288ea51b90ab20ed24dcffd7e6187029bc8`. Read README, TAXONOMY, book template, STATE, REJECTIONS, the latest catalog diff and all 20 baseline canonical records for metadata/source-domain verification. Substantive review was targeted, not claimed for every old book.

**Concurrency:** while this research was being consolidated, `50c8a773af139821e48680cd76015d4fa0f1dda5` published the same Continuous Delivery and Release It! works, two prior-work approvals and additional stale-index corrections. Its diff and saved source logs were inspected. Preserve that commit, its canonical `books/humble-farley-continuous-delivery-1.md` path and corrections; do not create the separately prepared `-2010` record or inflate counts. Source-only commits are not separate research cycles or new approvals. Logs 021–022 explain how the earlier proposed 19-pass snapshot was superseded.

## Verified catalog after reconciliation

| Measure | Distinct works |
| --- | ---: |
| Recommended | **22** |
| Passed subsequent-run review | **20** |
| Pending subsequent-run review | **2** |
| Canonical candidates, uncounted | **1** |
| Completed final collection audit | **0 / 2,000** |

**32 subject-index appearances represent 22 works**, across 23 populated subjects. Twenty subjects have primary coverage; platform-specific development, maintenance/legacy systems and data engineering remain secondary-only coverage. Recompute from current canonical records on each run.

Net changes in this final reconciliation: **0 additional recommendations beyond the overlapping commit, 1 new candidate, 1 existing book correction, 0 removals**. Combined cycle outcome since the starting catalog: two recommendations added, two prior recommendations passed review, one candidate persisted. Do not credit the same work or review twice.

## Decisions and evidence

- [Continuous Delivery, first edition](../books/humble-farley-continuous-delivery-1.md) and [Release It!, second edition](../books/nygard-release-it-2.md): already published in 50c8a773, both remain **pending later-run review**. Research included original publisher text/rendered excerpt, independent firsthand criticism and current pipeline/resilience documentation. Retain their dated-tool, security and errata limitations.
- [Pro Git](../books/chacon-straub-pro-git-2.md): preserve its pass reviewing b02eb322. Original §10.2, the YSU Fall 2026 assignments and draft-edition boundary support it. Correct one overstatement from the overlapping review: the official Git init manual still specifies SHA-1 and master as defaults, with configuration overrides and a planned future change. Hosting conventions differ. No new approval is counted.
- [Distributed Systems](../books/van-steen-tanenbaum-distributed-systems-4.md): preserve the overlapping pass with its explicit depth limitation. Author revision evidence and exact-edition current course maps/adoption support the qualified recommendation; direct full textbook prose and complete corrections remain final-audit priorities. Author 4.03x is newer small-correction material than print-corresponding 4.03, not another work. No email/CAPTCHA was submitted or bypassed. The earlier prepared pending decision is superseded after inspecting the published qualified assessment, not by acquisition status.
- [Infrastructure as Code, third edition](../books/morris-infrastructure-as-code-3.md): **candidate**, not recommended. Author/publisher and employer-interview evidence plus primary technology references establish scope and relevance questions; independent third-edition appraisal or explicit educational adoption is still missing.
- Older rotation: [Security Engineering](../books/anderson-security-engineering-3.md) official third-edition errata were reexamined and existing caveats retained. Metadata scans of other records are not new full book reviews.

## Exact sources and novelty

[Source registry](SOURCES.md) and [cycle audit](sources/2026-10-14-10/README.md) identify **25 newly documented websites** versus the complete 20-record persisted baseline and background/research ledgers. Combining PragProg and its linked Devtalk community into one publisher ecosystem still leaves 24. Known-site revisits, screenshots and repeated pages contribute zero novelty credits.

Every retrieval batch was saved before the next research batch, including failures, initial navigation-only responses and discovery-only search results. Logs 019–020 were also inspected and preserved when discovered on the live branch; 021–022 document reconciliation and the additional returning-site check. Earlier unrecorded failed browsing cannot be reconstructed: novelty is claimed against available persisted evidence, not unknowable execution histories. Source count never replaces independent book assessment.

## Taxonomy and preserved work

Retain all seven navigation groups and 23 subjects. DevOps now has a primary recommendation. Preserve the overlapping commit's fixes to stale DDIA, Crafting Interpreters and Software Engineering at Google topic statuses. No speculative category split was justified. Candidate records stay out of recommendation indexes.

[Historical checkpoint through 50c8a773](STATE-through-50c8a773.md) and [decisions R001–R047](REJECTIONS-through-50c8a773.md) are preserved as unchanged same-directory Git blob copies, keeping their relative links valid. [REJECTIONS.md](REJECTIONS.md) adds R048–R053 without overwriting concurrent decisions.

## Next priorities

1. Review this reconciliation and the 50c8a773 additions first, including the two original-book samples, criticism, exact source roles, Git default correction and remaining Distributed Systems depth gap. Only a genuinely later run may approve the two new recommendations.
2. Resolve independent **third-edition** IaC evaluation/adoption; inspect more original testing/component-design material. Author/employer repetition is not independence. Reuse logged exact leads.
3. Expand primary coverage in data engineering, platform-specific development and maintenance/legacy systems; use at least 20 genuinely new websites while revisiting known sources for depth. Do not pad either source or recommendation counts.
4. Preserve older gaps: 2026 Site Reliability Engineering 2e still needs independent edition-specific evidence; Logical Foundations v7.1 needs comparison with v7.0 under the same work ID; OSTEP retains the 1.10/1.20 extraction/rendering conflict; CLRS printing-specific errata and other recorded original-prose gaps remain for staged final audit.
5. Logged but uninspected discovery leads include a 2025 industrial study of continuous engineering constraints and specialized cloud anti-pattern reviews. Their snippets are not evidence or recommendations.

## Validation / publication limits

Validated metadata, stable IDs, controlled subject values, source-reference identifiers, relative links and counts for the reconciled changes against observed canonical records. No full external-link crawler, executable tutorial test suite, whole-book reading, exhaustive errata review or empirical taxonomy test was performed. Availability never became an eligibility gate. The publication process must re-fetch main, preserve intervening work and use a conditional non-force update; the final chat response reports the verified commit rather than embedding a circular self-hash here.
