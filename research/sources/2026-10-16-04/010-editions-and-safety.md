# Edition and safety crosschecks

Access2026-10-16.
- https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/ — inspected identity and full contents, not full book. June2021, Jim Blandy/Jason Orendorff/Leonora F. S. Tindall, 738pages; chapter4moves/5references/19concurrency/20async/22unsafe/23FFI. Current description claims Rust2021 coverage, which needs checking against original edition dates, not blindly repeated. Explicit link to Programming Rust3e discovered: newer-edition check now required, no assumption2e latest. ISBN9781492052586 listed without confirmed file subtype.
- https://doc.rust-lang.org/std/marker/trait.Sync.html — current standard-library header1.99.1, build2026-10-13. Definition and reference relations inspected: T:Sync iff &T:Send; &mut T:Sync when T:Sync. Supports rationale for corrected shared-lock-guard bounds in Bos, not complete proof of book algorithms. Implementor listing not exhaustively read.
- https://www.oreilly.com/catalog/errata.csp?isbn=0636920635048 — confirmed ledger retrieved117lines; targeted entry inspection follows. No new-family credit.
- https://cese.ewi.tudelft.nl/software-systems/ — repeated502; still no direct-read or novelty credit.
- https://bitemyapp.com/blog/notes-on-zero2prod-rust/ — Chris Allen's original review,160lines retrieved via Preslav link; detailed read follows. Treat independent production-Rust perspective as a lead, not yet accepted technical conclusions.
