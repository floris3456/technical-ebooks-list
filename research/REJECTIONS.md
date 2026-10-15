# Rejections and corrective decisions

Claim-level corrections are distinct from work-level non-selections. [UNSELECTED.md](UNSELECTED.md) retains deferred, rejected or retired works; no acquisition-based exclusion is permitted.

## Preserved history

[Decisions through f215171](REJECTIONS-through-f215171.md) preserves the previous ledger byte-for-byte, including its link to earlier R001–R047 decisions. These same-directory copies retain valid relative links. No previous decision is silently deleted.

## Cycle 2026-10-15-01

| ID | Decision | Compact reason / evidence |
| --- | --- | --- |
| R062 | Do not transfer publisher praise across editions | [Eloquent JavaScript publisher page](https://nostarch.com/eloquent-javascript-4th-edition) labels its reviews as third-edition reviews. Fourth-edition inclusion instead uses original text and exact-edition course adoption. |
| R063 | Preserve syllabus metadata conflict | [Santa Rosa PDF](https://portal.santarosa.edu/SrWeb/SR_DisplayDocument.aspx?SectionDocumentID=13469#page=1) has Spring 2026 in its rendered body, despite Spring 2025 metadata. Rendered textbook and schedule pages were checked; do not conceal the mismatch. |
| R064 | Separate browser-work adoption and publication dates | [UW Spring 2023](https://courses.cs.washington.edu/courses/cse493x/23sp/) adopts the online work, not the later Oxford print edition. [Oxford](https://academic.oup.com/book/59224) distinguishes December 2024 electronic and January 2025 print publication. No exact text equivalence or 2026 UW course is asserted. |
| R065 | Do not mistake a teaching browser for a production browser | [Original scheduling chapter](https://browser.engineering/scheduling.html) and [omissions appendix](https://browser.engineering/skipped.html) acknowledge simplified scheduling, memory leaks and omitted security/layout/test machinery. Retain those limits in the recommendation. |
| R066 | Preserve FoDE counterevidence and retrieval limits | The [reopened review](https://greyskullanalytics.com/blog/book-review-fundamentals-of-data-engineering) has an affiliate disclosure and questions universal real-time processing. The Tartu re-fetch failed; existing course evidence is not described as freshly verified. [Confirmed errata](https://www.oreilly.com/catalog/errata.csp?isbn=9781098108304) remain explicit. |
| R067 | Retain Python TDD third edition as deferred | [Original preface](https://www.obeythetestinggoat.com/book/ai_preface.html) is author opinion; targeted search did not produce inspected independent third-edition evaluation/adoption. [UNSELECTED.md](UNSELECTED.md) records the exact evidence gap, not a poor-quality verdict. |
| R068 | Read the actual older accessibility guidance | [Kalbag's label/input section](https://accessibilityforeveryone.site/accessibility-and-html/) already requires structural association, consistent with [WAI labeling](https://www.w3.org/WAI/tutorials/forms/labels/). Retain its qualified prior assessment; no extra approval or blanket compliance claim. |
| R069 | Test environments have fidelity limits | [Flask active contexts](https://flask.palletsprojects.com/en/stable/testing/) omit dispatch behavior unless invoked; [Vitest Browser Mode](https://vitest.dev/guide/browser/) has module-spy and dialog constraints. These qualify modern use of legacy testing methods, not invalidate their central value. |

No recommendations were removed this cycle. Two new records remain pending; two earlier records passed later-run review. Exact attempts and failures are in [the source audit](sources/2026-10-15-01/README.md).
