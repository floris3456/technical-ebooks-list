---
work_id: haverbeke-eloquent-javascript
title: "Eloquent JavaScript"
authors: ["Marijn Haverbeke"]
edition: "Fourth edition (2024); author web text and print differences noted"
publication_year: 2024
isbn_by_format: {}
primary_subject: programming
additional_subjects: [platform-specific-development]
concepts: [javascript, asynchronous-programming, promises, dom, event-handling, modules]
languages: [JavaScript]
technologies: [Node.js, DOM]
difficulty: mixed
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://eloquentjavascript.net/"
last_verified: "2026-10-15"
status: recommended
review_status: passed
reviewed_commit: "3c0c9d505e77a0d99bb5cb641b20d54da9df715c"
---

# Eloquent JavaScript — Fourth edition

## Recommendation and audience

**Recommend for learning JavaScript through explanations, worked programs and substantial exercises**, particularly programmers changing languages and learners willing to work through demanding projects. The mixed difficulty label is a curatorial judgment: introductory syntax is followed by considerably more involved asynchronous and browser programs. This is not a promise of effortless learning from no prior background.

The author identifies the fourth edition (2024); No Starch Press specifies **September 2024**, Marijn Haverbeke and a language/browser/Node structure. The displayed ISBN 9781718504103 is not assigned here to an unverified electronic subtype. The publisher's praise section explicitly contains **third-edition** reviews; it is not used as fourth-edition independent evaluation. [S1], [S2]

## Actual contents and classification

Original chapter 11 develops an asynchronous `fileSizes` example whose shared accumulation loses updates across `await`. The author explains the failure and replaces shared mutation with returned values combined through `Promise.all`. The broken intermediate example is a deliberate teaching step, not an undiscovered erratum. [S3]

Original chapter 14 demonstrates replacing images with text while traversing a live collection, explaining reverse iteration and the different behavior of `querySelectorAll`. That is directly inspected browser programming, not merely an appealing contents list. [S4]

**Programming** is primary because language learning organizes the book. Whole browser and Node sections, corroborated by inspected DOM material, justify **Platform-Specific Development** secondarily. A small interpreter project does not turn it into a comprehensive compiler text. [S1]–[S4]

## Independent adoption and usefulness today

Santa Rosa Junior College's **Spring 2026 CS50C** syllabus names **Eloquent JavaScript, fourth edition**, as required text and assigns specific chapters. Rendered PDF pages 1, 5 and 11 were inspected. The PDF metadata title says Spring 2025, but its actual heading and schedule identify Spring 2026; that conflict is retained rather than silently rewriting dates. Course adoption supports instructional relevance, not superior learning outcomes. [S6]

Promises, asynchronous control flow and DOM manipulation remain useful concepts. Current MDN documentation separates settled from resolved promises and notes that promises do not themselves provide a general cancellation mechanism. Node's filesystem reference warns that concurrent promise-based modifications are not automatically synchronized. These checks support relevance while limiting assumptions that async syntax eliminates races. [S7], [S8]

ECMA-262 now identifies **ECMAScript 2026, 17th edition (June 2026)**, whereas the publisher targets ECMAScript 2024. The book is a conceptual foundation, not a complete current language specification or compatibility table. [S2], [S9]

## Limitations, alternatives and corrections

**Correction after inspecting the original:** chapter 14 says inline CSS styles *always win*. That is overbroad: cascade origin, `!important`, element-attached styles and cascade layers have ordering rules under W3C CSS Cascade Level 5, §6.1. This is a real limitation of the short CSS exposition, not evidence the central JavaScript/DOM instruction is obsolete. Chapter 11 analogizes `async` functions to generators; its purpose is explaining suspension, **not** asserting that ordinary async functions return iterators. Ordinary `async` functions return Promises; `function*` returns an iterator; `async function*` is a separate construct. See [S3], [S4], [S11]–[S13].

The original fourth-edition errata identify a missing earlier definition on p.104 and an invalid generator template on p.407, plus smaller illustration/wording corrections. Consult the corrections; no error-free or all-printings claim is made. The print contents include an additional performance chapter not in the main web chapter list, so exact print/web coverage or pagination is not assumed. [S1], [S2], [S5]

For a specific modern React application, current framework guidance covers concerns beyond this language foundation; its existence does not make learning DOM and JavaScript obsolete. For browser internals, compare the separately catalogued [Web Browser Engineering](panchekha-harrelson-web-browser-engineering.md), which implements a browser rather than primarily using browser APIs. This is task-based positioning, not a measured ranking. [S10]

No full-book reading, exercise execution, complete errata audit or contemporary package-compatibility test was performed. Availability, price and age did not determine inclusion. No later completed edition was established from the inspected official pages.

## Evidence ledger

All sources accessed **2026-10-15**; dates below are original publication/update information, not access dates.

| ID | Exact source and inspected locator | Source date / role |
| --- | --- | --- |
| S1 | [Author home](https://eloquentjavascript.net/), fourth-edition label and Parts I–III | Edition 2024; page revision unknown |
| S2 | [No Starch Press](https://nostarch.com/eloquent-javascript-4th-edition), identity, contents and third-edition-review label | September 2024; publisher, not independent appraisal |
| S3 | [Original ch11](https://eloquentjavascript.net/11_async.html), shared-state `fileSizes` failure and correction | Fourth-edition web text; revision unknown |
| S4 | [Original ch14](https://eloquentjavascript.net/14_dom.html), Creating Nodes and Query Selectors | Fourth-edition web text; revision unknown |
| S5 | [Author errata](https://eloquentjavascript.net/errata.html), four fourth-edition items | Item update dates unspecified |
| S6 | [Santa Rosa syllabus](https://portal.santarosa.edu/SrWeb/SR_DisplayDocument.aspx?SectionDocumentID=13469#page=5), rendered pp.1,5,11 | Body Spring 2026; metadata title says Spring 2025 |
| S7 | [MDN Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise), Description and chaining | Current official reference; exact revision not recorded |
| S8 | [Node filesystem reference](https://nodejs.org/api/fs.html#promises-api), concurrency warning | Displayed v26.12.0; no LTS-status assertion |
| S9 | [ECMA-262](https://ecma-international.org/publications-and-standards/standards/ecma-262/), normative edition statement | 17th edition, June 2026 |
| S10 | [React application guide](https://react.dev/learn/creating-a-react-app), framework versus from-scratch scope | Current guide; update unspecified |
| S11 | [CSS Cascade Level 5](https://www.w3.org/TR/css-cascade-5/), §6.1 Origin/Importance and Element-Attached Styles | W3C Candidate Recommendation Snapshot, 2022-01-13; not book appraisal |
| S12 | [MDN async functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function), Return value and Description | Current reference, exact update unknown |
| S13 | [MDN async generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function*), Syntax and Description | Current reference, exact update unknown |

## Subsequent-run review (2026-10-15)

**Passed**, assessing the earlier published book record at `3c0c9d505e77a0d99bb5cb641b20d54da9df715c`, not self-approving a new entry. Reopened chapter 14 live DOM transformations and erroneous CSS cascade simplification; original chapter 11 Promise/generator explanation; inspected the previously saved exact-edition Santa Rosa Spring 2026 body/schedule and its older metadata conflict. Cross-checked CSS Level 5 §6.1 and separate current async function/generator references. Independent educational adoption and useful language instruction remain supported; correction and limitations are added, rather than hiding the flaw. No full JavaScript test suite, all-printings errata audit or final collection audit is claimed.

## Next review

Passed later-run review; future audit: Recheck exact-edition syllabus evidence and its date conflict, one original async/DOM example, the print-only chapter boundary and significant errata. Compare audience fit against a focused JavaScript reference; do not substitute older-edition publisher praise for independent fourth-edition evidence.

[S1]: https://eloquentjavascript.net/
[S2]: https://nostarch.com/eloquent-javascript-4th-edition
[S3]: https://eloquentjavascript.net/11_async.html
[S4]: https://eloquentjavascript.net/14_dom.html
[S5]: https://eloquentjavascript.net/errata.html
[S6]: https://portal.santarosa.edu/SrWeb/SR_DisplayDocument.aspx?SectionDocumentID=13469#page=5
[S7]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
[S8]: https://nodejs.org/api/fs.html#promises-api
[S9]: https://ecma-international.org/publications-and-standards/standards/ecma-262/
[S10]: https://react.dev/learn/creating-a-react-app

[S11]: https://www.w3.org/TR/css-cascade-5/
[S12]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
[S13]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function*
