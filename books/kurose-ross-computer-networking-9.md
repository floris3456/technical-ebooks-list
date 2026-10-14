---
work_id: kurose-ross-computer-networking-a-top-down-approach
title: "Computer Networking: A Top-Down Approach"
authors: ["James F. Kurose", "Keith W. Ross"]
edition: "Ninth edition; published 2025, copyright 2026"
publication_year: 2025
isbn_by_format: {ebook-unspecified: "9780135415603"}
primary_subject: networking-apis-and-integration
additional_subjects: []
concepts: [protocol-layers, http, dns, tcp, udp, quic, congestion-control]
languages: []
technologies: []
difficulty: mixed
focus: [conceptual, practical]
formats: []
access: unknown
official_url: "https://www.pearson.com/en-us/subject-catalog/p/computer-networking-a-top-down-approach/P200000013385/9780135415603"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Computer Networking: A Top-Down Approach — Ninth edition

## Recommendation and audience

**Recommend for programmers and networking students who want a well-structured model of how Internet applications communicate.** Pearson identifies the **ninth edition by James F. Kurose and Keith W. Ross**, published **2025-06-20**, copyright **2026**; the eTextbook ISBN is **9780135415603**. The year distinction is intentional. The **mixed** difficulty label reflects approachable concepts and the more demanding programming/lab tasks. [S1], [S5]

Inspection covers the publisher's full chapter-level ninth-edition table of contents and the authors' companion's actual interactive exercises; not the full textbook prose or completed exercises.

## Contents and subject fit

The book proceeds from application protocols (HTTP, DNS, sockets) through transport (reliable data transfer, TCP/UDP, congestion control and QUIC), network and link layers, wireless/mobile networks and security. This sustained protocol coverage makes **Networking, APIs & Integration** its primary subject. A security section alone is not adequate reason to duplicate it in the security category. [S1], [S2]

The authors' ninth-edition **chapter 3 §3.4** exercises ask about reliable transport, ACK/retransmission and pipelining; **§3.8** knowledge checks ask about QUIC streams, head-of-line blocking and application-layer transport evolution. These are inspected teaching **questions, not verified answers**. In particular, a multiple-choice distractor must not be presented as a protocol fact. [S3], [S4]

## Current relevance and outside adoption

The University of Rochester's **Fall 2026 CSC257/457 syllabus explicitly selects 9/E as its primary text**, emphasizes rapid protocol changes, and assigns networking labs, programming and RFC reading. The GWU Fall 2026 syllabus provides chapter-based course use. This is edition-specific current educational adoption, not an exhaustive quality experiment. [S5], [S6]

The publisher's updated ninth-edition contents explicitly include HTTP/3, QUIC and Wi-Fi 6. The IETF's normative RFC **9000** (QUIC) and **9114** (HTTP/3) clarify present-day protocol behavior; implementations must consult these standards rather than treating the book's simplifying teaching models as specifications. [S1], [S7], [S8]

## Limitations, comparison and errata

Rochester separately names Peterson/Davie's *Computer Networks: A Systems Approach* for a systems perspective and *TCP/IP Illustrated* for protocol depth. Those are comparative investigation leads, **not additional recommendations**. Product/vendor/wireless details change faster than protocol fundamentals; verify contemporary implementations independently. No authoritative ninth-edition printing-specific errata list was exhaustively inspected. Pearson's eTextbook identifier does not establish PDF/EPUB subtype, and format, subscription and price have no role in selection. [S1], [S5]

## Evidence ledger

All accessed **2026-10-14**. Dates below describe the original source, not the visit.

| ID | Source and inspected locator | Date/version |
| --- | --- | --- |
| [S1] | Pearson ninth edition publisher page, authors, ISBN, Table of Contents chapters 1–8 | Published 2025-06-20, ©2026 |
| [S2] | Kurose/Ross UMass ninth-edition online resources, chapter 3 transport section index | Ninth edition; page update unknown |
| [S3] | Author interactive chapter 3 §3.4 questions about reliable transfer and ACKs | Ninth-edition teaching resource, 2025 copyright |
| [S4] | Author interactive chapter 3 §3.8 questions about QUIC streams and implementation | Ninth-edition teaching resource, 2025 copyright |
| [S5] | University of Rochester Fall 2026 CSC257/457, Textbooks, prerequisites, schedule | Fall 2026 |
| [S6] | George Washington University Fall 2026 course syllabus, chapter schedule | Fall 2026 |
| [S7] | IETF RFC 9000, QUIC transport definitions | May 2021 |
| [S8] | IETF RFC 9114, HTTP/3 standard | June 2022 |

[S1]: https://www.pearson.com/en-us/subject-catalog/p/computer-networking-a-top-down-approach/P200000013385/9780135415603
[S2]: https://gaia.cs.umass.edu/kurose_ross/index.php
[S2-ch3]: https://gaia.cs.umass.edu/kurose_ross/videos/3/
[S3]: https://gaia.cs.umass.edu/kurose_ross/knowledgechecks/problem.php?c=3&s=4
[S4]: https://gaia.cs.umass.edu/kurose_ross/knowledgechecks/problem.php?c=3&s=8
[S5]: https://cs.rochester.edu/u/apurtee/257/
[S6]: https://gw-computer-networks-f26.github.io/syllabus/
[S7]: https://www.rfc-editor.org/rfc/rfc9000
[S8]: https://www.rfc-editor.org/rfc/rfc9114

## Next review

Inspect substantive original ninth-edition prose, correct any quiz-to-book mismatches, check printing-specific errata, and compare with Rochester's systems-oriented alternative. Pending subsequent-run review, then catalog-wide audit.
