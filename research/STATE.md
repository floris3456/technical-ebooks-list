# Research checkpoint

## Cycle 2026-10-14-09

**Reviewed starting main:** `154e499e02b872a859e7ee6b641b72365dd245a9` (tree `2ca4538433c0730fb0cccba5c2d1ad1163858067`). Read current README, TAXONOMY, record template, prior STATE/REJECTIONS, latest commit diff and complete tree. Reexamined two previous pending records and rotating older DDIA/OSTEP; reviewed relevant indexes and publication checks. Work in other live runs is not visible and was not assumed.

| Verified post-commit measure | Distinct works |
| --- | ---: |
| Recommended (unique `work_id`) | **20** |
| Passed subsequent-run independent review | **18** |
| Awaiting a later-run independent review | **2** |
| Canonical uncounted candidate files | **0** |
| Added / revised existing records / removed | **2 / 2 / 0** |
| Final collection-wide audit complete | **0 / 2,000** |

**28 subject-index appearances across 22 populated subject indexes ≠ 28 works.** Preserve stable IDs across editions, formats and translations. Never mark this cycle's additions passed in the same commit. Recompute counts from live remote tree, not this file alone.

## Review of prior published work

- [Dive into Deep Learning (Cambridge 2024 / online v1.0.3)](../books/zhang-lipton-li-smola-dive-into-deep-learning-2024.md) **passed** independent review of `154e499e02b872a859e7ee6b641b72365dd245a9`. Original author §§3.1.3 and 5.3.3 were reopened; Cambridge 2024 copyright+contents visually checked; [Cornell Spring 2026](https://www.cs.cornell.edu/courses/cs4782/2026sp/) calls it a primary textbook among other texts. No print/web exact pagination parity, framework execution or errata completeness asserted. Print paperback ISBN not copied as ebook ISBN.
- [Systems Performance second edition](../books/gregg-systems-performance-2.md) **passed** independent review of `154e499e02b872a859e7ee6b641b72365dd245a9`: visually rechecked original publisher sample PDF pp.42/56 (printed 91/105), [2024 independent review of Japanese second edition](https://blog.serizawa.me/p/2024-01-14-system-performance-2nd), and [live Linux tracing documentation](https://docs.kernel.org/trace/ftrace.html). Source translation cannot establish English page numbers; old CLI and kernel specifics remain caveated.
- Rotating older [DDIA 2e](../books/kleppmann-riccomini-ddia-2.md) revisited for substantial architecture/database/distributed-secondary fit, with remaining protocol depth and errata gaps. Older [OSTEP 1.10](../books/arpaci-dusseau-ostep-1-10.md) retains the known 1.10 rendered vs 1.20 extraction conflict and scheduler-currency caveat; neither falsely reapproved as a new review.

## New deeply researched recommendations (pending later run)

- [Pro Git 2e](../books/chacon-straub-pro-git-2.md): [official 2014 second edition](https://git-scm.com/book/en/v2); inspected original branch/merging/revision chapters; [Youngstown State Fall 2026](https://catalog.ysu.edu/syllabi/2026-fall/csci-5802-01-44236/) required reading, assigned chs.1–3,7,10; [Cornell Fall 2026](https://courses.cs.cornell.edu/cs3410/2026fa/rsrc/git.html) supplemental endorsement; [Git switch](https://git-scm.com/docs/git-switch) provides present-day command context. [Pro Git third edition](https://progit3.com/) is **in progress**, not an already complete book. Branch/default and GitHub UI examples may be dated.
- [Distributed Systems 4e](../books/van-steen-tanenbaum-distributed-systems-4.md): [author 2023 edition and v4.03 Jan 2025 corrections](https://www.distributed-systems.net/index.php/books/ds4/); visually inspected [LiU 2026 instructor original section-level reading map pp.1–2](https://www.ida.liu.se/~TDDD25/lectures/TDDD25-lasanvisningar-vanSteen-4e.pdf#page=1) (RPC, clocks, consistency, fault tolerance); independently [Linköping 2026](https://www.ida.liu.se/~TDDD25/info/courseinfo.en.shtml) and [UMass 2025](https://lass.cs.umass.edu/~shenoy/courses/spring25/materials/) adopt 4e; [etcd API](https://etcd.io/docs/v3.6/learning/api/) shows live consistency semantics. **Direct full original chapter prose not inspected**—first priority at later-run review. Educational adoption supports value, not a guarantee every code example remains current.

## Quality, taxonomy, corrections

- Fixed **stale Pending index status** for already-passed *Software Engineering at Google*. Newly-passed D2L and Systems Performance now show Passed in every subject index (including OS secondary).
- Retained **7 groups / 23 subjects**. Adding one formal distributed-systems text and one Git practices book improved retrieval under existing slugs, without evidence for taxonomy split. One primary per work; no duplicate index records.
- No availability/price/format filtering. No cover-to-cover book claims, full-page errata review, reproduced copyrighted binaries or executed code claims.
- See [REJECTIONS.md](REJECTIONS.md) for old-versus-current Git guidance, incomplete distributed chapter direct inspection, and metadata/index correction.

## Next research priorities

1. **First review this commit**, especially direct original *Distributed Systems* fourth-edition prose, professor-section mapping, v4.03 corrections, 2025/2026 course interpretation; demote if independent inspection raises central errors. Review Pro Git third-edition draft status, current Git defaults and a deep internals original chapter. A new book must not pass in the same publishing run.
2. Investigate still-empty **DevOps, Cloud & Infrastructure** as primary subject. Research Kief Morris *Infrastructure as Code* **third edition (2025)** through exact original chapter/sample and independent **third-edition** review or teaching—not through 2023 reviews of older editions.
3. Continue 2026 *Site Reliability Engineering* 2e as an uncounted lead until independent edition-specific assessment or adoption. Do not use publisher announcement as a substitute.
4. Compare [Logical Foundations 7.1](https://softwarefoundations.cis.upenn.edu/lf-current/Preface.html) against catalogued v7.0; avoid double counting and untested Rocq 9.x compatibility.
5. Develop automated validation of stable work IDs, distinct approved slugs, record statuses, index membership and evidence locators. Check OSTEP version conflict and CLRS printing-specific errata in later audit.

## Publication and coordination

All material source URLs and section/page locators are in canonical records; source dates distinct from 2026-10-14 access checks. Commit only atop observed branch head and with conditional non-force update; verify remote ref and published records afterward. This checkpoint intentionally does not include its own commit SHA.
