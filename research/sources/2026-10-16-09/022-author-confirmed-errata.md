# Individual author-confirmed corrections and primary-current recheck — accessed 2026-10-16

All exact URLs below opened and inspected as full short discussions, NOT copied from search summaries. **Returning Devtalk publisher-linked forum family**, not new domain credits.

* https://forum.devtalk.com/t/sql-antipatterns-volume-1-join-error-page-176/141945 — 2024-02-01 user reports erroneous derived-table join where two products have same max reported date; **Bill Karwin acknowledges the mistake 2024-02-02**, supplies corrected query joining on both date and product ID and grouping, *intends* future printing fix; no evidence the copy/printing already incorporates it.
* https://forum.devtalk.com/t/sql-antipatterns-volume-1-bad-column-in-partition-by-example-page-107/81455 — user 2022-11-05, **author confirms 2022-11-07** wrong partitioning column and suggests explicit TO_DAYS(date_reported) hash.
* https://forum.devtalk.com/t/sql-antipatterns-volume-1-duplicate-column-name-in-replace-into-page-235/81716 — user 2022-11-07, **author confirms same date** duplicate account_id and advises removing second identifier. Examples with errors are not safely copyable without correction.
* https://forum.devtalk.com/t/sql-antipatterns-volume-1-function-error-page-186/142664 — user 2024-02-06 reports round() row selection may yield row_count+1; **no author response on opened thread**. Treat as unverified but plausible boundary, not confirmed fixed or dismissed.
* https://devtalk.com/books/sql-antipatterns-volume-1/errata — book portal reopened; aggregate UI does not prove correction status or source build.
* https://www.postgresql.org/docs/18/indexes-multicolumn.html — section11.3 full re-read: leading columns most efficient; skip scan may apply later-key-only predicate with low distinct leading-key cardinality; version18 current, page revision not stated. Qualifies categorically obsolete advice; not a claim that every optimizer has skip scan.
* https://db.cs.uni-tuebingen.de/teaching/ss24/db2/ — full 2024 course re-read confirms original bibliographic ISBN9783950307818 (German edition), not English edition9783950307825. Source year2024, footer2026 irrelevant.

No examples compiled or queries benchmarked. Research access2026-10-16, source report dates/versions noted separately. 