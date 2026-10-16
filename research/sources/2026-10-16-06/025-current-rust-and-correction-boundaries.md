# Rust/current correction boundaries — accessed 2026-10-16

https://doc.rust-lang.org/edition-guide/rust-2024/static-mut-references.html — Summary/Details/Alternatives through OnceLock/LazyLock read. Rust2024 denies static_mut_refs by default, including implicit method-call references. This is a migration issue for Bos ch3 DATA.push demo, not proof its intended synchronized access was inherently racy. Preferred locally reasoned abstractions remain compatible with the book's guard-design lesson; disabling lint alone is not a correctness argument. Page revision unspecified.

https://doc.rust-lang.org/std/sync/atomic/enum.Ordering.html — variant definitions through SeqCst inspected, Rust1.99.1/build2026-10-13. Acquire/Release contracts and their relaxed counterpart for read-modify-write operations support continued relevance of ordering analysis. No claim of a full memory-model proof.

https://www.oreilly.com/catalog/errata.csp?isbn=0636920635048 — full confirmed table read. p68 direction corrected2023-01-27; guard-bound submitted2023-03-06 and p209 counter submitted2023-03-18 have blank correction dates, although latter says Fixed. p54 explicitly fixed second printing. Do not propagate unspecified fixes to all print/electronic copies.

Retrieved for final selected-page checks: https://mara.nl/atomics/building-locks.html ; https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/11599/selected_solutions.pdf ; https://cseweb.ucsd.edu/~dasgupta/book/toc.pdf . Header/retrieval alone not full-source reading; fresh renders and chapter sections follow. No new website credits.
