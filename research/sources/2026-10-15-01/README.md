# Cycle 2026-10-15-01 — source audit

**22 distinct newly investigated website families yielded substantive evidence**, checked against the preserved registries and cycle10/11/12 records at starting commit `f215171185fb7aeeb89a5cede06a006995bf6466`. Repeated pages and screenshots add no credits. The browser-book author blog is merged with its book site; Oxford hosts are one family. Source count is not an independent-review count.

All access dates in this cycle are **2026-10-15**. Each numbered log preserves source publication/update dates or explicitly states they were not established. The date a page was opened is not evidence it was newly published. Earlier unrecorded failed browsing cannot be reconstructed.

## New website audit

| # | Website and exact inspected source | Substantive contribution | Logs |
| --- | --- | --- | --- |
| 1 | [eloquentjavascript.net](https://eloquentjavascript.net/11_async.html) | Original fourth-edition async and DOM reasoning; errata | 004,005,007,015,016 |
| 2 | [santarosa.edu](https://portal.santarosa.edu/SrWeb/SR_DisplayDocument.aspx?SectionDocumentID=13469#page=5) | Rendered exact-edition required reading and chapter assignments; date conflict | 004,005 |
| 3 | [obeythetestinggoat.com](https://www.obeythetestinggoat.com/book/ai_preface.html) | Third-edition scope and author argument; independent evidence still missing | 004,008,010,016 |
| 4 | [browser.engineering](https://browser.engineering/scheduling.html) | Original task/thread mechanism and admitted omissions | 006,008,009,010,015 |
| 5 | [washington.edu](https://courses.cs.washington.edu/courses/cse493x/23sp/) | Actual 2023 online-text course implementation/exercises | 006,015 |
| 6 | [mozilla.org](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) | Promise states, chaining and cancellation limits | 006 |
| 7 | [whatwg.org](https://html.spec.whatwg.org/multipage/webappapis.html#event-loops) | Normative tasks/microtasks and promise jobs | 006,007 |
| 8 | [nodejs.org](https://nodejs.org/api/fs.html#promises-api) | Filesystem promise concurrency warning | 006,007 |
| 9 | [ecma-international.org](https://ecma-international.org/publications-and-standards/standards/ecma-262/) | 2026 normative edition versus a 2024 textbook | 007,009 |
| 10 | [nostarch.com](https://nostarch.com/eloquent-javascript-4th-edition) | Identity, fourth-edition scope and older-edition-review label | 007,009 |
| 11 | [python.org](https://docs.python.org/3/library/asyncio.html) | Current async I/O/task model and platform constraints | 007,009 |
| 12 | [djangoproject.com](https://docs.djangoproject.com/en/5.2/topics/testing/overview/) | Test isolation, database/context and cache boundaries | 008 |
| 13 | [selenium.dev](https://www.selenium.dev/documentation/webdriver/waits/) | Document readiness versus async changes; wait-strategy caveats | 008 |
| 14 | [palletsprojects.com](https://flask.palletsprojects.com/en/stable/testing/) | Fixtures, client-versus-live-server and request-context limits | 008,010 |
| 15 | [testing-library.com](https://testing-library.com/docs/guiding-principles/) | User-facing tests and simulated-environment tradeoffs | 008,010 |
| 16 | [oup.com](https://academic.oup.com/book/59224) | Electronic/print publication dates, authors, online ISBN and matching chapter titles | 010,011,016 |
| 17 | [web-platform-tests.org](https://web-platform-tests.org/) | Cross-browser compatibility methodology and source/result distinction | 011,013 |
| 18 | [vitest.dev](https://vitest.dev/guide/browser/) | Native-browser testing limits, module spies and dialogs | 011,013 |
| 19 | [react.dev](https://react.dev/learn/creating-a-react-app) | Current framework-versus-learning-from-scratch distinction | 011,012,014 |
| 20 | [javascript.info](https://javascript.info/event-loop) | Original teaching example for microtask versus timeout ordering | 011,012 |
| 21 | [sqlite.org](https://www.sqlite.org/lang_update.html) | Row-update semantics and product-specific SQL behavior | 011,013 |
| 22 | [webkit.org](https://webkit.org/blog/17818/announcing-interop-2026/) | Dated 2026 implementation/interoperability work | 012,013,014 |

The WPT and WHATWG sites serve different project roles, but both are part of the broader web-standards ecosystem. Even withholding WPT as a separate ecosystem credit leaves **21**; website diversity must not be portrayed as 22 independent book appraisals.

## Returning sources and unsuccessful work

Revisited Feathers' publisher sample and original Petersen review, FoDE original previews/review/errata, and Kalbag's HTML chapter with WAI labels. These strengthen review depth but are not new sites. The Tartu course re-fetch failed. Oxford's storefront initially returned only a robot-check page; Oxford Academic bibliography loaded without bypassing it, but chapter-link resolution later failed. Source boundaries remain in the records.

Search results—including irrelevant, retail and provenance-uncertain hits—were logged as discovery only. No retail prices, stock, PDF access or purchase links affected selection. No unauthorized book copy, credential, CAPTCHA submission or access-control workaround was used.

## Chronological records

[000 start](000-start.md) · [001 pending reviews](001-pending-reviews.md) · [002 review depth](002-review-depth.md) · [003 discovery](003-platform-discovery.md) · [004 openings](004-platform-openings.md) · [005 adoption/browser discovery](005-browser-and-js-evidence.md) · [006 platform primary](006-browser-platform-primary.md) · [007 runtime/errata](007-runtime-and-errata.md) · [008 testing/browser](008-testing-and-browser-depth.md) · [009 details](009-source-detail-checks.md) · [010 limits/identity](010-inspection-limits-and-book-identity.md) · [011 conformance/edition](011-conformance-and-edition.md) · [012 discovery/current standards](012-discovery-and-current-standards.md) · [013 fidelity](013-runtime-fidelity.md) · [014 older rotation](014-crosschecks-and-older-rotation.md) · [015 final content](015-final-content-checks.md) · [016 edition/link limits](016-edition-boundaries-and-failed-links.md).

Every external retrieval batch was logged in Git before the next external batch. Some initial opens returned only navigation or metadata; only later body inspection earned substantive credit. Source checkpoints are not separate research cycles or book approvals.

## Outcomes

Two new recommendations, both pending later review: Eloquent JavaScript fourth edition and Web Browser Engineering with explicit online/print boundaries. Two older pending books passed later-run review. Python TDD third edition remains deferred for independent-evidence gaps. Kalbag's earlier qualified assessment was retained after a targeted recheck. No recommendation was removed and no taxonomy split was justified. See [STATE](../../STATE.md) and [UNSELECTED](../../UNSELECTED.md).
