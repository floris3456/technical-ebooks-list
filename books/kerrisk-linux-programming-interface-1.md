---
work_id: kerrisk-the-linux-programming-interface
title: "The Linux Programming Interface: A Linux and UNIX System Programming Handbook"
authors: ["Michael Kerrisk"]
edition: "First edition (October 2010); printing-specific author errata checked in 2026"
publication_year: 2010
isbn_by_format: {}
primary_subject: platform-specific-development
additional_subjects: [computer-systems-and-operating-systems, networking-apis-and-integration]
concepts: [system-calls, file-descriptors, process-control, unix-signals, posix-threads, ipc, sockets, linux-api]
languages: [C]
technologies: [Linux, POSIX]
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: [pdf, epub]
access: unknown
official_url: "https://nostarch.com/tlpi"
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# The Linux Programming Interface — first edition (2010)

## Recommendation and audience

**Recommend to intermediate C programmers building or maintaining Unix/Linux userspace applications who need to understand the operating-system API, its contracts and portability limits.** Know pointers, C compilation and basic Unix shell work first. This is a substantial task-focused reference with worked examples, not a first programming textbook or a promise of currently runnable unmodified 2010 examples. Inspected three **publisher-original sample chapters**, publisher contents, contemporary university teaching, firsthand critical reviews, printing-specific errata and modern primary documentation. Neither all 64 chapters nor an executed exercise suite was inspected.

The publisher identifies **Michael Kerrisk**, **October 2010**, first edition, and hardcover ISBN 9781593272203; that number is **not** recorded as an ebook-specific ISBN. Official PDF/EPUB formats are described without treating acquisition as a selection criterion. A completed newer edition was not established from the sources inspected; ongoing 2026 errata are **not** a second edition. [S1], [S2]

## Substantive contents and classification

The detailed publisher TOC covers file I/O and descriptors, processes and signals, virtual memory, POSIX threads, System V and POSIX IPC, terminals, daemons and networking. In the actual chapter **4**, the introductory `open`/`read`/`write`/`close` copy program (printed p.71) demonstrates descriptor-level I/O; it **treats a partial write as an error** instead of a general retry loop, so this instructional demonstration is not a production-copy recipe. Chapter **24** (printed p.515) makes the process/fork/exec/wait lifecycle concrete; chapter **52** (printed p.1066) distinguishes POSIX message-queue descriptor close from name unlink. These are original passages, not just TOC assertions. [S1], [S3]–[S5]

**Primary: Platform-Specific Development.** Its overriding learning objective is writing Linux/Unix applications using the exposed platform APIs, whereas [Computer Systems: A Programmer's Perspective](bryant-ohallaron-computer-systems-programmers-perspective-3.md) studies the C-to-hardware and memory model and [Operating Systems: Three Easy Pieces](arpaci-dusseau-ostep-1-10.md) studies mechanisms inside an operating system. Sustained processes/filesystems and multiple socket/API chapters warrant **Computer Systems & Operating Systems** and **Networking, APIs & Integration** as secondary routes. They are links to this single record, not additional recommendations.

## Independent judgment and documented adoption

Jake Edge's **2011-01-19** firsthand critical analysis values the reference breadth and portable standards exposition while flagging awkward placement of alternative I/O methods and notably thin coverage of **ptrace, namespaces and container-related mechanisms**. His assessment pertains to the original book and cannot vouch for today's kernel details. Federico Lucifredi's **2010-11-08** firsthand technical review, written by a Unix man-page practitioner, independently praises short self-contained API chapters and Linux/UNIX standards mapping, but notes the missing man-page-authoring tutorial and compares the book to the more tutorial-oriented *Linux Application Development* (2004). These are evaluations, not controlled teaching outcomes. [S6], [S7]

**William & Mary CSCI415/515 Fall 2026** explicitly assigns many individual Kerrisk chapters and integrates systems-programming labs. A **TUM summer 2021** course also identifies Kerrisk alongside other systems references; this is older adoption, not 2026 proof. Modern syllabus use demonstrates continued educational value without certifying every call signature or example. [S8], [S9]

## Remaining usefulness and current limits

Core **file descriptor ownership, process creation, address spaces, error handling, threading, synchronous IPC, Unix sockets and POSIX semantics** remain practically important. The current Debian open(2) reference discusses `O_CLOEXEC` race prevention with concurrent exec, `openat`/`openat2` and `O_TMPFILE`; Linux kernel userspace API documentation includes modern futex, seccomp, Landlock and namespace interfaces. These are 2026-era **technical counterchecks**, not claims that the original text already describes newer APIs. [S10], [S11]

The book was written around **Linux 2.6.35/glibc 2.12**, as its period reviewer observes. Historic features, compatibility macros, paths and vendor-specific examples need revalidation before deployment. Author corrections updated **2026-09-12** include `_BSD_SOURCE` to `_DEFAULT_SOURCE`, kernel-path and example corrections; verify the particular printing, and do not treat an actively maintained errata list as a revised edition. The omission of modern container security, io_uring, eBPF, tracing or production-safe sandbox composition makes contemporary manuals and targeted books necessary for those topics. **Availability, price, print status and geography played no role.** [S2], [S6], [S10], [S11]

## Edition/errata and alternatives

No edition-specific full audit was performed. The original author's correction list identifies specific printings and newly queued fixes; an original chapter's simplified copy tool does not establish correct retry-on-short-write behavior for arbitrary devices. Compare with CSAPP for machine-level representation and with OSTEP for kernels, plus official Linux manuals for versioned calls. No exercise or example was executed; no broad claim that 2010 code runs unchanged was made.

## Evidence ledger

**Each URL accessed 2026-10-16 (Europe/Amsterdam).** Publication/revision dates below are separate; unknown update dates remain unknown. PDF inspection included selected rendered pages only.

| ID | Exact URL / original material inspected | Original date and evidence role |
| --- | --- | --- |
| S1 | [No Starch publisher](https://nostarch.com/tlpi), title, bibliographic block, TOC and formats | Oct 2010; identity/scope, not independent quality |
| S2 | [Author printing-specific errata](https://kerrisk.com/tlpi/errata/errata_by_print_run.html), introductory notes, pp.9,44,46,62,165,241; queued fixes | Last updated **2026-09-12**; correction scope varies by printing |
| S3 | [Original sample ch4](https://nostarch.com/download/samples/LinuxProgrammingInterface_Chapter4_Updated.pdf#page=3), printed p.71, §4.1–4.3 and copy example | Original 2010 sample; selected rendered pages, not whole text |
| S4 | [Original sample ch24](https://nostarch.com/download/samples/LinuxProgrammingInterface_Chapter24_Updated.pdf#page=5), printed p.515, process lifecycle | Original 2010 sample; selected rendered page |
| S5 | [Original sample ch52](https://nostarch.com/download/samples/LinuxProgrammingInterface_Chapter52_Updated.pdf#page=5), printed p.1066, queue close/unlink semantics | Original 2010 sample; selected rendered page |
| S6 | [Jake Edge at LWN](https://lwn.net/Articles/423417/), complete original assessment and missing-topic critique | **2011-01-19**, independent firsthand |
| S7 | [Federico Lucifredi at Slashdot](https://books.slashdot.org/story/10/11/08/1430238/The-Linux-Programming-Interface), reviewer/byline and entire original review | **2010-11-08**, independent firsthand |
| S8 | [William & Mary Fall 2026 syllabus](https://www.cs.wm.edu/~smherwig/courses/csci415-f2026/index.html), chapter assignments/labs | **Fall 2026**, exact-work educational adoption |
| S9 | [TUM advanced systems programming](https://dse.in.tum.de/advanced-systems-programing-sose2021/), reading/course materials | **Summer 2021**, older educational use |
| S10 | [Debian open(2) reference](https://manpages.debian.org/unstable/manpages-dev/open.2.en.html), `O_CLOEXEC`, `openat2`, `O_TMPFILE` | Live current branch; exact update unknown; not a book review |
| S11 | [Linux kernel userspace API guide](https://www.kernel.org/doc/html/latest/userspace-api/index.html), security, system calls, I/O sections | Live guide, date unknown; scope of omitted modern interfaces |

## Next review

**Pending genuinely later-run scrutiny.** Read chapter 4 error and short-write semantics more fully; verify printing-specific corrections against another original sample, assess chapter-coverage classification and independent reviewers' expertise, and check modern kernel/glibc current interfaces by version. No same-run pass, whole-book read, live code benchmark or final collection audit is implied.
