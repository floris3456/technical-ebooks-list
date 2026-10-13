# Technical Ebooks List

A curated, edition-aware catalog of programming, software engineering, and computer science ebooks. This repository catalogs **recommendations and legitimate source links**, not copyrighted ebook files.

## Explore subjects

There are **7 navigation groups and 23 subjects**. Groups help people browse; individual subjects classify books.

| Navigation group | Subjects |
| --- | --- |
| [Foundations & Theory](TAXONOMY.md#1-foundations-and-theory) | Algorithms & Data Structures; Computer Systems & Operating Systems; Mathematics & Formal Methods; Programming Language Theory & Compilers |
| [Programming & Platforms](TAXONOMY.md#2-programming-and-platforms) | Programming; Platform-Specific Development |
| [Software Engineering & Architecture](TAXONOMY.md#3-software-engineering-and-architecture) | Software Design & Code Quality; Software Architecture; Requirements & Software Analysis; Software Maintenance & Legacy Systems; Software Engineering Practices & Collaboration |
| [Data, Networking & Distributed Systems](TAXONOMY.md#4-data-networking-and-distributed-systems) | Databases & Data Modeling; Data Engineering; Networking, APIs & Integration; Concurrency & Distributed Systems |
| [Quality, Performance & Security](TAXONOMY.md#5-quality-performance-and-security) | Software Testing & Quality Assurance; Debugging & Performance Engineering; Software Security & Privacy |
| [Operations & Delivery](TAXONOMY.md#6-operations-and-delivery) | DevOps, Cloud & Infrastructure; Reliability & Observability |
| [Specialized Computing](TAXONOMY.md#7-specialized-computing) | Artificial Intelligence & Machine Learning; User Experience & Human–Computer Interaction; Computer Graphics & Visualization |

Definitions, subject boundaries, controlled names, and validation rules live in **[TAXONOMY.md](TAXONOMY.md)**.

## Catalog conventions

1. **One canonical record per included book edition** in `books/`. Different ebook formats of the same edition stay together, with format-specific ISBNs if available.
2. **One primary subject** plus any substantial additional subjects. A book can appear under more than one subject without duplicate records.
3. **Independent facets** for language, technology, subtopics, difficulty, focus, formats, access, author, year, and edition. A language tag is not the book's subject unless teaching that language is the focus.
4. **Subject indexes** in `topics/` link to canonical book records. Generate the indexes from metadata when the collection grows; do not copy full descriptions between pages.
5. **Separate research candidates from recommendations**. Each recommendation should have a grounded assessment and a legitimate publisher, author, or open-access source.

## Repository guide

| Path | Purpose |
| --- | --- |
| [TAXONOMY.md](TAXONOMY.md) | The authoritative subject vocabulary, classification rules, and validation plan |
| [books/BOOK_TEMPLATE.md](books/BOOK_TEMPLATE.md) | A reusable, edition-aware metadata and review template |
| [topics/README.md](topics/README.md) | How topic indexes will link to book records |
| README.md | Introduction and navigation |

## Project status

**Taxonomy v1 — not yet validated on a representative ebook sample.** Before compiling a large book list, evaluate the classification on roughly **25–30 real editions**, including books that span multiple subjects, and revise confusing boundaries.

There are **no curated book entries yet**. This commit establishes a maintainable foundation, not a claim that the taxonomy has been proven optimal.

## Research foundations

- [IEEE Computer Society — Software Engineering Body of Knowledge (SWEBOK)](https://www.computer.org/education/bodies-of-knowledge/software-engineering)
- [ACM — Computer Science Curricula knowledge areas](https://csed.acm.org/knowledge-areas/)
- [CNCF — Cloud Native Landscape](https://landscape.cncf.io/)
- [Dublin Core Metadata Terms](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/)
- [W3C — SKOS Primer](https://www.w3.org/TR/skos-primer/)

This is a practical synthesis, not an official reproduction of those frameworks.
