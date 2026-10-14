# Research checkpoint

## Cycle 2026-10-14-05

**Date:** 2026-10-14 (Europe/Amsterdam). Reviewed live parent commit `5aaf861920311aeb9b335600078847a93934ae18`, parent tree `60aa9fc2b3460cfb7b920e975868d7c4590f9bc2`, latest diff, README, taxonomy, book template, all newly pending records, prior checkpoint and rotating older material. Only observable GitHub files were reviewed; unpublished work from other runs was not assumed. No branch update is implied until GitHub verification.

## Actual collection counts

| Metric | Unique works |
| --- | ---: |
| Recommended after initial research | **12** |
| Passed subsequent-run independent review | **10** |
| Recommended, pending next-run review | **2** |
| Uncounted candidate records | **0** |
| Retired or deleted works | **0** |
| Completed collection-wide final audit | **0 / 2,000** |

**19 appearances across 17 populated subject indexes = 12 intellectual works**, counted by `work_id`; one book can appear in more than one topic without increasing the count. Editions, translations, file formats and copies cannot inflate progress. Review `passed` is not final-audit qualification. Recompute from canonical records and indexes each cycle instead of trusting prose counts.

## Independent review of previous published commit

- [*Accessibility for Everyone*, Laura Kalbag (original 2017)](../books/kalbag-accessibility-for-everyone-2017.md): **passed with scope caveats**. Read original [author chapter 5 HTML](https://accessibilityforeveryone.site/accessibility-and-html/) on explicit labels and keyboard interaction plus [chapter 6 testing](https://accessibilityforeveryone.site/evaluating-and-testing/), then cross-checked [W3C labels](https://www.w3.org/WAI/tutorials/forms/labels/) and [WCAG 2.2 keyboard G202](https://www.w3.org/WAI/WCAG22/Techniques/general/G202). Principles remain current; 2017 tools, legal examples and implied HTML sufficiency do not. HCI primary/platform development secondary retained. Original independent 2017 reviews support the original, not a nonexistent second edition.
- [*Mastering the Requirements Process*, Robertson/Robertson with Adrian Reed (4e, 2024)](../books/robertson-mastering-the-requirements-process-4.md): **passed, introductory-to-intermediate qualification**. Checked [Pearson 4e chapter 15 original](https://www.pearson.de/media/muster/ext/9780137969579.pdf#page=5), printed pp.167–170 and Figure 15.2, specifically where a prototype is insufficient as mission-critical specification. Independently read [Alejandro Teruel's dated 2025-06-20 firsthand comparison](https://www.goodreads.com/en/book/show/802028.Mastering_the_Requirements_Process) of editions 2 and 4; his criticisms (AI chapter, examples, fragmented organization) remain disclosed. Goodreads's generic 1999 book metadata does **not** describe the 4e review; current [IREB elicitation guidance](https://cpre.ireb.org/en/concept/requirements-elicitation) corroborates present-day requirements practice, not every proprietary framework technique.
- Rotating older sample: [*Software Engineering at Google* (2020)](../books/winters-manshreck-wright-software-engineering-at-google-2020.md) remains passed; its Abseil testing/test-double chapters substantiate additional testing classification while historical Google policies must not be treated as unchanged 2026 tooling. No unsupported status regression.
- Both newly approved records explicitly identify the **previously published** review target `5aaf861920311aeb9b335600078847a93934ae18`. Newly created/promoted records below remain pending; no self-approval.

## This cycle's research and decisions

- [*Software Testing: A Craftsman's Approach* (Jorgensen/DeVries, fifth edition 2021)](../books/jorgensen-devries-software-testing-5.md): **promoted from uncounted candidate to recommendation, review pending**. Evidence: exact author [5e homepage](https://www.softwaretestcraft.com/), [chapter-by-chapter technical outline](https://www.softwaretestcraft.com/outline), [comparison exercises](https://www.softwaretestcraft.com/spreadsheet-exercises); explicit independent [Kansas professor 2022 fifth-edition listing/appraisal](https://people.eecs.ku.edu/~saiedian/Teaching/814/); current [ISTQB CTFL v4.0.1 §4.2, 2024-09-15](https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf#page=40). Professor labels ch8 “Path Testing”, whereas 5e author outline names “Code-Based Testing” including basis paths; author outline is navigation authority. Full 5e book prose and corrections remain to inspect. Reviews of older editions were not misattributed.
- [*Physically Based Rendering: From Theory to Implementation* (Pharr/Jakob/Humphreys, 4e 2023)](../books/pharr-jakob-humphreys-physically-based-rendering-4.md): **new recommendation, review pending**. Inspected substantial author 4e actual [§13.4 path tracing/MIS](https://pbr-book.org/4ed/Light_Transport_I_Surface_Reflection/A_Better_Path_Tracer), [§7.3 BVHs](https://pbr-book.org/4ed/Primitives_and_Intersection_Acceleration/Bounding_Volume_Hierarchies), [§15.1 GPU mapping](https://pbr-book.org/4ed/Wavefront_Rendering_on_GPUs/Mapping_Path_Tracing_to_the_GPU) and [contents](https://pbr-book.org/4ed/contents); exact-edition [Texas A&M Spring 2026 textbook recommendation and chapter schedule](https://people.engr.tamu.edu/nimak/Courses/CSCE641-CompGraph/Spring2026/index.html), 2023 official author/publisher edition, and [4e errata](https://pbrt.org/errata-4ed). Advanced mathematical/light-transport reference, not a universal 2026 real-time engine manual. Original code was inspected but not executed.
- **Uncounted prospective research lead:** O'Reilly [*Site Reliability Engineering*, second edition (2026)](https://www.oreilly.com/library/view/site-reliability-engineering/9798341607675/) and [Google Cloud announcement (2026-10-12)](https://cloud.google.com/blog/products/devops-sre/sre-book-second-edition/). Avoid assuming the original 2016 edition is newest or less valuable by age alone. Inspected substantial **second-edition** technical material and independent 2e expert assessment/adoption are still needed before recommending; availability is irrelevant.

## Changes, source discipline and next priorities

Kept all **7 groups / 23 subject slugs** because a twelve-work sample is inadequate to substantiate category splits. Added graphics primary index and testing primary record, updated Kalbag/Robertson secondary or primary index review badges, corrected bibliographic overreach and source mismatch in [REJECTIONS.md](REJECTIONS.md) (R022–R025). No book deletions. Link all topic entries to canonical records rather than copying prose. All newly examined sources accessed **2026-10-14**; older publication dates or unknown web revisions are explicitly distinct.

1. Review **this new published commit** on next invocation, notably Jorgensen **actual original fifth-edition prose** and Kansas chapter mismatch, and PBRT §13.4/§15.1 and 2026 course use/errata. Pass, revise or demote using the new **published** SHA, never self-approve.
2. Deep research SRE **second edition (2026)** using original source material and independent edition-specific expertise, then diversify to database fundamentals, formal verification, reliability and/or AI. Neither publisher praise nor 2016 edition reviews alone substantiate 2e.
3. Continue toward **25–30 representative editions** for subject-boundary and discovery tests (architecture vs design, testing vs performance, graphics vs mathematical topics) before taxonomy surgery.
4. Return to older unresolved gaps: Ousterhout primary 2e excerpt, Kurose 9e prose/errata, Anderson significant errata, OSTEP rendered 1.10 vs extracted 1.20/CFS ambiguity, CLRS edition-specific course numbering and printing errata, Kalbag old law, Robertson methodology depth.
5. Before every publication re-fetch `main`, reconcile changed HEAD, conditionally advance without force, and verify remote files, source locators and unique IDs. No cover-to-cover reading, all-link crawler, executed exercises, ebook purchases or full collection audit are claimed. **Price, format, paywalls, print status, region and publication date remain non-selection criteria; present-day technical relevance is mandatory.**

This checkpoint intentionally does not embed a circular hash of its own commit.
