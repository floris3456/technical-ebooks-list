---
work_id: jorgensen-software-testing-a-craftsmans-approach
title: "Software Testing: A Craftsman's Approach"
authors: ["Paul C. Jorgensen", "Byron DeVries"]
edition: "Fifth edition"
publication_year: 2021
isbn_by_format: {}
primary_subject: software-testing-and-quality-assurance
additional_subjects: []
concepts: [boundary-value-testing, equivalence-partitioning, decision-tables, graph-testing, integration-testing, model-based-testing]
languages: [Java]
technologies: [JUnit]
difficulty: intermediate
focus: [conceptual, practical]
formats: []
access: unknown
official_url: "https://www.softwaretestcraft.com/"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Software Testing: A Craftsman's Approach — Fifth Edition (2021)

## Recommendation and audience

**Qualified recommendation for systematic test-design study**, especially developers/test engineers with basic programming and mathematical-model experience. This is not primarily a contemporary JUnit setup guide: its distinctive value is designing tests using boundaries, partitions, code-path graphs and model-based techniques. Fifth-edition authors Paul C. Jorgensen and Byron DeVries use a running *Foodies Wish List* application and Java/JUnit. [S1], [S2]

This assessment inspected the authors' detailed fifth-edition technical outline and exercise instructions, explicit university fifth-edition teaching appraisal/adoption, and a newer professional syllabus. **Full fifth-edition prose and exercises have not been personally read or executed**; that limitation remains for subsequent review.

## Actual subject coverage

The fifth-edition official outline describes normal/robust/worst-case boundary-value testing (chapter **5**), equivalence partitioning with *Triangle* and *NextDate* (chapter **6**), decision tables and cause-effect (chapter **7**), code-flow graphs and basis paths (chapter **8**), and dataflow and JUnit test doubles (chapter **9**). Chapters **12–14** cover integration, system and model-based testing. Chapters **17–19** include feature interactions, event-driven systems such as a garage-door controller and pairwise tests. The authors' accompanying *Spreadsheet Exercises* explain comparing naïve, specification-based and code-driven ways to derive tests for Triangle/NextDate; that explanation was inspected, **not** executed. These topics justify the single testing primary subject and the listed facets. [S2], [S3]

## Why the theory is still useful today

The independent **ISTQB CTFL v4.0.1 syllabus dated 2024-09-15, §4.2 printed pp.39–42 and §4.3** continues to cover equivalence partitioning, boundaries, decision tables, state transitions and white-box coverage. That independently supports present-day *conceptual* applicability of the corresponding fifth-edition outline, not that Java examples or legacy test frameworks reflect 2026 best practices. [S2], [S5]

## Expert adoption and critical limits

University of Kansas professor **Hossein Saiedian's Fall 2022 software quality-assurance course** explicitly names **Jorgensen and DeVries, fifth edition 2021**, commends its **graph models, case studies and integration testing**, and includes it as a selected supporting reading. Pezzè and Young is listed as the primary text. This is **edition-specific independent teaching assessment**, not proof the book is universally best or exhaustively taught. [S4]

**Important bibliographic conflict:** this university course refers to “chapter 8: Path Testing” while the authors' fifth-edition outline titles chapter 8 **Code-Based Testing** (including *Basis Path Testing*). The syllabus can corroborate educational use but cannot serve as definitive fifth-edition chapter navigation. Reviews describing 2013 editions were explicitly **not** used to evaluate fifth-edition revisions. [S2], [S4]

Strength: explicit design techniques, including uncommon event/interaction models. Limitations: mathematical density, narrower focus than a comprehensive modern automation/CI reference, uncertain currency of framework commands. For alternatives compare Pezzè/Young and Ammann/Offutt in a later cycle. Ebook availability, print status and price had no influence.

## Edition and corrections

Authors and Kansas identify fifth edition **2021**. No format-specific ISBN, complete fifth-edition corrections ledger or hands-on execution was established; no identifiers are invented. A subsequent run should inspect actual fifth-edition book prose and look for significant errata before passing review.

## Evidence ledger

Accessed **2026-10-14**; source dates below are publication dates where known, not access timestamps.

| ID | Exact inspected material | Source date |
| --- | --- | --- |
| [S1] | Authors' fifth-edition homepage, edition/authors/Java-JUnit changes | Work 2021; page update unknown |
| [S2] | Authors' detailed fifth-edition *Outline*, chapter 5–9, 12–14, 17–19 headings and examples | Fifth edition 2021; page update unknown |
| [S3] | Authors' *Spreadsheet Exercises*, first sections describing approaches and Triangle/NextDate | Fifth-edition companion; update unknown |
| [S4] | Kansas software-quality course by Hossein Saiedian, *Textbooks* and fall assignments | Fall 2022 |
| [S5] | ISTQB CTFL Syllabus v4.0.1, §4.2 printed pp.39–42 and §4.3 | 2024-09-15 |

[S1]: https://www.softwaretestcraft.com/
[S2]: https://www.softwaretestcraft.com/outline
[S3]: https://www.softwaretestcraft.com/spreadsheet-exercises
[S4]: https://people.eecs.ku.edu/~saiedian/Teaching/814/
[S5]: https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf#page=40

## Next review

**Pending independent subsequent-run assessment**, not self-approved. Read fifth-edition original prose or practical sample, check course-syllabus version mismatch, significant errata and a competing test-design book. Demote if edition-specific assessment proves materially incomplete.
