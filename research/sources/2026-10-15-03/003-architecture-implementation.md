# Batch 003 — original repository pattern and contemporary implementation limits

Access date 2026-10-15; source update/release date stated separately. Opening a page is not executing examples.

- https://www.cosmicpython.com/book/chapter_02_repository.html -> https://www.cosmicpython.com/book/chapter_02_repository : full author chapter 2, *Applying DIP*, *Inverting the Dependency*, *Repository*, *Trade-Off*, *Fake Repository*, *Ports and Adapters*. Original mapped code uses `sqlalchemy.orm.mapper`; examples explicitly add complexity to gain isolation. Old Flask pseudo-endpoint is labeled pseudocode. Returning author site; page original release 2020, web update unspecified.
- https://docs.sqlalchemy.org/en/20/orm/session_basics.html : primary SQLAlchemy **2.0** session guide, session lifecycle / transaction/rollback and context-manager patterns. **New substantive family sqlachemy.org** (spelled sqlalchemy.org). No claim old mapper code unchanged.
- https://redis.io/docs/latest/develop/interact/pubsub/ -> https://redis.io/docs/latest/develop/pubsub/ : 0-line response; **no reading or novelty credit**, retain attempted/resolved URL. Date unknown.
- https://fastapi.tiangolo.com/tutorial/dependencies/ : primary FastAPI dependency injection, nested dependencies and dependency request processing; substantial body. **New substantive family fastapi.tiangolo.com**, update unspecified.
- https://docs.celeryq.dev/en/stable/userguide/tasks.html : Celery **5.6.3**, actual tasks/retry/acknowledgment document; distributed execution requires delivery/retry/side-effect care, not solved by abstract messages alone. **New substantive family celeryq.dev**; release label 5.6.3, page updated date unknown.
- https://microservices.io/patterns/data/transactional-outbox.html : original transactional-outbox pattern, consistency between DB state and events, message relay and possible duplicate publication; documents a production gap in book's basic pub/sub example, not a quality rejection. **New substantive family microservices.io**, exact publication/update unknown.

Four new substantive site families; author site returning; empty Redis response excluded. Current technical documents are relevance checks, not independent judgments of the book.
