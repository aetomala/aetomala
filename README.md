# Hi, I'm Angel 👋
**Senior Platform Engineer** | Distributed Systems | Go | 0→1 Builder

I architect platform infrastructure from 0→1, scaling systems from prototype to production. Deep experience in Kubernetes, distributed systems, integration architecture, and production operations.

On my own time, I look for infrastructure gaps that most teams hit and few solve properly — then build the primitive and write through the design decisions in public. Right now I'm bringing worklease to a stable 1.0 before starting anything new.


## 🔧 Projects

**[jwtauth](https://github.com/aetomala/jwtauth)** — Stateful JWT authorization engine for Go. Most JWT libraries handle issuance and validation. jwtauth handles the part that comes after: token state management, key rotation, refresh lifecycle, and the operational observability to run it in production. Pluggable backends, structured logging, Prometheus metrics, and OpenTelemetry tracing — all wired in at construction. v1.0.0 stable.  
`Go` `Platform Engineering` `Distributed Systems` `Observability`

**[token-engine](https://github.com/aetomala/token-engine)** — A production-grade gRPC microservice that operationalizes jwtauth as a network service. Multi-tenant token lifecycle management over gRPC — with a six-interceptor chain, full OpenTelemetry instrumentation, Redis-backed distributed state, and zero-downtime key rotation at scale. Where jwtauth solves the library problem, token-engine solves the deployment problem.  
`Go` `gRPC` `Microservices` `OpenTelemetry` `Kubernetes`

📖 *Both projects are covered in a three-part series, [JWT as Infrastructure](https://medium.com/@angel.tomala.reyes/the-authentication-gap-what-happens-after-you-prove-who-you-are-9665ceede1ba), on Level Up Coding.*

**[worklease](https://github.com/aetomala/worklease)** — A Go library for lease-based work coordination in distributed systems. Most locking primitives answer who owns a resource. worklease answers what the next owner needs to continue the work the previous owner started — checkpoint state, fencing tokens, and clean handoff vs crash recovery, built on a single atomic backend operation. Where distributed locks solve presence, worklease solves continuity. v0.5.0.  
`Go` `Platform Engineering` `Distributed Systems` `PostgreSQL`

📖 *Covered in a three-part series, [Distributed Locks Don't Coordinate Work](https://medium.com/gitconnected/distributed-locks-dont-coordinate-work-c6251135176d), on Level Up Coding.*

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
