---
work_id: nystrom-crafting-interpreters
title: "Crafting Interpreters"
authors: ["Robert Nystrom"]
edition: "2021 publication; printing not verified"
publication_year: 2021
isbn_by_format: {}
primary_subject: programming-language-theory-and-compilers
additional_subjects: []
concepts: [interpreters, scanning, parsing, bytecode, virtual-machines]
languages: [Java, C]
technologies: []
difficulty: intermediate
focus: [practical, conceptual]
formats: [web]
access: unknown
official_url: "https://craftinginterpreters.com/"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "c1251db102898b3acc3c8ffec259153ae2dc0711"
---

# Crafting Interpreters — 2021 publication

**Recommend** for programmers learning how scanners, interpreters and bytecode virtual machines work by building them. The author's chapters have now been inspected directly through the original source repository, beyond the previous course references. It is a practical Java/C language-implementation book, not a Rust textbook or an exhaustive formal compiler theory treatment.

## Inspected evidence

Portland State's Winter 2026 Essentials of Compilation course lists Robert Nystrom's *Crafting Interpreters* (2021) among other useful references. Its main text is Jeremy Siek's *Essentials of Compilation*, not Nystrom's book. This is supplementary educational recommendation, not evidence that the whole course follows this work. [S1]

The University of San Francisco's Spring 2026 Rust/scanning lecture recommends the work in Further Reading for scanners and parsers. The lecture's learning objectives and scanning material make that subject connection concrete. They are not proof that the book teaches Rust, and Rust is deliberately not added as a book-language tag. [S2]

These sources support a provisional compiler/interpreter subject fit and a reason to investigate current usefulness. They do not establish the book's complete contents, exact printing, all prerequisites, limitations, errata, or comparative quality.

## Author chapter inspection and present-day fit (2026-10-14)

The original author's GitHub repository contains actual book manuscripts and implementations. The **Introduction** describes two interpreter implementations and explicitly prioritizes hands-on techniques over formal theory. The **Scanning** chapter explains character-to-token conversion and scanner/error-handling scaffolding in Java. The **A Virtual Machine** chapter builds bytecode execution in C and explicitly warns that its convenient single global VM is not ideal for embedded or multiple VM instances. Those concrete chapter excerpts establish the subject, prerequisites, technical substance, and a limitation; none imply every chapter or every exercise was completed. [S3], [S4], [S5]

Portland State's Winter 2026 course **assigns Nystrom chapters 2 and 15 on March 3**, more substantive adoption than a passive reference list. It still uses Siek's *Essentials of Compilation* as its main book. The University of San Francisco Spring 2026 lecture lists Nystrom as scanner/parser further reading, not Rust implementation. Tokenization, bytecode and VM tradeoffs remain relevant regardless of current framework fashion. [S1], [S2], [S3], [S5]

The author source is represented as an online work (web); no price/availability prerequisite or unverified edition ISBN is introduced. A subsequent-run reviewer should verify the pinned author source revision and inspect any significant errata.

## Retrieval and next actions

Earlier author-site fetches failed, but this cycle **inspected the full Markdown chapter source directly through the author's GitHub repository**. Earlier failed retrieval is not evidence of missing quality or availability.

Next run: independently review the now-inspected author's sections and current course assignments, verify exact edition/printing and errata, and compare pedagogical scope with Siek's book. Compare pedagogical scope with the Siek text named in the PSU course. Do not invent implementation-language or format metadata while that evidence remains unchecked.

## Evidence ledger

The author-book source files and two educational sources were inspected **2026-10-14**. Neither page supplied a reliable exact last-update date.

| ID | Source and inspected location | Source date/context |
| --- | --- | --- |
| [S1] | PSU course page, main-text description and Other Books/reference list | Winter 2026; Nystrom publication cited as 2021 |
| [S2] | USF CS631 Rust Programming and Scanning, Learning Objectives, Scanning, Further Reading | Spring 2026, lecture dated 2026-01-29 by page path; footer alone is not an update date |
| [S3] | Author book/introduction.md, opening purpose and Why Learn This Stuff? | Book source; revision date not stated |
| [S4] | Author book/scanning.md, scanner introduction, Interpreter Framework, Error Handling | Book source; revision date not stated |
| [S5] | Author book/a-virtual-machine.md, Instruction Execution Machine, single-VM limitation | Book source; revision date not stated |
| [S6] | Author repository README, book prose and two interpreter codebases and testing | Repository snapshot; update date not established |

[S1]: https://web.cecs.pdx.edu/~apt/cs510comp/
[S2]: https://cs631-s26.cs.usfca.edu/lectures/01-cs631-2026-01-29-rust-scanning/

The author's original Markdown chapters, rather than failed HTML site fetches, are the source for the inspected technical content. Three author-source chapter documents, an author-repository overview and two independent 2026 university references are now inspected. The three-document threshold is met without treating search snippets as inspected evidence.

[S3]: https://github.com/munificent/craftinginterpreters/blob/4a840f70f69c6ddd17cfef4f6964f8e1bcd8c3d4/book/introduction.md
[S4]: https://github.com/munificent/craftinginterpreters/blob/4a840f70f69c6ddd17cfef4f6964f8e1bcd8c3d4/book/scanning.md
[S5]: https://github.com/munificent/craftinginterpreters/blob/4a840f70f69c6ddd17cfef4f6964f8e1bcd8c3d4/book/a-virtual-machine.md
[S6]: https://github.com/munificent/craftinginterpreters

## Subsequent-run review (2026-10-14)

Independently reviewed the committed promotion in `c1251db102898b3acc3c8ffec259153ae2dc0711`. Via the native GitHub connector, the author's exact pinned revision `4a840f70f69c6ddd17cfef4f6964f8e1bcd8c3d4` was fetched, including complete `book/introduction.md`, `book/scanning.md`, and `book/a-virtual-machine.md`. They substantiate two implementations, Java token scanning and the deliberately simplified global C VM (not production guidance for multiple VM instances). Portland State Winter 2026 **assigns chapters 2 and 15** while naming Siek's *Essentials of Compilation* its main text. USF further reading supports the scanner topic without implying Rust instruction. Edition printing and complete errata remain unknown, not grounds for rejecting the underlying work. **Decision: pass with these limits.** [S1], [S2], [S3], [S4], [S5]

## Next review

Review printing/errata changes and compare hands-on interpreter goals with Siek's more formal compiler curriculum. Later-run review passed; final audit remains.
