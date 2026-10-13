# Subject Taxonomy — v1

This is the **single authoritative list of subject names, slugs, and definitions**. It contains **23 subjects** arranged into **7 browsing groups**. Groups are for navigation; subjects (identified by stable slugs) are used in book metadata.

This vocabulary is provisional. It has not been validated against a representative ebook sample.

## Classification rules

1. Assign exactly **one** `primary_subject` using a subject slug below. Choose the book's main teaching objective, not its example language or implementation tool.
2. Assign zero or more distinct `additional_subjects` when a book covers other subjects *substantially*. Never repeat the primary subject.
3. Store languages, technologies, narrower concepts, difficulty, focus, ebook format, and access as **separate facets** — not additional top-level subjects.
4. A book edition has **one canonical record**. PDF/EPUB/web variants of that edition share that record; track ISBNs for each format when verified. Distinct editions may get distinct records.
5. Multiple subject-index pages can link to the same canonical record. Do not duplicate descriptions or bibliographic metadata.
6. Preserve preferred labels and slugs; document aliases when terms or slugs change.
7. Use `candidate` until a sourced assessment supports `recommended`. Do not treat a publisher's promotional claims alone as independent evaluation.
8. Only introduce a new top-level subject when repeated classification or retrieval problems justify it. First consider additional subjects and narrower `concepts`.

## Subject groups and definitions

## 1. Foundations and Theory

- **Algorithms & Data Structures** (`algorithms-and-data-structures`): Algorithm design and analysis, complexity, trees, graphs, searching, sorting, and fundamental data structures.
- **Computer Systems & Operating Systems** (`computer-systems-and-operating-systems`): CPU/memory concepts, operating systems, processes, filesystems, and the hardware/software interface; not primarily cloud deployment.
- **Mathematics & Formal Methods** (`mathematics-and-formal-methods`): Discrete math, logic, proofs, formal specifications, model checking, and program correctness.
- **Programming Language Theory & Compilers** (`programming-language-theory-and-compilers`): Programming language semantics, type systems, interpreters, parsers, and compiler construction; daily language usage belongs under Programming.

## 2. Programming and Platforms

- **Programming** (`programming`): Learning and applying languages, paradigms, idioms, and general programming techniques.
- **Platform-Specific Development** (`platform-specific-development`): Web frontend/backend, mobile, desktop, embedded, and game development when a particular platform is the central focus.

## 3. Software Engineering and Architecture

- **Software Design & Code Quality** (`software-design-and-code-quality`): Design patterns, modularity, dependencies, clean code, refactoring, and component-level design; system-wide boundaries belong to Software Architecture.
- **Software Architecture** (`software-architecture`): Architectural styles, system boundaries, domain-driven design, architecture decisions, scaling, and system-level tradeoffs.
- **Requirements & Software Analysis** (`requirements-and-software-analysis`): Problem discovery, requirements elicitation, specifications, domain analysis, modeling, and stakeholder needs.
- **Software Maintenance & Legacy Systems** (`software-maintenance-and-legacy-systems`): Understanding and evolving existing systems, technical debt, migrations, modernization, and long-term maintainability.
- **Software Engineering Practices & Collaboration** (`software-engineering-practices-and-collaboration`): Version-control practices, code reviews, documentation, team workflows, process, communication, and technical leadership.

## 4. Data Networking and Distributed Systems

- **Databases & Data Modeling** (`databases-and-data-modeling`): SQL/NoSQL, storage engines, schemas, indexing, queries, and transactions; pipelines belong mainly to Data Engineering.
- **Data Engineering** (`data-engineering`): ETL/ELT, batch and streaming data pipelines, data platforms, warehouses, and lakes.
- **Networking, APIs & Integration** (`networking-apis-and-integration`): Network protocols, HTTP/TCP-IP, APIs, REST/GraphQL, messaging interfaces, and interoperability.
- **Concurrency & Distributed Systems** (`concurrency-and-distributed-systems`): Threads, synchronization, asynchronous programming, distributed coordination, consensus, consistency, and fault tolerance.

## 5. Quality Performance and Security

- **Software Testing & Quality Assurance** (`software-testing-and-quality-assurance`): Test strategies, unit/integration/property-based testing, test-driven development, verification, and automation.
- **Debugging & Performance Engineering** (`debugging-and-performance-engineering`): Debugging, profiling, benchmarking, memory analysis, root-cause analysis, and performance optimization.
- **Software Security & Privacy** (`software-security-and-privacy`): Secure coding, application security, cryptography, authentication, authorization, threat modeling, and privacy.

## 6. Operations and Delivery

- **DevOps, Cloud & Infrastructure** (`devops-cloud-and-infrastructure`): CI/CD, deployment, infrastructure as code, containers, orchestration, cloud services, and platform operations.
- **Reliability & Observability** (`reliability-and-observability`): Site reliability engineering, monitoring, tracing, logs, service objectives, incident response, and production resilience.

## 7. Specialized Computing

- **Artificial Intelligence & Machine Learning** (`artificial-intelligence-and-machine-learning`): AI and ML methods, model development and evaluation, and AI application engineering.
- **User Experience & Human–Computer Interaction** (`user-experience-and-human-computer-interaction`): Human–computer interaction, usability, interface design, accessibility, and user research; frontend implementation primarily belongs under Platform-Specific Development.
- **Computer Graphics & Visualization** (`computer-graphics-and-visualization`): Rendering, graphics algorithms, visualization techniques, and graphics programming.

## Independent facets

| Field | Preferred use / values |
| --- | --- |
| `primary_subject` | Required, exactly one approved subject slug above |
| `additional_subjects` | Other approved slugs, each at most once |
| `concepts` | Narrower normalized keywords, e.g. `microservices`, `domain-driven-design`, `test-driven-development`; lowercase kebab-case |
| `languages` | Consistent official language names, e.g. `Python`, `Java`, `Rust` |
| `technologies` | Consistent platform/tool names, e.g. `Kubernetes`, `PostgreSQL` |
| `difficulty` | `beginner`, `intermediate`, `advanced`, `mixed`, or `unknown` |
| `focus` | Zero or more of `conceptual`, `practical`, `reference` |
| `formats` | Verified `epub`, `pdf`, `web`, or another explicitly documented file format |
| `access` | `free`, `paid`, `subscription`, `mixed`, or `unknown` |
| `status` | `candidate`, `recommended`, or `retired` |
| `edition`, `publication_year`, `isbn_by_format` | Edition-aware bibliographic details; do not guess ISBNs |
| `official_url`, `last_verified` | A legitimate publisher/author/open-access source and check date |

### Term normalization

- **SRE** means *site reliability engineering*, a narrower concept under **Reliability & Observability**.
- **QA** means *quality assurance*, under **Software Testing & Quality Assurance**.
- **HCI** means *human–computer interaction*, under **User Experience & Human–Computer Interaction**.
- **DDD**, **microservices**, and **TDD** are narrower concepts, **not synonyms** of their parent subjects. Normalize them as `domain-driven-design`, `microservices`, and `test-driven-development` when used in `concepts`.
- If one term legitimately covers several subjects, assign the relevant subjects rather than inventing a misleading single alias.

## Boundary guidelines

- **Design vs. Architecture:** Code/component structure vs. system boundaries and broad structural tradeoffs.
- **Architecture vs. Distributed Systems:** Structural patterns and decisions vs. consistency, coordination, and distributed correctness.
- **Programming vs. Platform-Specific Development:** Languages/paradigms vs. building for a particular platform.
- **Databases vs. Data Engineering:** Data storage/modeling/query engines vs. pipelines and data platforms.
- **Networking/APIs vs. Distributed Systems:** Connectivity and interfaces vs. distributed algorithms and fault tolerance.
- **Testing vs. Debugging/Performance:** Validation/test strategy vs. diagnosing failures and optimizing behavior.
- **DevOps vs. Reliability:** Delivery/infrastructure automation vs. production reliability, observability, and incident response.

A book can receive **both** subjects when the coverage warrants it.

## Validation plan — not yet performed

Before adding hundreds of entries:

1. Collect approximately **25–30 real, publisher-verifiable ebook editions** spanning all seven groups; include books with more than one substantive subject.
2. Classify each edition without inventing facts. Note disagreements over primary subjects or missing metadata.
3. Check realistic retrieval tasks: finding books across overlapping subjects; filtering by language, level, format, and access; distinguishing revised editions.
4. Track missed books, misclassifications, duplicate records, inconsistent concepts, and unclear boundaries.
5. Revise definitions and retest; invite representative readers for more credible findability evidence.

The current structure is a **proposal to test**, not a proven optimum.

## Sources and inspiration

- [IEEE SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering)
- [ACM Computer Science Curricula](https://csed.acm.org/knowledge-areas/)
- [CNCF Cloud Native Landscape](https://landscape.cncf.io/)
- [Dublin Core Metadata Terms](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/)
- [W3C SKOS Primer](https://www.w3.org/TR/skos-primer/)
- [Nielsen Norman Group — Tree Testing](https://www.nngroup.com/articles/tree-testing/)
