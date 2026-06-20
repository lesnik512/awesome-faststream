<!-- lint disable double-link -->

# Awesome FastStream [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome libraries, tools, templates, and resources for [FastStream](https://github.com/ag2ai/faststream).

[FastStream](https://github.com/ag2ai/faststream) is an asynchronous Python framework for building event-driven services. It unifies message-broker integration (Kafka, RabbitMQ, NATS, Redis), dependency injection, validation, testing, and AsyncAPI documentation in a single toolkit.

## Contents

- [Official Resources](#official-resources)
- [Brokers and Transports](#brokers-and-transports)
- [Dependency Injection](#dependency-injection)
- [Patterns and Reliability](#patterns-and-reliability)
- [Observability](#observability)
- [Templates and Examples](#templates-and-examples)
- [Community](#community)

## Official Resources

- [FastStream](https://github.com/ag2ai/faststream) - Core asynchronous framework for building event-driven services across Kafka, RabbitMQ, NATS, and Redis.
- [Documentation](https://faststream.ag2.ai) - Official documentation, tutorials, and API reference.
- [faststream-gen](https://github.com/airtai/faststream-gen) - Generate FastStream applications from a natural-language description using AI.
- [FastStream Community](https://github.com/faststream-community) - Community organization hosting plugins, bridges, and templates.

## Brokers and Transports

- [faststream-sqlbroker](https://github.com/faststream-community/faststream-sqlbroker) - SQL-database-backed broker implementation for FastStream.
- [stompman](https://github.com/community-of-python/stompman) - Python STOMP 1.2 client and FastStream broker for STOMP-based messaging.
- [zMQTT](https://github.com/faststream-community/zMQTT) - Pure-asyncio MQTT 3.1.1 and 5.0 client, with no paho dependency, that brings MQTT support to FastStream.

## Dependency Injection

- [dishka-faststream](https://github.com/faststream-community/dishka-faststream) - Dishka dependency-injection integration for FastStream.
- [modern-di-faststream](https://github.com/modern-python/modern-di-faststream) - Modern-DI dependency-injection integration for FastStream.

## Patterns and Reliability

- [faststream-outbox](https://github.com/modern-python/faststream-outbox) - Transactional-outbox integration backed by a PostgreSQL table.
- [faststream-redis-timers](https://github.com/modern-python/faststream-redis-timers) - Redis-backed distributed timer scheduling for FastStream.
- [faststream-concurrent-aiokafka](https://github.com/modern-python/faststream-concurrent-aiokafka) - Concurrent message-processing middleware for FastStream with aiokafka.

## Observability

- [faststream-monitoring](https://github.com/faststream-community/faststream-monitoring) - Example monitoring setup for FastStream services.
- [lite-bootstrap](https://github.com/modern-python/lite-bootstrap) - Bootstrap production-ready microservices with FastStream, OpenTelemetry, Prometheus, and Sentry wired in.

## Templates and Examples

- [fastapi-dishka-faststream](https://github.com/faststream-community/fastapi-dishka-faststream) - Starter template combining FastAPI, dishka, FastStream, SQLAlchemy, and Pydantic.
- [nats-faststream-frontend-demo](https://github.com/faststream-community/nats-faststream-frontend-demo) - Demo connecting a NATS-backed FastStream service to a web frontend.

## Community

- [Discord](https://discord.gg/qFm6aSqq59) - English-speaking FastStream community chat.
- [Telegram](https://t.me/python_faststream) - Russian-speaking FastStream community chat.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
