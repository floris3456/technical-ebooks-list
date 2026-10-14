# Rejections and corrective decisions

This log distinguishes rejected **claims or selection rules** from rejected **books**. Version control preserves removed material. No work has been formally rejected or deleted in cycles 2026-10-14-01 and 2026-10-14-02.

| ID | Date | Decision | Reason and evidence |
| --- | --- | --- | --- |
| R001 | 2026-10-14 | Remove availability as a promotion gate | The original template required availability verification. The user's explicit rule makes price, access, formats, and purchase links non-selection criteria; the template and README now reflect that. |
| R002 | 2026-10-14 | Do not transfer an old review to a new edition | [DDIA candidate](../books/kleppmann-riccomini-ddia-2.md), sources S1/S3: the independent critique is from 2024 and addresses first-edition chapter 9; second edition was published in 2026 and reorganized. |
| R003 | 2026-10-14 | Do not use snippets as inspected book evidence | [Crafting Interpreters candidate](../books/nystrom-crafting-interpreters-2021.md): current course references were inspected, but failed author-page retrievals were not replaced with search snippets. Candidate status is an evidence decision, not an availability rejection. |
| R004 | 2026-10-14 | Do not infer subject tags from isolated mentions | [CLRS record](../books/cormen-introduction-to-algorithms-4.md), S2: an ML chapter does not establish this broad algorithms text as a dedicated AI recommendation. |
| R005 | 2026-10-14 | Reject an unqualified OSTEP latest-version claim | [OSTEP record](../books/arpaci-dusseau-ostep-1-10.md), S1/S4: official metadata and the rendered chapter support 1.10; extracted text gave conflicting 1.20 information. Preserve the discrepancy instead of asserting a new complete edition. |
| R006 | 2026-10-14 | Reject blanket current-kernel equivalence | OSTEP S4/S6: a CFS teaching case is not a complete description of current Linux scheduling. Current kernel documentation supplies the necessary qualification. |
| R007 | 2026-10-14 | Do not accept every course chapter number as edition evidence | CLRS S2/S4: the preliminary course schedule has mismatched later chapter numbers. Keep the explicit adoption evidence while using the publisher's contents for fourth-edition navigation. |

| R008 | 2026-10-14 | Do not conflate DDIA editions | A first-edition 2024 technical critique cannot substantiate or invalidate the second edition. [DDIA](../books/kleppmann-riccomini-ddia-2.md) is now recommended using exact 2026 edition contents, Fall 2026 Waterloo adoption and a March 2026 second-edition review. |
| R009 | 2026-10-14 | Reject applying tutorial VM shortcut to production | [Crafting Interpreters](../books/nystrom-crafting-interpreters-2021.md) explicitly acknowledges a global VM instance as teaching convenience, unsuitable for some multitenant/embedded scenarios. Its scanner and VM concepts still warrant a recommendation. |
| R010 | 2026-10-14 | Do not universalize 2020 Google procedures | [Software Engineering at Google](../books/winters-manshreck-wright-software-engineering-at-google-2020.md) offers lasting review/testing principles, but company-specific tools and missing 2026 coding-agent coverage limit direct transplantation. |
| R011 | 2026-10-14 | Do not erase evidence caveats on review pass | [OSTEP](../books/arpaci-dusseau-ostep-1-10.md) retains source extraction/rendering discrepancy; [CLRS](../books/cormen-introduction-to-algorithms-4.md) keeps incomplete printing errata and preliminary-course chapter-number caveats. |

Insufficiently researched books remain candidates, not negative quality judgments. Future removals should record the work identifier, decision, exact evidence, and whether reconsideration is warranted. Never reject a book solely for age or difficulty obtaining it.
