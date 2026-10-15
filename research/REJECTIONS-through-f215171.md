# Rejections and corrective decisions

A rejected claim is not necessarily a rejected work. Candidates are separate from recommendations; acquisition status never determines eligibility. Work-level non-selections and any future removals are retained compactly in [UNSELECTED.md](UNSELECTED.md).

## Preserved historical decisions

[Decisions R001–R047 through commit 50c8a773](REJECTIONS-through-50c8a773.md) preserve the previous ledger byte-for-byte, including the overlapping commit's new corrections. The archive remains in the same directory, so its relative links keep working. This index bounds future rewrites without discarding history.

## Cycle 2026-10-14-10 reconciliation

| ID | Decision | Evidence / reason |
| --- | --- | --- |
| R048 | Correct the overbroad Git-default claim | [Official-manual recheck](sources/2026-10-14-10/022-concurrent-commit-and-git-defaults.md): SHA-1 and master remain documented upstream defaults, with configuration overrides and a planned later change. They are not universal hosting conventions. Updated [Pro Git](../books/chacon-straub-pro-git-2.md); existing pass retained, no extra approval. |
| R049 | Do not duplicate concurrently published works or approvals | The live [50c8a773 commit](https://github.com/floris3456/technical-ebooks-list/commit/50c8a773af139821e48680cd76015d4fa0f1dda5) already added Continuous Delivery and Release It! and reviewed two older works. Reuse existing canonical paths and preserve its source/index corrections. |
| R050 | Website breadth is not independent book evaluation | [25-site audit](sources/2026-10-14-10/README.md): technical manuals support relevance, not independent pedagogical appraisal. Distinct pages, domains and publisher ecosystems are separated. Earlier unrecorded failed browsing is explicitly unknown. |
| R051 | Persist IaC 3e as candidate, not a hidden recommendation | [Canonical candidate](../books/morris-infrastructure-as-code-3.md) implements prior decision R047. Author/publisher/employer evidence does not resolve independent third-edition evaluation. No acquisition-based filter. |
| R052 | Preserve negative technical findings | OPA's [dated example](sources/2026-10-14-10/005-workflow-findings.md), [retired SLSA reference](sources/2026-10-14-10/006-supply-chain.md), and [development-version / differing breaker semantics](sources/2026-10-14-10/010-resilience-assessment.md) are not current universal implementation instructions. |
| R053 | Keep remaining audit limits explicit | [Older Security Engineering errata rotation](sources/2026-10-14-10/018-current-relevance-and-open-corrections.md) and the original-prose/errata gaps in the existing Distributed Systems pass remain open. No full audit or new approval claimed. |

No works removed in that reconciliation. Its net catalog change was **one uncounted candidate**, plus a corrected existing recommendation and durable source indexes. The two new recommendations were already published by the overlapping commit. [Preserved checkpoint](STATE-through-fc4e04d.md) distinguishes this from total cycle progress.

## Cycle 2026-10-14-12

| ID | Decision | Concise reason / evidence |
| --- | --- | --- |
| R054 | Retain evaluated-but-unselected works explicitly | [UNSELECTED.md](UNSELECTED.md) separates deferred evidence, quality rejection and retirement; deletion or promotion must not erase the decision trail. Implements the user's retention rule. |
| R055 | Do not confuse Feathers publication and copyright | [Publisher verification](sources/2026-10-14-12/020-edition-decisions.md): 2004 publication, 2005 copyright, one first-edition work. |
| R056 | Do not treat a related advertised title as a completed new edition | Brutal Refactoring's inconsistent future metadata and missing completed-text/independent evidence warrant deferral, not a cancellation claim or availability rejection. [Exact check](sources/2026-10-14-12/020-edition-decisions.md). |
| R057 | Characterization and test doubles are not correctness guarantees | [Original review/adoption checks](sources/2026-10-14-12/016-verified-legacy-review-and-data-adoption.md) and [rotating Google chapter check](sources/2026-10-14-12/019-confirmed-corrections.md) retain behavior-versus-requirement and fidelity limits. |
| R058 | Do not call Tartu's 2025/26 course Fall 2026 | [Inspected reading schedule](sources/2026-10-14-12/016-verified-legacy-review-and-data-adoption.md): academic-year label, not the later outage banner, dates the adoption evidence. |
| R059 | Empty unconfirmed errata does not mean no errors | [Confirmed FoDE corrections](sources/2026-10-14-12/019-confirmed-corrections.md) include diagram/SQL errors with dated corrections; retained in the recommendation. |
| R060 | Ordinary configuration versioning does not authorize plaintext secrets in Git | [OWASP CI/CD recheck](sources/2026-10-14-12/013-focused-followups.md) qualifies older Continuous Delivery advice. Later-run pass is not blanket implementation approval. |
| R061 | Do not inflate novel-site or recommendation counts | [Cycle audit](sources/2026-10-14-12/README.md) excludes empty/redirect-only pages and repeated sites; a conservative related-ecosystem count still exceeds 20. New books remain pending later review; unselected works remain uncounted. |

No books were removed this cycle. Prior corrections remain historically preserved rather than silently rewritten into new claims.
