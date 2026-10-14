# Technical Ebooks List

An evidence-backed catalog of programming, software engineering and computing ebooks, aiming for **2,000 distinct, high-quality works that remain useful today**. This repository stores assessments and exact sources, not ebook binaries.

## Collection status

| Measure | Distinct works |
| --- | ---: |
| Recommended after initial research | 24 |
| Passed a subsequent-run review | 22 |
| Recommendations awaiting later-run review | 2 |
| Canonical research candidates, not counted | 1 |
| Retained deferred works, including that candidate | 3 |
| Completed final collection audit | 0 |
| Target after review and final audit | 2,000 |

Count by stable `work_id`, not editions, translations, formats or subject-index appearances. Continuous Delivery and Release It! have now passed a subsequent-run review with their limitations retained. The two new recommendations below await later review. See [research/STATE.md](research/STATE.md) for the checkpoint, [UNSELECTED.md](research/UNSELECTED.md) for retained non-selections, and [the source registry](research/SOURCES.md) for exact visit logs and website novelty checks.

## Browse recommendations

| Work | Edition recorded | Primary subject | Review |
| --- | --- | --- | --- |
| [Operating Systems: Three Easy Pieces](books/arpaci-dusseau-ostep-1-10.md) | 1.10 (2023) | Computer Systems & Operating Systems | Passed later-run review |
| [Introduction to Algorithms](books/cormen-introduction-to-algorithms-4.md) | Fourth (2022) | Algorithms & Data Structures | Passed later-run review |
| [Database System Concepts](books/silberschatz-korth-sudarshan-database-system-concepts-7.md) | Seventh (2019) | Databases & Data Modeling | Passed later-run review |
| [Distributed Systems](books/van-steen-tanenbaum-distributed-systems-4.md) | Fourth (2023; 4.03/4.03x distinction noted) | Concurrency & Distributed Systems | Passed later-run review |
| [Designing Data-Intensive Applications](books/kleppmann-riccomini-ddia-2.md) | Second (2026) | Software Architecture | Passed later-run review |
| [Crafting Interpreters](books/nystrom-crafting-interpreters-2021.md) | 2021 | Programming Language Theory & Compilers | Passed later-run review |
| [Logical Foundations](books/pierce-logical-foundations-v7.md) | Vol. 1, v7.0 (2026; v7.1 noted) | Mathematics & Formal Methods | Passed later-run review |
| [How to Design Programs](books/felleisen-how-to-design-programs-2.md) | Second (2018; web revision 2026) | Programming | Passed later-run review |
| [Pro Git](books/chacon-straub-pro-git-2.md) | Second (2014; maintained web text) | Software Engineering Practices & Collaboration | Passed later-run review |
| [Software Engineering at Google](books/winters-manshreck-wright-software-engineering-at-google-2020.md) | 2020 | Software Engineering Practices & Collaboration | Passed later-run review |
| [Security Engineering](books/anderson-security-engineering-3.md) | Third (2020) | Software Security & Privacy | Passed later-run review |
| [Computer Networking: A Top-Down Approach](books/kurose-ross-computer-networking-9.md) | Ninth (2025) | Networking, APIs & Integration | Passed later-run review |
| [A Philosophy of Software Design](books/ousterhout-philosophy-of-software-design-2.md) | Second (2021) | Software Design & Code Quality | Passed later-run review |
| [Accessibility for Everyone](books/kalbag-accessibility-for-everyone-2017.md) | Original (2017) | User Experience & Human–Computer Interaction | Passed later-run review |
| [Mastering the Requirements Process](books/robertson-mastering-the-requirements-process-4.md) | Fourth (2024) | Requirements & Software Analysis | Passed later-run review |
| [Software Testing: A Craftsman's Approach](books/jorgensen-devries-software-testing-5.md) | Fifth (2021) | Software Testing & Quality Assurance | Passed later-run review |
| [Physically Based Rendering: From Theory to Implementation](books/pharr-jakob-humphreys-physically-based-rendering-4.md) | Fourth (2023) | Computer Graphics & Visualization | Passed later-run review |
| [Dive into Deep Learning](books/zhang-lipton-li-smola-dive-into-deep-learning-2024.md) | Cambridge 2024; online v1.0.3 | Artificial Intelligence & Machine Learning | Passed later-run review |
| [Systems Performance](books/gregg-systems-performance-2.md) | Second (2020) | Debugging & Performance Engineering | Passed later-run review |
| [The Site Reliability Workbook](books/beyer-murphy-rensin-kawahara-thorne-site-reliability-workbook-2018.md) | 2018 | Reliability & Observability | Passed later-run review |
| [Continuous Delivery](books/humble-farley-continuous-delivery-1.md) | First (2010; copyright 2011) | DevOps, Cloud & Infrastructure | Passed later-run review |
| [Release It!](books/nygard-release-it-2.md) | Second (2018) | Software Architecture | Passed later-run review |
| [Working Effectively with Legacy Code](books/feathers-working-effectively-with-legacy-code-1.md) | First (2004; copyright 2005) | Software Maintenance & Legacy Systems | Pending later-run review |
| [Fundamentals of Data Engineering](books/reis-housley-fundamentals-of-data-engineering-1.md) | First (2022) | Data Engineering | Pending later-run review |

[Topic indexes](topics/README.md) include substantial secondary subjects without duplicating works. All 23 subjects have a recommendation link and 22 now have primary coverage; that is coverage, not proof the taxonomy is optimal.

## Retained non-selections

[UNSELECTED.md](research/UNSELECTED.md) is the compact curated list of evaluated works that did not meet the criteria, with reasons, evidence and reconsideration conditions. It distinguishes incomplete evidence from a quality rejection and retains removed recommendations rather than relying only on Git history.

Currently deferred: [Infrastructure as Code, third edition](books/morris-infrastructure-as-code-3.md), the prior Site Reliability Engineering second-edition lead, and the uncertain Brutal Refactoring follow-up listing. Only the first has a canonical candidate file. None is rejected for age, format or acquisition status; see the retained list for exact reasons.

## Selection principles

**Present-day usefulness, not newness.** Older books qualify when their central teachings still apply. Identify dated examples and advice, explain remaining value, and check currency-sensitive claims with current primary sources. Historical influence alone is insufficient.

**Availability is not a filter.** Price, paywalls, print status, geography, missing purchase/download links and unknown ebook formats must not exclude or downgrade a work. Format and access fields are optional descriptive metadata.

Each recommendation needs at least three inspected substantive documents collectively supporting identity/edition, actual contents, independent expert assessment or educational adoption, and relevance today. Material claims link to exact sources and section/page locators. Publication/update dates are separate from access dates. Snippets, star ratings, publisher praise and recycled lists alone are insufficient; disclose inspection limits and unresolved evidence.

Record every external source attempt in Git immediately after its retrieval batch, including failures. Each cycle investigates at least 20 new websites, not repeated pages on the same website; revisiting known sites is encouraged but does not earn novelty credits. [Source records](research/SOURCES.md) distinguish breadth from evidence quality.

Cycles review earlier work, investigate gaps, and add, revise, reclassify or remove records with reasons. New recommendations need later-run review before audited progress, and completion also needs a final evidence, relevance, categorization and deduplication audit. Preserve work-level non-selections in [UNSELECTED.md](research/UNSELECTED.md) and claim-level corrections in [REJECTIONS.md](research/REJECTIONS.md); earlier decisions remain available.

## Explore all subjects

The **7 browsing groups and 23 controlled subjects** remain provisional. Real-book classification is ongoing; no empirical user test has established an optimum.

| Navigation group | Subjects |
| --- | --- |
| [Foundations & Theory](TAXONOMY.md#1-foundations-and-theory) | Algorithms & Data Structures; Computer Systems & Operating Systems; Mathematics & Formal Methods; Programming Language Theory & Compilers |
| [Programming & Platforms](TAXONOMY.md#2-programming-and-platforms) | Programming; Platform-Specific Development |
| [Software Engineering & Architecture](TAXONOMY.md#3-software-engineering-and-architecture) | Software Design & Code Quality; Software Architecture; Requirements & Software Analysis; Software Maintenance & Legacy Systems; Software Engineering Practices & Collaboration |
| [Data, Networking & Distributed Systems](TAXONOMY.md#4-data-networking-and-distributed-systems) | Databases & Data Modeling; Data Engineering; Networking, APIs & Integration; Concurrency & Distributed Systems |
| [Quality, Performance & Security](TAXONOMY.md#5-quality-performance-and-security) | Software Testing & Quality Assurance; Debugging & Performance Engineering; Software Security & Privacy |
| [Operations & Delivery](TAXONOMY.md#6-operations-and-delivery) | DevOps, Cloud & Infrastructure; Reliability & Observability |
| [Specialized Computing](TAXONOMY.md#7-specialized-computing) | Artificial Intelligence & Machine Learning; User Experience & Human–Computer Interaction; Computer Graphics & Visualization |

## Record conventions

One canonical record per included edition, with one primary subject and substantial additional subjects from [TAXONOMY.md](TAXONOMY.md). All editions and translations of a work share a stable identifier. Languages, technologies, concepts, difficulty and formats are independent attributes; a passing mention does not justify another subject.

Use [books/BOOK_TEMPLATE.md](books/BOOK_TEMPLATE.md). Unknown metadata is acceptable; invented metadata is not. Update all affected topic indexes and counts when classifications or review statuses change. No repository index generator or automatic review system is installed; validation performed in a cycle is described in its checkpoint.

## Research foundations

The initial subject vocabulary drew on [IEEE SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering), [ACM computing knowledge areas](https://csed.acm.org/knowledge-areas/) and the [CNCF landscape](https://landscape.cncf.io/). Cataloging was informed by [Dublin Core](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/) and [SKOS](https://www.w3.org/TR/skos-primer/). These references are not endorsements of this taxonomy or evidence for individual recommendations.
