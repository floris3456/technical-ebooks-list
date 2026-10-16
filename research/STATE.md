# Research checkpoint — 2026-10-16-02

Starting live `main` was `c175a47e4cb5cd4de97d1d62edeedd8d6216254a`, containing the prior Rust search-only WIP in `research/sources/2026-10-16-02/001-discovery.md`. Reviewed README, TAXONOMY, canonical book template, previous STATE and source audit, REJECTIONS, UNSELECTED, the latest source-only commit and TLPI record, plus platform index. Did not assume unpublished work. The preceding checkpoint remains in git history.

## Verified collection metrics

- **29** distinct recommended work IDs; **29** qualified subsequent-run reviews and **0** pending, subject to final audit (**0 / 2,000** completed).
- **1** canonical uncounted candidate; **6** distinct deferred works including it (newly deferred Mara Bos). No promoted Rust work, no removal, no category changes.
- All **23** controlled subjects remain in original taxonomy; the topic index and README were updated for TLPI's later-run pass. Formats, editions and subject appearances are not new works.

## Reviewed and newly researched

**TLPI** from the published record at `521ad1538df267f9fff2eb45420b02d6e64a8f7d`: qualified independent later-run pass. The original publisher chapter4 PDF was reopened with printed p71 code visually rendered; introductory `copy.c` treats short writes as fatal rather than retrying. Current [write(2)](https://man7.org/linux/man-pages/man2/write.2.html) confirms partial writes are valid. Chapter4 pp74–76 already describes `O_CLOEXEC`/exec race; avoid claiming that topic absent. Fall 2026 William & Mary course, Jake Edge's independent 2011 review, and printing-specific errata reopened. Durable descriptors/process control still useful, but full chapter corpus, all corrections, modern Linux API additions and example execution remain unverified. Older sample rotating Security Engineering 3e was reviewed at preceding checkpoint; no new fresh older-sample inspection claimed beyond TLPI itself.

**Rust Atomics and Locks** (Mara Bos, 2023): inspected original ch3 memory ordering and ch8 OS primitives, author preface/TOC, an independent 2024 reviewer with promotional conflict disclosure, publisher errata and Rust modern references. The reviewer describes strong examples and high prerequisites; publisher errata flag a direction-of-happens-before issue and a missing safety bound on `Guard` in ch4/9. Deferred in UNSELECTED until page-level live text and corrected print/ebook mapping are reconciled. The 2026 Rust Book 3e discovery remains a lead only; 2026 publisher and maintained online text do not establish independent exact-print expert evaluation.

**Sources:** [exact URL audit](sources/2026-10-16-02/001-discovery.md), accessed 2026-10-16. Multiple website families directly opened (some timed out); previous site history, index-only and duplicates make the demanded 20 **new** website families unverified. No 20-source-completion claim. Pages inspected are not equivalent to 20 independent book assessments. No full book or executable test was performed.

## Next focus

1. Reconcile original Rust Atomics ch4/9 lock guard `Sync` and chapter3 ordering errata with current reference; seek independent adoption or detailed technical critique without publisher/discount dependency.
2. Deepen 2026 Rust Programming Language third-print independent adoption and original chapter/errata; distinguish maintained HTML from printed edition.
3. Rotating older review and incomplete Petrov/OSTEP/CLRS issues; make a separate staged audit of source validity, present-day usefulness, duplicates and categories.
4. Investigate **at least 20 genuinely new** website families with substantive sources next cycle; this run's cross-website opens are logged but not miscounted.

This checkpoint reflects observable saved work only. Do not count deferred works. Work target remains **2,000** and final audit incomplete.
