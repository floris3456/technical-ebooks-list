# Research checkpoint

## Cycle 2026-10-14-08

**Reviewed starting `main` SHA:** `33f4e80a5dfd28a23b6b4b38732bfeffe46aa763`. Examined live README, TAXONOMY, BOOK_TEMPLATE, prior STATE/REJECTIONS, latest commit diff, both pending new books, related indexes and rotating older passed DDIA. Live Git tree/front matter confirmed **16 unique recommended work IDs; 14 reviewed, 2 pending** before this cycle. Did not claim access to unseen parallel work.

| Count after this commit | Distinct works |
| --- | ---: |
| Recommended | **18** |
| Passed independent subsequent-run review | **16** |
| Pending independent subsequent-run review | **2** |
| Canonical uncounted candidate files | **0** |
| Removed or retired this cycle | **0** |
| Completed final collection audit | **0 / 2,000** |

**26 appearances in 22 populated subject indexes represent 18 works**, not 26. Recompute these figures from remote files; do not inflate by edition/translation/format.

## Review-first conclusions

- [*Logical Foundations* v7.0](../books/pierce-logical-foundations-v7.md): **passed later-run review of above SHA** after inspecting the [original induction proof and `replace` examples](https://kodu.ut.ee/~kalmera/sf/lf/Induction.html), university use and compiler-version caveats. **New finding:** [UPenn current preface](https://softwarefoundations.cis.upenn.edu/lf-current/Preface.html) cites **v7.1**; this record is **v7.0**, tested Rocq 9.0.0; Tartu 2026 uses 9.1.0. Neither v7.1 parity nor cross-version script execution verified. Next run compare revisions within one work ID.
- [*How to Design Programs* 2e](../books/felleisen-how-to-design-programs-2.md): **passed later-run review** after inspecting original [Part II §§8–9](https://htdp.org/2026-5-28/Book/part_two.html) list-recursion design templates and tests. Previously claimed precise Brown Fall 2026 readings were unsupported by a now-unavailable deep link: [live 2026 Brown FAQ](https://cs.brown.edu/courses/cs019/2026/AFQ.html) supports current teaching use, [2025 reading list](https://cs.brown.edu/courses/cs019/2025/placement-readings.html) names exact second edition. Brown coauthor association prevents calling this an arm's-length evaluation. No extra edition counted for 2026 web release.
- Older passed [DDIA 2e](../books/kleppmann-riccomini-ddia-2.md) sample shows primary architecture with substantive data/distributed additional subjects, still requiring full taxonomy retrieval testing.

## Research and new recommendations

- [*Dive into Deep Learning*](../books/zhang-lipton-li-smola-dive-into-deep-learning-2024.md): **recommended, pending later-run review**. [Cambridge original print frontmatter, first published 2024](https://assets.cambridge.org/97810093/89433/frontmatter/9781009389433_frontmatter.pdf#page=4) and rendered contents; author original [§3.1 regression](https://d2l.ai/chapter_linear-regression/linear-regression.html) and [§5.3 backprop](https://d2l.ai/chapter_multilayer-perceptrons/backprop.html) inspected; independent [Cornell CS4782 Spring 2026](https://www.cs.cornell.edu/courses/cs4782/2026sp/) uses the book but not exclusively. Author's 2023 citation, online docs v1.0.3 and publisher print 2024 are distinct. Modern ML principles endure, sample framework APIs may drift. AI/ML gained first recommended book.
- [*Systems Performance* 2e](../books/gregg-systems-performance-2.md): **recommended, pending later-run review**. [Publisher 2020-12-09 edition/ebook](https://www.informit.com/store/systems-performance-9780136821649), original [ch3 printed pp.91 and 105 (PDF pp.42 and 56)](https://www.informit.com/content/images/9780136820154/samplepages/9780136820154_Sample.pdf#page=42) visually inspected, original [ch2 preview](https://www.oreilly.com/library/view/systems-performance-2nd/9780136821694/ch02.xhtml), independent [2024 firsthand review of Japanese translation](https://blog.serizawa.me/p/2024-01-14-system-performance-2nd), author [USE method](https://www.brendangregg.com/usemethod.html) and [current Ftrace docs](https://docs.kernel.org/trace/ftrace.html). Methods remain useful; old kernel flags not certified. Primary Debugging/Performance and additional substantial OS subject. First primary entry in performance.

All cited documents inspected/accessed **2026-10-14**, without implying publication that day. Book records contain source locators, caveats, inspection limits and dated citations. No cover-to-cover reading, runnable-code test, exhaustive errata audit, or complete live-link crawler claimed. Availability, year alone and popularity never used as admission filters.

## Corrections and category decisions

No category split or slug rewrite: **7 groups/23 subjects** remain provisional pending a 25–30 real-edition browsing pilot. Fixed unavailable Brown evidence, discovered official Logical Foundations v7.1, separated print-vs-online D2L versions and old-vs-current Linux interfaces; see [REJECTIONS.md](REJECTIONS.md). No existing book removed.

## Next priorities

1. **Independently review this published commit first**, especially original D2L online-vs-print differences and Systems Performance's translated-edition reviewer/source fit. Pass, revise or demote each after real inspections. Recheck one older passed book each cycle.
2. Compare official [*Logical Foundations* v7.1](https://softwarefoundations.cis.upenn.edu/lf-current/Preface.html) against recorded v7.0 and actual Rocq 9.x requirements; any material edition update stays the same work ID but resets review.
3. Research underrepresented **DevOps/Cloud**, distributed algorithms, and current AI alternatives; keep *Site Reliability Engineering* 2026 second edition uncounted until independent edition-specific evidence exists.
4. Continue known weaknesses: OSTEP v1.10/CFS vs newer source extracts; CLRS printing errata; older accessibility/OS protocol examples. Start machine checks for subject/ID/index integrity.

## Coordination

Re-fetch remote `main` before writes, create tree atop its head, conditional non-force update only, verify commit and canonical records remotely. Resume from this checkpoint; do not invent success or hidden concurrent state.
