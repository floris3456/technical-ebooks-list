---
work_id: winters-manshreck-wright-software-engineering-at-google
title: "Software Engineering at Google"
authors: ["Titus Winters", "Tom Manshreck", "Hyrum Wright"]
edition: "2020 O'Reilly edition"
publication_year: 2020
isbn_by_format: {}
primary_subject: software-engineering-practices-and-collaboration
additional_subjects: [software-testing-and-quality-assurance, software-maintenance-and-legacy-systems]
concepts: [code-review, automated-testing, knowledge-sharing, technical-debt]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://abseil.io/resources/swe-book"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "c1251db102898b3acc3c8ffec259153ae2dc0711"
---

# Software Engineering at Google — 2020

## Recommendation and audience

**Recommend for developers, reviewers and technical leads learning to maintain software over years and across teams.** O'Reilly identifies a March 2020 book by Titus Winters, Tom Manshreck and Hyrum Wright; the author-backed Abseil site publishes individual chapters. Prior engineering experience helps contextualize scale and process choices. This assessment inspected substantial chapter text, an independent analysis and current public guidance; it does not claim a full-book reading. [S1], [S2]

## Contents and classification

The book's *Testing Overview* (chapter 11) explains observable test behavior and how automated testing supports safe change. *Test Doubles* (chapter 13) examines why mock objects and fakes require judgment, rather than treating every test-double pattern as universally beneficial. Code review, knowledge sharing, team collaboration and long-lived codebases make **Software Engineering Practices & Collaboration** the primary subject; sustained chapters justify testing and maintenance as additional subjects. [S2], [S3], [S4]

## Why it remains useful today

Independent reader analysis (last updated December 18, 2024) examines the book's perspectives on code review, documentation, testing and engineering culture; its author explicitly presents an interpretation rather than personal experience working at Google. Google's publicly maintained engineering-practices guide continues to describe review standards and improving code quality. These sources corroborate ongoing *topic relevance*, not that Google's internal procedures are unchanged in 2026. [S5], [S6]

## Limitations and alternatives

Many practices are context-dependent on Google's historical organization, monorepo and tooling. The 2020 work does not systematically discuss 2026 coding-agent review risks. It is less focused than a testing-specific manual and less about system structure than a dedicated architecture book. Its independent reader analysis is useful criticism, not empirical proof of practices' effectiveness. No exhaustive errata review was performed; price or ebook accessibility did not affect selection. [S1], [S3], [S5]

## Evidence ledger

All documents inspected **2026-10-14**; access date does not imply recent publication.

| ID | Source and inspected location | Source date |
| --- | --- | --- |
| [S1] | O'Reilly book listing, authors and date | March 2020 |
| [S2] | Abseil resource page, chapter index | Original work 2020; page update unknown |
| [S3] | Book chapter 11, Testing Overview, Why Do We Write Tests? | 2020 work; page update unknown |
| [S4] | Book chapter 13, Test Doubles, introductory examples and tradeoffs | 2020 work; page update unknown |
| [S5] | The Code She Writes, reading notes on reviews, teams, documentation, testing | Updated 2024-12-18 |
| [S6] | Google engineering practices, Standard of Code Review | Page update unknown; accessed 2026-10-14 |
| [S7] | Cornell CS5150 Spring 2026 syllabus, Materials & services: several readings from this book | Spring 2026; exact syllabus update unknown |
| [S8] | Dr Milan Milanović independent detailed reading analysis, sections on reviews, testing and long-lived code | Published 2026-02-26 |
| [S9] | Javin Paul independent practical assessment, strengths and "What could have been done better?" | Published 2025-09-02 |

[S1]: https://www.oreilly.com/library/view/software-engineering-at/9781492082781/
[S2]: https://abseil.io/resources/swe-book
[S3]: https://abseil.io/resources/swe-book/html/ch11.html
[S4]: https://abseil.io/resources/swe-book/html/ch13.html
[S5]: https://thecodeshewrites.com/2024/05/12/software-engineering-at-google-book-takeaways/
[S6]: https://google.github.io/eng-practices/review/reviewer/standard.html
[S7]: https://www.cs.cornell.edu/courses/cs5150/2026sp/syllabus.html
[S8]: https://newsletter.techworld-with-milan.com/p/what-i-learned-at-swe-at-google-book
[S9]: https://javinpaul.medium.com/review-is-software-engineering-at-google-book-worth-it-e97091b9d5e2

## Subsequent-run review (2026-10-14)

Reviewed the published record in `c1251db102898b3acc3c8ffec259153ae2dc0711`, independently reopening the Abseil chapter substance and comparing it with additional current evidence. Cornell **Spring 2026 CS5150** explicitly assigns multiple *Software Engineering at Google* readings; this is direct modern educational use, not an assertion about unchanged internal 2020 tools. Dr Milan Milanović's 2026 analysis describes engineering-over-time, knowledge sharing, review and test doubles; Javin Paul's 2025 critique points out context-specific monorepo/tooling and missing open-source perspectives. These independent assessments and the sustained original chapters justify both testing and maintenance secondary subjects. The older 2024 reviewer link did not load for this reinspection, so was not needed for the pass. Principles are relevant; 2026 AI practices and Google policies need newer sources. **Decision: pass with transferability caveats.** [S2], [S3], [S4], [S6], [S7], [S8], [S9]

## Next review

Track evolving public review guidance, edition-specific errata and compare specialized testing/legacy engineering texts. A later-run review passed; the collection-wide final audit is outstanding.
