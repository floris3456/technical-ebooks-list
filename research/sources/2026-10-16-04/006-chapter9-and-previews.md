# Chapter9 corrections and preview attempts

All access dates 2026-10-16; source-update dates unknown unless stated.

- https://mara.nl/atomics/building-locks.html — inspected Mutex section (Guard Send/Sync bounds now present), reader-lock counter assertion (`s < u32::MAX - 1`) and later writer-starvation version (`s < u32::MAX - 2`), plus condvar overflow/stress-testing limitations. Corrected live text resolves both targeted chapter9 gaps. Author pins atomic-wait major1 and warns later versions may differ. Text's test discussion explicitly does not prove correctness. Not every chapter section was read.
- https://nostarch.com/download/samples/RustforRustaceans_Ch1.pdf — authorized original 18-page chapter1 retrieved; 644-line PDF extraction. Rendering/targeted reading is next, so no diagrams or full chapter inspection claimed yet. 2021 work.
- https://rust-for-rustaceans.com/ — author resources/errata retrieved, 538 lines; focused errata reading needed. Author site not independent review.
- https://www.zero2prod.com/ — redirects to https://www.zero2prod.com/index.html?country=Germany&discount_code=VAT20&country_code=DE . Geo/price parameters are automatic redirect artifacts, not selection factors or purchase instructions. 125-line author page retrieved, detailed contents/changelog not yet examined.
