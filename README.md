<!-- lint disable double-link -->

# Awesome FastStream [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Asynchronous Python framework for building event-driven services across Kafka, RabbitMQ, NATS, and Redis.

<a href="https://faststream.ag2.ai"><img align="right" width="120" alt="FastStream" src="https://raw.githubusercontent.com/ag2ai/faststream/main/docs/docs/assets/img/logo.svg"></a>

[FastStream](https://github.com/ag2ai/faststream) gives you one API for several message brokers, plus typed messages, dependency injection, testing helpers, and generated AsyncAPI docs. The libraries, integrations, and templates below build on top of it.

## Contents

- [Official Resources](#official-resources)
- [Brokers and Transports](#brokers-and-transports)
- [Dependency Injection](#dependency-injection)
- [Patterns and Reliability](#patterns-and-reliability)
- [Observability](#observability)
- [Templates](#templates)
- [Community](#community)

## Official Resources

- [FastStream](https://github.com/ag2ai/faststream) - The core framework, with one consistent API over Kafka, RabbitMQ, NATS, and Redis.
- [Documentation](https://faststream.ag2.ai) - Guides, tutorials, and the full API reference.
- [FastStream Community](https://github.com/faststream-community) - Organization that collects community plugins, framework bridges, and templates.

## Brokers and Transports

- [faststream-mq](https://github.com/davzucky/faststream-mq) - Standalone IBM MQ broker adapter for FastStream.
- [stompman](https://github.com/community-of-python/stompman) - STOMP 1.2 client that also works as a FastStream broker.

## Dependency Injection

- [dishka-faststream](https://github.com/faststream-community/dishka-faststream) - Wires the Dishka container into FastStream handlers.
- [modern-di](https://github.com/modern-python/modern-di) - DI framework with an IoC container and scopes; its [FastStream integration](https://github.com/modern-python/modern-di-faststream) plugs it into handlers.

## Patterns and Reliability

- [faststream-outbox](https://github.com/modern-python/faststream-outbox) - Transactional outbox that uses a PostgreSQL table as the queue, so messages publish only after the surrounding transaction commits.
- [faststream-redis-timers](https://github.com/modern-python/faststream-redis-timers) - Schedules delayed and recurring messages with Redis-backed distributed timers.
- [faststream-concurrent-aiokafka](https://github.com/modern-python/faststream-concurrent-aiokafka) - Processes Kafka messages concurrently within a partition via aiokafka middleware.
- [taskiq-faststream](https://github.com/taskiq-python/taskiq-faststream) - Adds Taskiq task scheduling to FastStream, for cron and delayed message publishing.

## Observability

- [faststream-monitoring](https://github.com/faststream-community/faststream-monitoring) - Example OpenTelemetry and Prometheus monitoring setup for FastStream.
- [lite-bootstrap](https://github.com/modern-python/lite-bootstrap) - Wires OpenTelemetry, Prometheus, Sentry, and health checks into FastStream and web services with little setup.

## Templates

- [fastapi-dishka-faststream](https://github.com/faststream-community/fastapi-dishka-faststream) - Starter project pairing FastAPI and FastStream with Dishka, SQLAlchemy, and Pydantic.

## Community

- [Discord](https://discord.gg/qFm6aSqq59) - Chat with the FastStream community in English.
- [Telegram](https://t.me/python_faststream) - Russian-speaking FastStream chat.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
