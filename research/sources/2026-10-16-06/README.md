# Cycle 2026-10-16-06 — algorithms comparison and review audit

All access dates: **2026-10-16, Europe/Amsterdam**. Original source dates are separate. The [initial review](000-review.md) and **26 external retrieval logs, 001–026**, were committed before subsequent retrieval batches. Logs include failures, incidental search collisions, partial reads, original PDF renders and contrary evidence. No entire-book reading, compiler test, benchmark or solver run is claimed.

## Review and coordination

Started from main **f164164656102f2381ad7548993f616b13792774**. Reviewed live README, TAXONOMY, BOOK_TEMPLATE, STATE, source/decision ledgers, latest validation commit, pending Bos/Gjengset/Palmieri records and the older CLRS record. Algorithm design had only one primary recommendation; four different teaching approaches were investigated instead of treating all overlapping textbooks as duplicates or padding the count.

The separate cycle05 storage/Rust WIP at **0d4441ac7793388c7304252cd6fc09673415db66** was observable at the start. Publication preparation found main advanced to **b1f414261241f2540ceefe559ee201a793a43295**, eight commits ahead with only eight added cycle05 logs. All eight saved logs were read or re-read; their exact Git blobs are preserved. They add no recommendation and receive no credit as this cycle's external research. The saved Gjengset p207/p235 corrections and Petrov MIT chapter-assignment lead are retained as next checks, not independently revalidated from those underlying sources here. No unpublished work was assumed.

## Four substantial candidate outcomes

| Work | Distinct teaching role and evidence | Decision |
| --- | --- | --- |
| [Algorithms — Dasgupta/Papadimitriou/Vazirani](../../../books/dasgupta-papadimitriou-vazirani-algorithms-2006.md) | Compact conceptual course; rendered author cover, preface, chapter6 dependency/LIS examples and first-edition errata; required work in Fall2026 Georgia Tech syllabus; current graph contracts | Recommend explicitly identified July2006 author text with draft/print and signed-product qualifications. Work-level adoption does not establish exact draft assignment. Pending later review. |
| [The Algorithm Design Manual — Skiena3e](../../../books/skiena-algorithm-design-manual-3.md) | Practical problem recognition and technique catalog; rendered original3e insertion-sort example, full author modeling excerpts, significant errata, independent exact3e supplementary-course use | Recommend with limited original3e sample scope, web/print distinction and numeric/code cautions. Pending later review. |
| [Algorithm Design — Kleinberg/Tardos1e](../../../books/kleinberg-tardos-algorithm-design-1.md) | Problem-driven design arguments; verified publisher identity/TOC, independent current recommended reading and earlier partial-course use | Strong canonical candidate, uncounted: original worked technical argument and relevant errata not sufficiently inspected. |
| [Algorithms — Sedgewick/Wayne4e](../../../books/sedgewick-wayne-algorithms-4.md) | Complete Java implementations and empirical analysis; original author preface, detailed TOC, independently required4e and actual chapter assignments | Strong canonical candidate, uncounted: substantive original implementation and corrections still need inspection. |

The two non-selections remain in [UNSELECTED](../../UNSELECTED.md); insufficient evidence is not a poor-quality or availability verdict. Four candidates did not require four approvals. None was selected because it is newer or free.

## Review results

**Bos:** qualified later-run review of the recommendation published in **ba27c63a3dbc093ceb91dc96a529f8fae76fd059**. Fresh ch4/ch9 reads confirm the specific guard and counter repairs; fresh ch3 explains release ordering but exposes a Rust2024 static-mut-reference migration boundary. Current Sync/Ordering/edition contracts and a full re-read of Westbrook's2024 critique support a qualified pass, not a production-lock proof or every-printing certification. Logs022–026 retain exact inspection limits.

**CLRS rotation:** rendered the original binary-search solution again and inspected a newly found2024–25 exact4e course syllabus. The errata interface still does not expose a complete selected correction list, and the JHU reopening failed. Earlier qualified pass retained; no fresh full-book clearance. Gjengset and Palmieri remain pending, not silently approved.

## Twenty conservative new website families

Newness is against the inspected persisted baseline and observable saved work, not unknowable unrecorded browsing. Related author/institution sites and subdomains are grouped. A dated old source can contribute useful evidence without becoming current normative guidance. Twenty substantive families below remain after withholding several debatable ecosystems. Their roles are not interchangeable: a technical manual is not an independent book endorsement.

| # | Family and exact representative source | Actually inspected / source date | Logs |
| --- | --- | --- | --- |
| 1 | https://www.algorist.com/problems/Shortest_Path.html and https://www3.cs.stonybrook.edu/~skiena/algorist/book/errata-adm3 | Full problem excerpt and material3e correction rows; excerpt revision unknown, last errata addition2026-01-09. Author/Stony Brook sites counted once. | 003,007,012,015,017 |
| 2 | https://www.cs.sfu.ca/~ishinkar/teaching/fall26/cmpt225/syllabus.html | Full course scope, grading and optional SW reading; Fall2026. | 003 |
| 3 | https://www.salleurl.edu/en/programacion-avanzada-y-estructura-de-datos-2 | Contents, teaching, assessment and exact-edition supplementary reading; syllabus date unknown, adjacent news not a date. | 007 |
| 4 | https://sedgewick.io/books/algorithms/ | Original preface's data abstraction, executable Java and measurement-based teaching method; work2011, page update unknown. Group with Princeton companion ecosystem. | 010 |
| 5 | https://omscs.gatech.edu/sites/default/files/documents/Syllabi/CS%206515%202026-3.pdf | Rendered pp1–2: required DPV, recommended KT and reading/outcome requirements; Fall2026. | 010–012 |
| 6 | https://networkx.org/documentation/stable/reference/algorithms/shortest_paths.html | Full substantive modeling/weight-selection guide and sentinel example; version3.7, date unknown. | 011 |
| 7 | https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.csgraph.dijkstra.html | Complete API, warnings and example; version1.18.0, date unknown. | 011 |
| 8 | https://igraph.org/c/html/latest/igraph-Structural.html | §§3.1–3.4 and worked C distance APIs; revision date unknown; not whole manual. | 012 |
| 9 | https://jgrapht.org/javadoc/org.jgrapht.core/org/jgrapht/alg/shortestpath/DijkstraShortestPath.html | Class contract, pairing-heap/injectable-heap constructors and method summaries; date unknown. | 013 |
| 10 | https://doc.cgal.org/latest/Manual/devman_robustness.html | Full exact-vs-floating-point robustness section; version6.2.1, date unknown. | 013 |
| 11 | https://www.unic.ac.cy/ECTS_Syllabi/COMP-370.pdf | Course prerequisites, outcomes and renderedp4 bibliography; undated, SW recommended rather than required. | 015,020 |
| 12 | https://www.tedu.edu.tr/sites/default/files/2026-06/CMPE224_Syllabus-v1_0.pdf | Rendered required-text table and course outcomes; bodyFall2025–26, not upload-month semester. | 015–016 |
| 13 | https://wwwtest.sjsu.edu/cs/docs/syllabi/summer25/Data_Structures_and_Algorithms_CS_146_Summer_2025.pdf | Chapter assignments, bibliography and renderedp8; Summer2025, modified2025-06-03. SJSU and Sacramento/CalState reserve grouped conservatively. | 015–016,020 |
| 14 | https://docs.mosek.com/modeling-cookbook/practical.html | §§7.1–7.2 inspected formulation and near-dependence examples; version3.4.0, date unknown. | 017 |
| 15 | https://graph-tool.skewed.de/static/docs/stable/autosummary/graph_tool.topology.shortest_distance.html | Parameters, Notes and worked examples: DAG/negative-weight/initialization conditions; version3.9, date unknown. Simplified complexity wording not adopted. | 018–019 |
| 16 | https://petsc.org/release/manual/ksp/ | Residual monitoring, spectrum, flexible/pipelined methods and preconditioning sections; version3.26.0, date unknown. | 019 |
| 17 | https://www.comp.nus.edu.sg/~rahul/cs6234-13.html | Original course structure, evaluation and possible partial KT use; body2013 despite discrepant browser title. | 020 |
| 18 | https://services.just.edu.jo/CourseQA/Uploads/Syllabus/1737840.pdf | Full extracted syllabus and renderedp1 exact CLRS4e/SW4e roles; semester2024–25, printed2024-11-03. | 020 |
| 19 | https://doc.sagemath.org/html/en/reference/graphs/sage/graphs/distances_all_pairs.html | floyd_warshall signature, memory/index warnings and examples; date unknown, not whole manual. | 022 |
| 20 | https://www.netlib.org/lapack/explore-html/d8/da6/group__gesv_ga831ce6a40e7fd16295752d18aed2d541.html | Complete DGESV purpose/arguments/driver, overwrite and singularity contracts; LAPACK3.12.1, generated2025-01-20. | 023 |

Withheld from this conservative tally: publisher ecosystems with ambiguous earlier history, Berkeley/UCSD author-site overlap, FFTW/MIT association, SLEPc/PETSc association, GNU GMP/MPFR, IBM-associated rustworkx, Edinburgh-associated HiGHS, IEEE-associated SE Radio, returning Rust sources, all failures and snippet-only results. Useful substantive reads of those sources remain in the logs. No source is counted simply for loading a navigation shell.

## Important corrective findings

DPV's July2006 author pagination must not be silently equated with final-print errata or the build used by a course. Its sum-to-product aside needs domain assumptions: the signed-edge counterexample in the canonical record is curator reasoning, not a claim quoted from an author. Skiena's loose LP/probability modeling wording was observed on undated web excerpts, not assigned without proof to3e print pages. Its serious errata limit blind code copying.

Pearson electronic-product dates and Springer's paperback publication dates are not new intellectual works. Course dates were read from document bodies rather than upload directories, and optional reading was not promoted to required adoption. Current library/solver documentation establishes concrete preconditions and numeric/representation limits rather than universal correctness of textbook examples.

## Chronological records

[000 review](000-review.md) · [001 discovery](001-discovery.md) · [002 author/course discovery](002-author-and-course-discovery.md) · [003 scope/adoption](003-scope-and-adoption.md) · [004 errata/leads](004-errata-and-further-leads.md) · [005 rendered DPV corrections](005-rendered-dpv-corrections.md) · [006 original retrieval](006-original-material-retrieval.md) · [007 publisher/chapter findings](007-publisher-and-chapter-findings.md) · [008 rendered DP/editions](008-rendered-dp-and-editions.md) · [009 chapter navigation](009-chapter-navigation.md) · [010 pedagogy](010-pedagogy-and-current-algorithms.md) · [011 shortest-path contracts](011-shortest-path-contracts.md) · [012 rendered adoption/sorting](012-rendered-adoption-and-sorting.md) · [013 implementation tradeoffs](013-implementation-tradeoffs.md) · [014 syllabus attempts](014-syllabus-and-original-index-attempts.md) · [015 draft boundaries](015-curriculum-and-draft-boundaries.md) · [016 exact-edition teaching](016-exact-edition-teaching.md) · [017 modeling](017-modeling-counterevidence.md) · [018 graph/integer contracts](018-graph-and-integer-contracts.md) · [019 solver costs](019-algorithm-selection-and-solver-costs.md) · [020 rendered bibliographies](020-rendered-course-bibliographies.md) · [021 eigenproblem scope](021-eigenproblem-scope.md) · [022 finite representations](022-finite-representations-and-review-openings.md) · [023 original review](023-original-review-findings.md) · [024 independent review](024-independent-review-and-product-dates.md) · [025 current Rust](025-current-rust-and-correction-boundaries.md) · [026 final checks](026-final-targeted-checks.md).

[STATE](../../STATE.md) records actual counts and unfinished evidence. [REJECTIONS](../../REJECTIONS.md) retains corrections. Final publication and structural validation are recorded separately; this audit is not itself proof of a remote main update or a completed collection-wide audit.
