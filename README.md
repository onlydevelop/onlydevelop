# Dipanjan Bhowmik

Backend engineer, 25+ years in. Distributed systems, JVM tuning, high-throughput services — most recently worked at Oracle Cloud Infrastructure, where I owned a hardware metrics-ingestion service handling ~100K requests/minute. Currently looking at Staff / Senior Staff roles, and using that search as an excuse to go build things properly rather than just read about them.

What does a career's worth of production incidents actually teach you about system design? Mostly that the interesting decisions are the small ones — where you put a lock, how you name a queue, what you choose *not* to build. The projects below are an attempt to show that thinking directly, at a scale small enough to read in one sitting.

## Start here

| Project | What it demonstrates |
|---|---|
| [ticket-master](https://github.com/onlydevelop/ticket-master) | A deliberately minimal Ticketmaster-style booking system — two Go microservices, row-level Postgres locking for the no-double-booking guarantee, full CI/CD to a k3s cluster on ARM64 EC2 via GitHub Actions and GHCR. |
| [observability-demo](https://github.com/onlydevelop/observability-demo) | End-to-end observability stack — OpenTelemetry traces propagated across services, Prometheus/Loki/Tempo, Grafana dashboards wired up from scratch. |
| [fitness-function-build-gate](https://github.com/onlydevelop/fitness-function-build-gate) | A Gradle/Maven plugin that fails a build when code-smell thresholds are crossed, tested against a deliberately messy legacy codebase. |

## Elsewhere

I write occasionally on engineering and infrastructure topics on LinkedIn. Learning Classical Guitar, managing multiple portfolio in my housing society, and have a excessive curiosity in various things from psychology to photography.

---
*Open to Staff / Senior Staff Engineer conversations — feel free to reach out.*
