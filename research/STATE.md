# Research checkpoint

## Cycle 2026-10-14-04

Date **2026-10-14** (Europe/Amsterdam). Reviewed the live parent commit `ded3ed1422b6a73ac795da6c52693ebb084bc7df`, its diff, README, TAXONOMY, template, prior checkpoint, all three new pending records and older sampling (CLRS/OSTEP). No accessible competing unpublished work was assumed. Prior taxonomy remains at **7 groups/23 subjects**; findings do not yet justify a split.

## Actual work counts

| Metric | Distinct works |
| --- | ---: |
| Recommended (including awaiting later-run review) | **10** |
| Passed subsequent-run independent review | **8** |
| Pending later-run review | **2** |
| Research candidates, not counted | **1** |
| Retired/rejected works | **0** |
| Completed collection-wide final audit | **0 / 2,000** |

**17 topic appearances** represent ten unique recommended works, not seventeen recommendations. Counts use unique `work_id` across edition records, not translations, formats, indexes or candidate files. Review passed does **not** equal final-audit qualified. Every new recommendation gets reviewed in a following invocation against the *published SHA containing this checkpoint*. If later evidence fails, revise/demote/delete without preserving artificial totals.

## Previous-commit review — `ded3ed1422b6a73ac795da6c52693ebb084bc7df`

- [Anderson — Security Engineering 3e](../books/anderson-security-engineering-3.md): **pass**. Independently checked actual third-edition author PDF chapter 1 §1.2 and chapter 27, author's third-edition errata, third-edition expert review (Dietrich, 2021-05-31), Edinburgh 2026/27 exact-edition prerequisite reading, and July 2026 CIS/SAFECode context. Page-specific errata need further assessment; old cases are not present-day threat feeds.
- [Kurose/Ross — Computer Networking 9e](../books/kurose-ross-computer-networking-9.md): **pass**. Rechecked Pearson edition distinction (publication 2025/©2026), actual chapter-three author exercises, Rochester Fall 2026 exact 9e adoption, IETF QUIC/HTTP3 RFC 9000/9114. Exercise choices are not facts. Direct ninth-edition chapter prose and errata remain uninspected and are openly qualified.
- [Ousterhout — A Philosophy of Software Design 2e](../books/ousterhout-philosophy-of-software-design-2.md): **pass with explicit limits**. Stanford 2021 second-edition changes, independent Milanović **2024-03-14** detailed second-edition chapter analysis, 2026 practitioner notes and 2025 author interview support content/current value. The full official second-edition PDF excerpt again was not inspected due to retrieval limitations. Do **not** claim first-hand source reading or universally valid advice (esp. TDD and module sizing). Prioritize original extract at final audit. Edition-specific reviewer critique supplies substantive inspection corroboration.
- Rotating older sample: [CLRS 4](../books/cormen-introduction-to-algorithms-4.md) retains verified 2026 course use but preliminary JHU chapter-number discrepancy/printing errata; [OSTEP 1.10](../books/arpaci-dusseau-ostep-1-10.md) retains CFS-vs-EEVDF extractor/render conflict. No unsupported cleanup or review-status regression.

These three new passes record this already-published **parent** SHA. No review of a newly created record was self-approved.

## New researched works

- [Laura Kalbag — Accessibility for Everyone (2017)](../books/kalbag-accessibility-for-everyone-2017.md), **recommended, review pending**. Primary web HCI/inclusive design; secondary platform-specific development for substantive browser/HTML chapters. Inspected actual author-hosted chapters 1, 4, 5, 6; independent reviews from 2017; a substantive negative reader critique; authoritative W3C WCAG 2.2 (2024-12-12). The author's 2026 warning confirms dated vendor tools and no second edition; this is a conceptual introductory book, **not** a 2026 legal or ARIA implementation authority. Relevance is supported, not inferred from its age.
- [Robertson/Robertson, with Adrian Reed — Mastering the Requirements Process (4e, 2024)](../books/robertson-mastering-the-requirements-process-4.md), **recommended, review pending**. Primary requirements analysis; original publisher excerpt inspected (chapter 15, printed pp.167–170, neobank Figure 15.2 on p.168), detailed O'Reilly 45-chapter contents, critical 2025 independent firsthand fourth-edition comparison, 2026 requirements engineering research. The critic dislikes over-simplified methods, chopped chapter organization and dated AI chapter: this is a **qualified** practical recommendation.
- [Jorgensen/DeVries — Software Testing: A Craftsman's Approach (5e, 2021)](../books/jorgensen-devries-software-testing-5.md), **uncounted candidate**. Publisher bibliographic description and fifth-edition preface leads identified; search results for detailed independent reviews actually concerned **older editions**. Promote only after verifying the fifth-edition technical sample and independent evaluation/adoption. Not an availability rejection.

## Classification and data hygiene

Added two new primary subject indexes (HCI and requirements) plus **Platform-Specific Development** as an additional route to the accessibility book. The small pilot does not justify changing taxonomy labels; re-evaluate secondary assignment at next audit. Updated three review index badges and corrected the earlier **Software Engineering at Google** testing index's stale pending badge. Rebuilt the research rejection log table for consistent formatting and added new evidence decisions.

## Next cycle priorities

1. Inspect **this published commit**, independently reassess Kalbag original web chapters against current W3C techniques and Robertson fourth-edition printed sample (esp. author credits/critic's review); pass, revise or demote **only on the next invocation**, recording reviewed SHA.
2. Investigate independent **fifth-edition-specific** Jorgensen evaluation and actual exercises, then either promote or retain with reason. Avoid mixing 2013 fourth edition with 2021 fifth edition.
3. Rotate into underrepresented **DevOps/reliability, database fundamentals, formal verification, graphics and contemporary AI**, while preserving evidence depth; do not just fill numeric quotas.
4. Audit ongoing limitations: Ousterhout full primary second-edition excerpt; Kurose original 9e prose and errata; Anderson significant errata; OSTEP version/extraction conflict; CLRS course schedule/printing.
5. Run the **25–30 edition retrieval/classification pilot** before structural category changes. Check distinct intellectual work IDs, subject indexes, source credibility/date, and present-day relevance. **Availability is never a selection filter.**
6. On every publish, re-fetch `main`, reconcile overlap, use conditional non-force update and verify the new HEAD and file content. No cover-to-cover reading, executed exercises, exhaustive live-link scan, purchases, or false ISBN/format claims were made.

Source access dates in records reflect **2026-10-14**, not necessarily original publication/update dates. This checkpoint deliberately does not embed its own commit SHA.
