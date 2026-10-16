---
work_id: gjengset-rust-for-rustaceans
title: "Rust for Rustaceans: Idiomatic Programming for Experienced Developers"
authors: ["Jon Gjengset"]
edition: "First edition, November 2021"
publication_year: 2021
isbn_by_format: {paperback: "9781718501850"}
primary_subject: programming
additional_subjects: [software-design-and-code-quality]
concepts: [ownership, lifetimes, library-design, error-handling, asynchronous-programming, unsafe-rust, foreign-function-interfaces]
languages: [Rust]
technologies: []
difficulty: advanced
focus: [conceptual, practical, reference]
formats: [pdf, epub, mobi]
access: unknown
official_url: https://nostarch.com/rust-rustaceans
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# Rust for Rustaceans — First Edition

## Recommendation and audience

Recommend to developers who already understand basic Rust and want to design libraries and reason more carefully about ownership, interfaces, errors and lower-level code. This is not a first programming course. The publisher positions it for experienced developers; the original sample begins by refining existing mental models rather than introducing programming from scratch [G1–G2]. The catalog's advanced label describes that prerequisite, not a claim that every chapter is equally difficult.

## Concrete value, contents and subject fit

In the inspected chapter1 sample, the author contrasts memory-oriented and flow-oriented models of values and demonstrates why the last use of a borrow matters. Rendered printed pages4 and13 contain worked ownership/lifetime examples rather than merely a contents list [G2]. The wider contents cover types and interfaces, errors, project organization, testing, macros, asynchronous programming, unsafe code, concurrency, foreign interfaces and embedded development [G1]. Only the identified sample pages and errata were inspected in depth; this is not a claim to have read or tested all280 pages.

**Programming** is the primary subject because the objective is effective use of Rust across applications. **Software Design & Code Quality** is a substantial secondary subject because interface and error design are explicit teaching goals. The presence of async, unsafe and embedded chapters does not automatically justify indexing this broad language book in every related subject.

Independent educational evidence is unusually concrete: a Johns Hopkins instructor lists the exact book and acknowledges adapting lecture/homework examples from it [G3]. A VSB Technical University course record lists the 2021 book as recommended literature, with the course appearing in2026/27 study plans [G4]. Neither document proves that every chapter is mandatory or that learning outcomes were measured.

## Present-day relevance and dated material

The sample's emphasis on borrowing, lifetimes and interface boundaries remains useful, while contemporary Rust contracts are needed for implementation details [G2, G6–G8]. Important first-edition corrections remain visible in the author's ledger: the p9 reference/drop statement, p156 pointer-mutability discussion, p158 initialized-length count and p202 nullable-pointer representation are not cosmetic errors [G5]. Read the errata alongside unsafe/FFI examples rather than copying an unidentified printing unchanged.

Current `Vec::set_len` documentation requires both a length within capacity and initialization of newly included elements. Current `Option` representation guarantees apply to specified types such as `NonNull`, not arbitrary raw-pointer options [G6–G7]. The errata page's `NotNull` spelling must not be propagated as the modern standard-library type name. These checks establish specific correction boundaries, not a proof of all examples.

Language evolution also matters: Rust2024 warns by default about unsafe operations lacking explicit unsafe blocks inside unsafe functions [G8]. Async functions in traits became available after this book's publication, but current trait-object dispatch restrictions still need separate treatment [G9–G10]. A2021 explanation should not be treated as the complete2026 async feature map.

## Limitations and alternatives

This is broad advanced-language guidance, not a production backend project or a synchronization-library correctness certificate. Compared with [Rust Atomics and Locks](bos-rust-atomics-and-locks-1.md), its distinct value is wider library/interface and project practice; Bos concentrates on constructing synchronization primitives. [Zero To Production in Rust](palmieri-zero-to-production-in-rust-2022.md) is the better subject fit for a guided HTTP/backend implementation. The uncounted [Programming Rust candidate](blandy-orendorff-tindall-programming-rust-3.md) addresses a wider foundations-to-reference role, but its new edition's evidence cannot be borrowed from older reviews.

No exercises, compiler migrations or unsafe examples were executed. Corrections are a condition of responsible use, not an availability restriction. A2026 learner review was also inspected during research, but its technical notes contain errors; it is not used as the authority for Rust semantics or as a substitute for the educational evidence.

## Edition and errata check

The publisher identifies Jon Gjengset, November2021,280 pages and paperback ISBN9781718501850; it explicitly describes PDF, EPUB and Mobi formats [G1]. The printed ISBN is not assigned to an ebook subtype. The author's errata contain reports through2026, but report dates do not establish when every distributed copy was corrected [G5]. A bounded official-site search found no substantiated newer edition; this is not proof that no future edition exists.

## Evidence ledger

All sources accessed **2026-10-16**; source dates are separate below.

| ID | Exact source and inspected locator | Source date / evidentiary scope |
| --- | --- | --- |
| G1 | https://nostarch.com/rust-rustaceans — identity, format description and contents | November2021 work; page update unstated. Original metadata and scope, not independent praise. |
| G2 | https://nostarch.com/download/samples/RustforRustaceans_Ch1.pdf#page=4 and #page=13 — rendered chapter1 printed pp4 and13 | 2021 original sample. Selected worked examples, not a full-book read. |
| G3 | https://osdi.dev/rust-jhu/ — extended reading and acknowledgments | Intersession2023, updated2023-01-17. Instructor's documented lecture/homework use, not a2026 syllabus. |
| G4 | https://edison.sso.vsb.cz/cz.vsb.edison.edu.study.prepare.web/SubjectVersion.faces?back=true&locale=en&studyFormId=1&studyPlanId=25878&subjectBlockAssignmentId=539402&version=460-4157%2F01 — recommended literature, syllabus and study-plan links | Course introduced2024/25, listed in2026/27 plans; page update unstated. Recommended reading, not mandatory full-text assignment. |
| G5 | https://rust-for-rustaceans.com/ — complete retrieved errata ledger, especially pp9,156,158,202 | Individual reports2021–2026; overall update/copy-correction dates unknown. Original author corrections. |
| G6 | https://doc.rust-lang.org/std/vec/struct.Vec.html#method.set_len — Safety | Current standard-library contract; page publication/update date unstated. Only targeted API section inspected. |
| G7 | https://doc.rust-lang.org/std/option/index.html#representation — guaranteed representations | Current standard-library contract; update date unstated. Does not guarantee every `Option<T>` layout. |
| G8 | https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html — migration and lint behavior | Current edition guide; update date unstated. Warning behavior, not an unconditional compile-error claim. |
| G9 | https://blog.rust-lang.org/2023/12/21/async-fn-rpit-in-traits/ — stabilization announcement and examples | 2023-12-21. Historical feature introduction; roadmap is not current status. |
| G10 | https://doc.rust-lang.org/reference/items/traits.html#dyn-compatibility — dispatchable method restrictions | Current Reference; update date unstated. Current limitations checked separately. |

## Next review

A later invocation must independently inspect this published record, revisit the material unsafe/FFI errata, and inspect another substantive original chapter. Check whether a newer edition has appeared without automatically preferring it. Preserve the distinction between independent course use, publisher testimonials and verified technical contracts. Review remains **pending**.
