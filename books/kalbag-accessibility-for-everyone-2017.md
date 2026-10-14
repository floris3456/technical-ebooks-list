---
work_id: kalbag-accessibility-for-everyone
title: "Accessibility for Everyone"
authors: ["Laura Kalbag"]
edition: "Original 2017 edition; author-hosted online text, not a second edition"
publication_year: 2017
isbn_by_format: {}
primary_subject: user-experience-and-human-computer-interaction
additional_subjects: [platform-specific-development]
concepts: [web-accessibility, inclusive-design, semantic-html, keyboard-navigation, user-testing]
languages: []
technologies: [HTML]
difficulty: beginner
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://accessibilityforeveryone.site/"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "5aaf861920311aeb9b335600078847a93934ae18"
---

# Accessibility for Everyone — Laura Kalbag (2017)

## Recommendation and audience

**Recommend as an approachable introduction to inclusive web design for designers, developers, content authors and testers.** Its teaching objective is to incorporate accessibility throughout product work, not to teach a complete 2026 ARIA or framework implementation reference. The original author-hosted book calls itself the **2017 original**, says a second edition has **not** been written, and expressly cautions that tools and some roles have aged. Do not invent a new edition because the author restored web publication. [S1], [S2]

This cycle read selected full author chapters and two independent firsthand reviews, not every book page or an exhaustive compliance audit. Earlier publication date and acquisition status were **not** reasons for selection or exclusion.

## Contents and classification

The author's original chapter 1, **Considering Accessibility**, explains that screen-reader and keyboard access depend on decisions across content, design, product and engineering (paragraphs before *Excuses, Excuses*), and frames inclusion as whole-product design. Chapter 4 **Content and Design** gives concrete descriptive-link text and heading-hierarchy examples; chapter 5 **Accessibility and HTML** addresses native controls, form labels, preserved button states and keyboard navigation. Chapter 6 **Evaluating and Testing** discusses device/browser and assistive-technology test planning, including choosing representative configurations rather than claiming exhaustive coverage. [S2], [S3], [S4], [S5]

**Primary subject: User Experience & Human–Computer Interaction** for inclusive interaction and user needs. **Secondary: Platform-Specific Development** because accessible HTML and browser interactions receive substantive attention, not merely a passing mention. This is not a general-purpose automated software-testing textbook.

## Present-day usefulness and technical currency

The core arguments for inclusive content structure, keyboard access, native HTML semantics, and testing with diverse users remain consistent with the W3C's **WCAG 2.2 Recommendation (2024-12-12)**: perceivable content, keyboard accessibility, semantic relationships, accessible interaction and testable success criteria. The book is a conceptual and practice-oriented gateway; **WCAG 2.2 is the authoritative standards reference** for current technical conformance. The W3C explains it includes later criteria for focus, dragging, target size, assistance and authentication and is distinct from the still-developed next major guidelines version. [S3], [S4], [S5], [S8]

The author's own 2026 note warns that some tools are obsolete and that guidance is evolving. In chapter 6, named historical automation tools and platform anecdotes should **not** be read as current vendor/tooling recommendations. The 2017 law discussion and statistics are not reliable 2026 legal/regulatory advice. Use current regional law and W3C guidance for compliance. [S1], [S5], [S8]

## Independent scrutiny and alternatives

Terence Eden's **2017-09** firsthand review, written from his accessibility and W3C Advisory Committee perspective, found the book especially useful for inclusive team practices and recruiting representative users, while emphasizing it is **not** a detailed ARIA/alt-text manual and disclosing personal acquaintance with the author. Michael Larsen's **2017-09-26** chapter-by-chapter first review independently analyzes why accessibility is cross-team work, including keyboard/navigation lessons. Both reviews apply to the **original** book, not a hypothetical newer edition. [S6], [S7]

There is meaningful counterevidence: a **2020-11-02** critical reader review finds the work too short and implementation-thin, especially with CSS/JS and advanced components. This confirms the intended audience: useful introductory design framing, **not** comprehensive modern implementation. Readers needing deep 2026 solutions should pair it with current W3C techniques and specialist references. [S9], [S8]

## Edition, verification, and unresolved work

The author says first publication was **2017**, and as of the inspected page in **October 2026** no second edition existed. The accessible HTML edition is author-hosted; neither the version nor the source is counted as a new intellectual work. No guessed format-specific ISBN or obsolete purchase link is supplied; price and availability are immaterial. No full errata or every-link audit was performed.

## Evidence ledger

All sources inspected **2026-10-14**. Publication dates below are distinct from that date.

| ID | Exact source and inspected locator | Source date |
| --- | --- | --- |
| [S1] | Author's book homepage, note that 2017 original still useful but tools age, and chapter outline | Original 2017; note references 2026; last page update unknown |
| [S2] | Original chapter 1 *Considering Accessibility*, beginning and *Inclusion* | Original 2017; web last revision unknown |
| [S3] | Original chapter 4 *Content and Design*, descriptive links and *Hierarchy and structure* | Original 2017; revision unknown |
| [S4] | Original chapter 5 *Accessibility and HTML*, *Buttons* and *Keyboard Navigation* | Original 2017; revision unknown |
| [S5] | Original chapter 6 *Evaluating and Testing*, *Device and Browser Testing* and *Choosing your testing suite* | Original 2017; revision unknown |
| [S6] | Terence Eden, independent firsthand review, *What I liked*, *Verdict*, and declared author acquaintance | September 2017 |
| [S7] | Michael Larsen, first long-form review, chapter 1, *Key Takeaway* | 2017-09-26 |
| [S8] | W3C WCAG 2.2 Recommendation, *Abstract*, *WCAG 2 Layers*, and *New Features in WCAG 2.2* | W3C Recommendation 2024-12-12 |
| [S9] | Critical independent reader, Goodreads, Dhuaine, implementation-depth limitations | 2020-11-02; edition unspecified, likely original |

[S1]: https://accessibilityforeveryone.site/
[S2]: https://accessibilityforeveryone.site/considering-accessibility/
[S3]: https://accessibilityforeveryone.site/content-and-design/
[S4]: https://accessibilityforeveryone.site/accessibility-and-html/
[S5]: https://accessibilityforeveryone.site/evaluating-and-testing/
[S6]: https://shkspr.mobi/blog/2017/09/review-accessibility-for-everyone/
[S7]: https://www.mkltesthead.com/2017/09/accessibility-for-everyone-long-form.html
[S8]: https://www.w3.org/TR/WCAG22/
[S9]: https://www.goodreads.com/book/show/36312164

## Subsequent-run assessment (2026-10-14)

**Decision: pass with limitations.** Independently reviewed the published version at `5aaf861920311aeb9b335600078847a93934ae18` against the original author's chapters *Accessibility and HTML* (form labels, native buttons and keyboard interactions) and *Evaluating and Testing*. [W3C Forms Labeling](https://www.w3.org/WAI/tutorials/forms/labels/) corroborates explicit input-label relationships; [WCAG 2.2 technique G202](https://www.w3.org/WAI/WCAG22/Techniques/general/G202) independently confirms keyboard-operation expectations. These are current technical cross-checks, not certification that a 2017 book implements every present standard. [S4], [S5], [S8]

The author's web text remains the original **2017 edition**, not a newly revised edition. Original independent 2017 assessments are relevant to the book's inclusive design teaching but not 2026 browser-tool recommendations. Historic legal examples, named tools and simplistic inference from semantic HTML to complete compliance must be rejected. HCI remains its primary subject; its substantive HTML/browser chapter justifies additional platform-specific development. No full-book or final collection-wide audit is claimed.

## Further checks

Audit outdated legislation in chapter 7, tool-specific recommendations and detailed WCAG 2.2 mapping later. Passed subsequent review is not final-audit approval.
