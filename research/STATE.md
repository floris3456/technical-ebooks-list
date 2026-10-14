# Research checkpoint

## Cycle 2026-10-14-02

Date: **2026-10-14** (Europe/Amsterdam). Reviewed published parent commit `66ba2abdc241a80f999bd7e58ad4ca5853ffc487`, all four book records, the latest commit's changed files, taxonomy, template, existing topic indexes and both research logs. No accessible unfinished data beyond those files; no claim of reading another run's live work.

## Distinct-work counts

| Measure | Count |
| --- | ---: |
| Recommended, research-backed | **5** |
| Passed subsequent-run review | **2** |
| Pending subsequent-run review | **3** |
| Uncounted candidates | **0** |
| Retired/removed works | **0** |
| Final-audit-qualified works | **0 / 2,000** |

Count stable unique `work_id` among `status: recommended`, never editions, translations, formats or index appearances. A review pass is not the eventual staged final audit. The 7 browsing groups and 23 subject slugs remain provisional.

## Reviewed and newly substantiated work

| Work | Decision | Evidence and unresolved check |
| --- | --- | --- |
| [OSTEP](../books/arpaci-dusseau-ostep-1-10.md) | **Passed** review of parent commit | Official 1.10 and UCSD Fall 2026 adoption corroborated; rendered chapter 9 shows 1.10/CFS but extraction said 1.20/EEVDF. Keep documentation caveat; errata audit incomplete. |
| [Introduction to Algorithms](../books/cormen-introduction-to-algorithms-4.md) | **Passed** review of parent commit | MIT Press selected fourth-edition binary-search solutions inspected; JHU Fall 2026 edition adoption verified; inconsistent preliminary course chapter numbering retained as caution; errata not fully enumerated. |
| [DDIA second edition](../books/kleppmann-riccomini-ddia-2.md) | **Promoted** from candidate; pending new review | O'Reilly February 2026 exact edition, chapter introductions, Fall 2026 Waterloo exact-edition assignments, March 2026 independent review, official PostgreSQL transaction model. First-edition criticism not transferred. |
| [Crafting Interpreters](../books/nystrom-crafting-interpreters-2021.md) | **Promoted** from candidate; pending new review | Author's actual Markdown introduction/scanner/VM chapters and implementations inspected via original repo; PSU Winter 2026 **assigned** chapters 2 and 15; USF 2026 reference. No Rust tag. |
| [Software Engineering at Google](../books/winters-manshreck-wright-software-engineering-at-google-2020.md) | **Added** recommended, pending new review | O'Reilly/Abseil official 2020 edition, substantive testing/test-double chapters, independent 2024 reader analysis, official Google review guidance. Context-specific and 2026 agent omissions disclosed. |

Review `reviewed_commit` in the **two passed records** identifies `66ba2abdc241a80f999bd7e58ad4ca5853ffc487`. Only a *later* invocation may review the other three against the **published SHA of this cycle**. Material changes reset a pass.

## Reasoned taxonomy decisions

Keep 23 subjects pending the 25–30-edition pilot. DDIA uses architecture primary plus database, data engineering and distributed systems, since its chapters sustain all four areas. OSTEP's concurrency index is secondary; Crafting Interpreters belongs to compiler theory despite its project style; Google's collaboration book has meaningful testing and maintenance coverage. Five works are inadequate to justify splitting or renaming categories. Cross-index links are not duplicate records.

Availability is **not a filter** and no work was screened by price, access, region or file format. Older content is accepted only with verified present-day usefulness; the 2020 Google work is assessed using later independent critique and public engineering guidance without claiming unchanged internal practices.

## Next-run priorities

1. **Independently review the three pending recommendations** against the exact new commit; check original source links, dated evidence, content locators and material limitations. Pay particular attention to DDIA secondary subject breadth, author GitHub revision pin in Crafting Interpreters, and Google chapter/maintenance coverage. Mark pass or revert to candidate where required.
2. Run a small rotating audit of older passes: OSTEP PDF rendering/text-extraction conflict and Linux EEVDF caveat; CLRS printing-specific errata and JHU preliminary schedule. Do not claim issues resolved by inability to read them.
3. Research underrepresented **security, testing, networking, requirements and accessibility** works, with substantial contents, independent critical assessment or documented 2026 adoption, exact edition and current applicability. Leads (not endorsements): *Essentials of Compilation*, *Algorithm Design*, *Computer Systems: A Programmer's Perspective*.
4. Validate all new/revised Markdown metadata, source identifiers, indexes and unique work IDs against the actual branch head. Complete the 25–30-edition classification pilot before structural taxonomy changes; eventually final-audit 2,000 works.

## Publication and limitations

Publish only against the freshly confirmed `main` head using a conditional non-force update. Source access date **2026-10-14** is not a source publication date. No full-book reading, completed exercises, exhaustive errata inspection, real-user taxonomy experiment, external purchase or unauthorized book-copy storage is claimed. The records hold exact source URLs, locations and date distinctions. Commit SHA cannot be embedded here without a circular self-reference.
