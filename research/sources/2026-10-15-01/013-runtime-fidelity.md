# Batch 013 — substantive runtime-fidelity checks

Accessed 2026-10-15; original update dates unspecified unless noted.

- https://web-platform-tests.org/ — original project purpose, test-source versus result-archive roles and cross-browser compatibility methodology read. This corroborates the large conformance gap between a teaching browser and production engines, not a textbook endorsement.
- https://vitest.dev/guide/browser/ — original Browser Mode examples and Limitations: native ESM namespaces constrain spying; blocking dialogs are mocked; event simulation differs from protocol-driven interactions. Even browser-based test environments have fidelity boundaries. No tests executed.
- https://www.sqlite.org/lang_update.html — original §§1–2: UPDATE modifies stored row values, not schema; §2.2 warns of product-specific UPDATE-FROM and arbitrary matching rows. Supports concrete SQL correction and implementation caveats in the FoDE review.
- https://webkit.org/blog/17818/announcing-interop-2026/ — original WebKit announcement returned; detailed focus areas to inspect next. New webkit.org family, not a second credit for earlier search snippets.

These technical documents give independently checkable current-practice constraints. They do not turn author/publisher material into independent evaluation of a book.
