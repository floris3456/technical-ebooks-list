# 2026-10-16-03 — exact attempted-source register, batch 1

Access date 2026-10-16 Europe/Amsterdam for every URL; source publication/update dates recorded separately. Starting main b4da510e517c327c083ad22b25cbdea2a9c2b18e. Reviewed live README, TAXONOMY, books/BOOK_TEMPLATE.md, research/STATE.md, REJECTIONS, UNSELECTED and saved cycle-02 Rust WIP, plus older Systems Performance 2e. Latest main commit only synchronized deferral count; no external unpublished work presumed. Search discovery and opened sources distinguished below. Earlier visits to mara.nl, O'Reilly, github.com, habr.com do not earn new-site credit.

Search queries: Rust Atomics and Locks Mara Bos Guard Sync errata ch4 ch9 2023 2026; Rust Atomics and Locks 2023 university course textbook assigned concurrency; Rust Atomics and Locks Mara Bos detailed review code quality.

Direct openings:
- https://bwestbro.com/blogs/br-rust-atomics.html — independent Brent Westbrook personal review dated 2024-09-02 appeared in full search retrieval; direct open returned 502 (do not claim direct body inspection; retrieved original article excerpt discusses hardware and Rust applicability).
- https://budevg.github.io/posts/2023-01-20-book-review-rust-atomics-and-locks.html — direct full 22-line article read, dated 2023-01-20, firsthand engineer explanation ch7 processor/Compiler Explorer and learning approach; distinct new personal website family, GitHub Pages hosting caveat.
- https://www.oreilly.com/catalog/errata.csp?isbn=0636920635048 — direct inspected confirmed errata rows p68 happens-before reversed (submitted 2023-01-06, corrected 2023-01-27); ch4/ch9 Guard Sync impl omission (submitted 2023-03-06, no correction date), p209 reader count operator (submitted 2023-03-18, no correction date), p76 is_err correction (2023-01-27). No claim subsequent print corrected unscheduled entries.
- https://mara.nl/atomics/3_memory_ordering.html — direct URL unsuccessful; no body read (path invalid or inaccessible).
- https://mara.nl/atomics/4_building_our_own_spin_lock.html — direct URL unsuccessful; no body read.

Search-returned original pages not opened anew in this batch (discovery, not substantive-read credit): https://marabos.nl/atomics/ ; https://mara.nl/atomics/foreword.html ; https://mara.nl/atomics/preface.html ; https://mara.nl/atomics/ ; https://best-devbooks.github.io/rust-books/books/rust-atomics-and-locks/ ; https://github.com/m-ou-se/rust-atomics-and-locks ; https://github.com/StevenBlack/rust-atomics-and-locks ; https://www.oreilly.com/library/view/rust-atomics-and/9781098119430/ ; https://news.ycombinator.com/item?id=41239913 ; https://play.google.com/store/books/details/Mara_Bos_Rust_Atomics_and_Locks?id=jPqhEAAAQBAJ . Bibliography in author page says Jan 2023, print ISBN 9781098119447, while O'Reilly ebook URL identifies 9781098119430; do not infer all ISBN format assignments from URL. Foreword by Paul E McKenney is included in the authored book and is not a substitute for genuinely independent external evaluation.

Provisional decision: original book still deferred pending exact ch4/ch9 code/errata comparison and more independent verification; do not imply code was run or assertions tested. More source research needed, 20 genuinely new websites NOT established by batch 1.

## Batch 2, direct opens (2026-10-16)
- https://news.ycombinator.com/item?id=41239913 — full 2024-08-13/14 user discussion inspected, including technically specific warning that Windows SRWLock behavior and Rust's implementation have changed since book was written; poster links rust-lang/rust PR 121956. Community commentary, not proof of API behavior without primary crosscheck.
- https://mara.nl/atomics/foreword.html — full foreword by Paul E. McKenney within the book; favorable expert foreword, not institutionally independent review.
- https://bwestbro.com/blogs/br-rust-atomics.html — direct retry succeeded with 35 lines: firsthand book review 2024-09-02 describes the concrete value of memory-ordering/assembly explanations and its Rust-oriented chapters; earlier failed opening retained above.
- https://www.oreilly.com/library/view/rust-atomics-and/9781098119430/ — opened 494-line publisher edition/TOC; 2023, 249 pages, intermediate-to-advanced, no proof of correction to a given print/ebook build.
- https://mara.nl/atomics/building-our-own-spin-lock.html — failed open (wrong path).
- https://mara.nl/atomics/building-our-own-locks.html — failed open (wrong path).

New factual caution: a 2024 reader's Windows SRWLock platform-update claim should be checked against Rust official implementation before using as fact; book's 2022-compiler examples are not a 2026 platform API manual. The independent Westbrook/Budilovsky assessments provide more credible independent learning evaluation than a publisher foreword or promotional third-party page, but recorded Guard Sync erratum still requires code-version verification. 20 new website families NOT met or claimed.
