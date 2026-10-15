# Batch 013 — rotating older database recommendation, primary comparison

Accessed 2026-10-15. PostgreSQL.org and db-book.com were already in old book ledgers, **zero new website credits**.

- https://www.postgresql.org/docs/15/release-15.html — original PostgreSQL 15 release notes, **published 2022-10-13**, §E.20.3.1.5 Monitoring: cumulative statistics now shared memory; former separate statistics collector process removed. This remains a concrete obsolete implementation detail in the seventh-edition textbook. Page banner October 15 2026 says PostgreSQL 19 RC1, **not** a stable version promise.
- https://db-book.com/online-chapters-dir/32.pdf — original seventh-edition online chapter 32 (PostgreSQL). PDF 58 pages; rendered **zero-index page 4**, printed p.5, §32.3 *Storage and Indexing*, read system file layout, tablespaces and heap slotted-page structure. Long-lived storage concepts distinct from old process assumptions; other pages not freshly rendered, so do not claim a full-chapter re-read. Original chapter updated 2019-09-27 in existing ledger; access 2026-10-15.
- https://www.postgresql.org/docs/current/monitoring-stats.html — current documentation resolved PostgreSQL 18 monitoring §27.2 cumulative statistics. Used for contemporary implementation boundary, not an endorsement of all book statements. Version 18 displayed; exact page update date unknown.

Older record remains qualified: relational calculus, transaction/storage fundamentals stay applicable; version-specific PostgreSQL internals require current manual. No extra subsequent-review pass, no content/metadata changes needed.
