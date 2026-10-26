<div align="center">

# Daniil Oleinic

**C# / .NET Backend Developer**

Third-year Software Engineering student at ITMO University

[Email](mailto:dnloeinik@gmail.com) · [Projects](#selected-projects)

**Open to backend internships · Saint Petersburg or remote**

</div>

---

I build backend services and developer tools with on .NET. I enjoy exploring how things work, finding useful problems to solve, and turning ideas into practical projects.
## Stack

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&amp;logo=dotnet&amp;logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square" alt="gRPC" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&amp;logo=apachekafka&amp;logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />
</p>

## Selected projects

### [Workflow Scheduler](https://github.com/danieloileinik/workflow-scheduler)

A business-process orchestrator that coordinates steps across services: sends commands, waits for external events, retries failures, and runs compensating actions.

- Client and Worker SDKs, plus a runnable order-processing demo.
- Unit, integration, and end-to-end tests; k6 workloads for load testing.

<sub>C# · .NET 10 · gRPC · PostgreSQL · Kafka · Redis · Testcontainers · k6</sub>

### [gRPC Safety Analyzers](https://github.com/danieloileinik/grpc-safety-analyzers)

A Roslyn analyzer that catches gRPC call-safety issues during compilation, before running the application.

- Four rules covering missing deadlines, deadline propagation, and retry or hedging policies without an overall deadline or declared idempotency.
- Uses client configuration and `.proto` contracts to identify confirmed violations; unresolved inputs remain unknown.

<sub>C# · Roslyn · gRPC · Protocol Buffers</sub>

### [Conversion Reporter](https://github.com/danieloileinik/conversion-reporter)

An event-driven service that records views and payments, calculates report ratios in PostgreSQL, and serves reports over gRPC.

- Kafka commands, Redis caching, and idempotent command processing.
- Transactional outbox for publishing events, with delivery retries and configurable quarantine.

<sub>C# · .NET 10 · gRPC · PostgreSQL · Kafka · Redis</sub>
