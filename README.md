# Sajid Manzoor

**Backend Developer | Java · Apache Kafka · Kafka Connect · Spring Boot**

I build backend systems with an emphasis on reliable integrations, event-driven architecture, and operational resilience.

[![GitHub](https://img.shields.io/badge/GitHub-sajuu730-181717?logo=github)](https://github.com/sajuu730)

## Featured engineering projects

### 1. Kafka Connect Toolkit
[![CI](https://github.com/sajuu730/kafka-connect-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/sajuu730/kafka-connect-toolkit/actions/workflows/ci.yml)

A Java 17 multi-module project with a custom REST source connector and JDBC sink connector.
- Incremental source offsets and stable-ID checkpointing
- HTTP pagination, bounded retries and rate-limit handling
- JDBC batching, transactions, upsert and malformed-record DLQ reporting
- Docker Compose integration environment with Kafka, Schema Registry, MySQL, Prometheus and Grafana

**Stack:** Java 17, Kafka Connect 3.8.1, Maven, Testcontainers, Docker, MySQL, Prometheus, Grafana.

[Repository](https://github.com/sajuu730/kafka-connect-toolkit) · [Architecture](https://github.com/sajuu730/kafka-connect-toolkit/blob/main/docs/architecture.md) · [Operations guide](https://github.com/sajuu730/kafka-connect-toolkit/blob/main/docs/operations.md)

### 2. Kafka Connect Ops Guardian
[![CI](https://github.com/sajuu730/kafka-connect-ops-guardian/actions/workflows/ci.yml/badge.svg)](https://github.com/sajuu730/kafka-connect-ops-guardian/actions/workflows/ci.yml)

A Spring Boot service for monitoring Kafka Connect distributed clusters and coordinating guarded task recovery.
- Polls connector and task status through the Connect REST API
- Detects failed tasks and classifies common failure signatures
- Optional task restart guarded by rolling-window limits and cooldown
- Prometheus metrics and structured incident webhook delivery
- Docker and Kubernetes deployment examples

**Stack:** Java 21, Spring Boot, Kafka Connect REST API, Micrometer, Prometheus, Docker, Kubernetes.

[Repository](https://github.com/sajuu730/kafka-connect-ops-guardian) · [Architecture](https://github.com/sajuu730/kafka-connect-ops-guardian/blob/main/docs/architecture.md) · [Configuration](https://github.com/sajuu730/kafka-connect-ops-guardian/blob/main/docs/configuration.md)

## Technical skills

| Area | Technologies |
|---|---|
| Languages | Java, Python, SQL |
| Streaming | Apache Kafka, Kafka Connect, Avro, Schema Registry |
| Backend | Spring Boot, REST APIs, JDBC |
| Reliability | Retries, backoff, idempotent writes, DLQ, health monitoring |
| DevOps | Docker, Docker Compose, Kubernetes, GitHub Actions |
| Observability | Prometheus, Grafana, Micrometer, JMX |

## Engineering interests

Distributed systems · Event-driven architecture · Resilient integrations · Backend reliability · Cloud-native services

## Connect

- GitHub: [@sajuu730](https://github.com/sajuu730)

---

*The repositories document implemented behavior, automated test coverage, and known limitations. CI badges reflect the latest workflow status; they are not production-readiness certifications.*
