# Batch 007 — runtime and errata checks

Accessed 2026-10-15. New sites opened: ecma-international.org, nostarch.com, python.org. Their relevant body content needs targeted inspection where noted; dates not inferred from access.

- https://nodejs.org/api/fs.html#promises-api — inspected warning that concurrent modifications through promise-based filesystem methods are not synchronized/threadsafe. Displayed v26.12.0; no LTS claim. Returning site this cycle.
- https://html.spec.whatwg.org/multipage/webappapis.html#event-loops — inspected §8.1.6.6.4 promise-job scheduling and §8.1.7 task/microtask distinction. Live standard, update unspecified. Returning site this cycle.
- https://eloquentjavascript.net/11_async.html — inspected shared-state `fileSizes` failure around await and corrected return-values/Promise.all approach. A deliberately broken teaching example is not an author-undetected bug. Fourth edition 2024, web update unknown.
- https://eloquentjavascript.net/errata.html — actual fourth-edition errata read: p.104 missing earlier definition, p.304 missing screenshot fields, p.322 wording, p.407 generator asterisk placement. No exhaustive all-printing clearance.
- https://www.oreilly.com/catalog/errata.csp?isbn=9781098108304 — confirmed p.273 UPDATE/DML correction and March 20, 2026 corrected date inspected. Earlier exact-string search failure did not mean the erratum was absent.
- https://www.ecma-international.org/publications-and-standards/standards/ecma-262/ -> https://ecma-international.org/publications-and-standards/standards/ecma-262/ — official standard page returned; publication details to inspect.
- https://nostarch.com/eloquent-javascript-4th-edition — publisher edition listing returned; exact dates/contents to inspect.
- https://docs.python.org/3/library/asyncio.html — official asyncio entry returned, labeled Python 3.15.0; relevant explanatory body to inspect. Not proof of compatibility of book programs.
