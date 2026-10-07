# Awesome FastStream [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Asynchronous Python framework for building event-driven services across Kafka, RabbitMQ, NATS, Redis, and MQTT.

<a href="https://faststream.ag2.ai"><img align="right" width="120" alt="FastStream" src="https://raw.githubusercontent.com/ag2ai/faststream/main/docs/docs/assets/img/logo.svg"></a>

FastStream gives you one API for several message brokers, plus typed messages, dependency injection, testing helpers, and generated AsyncAPI docs. The libraries, integrations, and templates below build on top of it.

## Contents

- [Official Resources](#official-resources)
- [Brokers and Transports](#brokers-and-transports)
- [Dependency Injection](#dependency-injection)
- [Patterns and Reliability](#patterns-and-reliability)
- [Observability](#observability)
- [Templates and Examples](#templates-and-examples)
- [Community](#community)

## Official Resources

- [FastStream](https://github.com/ag2ai/faststream) - The core framework, with one consistent API over Kafka, RabbitMQ, NATS, Redis, and MQTT.
- [Documentation](https://faststream.ag2.ai) - Guides, tutorials, and the full API reference.
- [FastStream Community](https://github.com/faststream-community) - Organization that collects community plugins, framework bridges, and templates.

## Brokers and Transports

- [faststream-mq](https://github.com/davzucky/faststream-mq) - Standalone IBM MQ broker adapter for FastStream.
- [kubemq-faststream](https://github.com/kubemq-io/kubemq-faststream) - KubeMQ broker adapter for FastStream.
- [stompman](https://github.com/community-of-python/stompman) - STOMP 1.2 client that also works as a FastStream broker.
- [zMQTT](https://github.com/faststream-community/zMQTT) - Pure asyncio MQTT 3.1.1 and 5.0 client that FastStream's MQTT broker is built on.

## Dependency Injection

- [dishka-faststream](https://github.com/faststream-community/dishka-faststream) - Wires the Dishka container into FastStream handlers.
- [FastDepends](https://github.com/Lancetnik/FastDepends) - Lightweight dependency-injection system, by FastStream's author, that powers FastStream's own dependency injection.
- [faststream_fastapi](https://github.com/faststream-community/faststream_fastapi) - Brings FastAPI's `Depends`, request parameters, and dependency overrides into FastStream handlers; replaces FastStream's deprecated built-in FastAPI integration.

## Patterns and Reliability

- [faststream-outbox](https://github.com/modern-python/faststream-outbox) - Transactional outbox that uses a PostgreSQL table as the queue, so messages publish only after the surrounding transaction commits.
- [faststream-redis-timers](https://github.com/modern-python/faststream-redis-timers) - Schedules delayed and recurring messages with Redis-backed distributed timers.
- [faststream-concurrent-aiokafka](https://github.com/modern-python/faststream-concurrent-aiokafka) - Processes Kafka messages concurrently within a partition via aiokafka middleware.
- [python-cqrs](https://github.com/pypatterns/python-cqrs) - CQRS and event-driven framework that uses FastStream brokers to publish and consume domain events.
- [taskiq-faststream](https://github.com/taskiq-python/taskiq-faststream) - Adds Taskiq task scheduling to FastStream, for cron and delayed message publishing.

## Observability

- [fast-healthchecks](https://github.com/ZYLVEXT/fast-healthchecks) - Health checks for PostgreSQL, Redis, Kafka, RabbitMQ, and more, served as health routes through a FastStream integration.
- [lite-bootstrap](https://github.com/modern-python/lite-bootstrap) - Wires OpenTelemetry, Prometheus, Sentry, and health checks into FastStream and web services with little setup.
- [microbootstrap](https://github.com/community-of-python/microbootstrap) - Bootstraps microservices with Sentry, Prometheus, and OpenTelemetry preconfigured, including for FastStream services.

## Templates and Examples

- [clean-architecture-fastapi-project-template](https://github.com/Peopl3s/clean-architecture-fastapi-project-template) - Cookiecutter template for clean-architecture FastAPI services, with optional Kafka, RabbitMQ, or NATS messaging through FastStream.
- [fastapi-dishka-faststream](https://github.com/faststream-community/fastapi-dishka-faststream) - Starter project pairing FastAPI and FastStream with Dishka, SQLAlchemy, and Pydantic.
- [faststream-monitoring](https://github.com/faststream-community/faststream-monitoring) - Example OpenTelemetry and Prometheus monitoring setup for a FastStream service.

## Community

- [Discord](https://discord.gg/qFm6aSqq59) - Chat with the FastStream community in English.
- [Telegram](https://t.me/python_faststream) - Russian-speaking FastStream chat.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

Curator disclosure: I maintain the [modern-python](https://github.com/modern-python) entries in this list - faststream-outbox, faststream-redis-timers, faststream-concurrent-aiokafka, and lite-bootstrap. I also contribute to microbootstrap and stompman, which are maintained by others.
