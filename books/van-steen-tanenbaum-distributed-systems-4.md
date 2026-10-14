---
work_id: van-steen-tanenbaum-distributed-systems
title: "Distributed Systems"
authors: ["Maarten van Steen", "Andrew S. Tanenbaum"]
edition: "Fourth edition (2023); author revision 4.03 announced January 2025"
publication_year: 2023
isbn_by_format: {}
primary_subject: concurrency-and-distributed-systems
additional_subjects: []
concepts: [logical-clocks, distributed-coordination, consistency-models, replication, fault-tolerance, message-passing]
languages: [Python]
technologies: []
difficulty: intermediate
focus: [conceptual, practical]
formats: []
access: unknown
official_url: "https://www.distributed-systems.net/index.php/books/ds4/"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Distributed Systems — Fourth edition (2023; v4.03 corrections 2025)

## Recommendation, edition and audience

**Recommend for programmers with operating-systems and networking foundations who need to reason about distributed coordination, communication, consistency and failures.** The [author's fourth-edition site](https://www.distributed-systems.net/index.php/books/ds4/) explicitly gives the preferred citation **van Steen and Tanenbaum, *Distributed Systems*, fourth edition, 2023**, and announces **v4.03 (January 2025)** as a correction release, **not** a fifth edition. It says examples have been revised for Python 3, with dependencies such as Redis. An exact ebook file subtype and ISBN are not independently verified; neither affects eligibility. [S1]

## Actual scope and classification

The author describes real-system examples including blockchain components and revised executable Python demonstrations. More importantly, Linköping University's directly inspected [2026 fourth-edition reading map, pp. 1–2](https://www.ida.liu.se/~TDDD25/lectures/TDDD25-lasanvisningar-vanSteen-4e.pdf#page=1) assigns exact chapters and sections: architecture and middleware (chapter 2); RPC, brokers and multicast (§§4.2–4.4); physical and logical clocks, mutual exclusion and election algorithms (§§5.1–5.4); sequential and causal consistency and protocols (§§7.2.1, 7.5); and Byzantine agreement, reliability and fault tolerance (§8.1–8.3). This independently verifies a broad **distributed systems** pedagogical scope rather than incidental mention of network tools. Its primary subject is **Concurrency & Distributed Systems**; networking is involved but not promoted to an additional subject without demonstrated sufficiently independent breadth. [S1], [S3]

**Inspection limitation:** the actual publisher/author full chapter prose and exercises were **not** directly inspected in this run; we inspected the author's release description and the instructor's original, edition-specific, section-level reading guide (visually on its first two PDF pages). This is an important next-review gap, **not** an inference that the book lacks quality based on acquisition or access. The section map is substantive evidence of what the book teaches but is not a substitute for validating each explanation.

## Independent evaluation and relevance today

[Linköping University TDDD25 Spring 2026](https://www.ida.liu.se/~TDDD25/info/courseinfo.en.shtml), updated **2026-02-20**, explicitly recommends the **fourth edition (2023)** and uses the listed sections for assessed coursework; this is educational adoption, not a controlled learning study. Independent [UMass Amherst COMPSCI 677 Spring 2025](https://lass.cs.umass.edu/~shenoy/courses/spring25/materials/) also names the **fourth edition** as a course textbook while warning that the course requires additional topics not covered by it. This supports continuing usefulness, and cautions against calling the textbook complete for all modern distributed-system applications. [S2]–[S4]

The book's recurring themes—failure models, consistency semantics, clock uncertainty and coordination—remain live engineering decisions. For a concrete contemporary primary check, the [etcd 3.6 Range API documentation](https://etcd.io/docs/v3.6/learning/api/) explicitly distinguishes **default linearizable reads** from **member-local serializable reads that may be stale** (§*Range*, `serializable` field). That is independent evidence of the *topics'* relevance, not proof that any textbook algorithm or implementation matches contemporary etcd. Versioned API examples, blockchain platforms, Python libraries and Redis integration must be checked against current official references before direct adoption. [S5]

## Strengths, limitations and alternatives

The value is a structured, academic progression from architecture through messaging, clocks, consistency and fault tolerance, with specific 2026 course readings. Its theoretical and architectural breadth is not a standalone deployment recipe for cloud vendors, Kubernetes or current service meshes. The instructor's reading map expressly notes course topics omitted by each textbook. Compared with *Designing Data-Intensive Applications* (second edition), this work emphasizes distributed mechanisms and formal distinctions; DDIA centers on selecting data-system architectures and their tradeoffs. Compared with *Operating Systems: Three Easy Pieces*, the failures and coordination extend beyond one host.

Errata/revision evidence is limited to the author's notice of **v4.03 small corrections**; no complete per-page errata history or full exercise run was inspected. No full-book reading, exact command verification, or source-file acquisition is claimed. Current value is justified by primary technical practice and adoption, never price, paywall, format or age.

## Evidence ledger

**Inspected/accessed 2026-10-14**, recording actual document dates separately.

| ID | Document and exact locator | Source publication/update |
| --- | --- | --- |
| [S1] | [Author fourth-edition site](https://www.distributed-systems.net/index.php/books/ds4/), citation, v4.03 note, Python3 and Redis warnings | 4e 2023; v4.03 2025-01; site update unknown |
| [S2] | [Linköping course information](https://www.ida.liu.se/~TDDD25/info/courseinfo.en.shtml), *Literature* and *Reading Directions* | Spring 2026; updated 2026-02-20 |
| [S3] | [Linköping original reading directions PDF](https://www.ida.liu.se/~TDDD25/lectures/TDDD25-lasanvisningar-vanSteen-4e.pdf#page=1), rendered pp.1–2, exact 4e chs.1–8 and subsections | 2026 edition-specific course guide; exact PDF update unknown |
| [S4] | [UMass Amherst Spring 2025 materials](https://lass.cs.umass.edu/~shenoy/courses/spring25/materials/), *References*, fourth-edition text and supplementary readings | Spring 2025 |
| [S5] | [etcd v3.6 API reference](https://etcd.io/docs/v3.6/learning/api/), *Range / serializable* field | Version 3.6; document update unknown |

## Next review

**Pending subsequent-run review**. Prioritize inspecting author-published substantive fourth-edition prose or worked examples and identifying specific v4.03 corrections; compare to contemporary consensus/fault-tolerance literature. Confirm an unbiased expert pedagogical evaluation beyond independent 2025/2026 educational adoption. Do not assert whole-chapter verification or code execution without actually doing so.
