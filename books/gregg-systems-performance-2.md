---
work_id: gregg-systems-performance
title: "Systems Performance: Enterprise and the Cloud"
authors: ["Brendan Gregg"]
edition: "Second edition, published 2020-12-09; copyright 2021"
publication_year: 2020
isbn_by_format: {ebook-unspecified: "9780136821649"}
primary_subject: debugging-and-performance-engineering
additional_subjects: [computer-systems-and-operating-systems]
concepts: [performance-analysis, profiling, tracing, benchmarking, use-method, bpf]
languages: []
technologies: [Linux, perf, Ftrace, bpftrace]
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: [epub, pdf]
access: unknown
official_url: "https://www.informit.com/store/systems-performance-9780136821649"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "154e499e02b872a859e7ee6b641b72365dd245a9"
---

# Systems Performance — Second Edition

## Recommendation and subject fit

**Recommend to software/platform engineers diagnosing Linux and cloud performance, not as a 2026 CLI cookbook.** InformIT's [publisher listing](https://www.informit.com/store/systems-performance-9780136821649) identifies Brendan Gregg, **2020-12-09** publication, **2021** copyright and **second edition**. Electronic ISBN **9780136821649** is listed for an ebook including both EPUB and PDF; do not invent separate format ISBNs.

The legitimate [141-page original publisher sample](https://www.informit.com/content/images/9780136820154/samplepages/9780136820154_Sample.pdf#page=42) was inspected in rendered form: chapter 3 §3.2.1 printed p.91/PDF p.42 presents the kernel/system-call/hardware model (Fig 3.1); §3.2.9 printed p.105/PDF p.56 explains CPU scheduling (Fig 3.12). [O'Reilly's original chapter 2 preview](https://www.oreilly.com/library/view/systems-performance-2nd/9780136821694/ch02.xhtml) and publisher contents identify methodologies, resource diagnosis, perf, Ftrace and BPF. The preview was not treated as the full chapter. The book's diagnostic goal warrants **Debugging & Performance Engineering** primary; substantial OS, CPU, memory and filesystem foundations justify an OS secondary index, not another book.

## Independent evaluation and relevance

A firsthand [2024-01-14 practitioner review](https://blog.serizawa.me/p/2024-01-14-system-performance-2nd) reports reading the **Japanese translation of the second edition**, praising USE/RED approaches, exercises and a Netflix case study but recommending selective reading for a roughly 900-page reference. It does **not** verify English pagination or current command syntax. The author separately explains [the USE method](https://www.brendangregg.com/usemethod.html), which checks utilization, saturation and errors before blindly choosing tools; he acknowledges it is not universal. Current [Linux kernel Ftrace documentation](https://docs.kernel.org/trace/ftrace.html) confirms tracing remains relevant, but **not** that all 2020 tool flags, Linux schedulers and BPF interfaces still match. Durable diagnostic reasoning differs from dated implementation examples.

## Limitations, sources and next review

The lengthy Linux focus is less suitable for a quick language-specific profiler introduction, and OS overlap with OSTEP is conceptual, not duplication. No 928-page read, executed benchmark, full errata inspection or CLI compatibility test is claimed. Availability did not affect selection.

Evidence inspected/accessed **2026-10-14**: [S1 publisher date/TOC/ebook](https://www.informit.com/store/systems-performance-9780136821649), 2020-12-09; [S2 original ch3 §§3.2.1, 3.2.9, PDF pp.42 and 56](https://www.informit.com/content/images/9780136820154/samplepages/9780136820154_Sample.pdf#page=42), 2e; [S3 original ch2 exposed preview](https://www.oreilly.com/library/view/systems-performance-2nd/9780136821694/ch02.xhtml), 2020; [S4 independent 2024-01-14 firsthand translation review](https://blog.serizawa.me/p/2024-01-14-system-performance-2nd); [S5 author USE method](https://www.brendangregg.com/usemethod.html), update unknown; [S6 current Linux Ftrace manual](https://docs.kernel.org/trace/ftrace.html), update unknown.

## Subsequent-run independent review — 2026-10-14

**Passed after independent inspection of published commit `154e499e02b872a859e7ee6b641b72365dd245a9`.** Reopened the original [publisher chapter 3 sample](https://www.informit.com/content/images/9780136820154/samplepages/9780136820154_Sample.pdf#page=42) at **PDF pp. 42 and 56** (printed pp. 91 and 105) and checked the kernel/system-call/CPU scheduling diagrams. Revisited the [2024-01-14 firsthand second-edition translation review](https://blog.serizawa.me/p/2024-01-14-system-performance-2nd) and [current Linux Ftrace manual](https://docs.kernel.org/trace/ftrace.html). Translation review is **not** evidence of English page identity; documentation confirms tracing remains operational, **not** that all old flags or commands will work. The book is distinct from OSTEP because its dominant teaching purpose is diagnosis of live systems, not OS introduction, so its OS secondary tag remains justified. No benchmark or command was executed and no exhaustive errata audit is claimed. Decision: **pass with kernel/version and inspection caveats**.

## Next review

Passed subsequent review. Inspect later chapters on CPU and BPF, author errata and other independent evaluations, then test one dated tracing command in a pinned environment. Retain platform-specific qualifications; do not transfer kernel examples uncritically.
