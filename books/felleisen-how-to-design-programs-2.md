---
work_id: felleisen-how-to-design-programs
title: "How to Design Programs: An Introduction to Programming and Computing"
authors: ["Matthias Felleisen", "Robert Bruce Findler", "Matthew Flatt", "Shriram Krishnamurthi"]
edition: "Second edition (2018); author-hosted 2026-05-28 revision"
publication_year: 2018
isbn_by_format: {ebook-unspecified: "9780262344128"}
primary_subject: programming
additional_subjects: []
concepts: [systematic-program-design, data-definitions, function-signatures, recursion, functional-programming, examples-and-tests]
languages: [Racket]
technologies: [DrRacket]
difficulty: beginner
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://htdp.org/2026-5-28/Book/index.html"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "33f4e80a5dfd28a23b6b4b38732bfeffe46aa763"
---

# How to Design Programs — Second Edition

## Recommendation and audience

**Recommend as an unusually systematic introduction to programming through design recipes, data definitions, and testing one's functions.** It is particularly useful for beginners who want to learn *how to construct programs*, not merely Racket syntax. MIT Press identifies Felleisen, Findler, Flatt and Krishnamurthi, the **second edition** (paperback May 4, 2018; ebook May 18, 2018), and ebook ISBN **9780262344128**. The publisher does not specify a particular ebook file format for this ISBN, so the subtype remains unspecified. [S1]

The [authors' original second-edition site](https://htdp.org/2026-5-28/Book/index.html) expressly calls its **May 28, 2026** online release a version of **the second edition**, not a new third edition. This record groups it with the 2018 second-edition work and does not count a 2026 web update as a separate book. [S2]

## Original text and subject fit

The inspected original [Part I, chapter 3, §§3.1 and 3.5](https://htdp.org/2026-5-28/Book/part_one.html) teaches a design recipe: describe data, state a function's signature and purpose, make examples and tests, then derive and check a definition. The [2026 online contents](https://htdp.org/2026-5-28/Book/index.html) shows a substantial progression through structure and itemization, lists and self-reference (chs. 8–9), abstraction (chs. 14–17), and generative recursion (Part V). These chapters are worked teaching material, not a marketing synopsis. [S2], [S3]

Assign **Programming** as the primary subject. Although testing and clean structure are prominent, these are elements of its method for teaching introductory programming; the book is not a broad professional QA/testing manual, and mere overlap does not justify secondary tags.

## Independent current evidence of relevance

The previously cited Brown Fall 2026 placement page did **not** reopen; its exact chapter-assignment claim is withdrawn. The [current Brown 2026 course FAQ](https://cs.brown.edu/courses/cs019/2026/AFQ.html), *Why do we change programming languages?*, confirms using Racket to learn HtDP content; a separate [Brown 2025 placement reading list](https://cs.brown.edu/courses/cs019/2025/placement-readings.html) explicitly prescribes the **second edition** and Part II chapters 8–10. The 2025 edition assignment is not mislabeled as Fall 2026. Brown has a coauthor on staff, so course use is educational adoption, not independent critical evaluation. [S4], [S6] UBC 2026W1 mentions HtDP design methods but does not identify an edition. [S5]

The principles of describing problem data, decomposing functions and designing examples/tests are generalizable in 2026. By design, this is taught with Racket's Beginning Student language and DrRacket instead of current industrial stack APIs. iTunes and some legacy data exercises are historically situated examples, not a recommendation to use their old integrations today. The 2026 source update is evidence the material continues to be maintained, not proof that every embedded tool instruction is current. [S2], [S3]

## Limitations and comparison

Its disciplined design recipe rewards patient beginners but may feel prescriptive to experienced developers; it focuses on pure functions and progressive language levels, not production deployment, concurrency infrastructure, contemporary framework APIs, or performance engineering. It compares best with syntax-first introductory courses when the learning goal is *design process*. Neither student outcomes nor superiority over other beginners' books have been experimentally established here. No complete cover-to-cover reading, execution of all exercises, full errata audit, or live compatibility test is claimed. Price and access were not selection factors.

## Evidence ledger

All sources below inspected/accessed **2026-10-14**, separating document dates from retrieval.

| ID | Source and inspected section | Source date |
| --- | --- | --- |
| [S1] | [MIT Press second-edition listing](https://mitpress.mit.edu/9780262534802/how-to-design-programs/), Authors, Paperback/eBook ISBN and publication dates, Description | May 2018 second edition |
| [S2] | [Authors' second-edition page](https://htdp.org/2026-5-28/Book/index.html), title, named authors, explicit release date and chapter outline | Release May 28, 2026 |
| [S3] | [Original Part I](https://htdp.org/2026-5-28/Book/part_one.html), ch.3 §§3.1 and 3.5; examples and tests | Author-hosted second-edition revision, 2026-05-28 |
| [S4] | [Brown Fall 2026 CSCI 0190 FAQ](https://cs.brown.edu/courses/cs019/2026/AFQ.html), *Why do we change programming languages?* | Fall 2026, updated date unknown |
| [S5] | [UBC 2026W1 assignments](https://www.students.cs.ubc.ca/~cs-311/2026W1/nav/assignments.html), HtDP reading/design recipe references | 2026W1; exact edition not specified |
| [S6] | [Brown 2025 placement readings](https://cs.brown.edu/courses/cs019/2025/placement-readings.html), *second edition*, Part II chs.8–10 | 2025; exact edition, not current-year assignments |
| [S7] | [Original Part II chapters 8–9](https://htdp.org/2026-5-28/Book/part_two.html), recursive data/template/testing in §9 | Author web revision 2026-05-28 |

## Subsequent-run independent review — 2026-10-14

**Passed with corrections after reviewing published commit `33f4e80a5dfd28a23b6b4b38732bfeffe46aa763`.** Original [Part II §9](https://htdp.org/2026-5-28/Book/part_two.html) derives a natural-recursion template from a self-referential list definition, covering empty/cons cases, function contracts, examples and tests. [MIT Press](https://mitpress.mit.edu/9780262534802/how-to-design-programs/) confirms edition and eISBN. The older cited 2026 Brown assignment deep link failed retrieval; the accessible 2026 course FAQ plus 2025 exact-edition list replace the overstated claim. The Racket instructional approach remains relevant; legacy APIs and some dated exercises are not current integration guidance. No exercises were executed and no comprehensive errata audit was done.

## Next review

**Subsequent-run review passed.** Re-examine original Part II chapters 8–9 and formal test recipe against Brown assignments; check errata/version differences between the 2018 print and author-hosted 2026 text. Seek an independent expert critical assessment beyond university use. Do not count the online revision as a second work.
