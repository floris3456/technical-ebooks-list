# Cycle 2026-10-15-05 — exact source audit

**Access date:** 2026-10-15 (not document publication/update date). Starting remote main `982ba88e4d8ab0b1489bd41fb91271f5f52f22db`. Previous cycle-04 source-only logs 001–002 were observable saved work; their unknown six original source URLs cannot be reconstructed. External retrieval batches were logged in Git before the next batch; no full copyrighted book binary was fetched or stored.

## Site novelty — conservative accounting

**26 newly opened website families**, all distinct from one another and historical persisted site keys under conservative host consolidation. **22 conservatively substantively inspected**: exclude Intel's broad manual index, DWARF's specification navigation index, Godbolt's tool homepage, and ISO's edition-only record from book-content/technical-depth credit. The 22 counted families are:

| New family | Representative exact URL | Actually inspected role / original source date |
| --- | --- | --- |
| llvm.org | https://clang.llvm.org/docs/AddressSanitizer.html | Memory fault diagnostics and limitations; live docs, update unknown |
| sourceware.org | https://sourceware.org/glibc/manual/2.31/html_node/Unsafe-Features.html | glibc 2.31's signal/cancellation pitfalls; **version 2.31**, not current manual |
| valgrind.org | https://valgrind.org/docs/manual/mc-manual.html/manual-core-adv.html | Memcheck error types; 3.27.1 manual TOC **2026-05-20**, not this page's date |
| man7.org | https://man7.org/linux/man-pages/man7/signal-safety.7.html | POSIX async-signal-safety examples; page update not confirmed |
| gnu.org | https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html | GCC optimization flags/tradeoffs; undated |
| qemu.org | https://www.qemu.org/docs/master/system/introduction.html | Virtualized/accelerated architecture modes; displayed 11.1.50 |
| agner.org | https://www.agner.org/optimize/ | Independent optimization manual family and versioned updates; precise guide date varies |
| openmp.org | https://www.openmp.org/spec-html/5.2/openmp.html | OpenMP **5.2** formal parallel API/specification; publication date not separately verified |
| open-std.org | https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3220.pdf | Rendered **2024 draft** C language pages; not final standard |
| osdev.org | https://wiki.osdev.org/ELF | ELF executable object format/loader wiki, update unspecified |
| freebsd.org | https://www.freebsd.org/cgi/man.cgi?query=signal&sektion=3 | Redirect to FreeBSD manual; signal handler semantics |
| ziglang.org | https://ziglang.org/documentation/0.15.2/ | Zig 0.15.2 programming reference; not C equivalent |
| wellesley.edu | https://cs.wellesley.edu/~cs240/f20/syllabus/ | Fall **2020** independent CSAPP3e assigned course, not a modern technical reference |
| alistair.cockburn.us | https://alistair.cockburn.us/hexagonal-architecture/ | Original **2005-09-04** ports/adapters essay; author opinion, not book review |
| ploeh.dk | https://blog.ploeh.dk/2013/12/03/layers-onions-ports-adapters-its-all-the-same/ | Mark Seemann **2013-12-03** architecture comparison; not book endorsement |
| go.dev | https://go.dev/ref/mem | Go memory model **2022-06-06**, illustrates concurrency model contrasts |
| jemalloc.net | https://jemalloc.net/jemalloc.3.html | Heap allocator arenas, allocation diagnostics and flags; update unknown |
| umd.edu | https://www.cs.umd.edu/class/fall2025/cmsc216-030X/index.html | Fall **2025** CSAPP3e **recommended**, not required |
| lwn.net | https://lwn.net/Articles/773118/ | Dated CPU speculative execution/security analysis, not 2026 architecture norm |
| sel4.systems | https://sel4.systems/About/ | Verified microkernel goals and scope; introductory primary project overview |
| hmc.edu | https://www.cs.hmc.edu/~beth/courses/cs105/fall2026/ | Independent **Fall 2026** CSAPP3e text and lab-focused syllabus |
| harvard.edu | https://cs61.seas.harvard.edu/site/2026/Textbook/ | **2026** third-edition section map and firsthand faculty criticisms |

Four other newly opened site families, too shallow for substantive credit: Intel's current manual index (`https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html`), DWARF v5 specifications index (`https://dwarfstd.org/dwarf5std.html`), Compiler Explorer homepage (`https://godbolt.org/`), ISO/IEC 9899:2018 metadata page (`https://www.iso.org/standard/74528.html`). Already-known authors/publishers/CMU/SQLAlchemy/Rust websites add no fresh novelty.

### Failed and incomplete external attempts

The exact failures are retained in numbered records: Linux Foundation ABI PDF fetch error, AMD manual error, ARM redirect to empty page, musl timeout, elfutils failure, Princeton 2017 course opening error, Open Group error, RISC-V index redirect, short Linux EEVDF response and a CSAPP appendix screenshot timeout. Each is logged but does **not** count as substantive reading. Discovery-only retailer/community/repost links remain **search-only** and were not used as book-specific evidence. Do not infer original content from search excerpts.

## Book-specific quality findings

Read the full original **[Cosmic Python unit-of-work chapter](https://www.cosmicpython.com/book/chapter_06_uow)**, original repository chapter, **[Buresund review](https://www.buresund.se/books/architecture-patterns-with-python/)** and **[SQLAlchemy 2.0 migration guide](https://docs.sqlalchemy.org/en/20/changelog/migration_20.html)** for qualified later-run review. Independently sourced CSAPP third edition via original accessible preface, two original authors' Web Asides and exact US errata plus Harvard/HMC current course sources and 2026 future-edition author statement. Pages/sections and source dates reside in canonical records. Older OSTEP original condition-variable PDF was rendered in the rotation.

This audit supports **one new CSAPP work pending later review** and **one genuine later-run Python Architecture pass**; it does not imply a full-book read, executed lab suite, cleared errata or final catalog audit.

## Chronological records

Git-tracked exact retrieval logs in this folder: `001-checkpoint.md`, `002-a.md`, `002-b.md`, `003-log.md`, `003-d.md`, `003-f.md`, `003-g.md`, `004-a.md` through `004-e.md`, `005-a.md` through `005-f.md`, `006-a.md` through `006-f.md`, `007-a.md` through `007-f.md`, `008-a.md` through `008-c.md`, `009-a.md` through `009-e.md`, `010-a.md` through `010-f.md`, `011-*.md`, `012-*.md`. Exact read boundaries differ by source. Some early small log files were committed separately after write-request validation blocked longer single-file content; log coverage is the aggregate, not a claim of one multi-URL file per request.
