# Hi, I'm Angel 👋

**Senior Platform Engineer** | Distributed Systems | Go | 0→1 Builder

I architect platform infrastructure from 0→1, scaling systems from prototype to production. Deep experience in Kubernetes, distributed systems, integration architecture, and production operations. Currently building distributed systems tooling in Go — focusing on observability patterns and infrastructure lifecycle management.

## 🔧 What I'm Working On

**[jwtauth](https://github.com/aetomala/jwtauth)** - Stateful JWT authorization engine for Go. Most JWT libraries handle issuance and validation. jwtauth handles the part that comes after: token state management, key rotation, refresh lifecycle, and the operational observability to run it in production. Pluggable backends, structured logging, Prometheus metrics, and OpenTelemetry tracing — all wired in at construction. v1.0.0 stable.  
`Go` `Platform Engineering` `Distributed Systems` `Observability`

*Recent: Comprehensive documentation overhaul complete — migration guides, architecture decision records, and visual diagrams*

**[token-engine](https://github.com/aetomala/token-engine)** — A production-grade gRPC microservice that operationalizes jwtauth as a network service. Multi-tenant token lifecycle management over gRPC — with a six-interceptor chain, full OpenTelemetry instrumentation, Redis-backed distributed state, and zero-downtime key rotation at scale. Where jwtauth solves the library problem, token-engine solves the deployment problem.
`Go` `gRPC` `Microservices` `OpenTelemetry` `Kubernetes`

## 💡 Technical Focus

- **Platform Engineering**: Kubernetes infrastructure, multi-tenant platforms, container orchestration
- **Integration Architecture**: Distributed systems, API design, service provider onboarding
- **Observability & Operations**: Prometheus/Grafana, SLIs/SLOs, automation-first reliability
- **Infrastructure**: Terraform, CI/CD pipelines, secrets management, database operations
- **Languages**: Go (primary), Java, Node.js, Python (scripting)

## 📚 Continuous Practice

I explore production Go patterns through focused projects:

- **[fileprocessor](https://github.com/aetomala/fileprocessor)** - Worker pool patterns and bounded parallelism (30+ tests)
- **[lastmodstore](https://github.com/aetomala/lastmodstore)** - Thread-safe TTL cache with graceful shutdown (67 tests)
- **[gstorage](https://github.com/aetomala/gstorage)** - Concurrent file operations and worker pools (62 tests)

All projects include comprehensive test suites, race detection, and CI/CD pipelines.

## 🎯 Engineering Philosophy

**Good software is observable, testable, and maintainable.** I design systems with these properties as first-class concerns, not afterthoughts.

- Write tests first, watch them fail, make them pass
- Observability isn't optional - log, measure, trace everything
- Simple solutions that handle edge cases beat complex solutions that don't
- Production code needs graceful shutdown, proper error handling, and clear lifecycle management

## 📫 Let's Connect

- **GitHub**: You're already here!
- **LinkedIn**: [linkedin.com/in/angel-tomala-reyes](https://www.linkedin.com/in/angel-tomala-reyes/)
- **Email**: [angel.tomala.reyes@gmail.com](mailto:angel.tomala.reyes@gmail.com)

---

*Building systems that work when it matters.*
