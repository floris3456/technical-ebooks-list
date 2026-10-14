# Research checkpoint

## Cycle 2026-10-14-10 — new substantive review/research cycle

**Starting reviewed catalog:** `b02eb3227d76c32381edbed90862b0b2b8d69876` (20 recommended; 18 later-reviewed, two pending). Interim evidence-log commits were observed on `main`; first/current source logs are under [cycle-10](sources/2026-10-14-10/000-start.md). Every successfully inspected URL, retrieval failure and discovery-only lead is preserved in numbered chronological Git files 000–020. No unpublished concurrent research was assumed.

| Recomputed planned publication metric | Distinct works |
| --- | ---: |
| Recommended canonical works | **22** |
| Passed independent subsequent-run review | **20** |
| Awaiting later-run review (new recommendations) | **2** |
| Canonical uncounted candidate files | **0** |
| Added / materially revised / removed | **2 / 0 / 0** |
| Final audit complete | **0 / 2,000** |

One immutable work ID per recommendation; edition/file-format/subject-index appearances do not inflate the count. Subject taxonomy remains seven groups and 23 controlled subjects; all 23 now have populated indexes, with **32 subject appearances**.

### Existing-record review and corrections

- [Pro Git, second edition](../books/chacon-straub-pro-git-2.md): passed a new review of `b02eb322...`. Reopened original §10.2 Git Objects, 2026 Youngstown course assignments, current `git-init` and third-edition draft status. Retained caveat: SHA-1/branch examples and GitHub UI do not prescribe current or future defaults; official Git 3.0 work is not a completed Pro Git third edition.
- [Distributed Systems, fourth edition](../books/van-steen-tanenbaum-distributed-systems-4.md): passed a source-qualified later review of `b02eb322...`. Rechecked Linköping's original 2026 section-specific guide and author version page. Important correction: **4.03x** includes newer small corrections than print-corresponding **4.03**; their page numbering is unchanged. Original whole-chapter prose was not anonymously accessible and was **not** claimed inspected; educational adoption and exact chapter map justify the qualified choice, with a final-audit gap.
- Rotating older [Security Engineering third-edition errata](https://www.cl.cam.ac.uk/archive/rja14/book/v3errata.html): inspected specific author corrections, but did not reapprove the work as a new later-run review or assert complete errata coverage.
- Found and repaired stale **Pending** statuses in older topic indexes for already-passed DDIA (architecture and data engineering), Software Engineering at Google (maintenance), and Crafting Interpreters (compilers). Index corrections do not constitute fresh book assessments.

### Newly recommended (pending a subsequent run)

- [Continuous Delivery — first edition](../books/humble-farley-continuous-delivery-1.md) (2010): original chapter-5 practices, independent Bas Vodde critical reading and contemporary artifact/pipeline technical references. Why now: trace/promote one tested artifact, feedback, gates, configuration discipline. Limits: dated tools, secrets/provenance and infrastructure assumptions; first ebook ISBN verified but format-specific allocation unknown. Primary DevOps/Cloud, additional testing.
- [Release It! — second edition](../books/nygard-release-it-2.md) (2018): visually inspected original P1.0 publisher excerpt and coupling diagrams, independent **second-edition** evaluations (2018 and 2023), present-day Dapr/Envoy circuit-breaker references. Why now: failure containment, bulkheads, back-pressure, production design. Limits: OWASP 2017, manually configured infrastructure, incomplete errata, and difference between dev documentation and stable releases. Primary software architecture, additional reliability.

### Source discovery coverage and rejected shortcuts

Logged **25 distinct successfully investigated website domains** across this cycle, not 39 independently verified books or 39 independent endorsements. Repeat pages/hosts did not increase this count. Record exact URLs and outcomes including failures F01 (redirect) and F02 (SLSA v1.2). Source roles are separated: first-party book material, expert/education assessment, live technical relevance, partial/failed discovery. Some visited domains might have been used in undocumented earlier searches; no unseen earlier browsing is asserted. Evidence-log entries 001–020 are the audit trail. At least 20 distinct websites were researched in this cycle.

**Not promoted**: Kief Morris *Infrastructure as Code* **third edition** (O'Reilly original ch.14 opening inspected and official 2025 author interview; independent third-edition assessment not established), and *Site Reliability Engineering* 2026 second edition (publisher/author evidence lacks independent edition-specific evaluation). Both remain leads irrespective of availability, and are not counted.

**Conscious restrictions**: do not infer an errata-free printing from a form, assume a third edition is finished from promotional copy, transfer first-edition reviews to later books, or treat 2018/2010 product commands as 2026 operational instructions. Publisher/sample titles are stronger edition evidence than a conflicted storefront sidebar. No acquisitions, copyrighted ebook binaries, example deployments or code executions performed.

### Next cycle priorities

1. Independently review **both additions** using more original deployment/data-migration prose and a Release It! stability-pattern chapter; verify adverse claims and errata beyond the single unadjudicated 2025 diagram report. Change/demote if warranted; the new pair cannot pass in this publishing cycle.
2. Resolve direct section-level prose and **4.03x** corrections for Distributed Systems while honoring its source-depth limitation; review 2026 Git object-format and command defaults without confusing pre-release announcements.
3. Develop independent **third-edition** assessment or adoption for *Infrastructure as Code* (2025) and inspect substantive version-specific text. Other high-priority empty/weak primary areas: data engineering, legacy-system maintenance and platform-specific development.
4. Audit older OSTEP version-extraction conflict and CLRS printing errata; test proposed 23-subject taxonomy against 25–30 works and repair any index drift automatically.
5. Review final evidence precision/URLs, edition metadata and duplicate work IDs across every published work. No work is final-audit-qualified yet.

Publication rule: branch head must be re-fetched and conditional non-force update verified remotely. This checkpoint does not embed its own circular commit SHA.

---

### Prior checkpoint (archived; figures below are historical)


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
