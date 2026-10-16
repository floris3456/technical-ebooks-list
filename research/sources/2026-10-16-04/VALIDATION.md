# Validation and self-review — 2026-10-16-04

Catalog commit inspected: **ba27c63a3dbc093ceb91dc96a529f8fae76fd059**, tree **80afd3952d874e2ab1dab45aceab244c8083937b**. Starting main: **e0e6c5543a4af14116361ef9d5cbfca29cb8d19e**. Validation occurred before the final conditional publication; the existence of this record alone does not assert that main was updated.

## Actual checks

The authorized GitHub comparison reported **32 commits ahead, zero behind** the starting head, with that head as merge base. Inspected all48 changed-path summaries and self-reviewed the authored record/index/ledger changes. Only four new book records and the intended older Gregg annotation affect canonical books; no existing book file was removed. The remaining changes are README, seven topic files, exact source logs, retained decisions and checkpoint/archive updates. No unrelated branch history was rewritten.

The remote books tree **7996c4917ce74f1768b4a44be3f77d33bef906a3** contains the template plus **34 canonical files**. The two candidate files are Morris and Programming Rust; all other32 files are recommendation records. The baseline had29 distinct recommendation rows; the diff adds three distinct new works without removing or duplicating any baseline row. New work IDs are distinct from one another and from the existing catalog's works. The title/role comparison does not count a format, translation, new edition or secondary index appearance as another work.

Re-fetched the four new canonical frontmatters, Morris's candidate status and Kerrisk's existing pass. New recommendations are pending with null reviewed_commit. Programming Rust is candidate, not recommended. The older Gregg annotation retains the pre-existing qualified pass rather than creating a same-run approval. Kerrisk's stale networking-index label was corrected to match the already passed canonical record.

A local arithmetic/check-digit check on a **transcribed inventory from the GitHub responses**, not a network clone or repository-wide YAML parser, produced:

```
canonical files: 34
recommended works: 32
preserved prior passes: 29
new pending recommendations: 3
canonical candidates: 2
controlled topic rows: 23
subject appearances: 53
registered new website families: 20
checked ISBN-13 check digits: pass
```

Check digits were tested for the explicitly retained identifiers9781718501850,9781098119447,9781098176228 and9780136821649. A valid check digit is not bibliographic identity evidence; identity and format attribution remain sourced separately. No unverified platform identifier was promoted to an ebook-format ISBN.

Manually checked the new/changed primary and additional subjects against TAXONOMY, with no repeated primary in secondary fields; corresponding recommendation indexes add2+2+3 appearances. Candidate files are not included in those indexes. README, topic summary and STATE agree on32/29/3, two canonical candidates and six active deferrals. Bos's superseded deferral is retained historically but not counted as a seventh active deferral.

Self-reviewed the B/G/P/R evidence labels and their exact URL/section mappings. The three recommendations have original technical material and independent appraisal/teaching evidence, not just three seller pages. The fourth candidate explicitly fails the full evidence gate and remains uncounted. Current language/library/operational contracts are distinguished from old reviews and unknown source-update dates. Local book, index, source-log and archive targets added in this cycle match the committed paths; no exhaustive external-link crawler was run.

## Preservation verified by remote Git tree

The fetched research tree **99268870b2315706da05e080978ca3e42fc3d872** confirms the archived files retain the exact original blobs:

| Archive | Original and preserved blob |
| --- | --- |
| research/REJECTIONS-through-e0e6c55.md | 70bd05c246aec17609981bb027d624882bbfc731 |
| research/SOURCES-through-e0e6c55.md | 849ef74f726867ce7fb23e83eca72248d429e913 |
| research/STATE-through-e0e6c55.md | 1b072f36b159d0f31936d98c72d41df3a569005e |

Same-directory archive links preserve their prior relative targets. The working-branch move from d4110f5ba605e46b7fcf55790180c3c4a7ca4a46 to ba27c63a3dbc093ceb91dc96a529f8fae76fd059 already succeeded with force=false and an exact expected head. An encoded-slash branch GET earlier returned a wrapper400; a pinned commit/tree read resolved the inspection need. This was not a permission bypass or a main publication success.

## Limits and final publication

These are structural, metadata and scoped evidence checks, not a fresh factual audit of all32 works. Original-book examples, unsafe algorithms, tests, benchmarks and deployments were not executed. The27 immediate source logs and20-family register preserve partial reads, failures and source-quality limitations. Historical unrecorded browsing and every file in other saved branches were not claimed as inspected.

Before publishing, re-fetch main and use a conditional non-force update against its observed head; inspect/reconcile any intervening changes rather than forcing them away. Verify the resulting remote main SHA and STATE after success. The final response reports the actually observed outcome. All three additions still require a later invocation's review, and the staged final collection audit remains incomplete.

[Source audit](README.md) · [Current STATE](../../STATE.md) · [Retained non-selections](../../UNSELECTED.md).
