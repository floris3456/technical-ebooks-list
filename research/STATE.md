# Research checkpoint

## Cycle 2026-10-14-03

Date: **2026-10-14**, Europe/Amsterdam. Reviewed the published parent commit `c1251db102898b3acc3c8ffec259153ae2dc0711`, all five prior book records, latest commit diff, README, taxonomy, template, indexes and research logs. Independently rechecked author primary sources, course adoption and expert reviews. No other run's unpublished work was visible.

## Actual counts (unique work_id, not editions or index appearances)

| Measure | Works |
| --- | ---: |
| Research-backed recommendations | **8** |
| Passed subsequent-run review | **5** |
| New recommendations pending later-run review | **3** |
| Uncounted candidate files | **0** |
| Retired/removed works | **0** |
| Final collection-wide audit completed | **0 / 2,000** |

Passing a subsequent-run review is **not** the collection-wide final audit. All entries and topic pages remain mutable; quality outranks count.

## Review of previous commit `c1251db102898b3acc3c8ffec259153ae2dc0711`

- **DDIA second edition: passed.** O'Reilly chapter 1/6 actual introductions, Waterloo **Fall 2026 exact-second-edition** chapter assignments and the March 30, 2026 second-edition independent review establish this edition's content and present-day use. PostgreSQL 18 supports continuing relevance of transactions, not a full correctness guarantee. A 2024 first-edition critique is not misapplied. Architectural and three substantial secondary subjects remain provisional until retrieval-pilot testing.
- **Crafting Interpreters: passed.** Author's GitHub revision `4a840f70f69c6ddd17cfef4f6964f8e1bcd8c3d4` actually contains the introduction, scanning and VM manuscripts, including the caveat about the simplistic global VM. PSU Winter 2026 assigned chapters 2 and 15; USF's additional reference is not a Rust-language teaching claim.
- **Software Engineering at Google: passed.** Abseil chapters 11 and 13, Cornell **Spring 2026 assigned book readings**, February 2026 independent engineering analysis and a September 2025 critical review corroborate lasting collaboration, testing and maintenance topics. Google-specific tooling and 2020 procedures must not be universalized; a previously recorded 2024 reviewer link failed on reinspection.
- **OSTEP and CLRS: prior passes retained.** Rotating audit corrected stale “awaits review” text without resetting a substantive pass or claiming their unresolved chapter-version and printing/syllabus discrepancies are fixed.

The three passes record the **already-published parent SHA** in their respective `reviewed_commit` fields. The three new works below must receive a later-run review of **the commit containing this checkpoint**, not self-approval now.

## Three researched additions, later-run review pending

| Work | Substantive inspected evidence | Main residual limitation |
| --- | --- | --- |
| [Anderson, Security Engineering, 3rd (2020)](../books/anderson-security-engineering-3.md) | Wiley exact electronic ISBN; author actual chapters 1/2/27 and official errata; Sven Dietrich's IEEE expert review; Edinburgh 2026/27 exact-edition prerequisite reading; CIS/SAFECode secure design guidance from July 2026 | Old case studies do not define current regulations, exploits or AI/supply-chain risks; selected chapter/errata review only |
| [Kurose/Ross, Computer Networking, 9th (2025/©2026)](../books/kurose-ross-computer-networking-9.md) | Pearson exact edition, publisher chapters and electronic ISBN; author actual §3.4 and §3.8 protocol exercises; Rochester Fall 2026 exact-edition primary course; GWU 2026 course; IETF QUIC/HTTP3 standards | Companion exercises are not validated solutions or full book prose; edition errata remain unverified |
| [Ousterhout, A Philosophy of Software Design, 2nd (2021)](../books/ousterhout-philosophy-of-software-design-2.md) | Author's second-edition changes; explicit second-edition March 2024 critical analysis; Jan 2026 chapter notes; Apr 2025 expert interview on deep modules and AI-assisted development | Author's actual large second-edition excerpt failed retrieval; current recommendation transparently rests on detailed first-hand readers and author notes, **priority re-review** |

There are **8 distinct works**, **14 subject-index appearances**, **23 controlled subjects** in **7 groups**. The dataset is too small to justify splitting categories before the promised 25–30-edition validation pilot. Three new primary indexes now serve security, networking and software component design.

## Next priorities

1. Independently review the three new recommendations against this published SHA. Prioritize **reading Ousterhout's primary chapter extract** and demote if the evidence falls short; inspect Anderson's third-edition page-specific errata and Kurose/Ross original ninth-edition prose if possible. Check precise source dates, technical currency, duplicates, and every subject/index link.
2. Broaden toward **software testing, requirements, accessibility/HCI, data engineering**, which lack dedicated recommendations. Do not simply repeat foundations. Unvetted leads from courses/research include Siek's *Essentials of Compilation*, Peterson/Davie's *Computer Networks: A Systems Approach*, and Kalbag's *Accessibility for Everyone*.
3. Continue rotating older review audits: OSTEP scheduler PDF renders 1.10/CFS while another extraction gave 1.20/EEVDF; CLRS's fourth-edition table differs from an explicitly preliminary JHU course schedule. Errata remain incomplete.
4. Finish the 25–30-edition classification/findability pilot before renaming/splitting controlled subjects. Keep independent metadata separate. Candidate and retired records never count. Count **works**, not editions/translations/formats or index references.
5. Preserve checkpoint and decisions, validate metadata/source links, self-review diff, and publish only from a **fresh confirmed `main` head** via a conditional **non-force** update.

No cover-to-cover book readings, completed book exercises, complete live-source crawler, conclusive errata audit, availability/access filtering, purchases or unauthorized ebook copies are claimed. Source access date 2026-10-14 is not automatically a source publication date. The commit SHA of this checkpoint is deliberately not embedded inside itself.
