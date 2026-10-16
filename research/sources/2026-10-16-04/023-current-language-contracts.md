# Current language contracts

Access2026-10-16; all Rust project sources returning, zero new-site credit.
- https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html — full54-line current migration explanation read: edition2024 warns by default about unsafe operations lacking explicit blocks inside unsafe functions. Old examples need explicit-scope review, not an assumption that unsafe fn validates its body. Page update date unstated.
- https://doc.rust-lang.org/std/option/index.html#representation — Representation section inspected: niche guarantees explicitly include NonNull<U> under stated Sized/ABI conditions, not arbitrary nullable raw pointers. Correct modern type name is NonNull, not the errata page's NotNull. This supports a concrete Gjengset FFI caveat without claiming ABI guarantees for all Option<T>.
- https://doc.rust-lang.org/std/vec/struct.Vec.html#method.set_len — current rustdoc retrieved6780lines; targeted contract still to inspect, not an entire API read.
- https://blog.rust-lang.org/2023/12/21/async-fn-rpit-in-traits/ — original Async Working Group2023-12-21 announcement and examples read through FAQ. Establishes post2021 availability in1.75; its then-future plans/remaining limits are not automatically today's status. Current Reference needed for present dyn-compatibility claims. No compiler or migration commands run.
