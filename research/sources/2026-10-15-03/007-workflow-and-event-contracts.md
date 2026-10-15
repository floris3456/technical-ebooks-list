# Batch 007 — message delivery, workflow, validation, event contracts

Read 2026-10-15. Original revision dates unavailable unless page shows a version; accessed date is not source publication.

- https://www.cosmicpython.com/book/chapter_11_external_events.html → /book/chapter_11_external_events : original full ch11, temporal coupling, message listener/publisher, Redis pub/sub illustration, acknowledges ordering/failure/idempotency tradeoffs, shows end-to-end test with retry and hardcoded channels. Returning author domain.
- https://docs.temporal.io/workflow-execution : primary workflow execution/durable replay semantics; durable execution versus transient async pub/sub is a specific modern alternative. **New substantive temporal.io**.
- https://docs.nats.io/nats-concepts/what-is-nats → https://docs.nats.io/concepts/what-is-nats : original messaging and NATS core/JetStream positioning; delivery semantics differ and must be checked per service. **New substantive nats.io**.
- https://www.rabbitmq.com/tutorials/tutorial-one-python : original RabbitMQ Python Hello World, producer/queue/consumer introduction; cannot assume no-duplicate or exactly-once processing. **New substantive rabbitmq.com**.
- https://docs.pydantic.dev/latest/concepts/models/ → https://pydantic.dev/docs/validation/latest/concepts/models/ : original model validation/coercion and structuring boundary data, not a universal alternative to domain modeling. **New substantive pydantic.dev**.
- https://docs.sentry.io/product/issues/ : internal retrieval error, no content inspected, no site credit.
- https://www.eventcatalog.dev/docs → https://www.eventcatalog.dev/docs/development/getting-started/introduction : original event-domain documentation intro, discovery/contract description; countercheck coupling to event names and schemas. **New substantive eventcatalog.dev**.
- https://docs.opensearch.org/latest/getting-started/intro/ : official OpenSearch intro and search/index system boundaries; relevance to read-model implementation, not a book evaluation. **New substantive opensearch.org**.

Six new substantive independent website families this batch. Current implementation references support/restrict book concepts, never independent praise of the book.
