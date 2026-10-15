# Batch 009 — authoritative editions, errata, ORM migration

Accessed 2026-10-15. Existing website families O'Reilly and SQLAlchemy, zero newly explored sites.

- https://www.oreilly.com/library/view/architecture-patterns-with/9781492052197/ — publisher *Architecture Patterns with Python*, Harry Percival/Bob Gregory, **March 2020**, 301-page digital listing and chapter contents from domain model, Repository, Unit of Work, aggregates through CQRS/DI; electronic-site identifier 9781492052197, do NOT infer file-specific ISBN. Identity/contents, not independent evaluation.
- https://www.oreilly.com/catalog/errata.csp?isbn=9781492052203 — internal error, no confirmed errata body read; cannot imply absence of errors; target ISBN not verified as electronic edition.
- https://www.oreilly.com/library/view/database-internals/9781492040330/copyright-page01.html — publisher original Alex Petrov *Database Internals*, October 2019 first edition and subsequent release-history visible. Exact release dates to be checked against body: 2019-09-12 first, 2019-10-25 second, 2020-01-31 third, 2020-09-04 fourth in same edition. This does not create four distinct works or necessarily a newer edition.
- https://www.oreilly.com/catalog/errata.csp?isbn=9781492040347 — internal error, no issue list read. Do not assert error-free.
- https://docs.sqlalchemy.org/en/20/changelog/migration_20.html — current official SQLAlchemy 2.0 migration guide. API changes mean 2020 `sqlalchemy.orm.mapper`/legacy `session.execute` code is not drop-in; now use registry mapping and current execution idioms. Precise section/compatibility to recheck before claim of removal; conceptual repository/dependency inversion persists. Version 2.0 docs, exact page revision unspecified.

Known-site revisit only. Source dates distinct from 2026-10-15 access, no code run.
