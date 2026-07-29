# Dipanjan Bhowmik

Distributed systems engineer stabilizing high-throughput, cloud-native platforms. At Oracle Cloud Infrastructure, owned a metrics ingestion service handling hardware telemetry at scale. At Lexmark, built the AWS deployment pipeline and led legacy-platform refactoring for stability and performance. Now instrumenting AI workloads on the JVM against OpenTelemetry GenAI conventions.

Open to Staff/Principal Engineer roles and contract/consulting work in distributed systems, reliability, observability.

What does a career's worth of production incidents actually teach you about system design? Mostly that the interesting decisions are the small ones — where you put a lock, how you name a queue, what you choose *not* to build. The projects below are an attempt to show that thinking directly, at a scale small enough to read in one sitting.

## Start here


| Project | What it demonstrates |
|---|---|
| [agent-driven-dev-template](https://github.com/onlydevelop/agent-driven-dev-template) | A token-efficient policy framework for AI coding agents — a minimal always-loaded core constitution, with TDD, refactoring, and architecture policies retrieved on demand via tag-based prompt assembly. |
| [ticket-master](https://github.com/onlydevelop/ticket-master) | A deliberately minimal Ticketmaster-style booking system — two Go microservices, row-level Postgres locking for the no-double-booking guarantee, full CI/CD to a k3s cluster on ARM64 EC2 via GitHub Actions and GHCR. |
| [otel-observability-stack](https://github.com/onlydevelop/otel-observability-stack) | End-to-end observability stack — OpenTelemetry traces propagated across services, Prometheus/Loki/Tempo, Grafana dashboards wired up from scratch. |
| [fitness-function-build-gate](https://github.com/onlydevelop/fitness-function-build-gate) | A Gradle/Maven plugin that fails a build when code-smell thresholds are crossed, tested against a deliberately messy legacy codebase. |
| [cloud-native-migration](https://github.com/onlydevelop/cloud-native-migration) | A Spring Boot order-monolith walked through a staged cloud-native migration, PR by PR — statelessness, containerization, health checks, Resilience4j circuit breakers/retries, OTel tracing + Prometheus metrics, K8s manifests, GitHub Actions CI/CD, idempotency keys, and a saga replacing the one-giant-transaction anti-pattern. |


## Elsewhere

I write occasionally on engineering and infrastructure topics on LinkedIn. Learning Classical Guitar, managing multiple portfolio in my housing society, and have a excessive curiosity in various things from psychology to photography.

---
*Open to Staff Engineer / Contractual conversations — feel free to [reach out](https://onlydevelop.github.io/).*
