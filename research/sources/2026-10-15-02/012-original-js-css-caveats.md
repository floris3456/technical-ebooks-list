# Batch 012 — newly identified current-teaching caveats

Accessed 2026-10-15. No new website-family credits: W3C and Mozilla were known in historical research. Original publication dates separate; standards are current references, not a claim that the textbook is freshly updated.

- https://eloquentjavascript.net/14_dom.html — fourth-edition original ch14 *Cascading styles* inspected: text says most recently read CSS rule wins, then qualifies specificity, but also says inline styles have highest priority and always win. CSS cascade precedence is richer (importance, origins, layers); this sentence is overgeneralized, especially for !important styles. The chapter itself says this is a brief CSS introduction, not a complete CSS book. No claim all DOM instruction is obsolete.
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascade/Cascade — redirect https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Cascade/Introduction, original cascade overview returned; prioritize the cascade-origin/importance section rather than only source order. Exact revision date not extracted.
- https://www.w3.org/TR/css-cascade-5/ — original CSS Cascading and Inheritance Level 5 spec returned: ordering via origin/importance/layers, rather than unconditional inline-style priority. Original TR document publication/update date not extracted this batch.
- https://eloquentjavascript.net/11_async.html — original fourth-edition ch11 *Generators* uses an analogy calling async functions a special type of generator. This is pedagogical, not a claim that ordinary async functions have the same JS syntax/interface as async generator functions.
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function — current reference for async function returning Promise, not generator iterator. Date unspecified.
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function* — current separate async-generator syntax; returned article with distinct async iterator semantics. Date unspecified.
- https://www.w3.org/TR/css-values-4/ — CSS values/units module returned; exact dimension token rule still to inspect. Do **not** yet assert that spaced units in the book are genuine source errors versus display/transcription artifacts.

Decision: retain Eloquent JavaScript's strong programming fundamentals but add a precise caveat for CSS cascade and async/generator analogy. Secondary web coverage is useful, not an up-to-date comprehensive CSS/ECMAScript specification.
