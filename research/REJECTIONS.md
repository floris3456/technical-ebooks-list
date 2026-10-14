# Rejections and corrective decisions

A rejected claim is not necessarily a rejected work. Candidates are separate from recommendations; acquisition status never determines eligibility.

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

No works removed in this reconciliation. Its net catalog change is **one uncounted candidate**, plus a corrected existing recommendation and durable source indexes. The two new recommendations were already published by the overlapping commit. [STATE.md](STATE.md) distinguishes this from total cycle progress.
