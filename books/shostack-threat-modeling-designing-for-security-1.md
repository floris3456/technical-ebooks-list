---
work_id: shostack-threat-modeling-designing-for-security
title: "Threat Modeling: Designing for Security"
authors: ["Adam Shostack"]
edition: "First edition, April 2014"
publication_year: 2014
isbn_by_format: {print: "9781118809990"}
primary_subject: software-security-and-privacy
additional_subjects: [requirements-and-software-analysis]
concepts: [threat-modeling, attack-trees, stride, risk-assessment, security-requirements]
languages: []
technologies: []
difficulty: intermediate
focus: [conceptual, practical, reference]
formats: []
access: unknown
official_url: "https://www.wiley-vch.de/de/fachgebiete/computer-und-informatik/threat-modeling-978-1-118-80999-0"
last_verified: "2026-10-16"
status: recommended
review_status: pending
reviewed_commit: null
---

# Threat Modeling: Designing for Security — first edition

## Recommendation and audience

Recommend to engineers, architects, security reviewers and technically minded product teams who need a repeatable way to identify threats during design rather than only after software ships. Readers should be able to draw a system/data-flow boundary and discuss trust assumptions. This is a methods book for collaborating on an adversarial design review, not a catalogue of every contemporary exploit or an introductory programming textbook [T1–T4].

The first-edition work has a genuinely separate role from the catalog's broad *Security Engineering*: it organizes an actionable team workflow around what is being built, what can go wrong, what will be done about it and how well the analysis went [T2–T4]. It complements rather than replaces implementation-focused *Secure by Design*; a secure value object cannot substitute for identifying trust boundaries.

## Inspected contents and classification

Wiley's first-edition contents span system modeling, STRIDE, attack trees, threat elicitation, evaluation, requirements and adopting threat modeling in organizations [T1]. The author's original chapter 4 shows an AND/OR attack-tree decomposition with a worked diagram (PDF pp. 3 and 6, corresponding to printed pp. 88 and 91), letting readers reason about alternative and combined attacker steps [T2]. Samples from chapter 11 on choosing tools and chapter 12 on developing requirements reinforce the connection from identified failure modes to actionable controls [T3]. Only those identified pages and the detailed contents were inspected—not all 624 pages or completed workshop exercises.

**Software Security & Privacy** is primary because adversarial reasoning and safeguards motivate the method. **Requirements & Software Analysis** is a substantial secondary subject because eliciting and validating security requirements is an explicit chapter-level process, not incidental jargon [T1,T3]. STRIDE and attack trees remain narrower concepts, not additional top-level subjects.

## Independent appraisal and documented use

A full independent IAPP review by privacy specialist Michael Whitener discusses the book's four-question technique and its usefulness for privacy/security practitioners, while also explaining that tradeoffs and expertise still matter [T4]. This is substantive first-edition appraisal, not proof every engineering example is flawless. Kuwait University's security-design page lists the book as textbook under a vague "latest edition" label; the current teaching term and actual printing cannot be inferred [T5]. The University of Washington's Autumn 2023 course assigns early chapters but was taught by Shostack, so it is evidence of usage rather than independent endorsement [T6].

## Why the central method still matters, and dated edges

Recent primary and expert guidance retains the structure of system boundaries, attacker goals, mitigations and risk decisions. The 2025 Carnegie Mellon SEI worked method and the current UK NCSC threat-modeling guide demand explicit threat-to-control decisions; the community manifesto articulates a closely related four-question workflow [T7–T9]. They support the continuing value of the method, not all of the book's 2014 threat examples, tools or compliance context.

Do not copy a 2014 tooling catalog or assume an attack-tree diagram exhaustively models a modern deployment. Contemporary supply-chain, identity, SaaS and AI-integrated risks can require new threats and new iteration. A threat inventory by itself does not verify a control or prove a system secure. The first-edition errata includes substantive corrections (notably pp. 14, 154 and 225); specific print/digital repair status is unknown [T10]. The author lists a **second edition planned for February 2, 2027**, so the later version was **not** a completed book as of this review. It is neither counted nor a reason to downgrade useful first-edition principles [T11].

## Alternatives, edition and limits

Choose *Security Engineering* for a broader, sometimes sector-specific explanation of real systems and incentives; choose this work for a focused repeatable threat-analysis workshop. Choose *Secure by Design* for coding/design-level domain models and validation once risks have been identified. These are distinctions between evidenced scopes, not a head-to-head learning experiment. No attack model was exercised against live software or independently penetration-tested in this research.

Publisher bibliographic identity is first edition, April 2014; print ISBN is not relabeled as a PDF or EPUB identifier [T1]. Access, price and electronic format uncertainty did not govern the recommendation. No complete first-edition errata or every printable revision was audited.

## Evidence ledger

All external evidence accessed **2026-10-16**; document dates below are separate from access dates.

| ID | Exact URL and inspected locator | Source date and evidentiary limit |
| --- | --- | --- |
| T1 | https://www.wiley-vch.de/de/fachgebiete/computer-und-informatik/threat-modeling-978-1-118-80999-0 — author, April 2014, first edition, contents chapters 1–17 | Work April 2014; page update unspecified. Publisher metadata/scope, not independent review. |
| T2 | https://adam.shostack.org/files/tmbookchapters/Chapter4-AttackTrees-web.pdf#page=3 and #page=6 — original attack-tree explanations and example | First-edition original 2014; PDF revision unspecified; selected of 16 pages rendered, not full chapter read. |
| T3 | https://adam.shostack.org/files/tmbookchapters/Chapter11-ThreatModelingTools-web.pdf#page=2 and https://adam.shostack.org/files/tmbookchapters/Chapter12-RequirementsCookbook-web.pdf#page=2 — tool choice and requirements framing | First-edition original; revision dates unknown, selected pages inspected. |
| T4 | https://iapp.org/news/a/threat-modeling-designing-for-security — full Michael Whitener independent privacy-professional appraisal | Published 2014-08-26; current site revision unknown; not a live security validation. |
| T5 | https://www.cs.ku.edu.kw/cs493/ — course textbook field and syllabus | Course date not reliably established; not exact-print proof. |
| T6 | https://courses.cs.washington.edu/courses/csep590b/23au/ — textbook and first-chapter course assignments | Autumn 2023; author taught course; not independent appraisal. |
| T7 | https://www.ncsc.gov.uk/collection/risk-management/threat-modelling — Model/Analyse and risk-decision sections | Current retrieved NCSC advice; exact page revision date unknown. |
| T8 | https://www.sei.cmu.edu/blog/stop-imagining-threats-start-mitigating-them-a-practical-guide-to-threat-modeling/ — Four Questions, CAPEC and mitigation mapping | Carnegie Mellon SEI, published 2025-05-15. |
| T9 | https://www.threatmodelingmanifesto.org/ — values, practices and four questions; https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html — common modeling approaches | Dates unspecified; manifesto includes the book's author; neither is independent book-review evidence. |
| T10 | https://adam.shostack.org/books/threat-modeling-book/supplemental — first-edition errata and source list | Errata page last-updated 2018-06-25, printing coverage uncertain. |
| T11 | https://adam.shostack.org/books/threat-modeling-book-2nd-edition — next-edition projected publication announcement | Future date 2027-02-02; notice update unspecified, not published-edition evidence. |

## Next genuine later-run review

Independently recheck a second worked original attack or requirements section, and map at least two significant errata to the chosen first-edition text. Confirm actual course use without borrowing future second-edition evidence. Test classification against broad Security Engineering and requirements readers. This recommendation remains **pending** later-run review and final audit.
