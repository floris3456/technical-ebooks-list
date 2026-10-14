---
work_id: anderson-security-engineering
title: "Security Engineering: A Guide to Building Dependable Distributed Systems"
authors: ["Ross Anderson"]
edition: "Third edition"
publication_year: 2020
isbn_by_format: {ebook-unspecified: "9781119644682"}
primary_subject: software-security-and-privacy
additional_subjects: []
concepts: [threat-modeling, security-economics, access-control, assurance, secure-development]
languages: []
technologies: []
difficulty: advanced
focus: [conceptual, reference]
formats: [pdf]
access: unknown
official_url: "https://www.cl.cam.ac.uk/archive/rja14/book.html"
last_verified: "2026-10-14"
status: recommended
review_status: pending
reviewed_commit: null
---

# Security Engineering — Third edition

## Recommendation and audience

**Recommend to advanced developers, security engineers and architects designing dependable systems that must withstand motivated opponents.** Wiley identifies Ross Anderson, the third edition (published **2020-12-02**), and an electronic ISBN **9781119644682** distinct from the print edition. This technical security-systems perspective is not a comprehensive 2026 attack-technique manual. [S1], [S2], [S5]

Research inspected the author's chapter list, excerpts of actual chapters 1, 2 and 27, an independent expert appraisal, current university prerequisites/reading, third-edition errata and newer security guidance. It does not represent a cover-to-cover reading or completed exercises.

## Contents and subject fit

The author's **29-chapter** contents address opponents, protocol design, cryptography, access control, security economics, real-world sectors, risk management, assurance, and privacy. In chapter **1 §1.2**, the author distinguishes security policy, mechanisms, assurance and incentives; chapter **2** foregrounds opponent and threat modeling; chapter **27 §27.2** links secure development to risk and organizational constraints. These inspected ideas make **Software Security & Privacy** the primary subject. Other technologies mentioned are part of this security viewpoint, not automatically additional subjects. [S2], [S3], [S4]

## Why this 2020 book is still useful

The University of Edinburgh **2026/27** Security Engineering course explicitly lists the third edition and tells entrants lacking assumed security background to read **chapters 1–7, 9, and 11**. This is present-day edition-specific educational reliance, not a claim that all examples are current. [S6]

CIS/SAFECode's **2026-07-15 Secure by Design v1.1** guidance still focuses on secure design, supply-chain controls, code integrity and vulnerability remediation, while adding new AI-security considerations. The book's enduring contribution is a threat/system/incentive framework; 2026 product, legal, AI and supply-chain implementation details must be refreshed from authoritative new references. [S7]

## Independent assessment and limitations

Sven Dietrich's **2021-05-31 IEEE Cipher expert review** evaluates **this third edition**, praising broad real-world system reasoning while explaining that its case-driven exposition is **not a full rigorous mathematical treatment** of each security discipline. The breadth is a strength for general threat modeling and secure systems design; use specialized modern cryptography, platform-hardening and security-testing manuals for deep, implementation-specific treatment. Historical quantitative or regulatory claims must not be treated as contemporaneous facts. [S5], [S7]

The author hosts actual third-edition PDFs and an **errata page** with concrete corrections (including printed pages 406 and 627). Corrections were observed but not exhaustively mapped into every paragraph; no error-free claim is made. Availability or price did not affect selection. [S2], [S8]

## Evidence ledger

All sources inspected **2026-10-14**; the access date is not the source date.

| ID | Source and precise inspected locator | Date/version |
| --- | --- | --- |
| [S1] | Wiley third edition book DOI page, bibliographic and electronic/print ISBN | Published 2020-12-02 |
| [S2] | Author's third-edition page, full chapter list and author-hosted chapter links | Third edition, 2020; page update unknown |
| [S3] | Author chapter 1, *What Is Security Engineering?*, §1.2, printed pp. 3–6 | Third edition; chapter revision unknown |
| [S4] | Author chapter 2 *Who Is the Opponent?* and chapter 27 *Secure Systems Development*, §27.2 | Third edition; chapter revision unknown |
| [S5] | Sven Dietrich, IEEE Cipher independent review, critique of scope and style | Published 2021-05-31 |
| [S6] | Edinburgh INFR11208, 2026/27 prerequisite reading and course reading list | 2026/27 academic year |
| [S7] | CIS/SAFECode Secure by Design v1.1, six foundational considerations and AI changes | Published 2026-07-15 |
| [S8] | Ross Anderson, official third-edition errata, printed-page corrections | Third edition; precise update unknown |

[S1]: https://onlinelibrary.wiley.com/doi/book/10.1002/9781119644682
[S2]: https://www.cl.cam.ac.uk/archive/rja14/book.html
[S3]: https://www.cl.cam.ac.uk/archive/rja14/Papers/SEv3-ch01.pdf#page=4
[S4]: https://www.cl.cam.ac.uk/archive/rja14/Papers/SEv3-ch02.pdf#page=4
[S4-ch27]: https://www.cl.cam.ac.uk/archive/rja14/Papers/SEv3-ch27.pdf#page=3
[S5]: https://www.ieee-security.org/Cipher/BookReviews/2021/RAnderson_by_dietrich.html
[S6]: https://www.drps.ed.ac.uk/26-27/dpt/cxinfr11208.htm
[S7]: https://www.cisecurity.org/about-us/media/press-release/cis-and-safecode-release-secure-by-design-v1-1-a-guide-to-assessing-software-security-practices
[S8]: https://www.cl.cam.ac.uk/archive/rja14/book/v3errata.html

## Next review

Independently inspect the chapter claims and page locators, significant errata, and comparison with a security-specialist text that includes newer secure-software practice. Pending subsequent-run review and final catalog audit.
