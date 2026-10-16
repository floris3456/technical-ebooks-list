# Structural validation and publication checkpoint — 2026-10-16

## Assembled catalog commit

Reviewed commit **b024ef778ee60732476be4b493e6d5dc398a379f**, tree **b90a0cf9e4e323b0605c88d61a9607538a4871cd**. Its first parent is the intervening main **b1f414261241f2540ceefe559ee201a793a43295**; its second parent is this cycle's recorded research/canonical-file head **dada0b775d14ed65ac752df9c8137b7e545eebc5**. This preserves both histories instead of force-replacing main. This document is a child checkpoint, not an assertion that main had already moved when it was written.

Authorized GitHub comparison against b1f414 reports **ahead32 / behind0**,47 changed paths and no deleted files. Changed scope: README; two older book annotations/review metadata; four new canonical book records; four current research ledgers and four exact archive copies;27 numbered review/source logs plus their audit; four affected topic-index files. No unrelated book, taxonomy, template or cycle05 log changed. The actual README, Bos and CLRS patch bodies were inspected, not just their statistics.

## Counts and metadata

Read the assembled books tree **72bd931c3214ceaf7111b5b3a88e35c5c2838781** and fetched all four new front matters back from the assembled commit. It contains38 canonical records excluding BOOK_TEMPLATE. Existing32-recommendation/two-candidate baseline is unchanged except Bos review status and CLRS annotation; four added files comprise two recommendations and two candidates.

An offline Python check on values transcribed from authorized GitHub tree/front-matter/index responses confirmed:

-38 unique canonical paths, four candidate paths excluded,34 recommendation records;
-four pending recommendation paths (DPV, Skiena, Gjengset, Palmieri), leaving30 passed;
-four new lowercase kebab-case work IDs, all distinct: dasgupta-papadimitriou-vazirani-algorithms, skiena-algorithm-design-manual, kleinberg-tardos-algorithm-design, sedgewick-wayne-algorithms;
-23 controlled-subject counts sum to55 appearances; Algorithms has three, Programming four and Concurrency four;
-all five newly recorded ISBN-13 check digits valid:9783030542566,9783030542559,9783030542580,9780321295354,9780321573513. A valid checksum is not bibliographic provenance; the publisher/source ledgers establish assignments separately;
-the curator signed-product counterexample evaluates to−2 when retaining only the smaller prefix, versus true minimum−3. This arithmetic check is not execution of book examples.

The equal title *Algorithms* for DPV and SW does not indicate duplicate authorship; both work IDs and source identities differ. SW remains a candidate. No translation, format, paperback date or electronic-product refresh adds a counted work. Bos is passed with reviewed_commit ba27c63a3dbc093ceb91dc96a529f8fae76fd059; CLRS retains its prior reviewed_commit. New recommendations have null reviewed_commit and pending status. Unknown metadata does not block qualification.

This is **delta/structural validation**, not a new full YAML/evidence audit of all38 records. The retained baseline and unchanged blob comparisons support the unchanged counts; no claim of freshly re-reading every older book assessment is made. No repository generator, CI test or automated external-link crawler was installed or run.

## Preservation and references

The assembled research tree **5a80e5abe8bb2b5eef1f35696de0edbf7c92a663** verifies exact prior blobs at new same-directory archive paths:

| Archive | Original blob retained |
| --- | --- |
| STATE-through-f164164.md |13007743362b4b7ad800ff68bf01720c8515cd94 |
| SOURCES-through-f164164.md |47954a2bc3efde0635f92139db9128e4b715de7e |
| REJECTIONS-through-f164164.md |6a1bac2dac1a40e1737b491ea701c05e5863f391 |
| UNSELECTED-through-f164164.md |d9f129b4b41223627c4e75c79e6166d57219339a |

All eight cycle05 files are absent from the changed-file list against b1f414, establishing unchanged preservation. Their fetched SHA values were used directly in reconciliation. The current research ledgers link that saved work rather than falsely crediting its external reads to cycle06.

Manually checked new book source IDs against their ledgers: DPV D1–D12, Skiena K1–K10, KT T1–T5, SW W1–W7; Bos retains B1–B10 and adds B11–B13. Exact URL/section/page and date boundaries are present, with unsuccessful searches classified as traces rather than gate evidence. The source audit now exists at every newly referenced relative path. Newly added book-to-book links match canonical filenames. The27 numbered logs, candidate links, updated indexes and four archives resolve to recorded repository paths. Old arbitrary external links and every historical Markdown anchor were not exhaustively crawled.

README counts, current STATE, UNSELECTED's eight active rows, algorithm index and Bos's two subject labels were reconciled manually. Current topics summary excludes all four candidates. No work was removed; therefore no retirement record was needed. Earlier Bos deferral remains discoverable as superseded.

## Publication conditions and remaining audit

Before updating refs, re-fetch main and use **force=false plus expected_sha**. If main differs from the reconciled parent, inspect and preserve intervening changes rather than overwrite them. Move the research branch conditionally, then main only after the final head check, and verify the remote ref and checkpoint. A failed update must be reported as a blocker, not publication success.

The source-evidence audit is [README.md](README.md). Final completion is still open:34 recommendations,30 subsequent passes, four pending, eight active deferrals, zero final-audit clearances. No automation settings changed, book purchased or unauthorized copy stored. No book examples, compiler tests, concurrency stress tests, numerical solvers or benchmarks were executed.
