Java Application Monitoring and Troubleshooting (part 1)
========================================================
Common Java Application Monitoring and Troubleshooting Overview. 12 hrs, 3 days.

Prerequisites
-------------
- JDK 21
- Maven 3.9
- Docker/Podman + Compose
- VirtualBox / VMWare Workstation / Hyper-V
- JMeter 5 / Gatling 3

Agenda
------

## Training introducing and focusing
## Hands-on: Teams and their demand

## Multi-user System Core Concepts
- Metaphor for Multi-user system
- Metaphor for Threads and its types
- Metaphor for Thread Pools
- Metaphor for Data input
- Metaphor for Data Processing
- Metaphor for Data storage
- Metaphor for Data output
## Hands-on: Why we do monitoring? 

## Multi-user System internals
- How we do model the behavior?
- How we do model the data?
- Where data is stored? Core data scopes
- Java specials
## Hands-on: What metrics do we consider for test, and production environments?

---

## Java Service Runtime Environment Overview
- Hardware: CPU, RAM, HDD/SSD
- OS: Processes, Threads
- Container: Core, Networking
- JVM: process
- JVM: memory, GC
- JVM: threads, IO
- JVM: exceptions
- JVM: JMX universal monitoring API
## Hands-on research: Environment Configuration and Diagnostics and Monitoring 
- Command-line Tools
- JMX Tools
- Exception stack traces

## Java Service Architecture Overview
- Application Server/Servlet Container: Tomcat
- Application Framework: Spring Core, Spring Boot
- Web/SOAP/REST Framework: Spring MVC, Spring WebFlux
- JDBC subsystem, JDBC Connection Pools
- JPA subsystem, JPA Caching
- Thread Pools: types and today's purpose
- Application caching
- Application logic layers: UI/P, API/C, BL/S, DAL/R
## Hands-on research: Spring Boot Application Configuration and Metrics changes monitoring
- Configuration Profiles
- yml/properties Configuration
- Annotation-driven Configuration
- Java-based Configuration

---

## Monitoring Infrastructure Overview
- Application Monitoring endpoint: Spring Actuator, Micrometer
- Node Monitoring endpoint: Node Exporter
- Monitoring aggregation: Prometheus
- Monitoring visualization: Grafana
## Hands-on research: Setup monitoring infrastructure and Metrics monitoring

## Loading Infrastructure Overview
- Load Tools: JMeter, Gatling
- Loading vs Performance Testing
## Hands-on research: Setup loading infrastructure and Metrics monitoring

---

Java Application Monitoring and Troubleshooting (part 2)
========================================================
Deep Dive to Java Application Monitoring and Troubleshooting. 20 hrs, 5 days.

Prerequisites
-------------
- JDK 21
- Maven 3.9
- Docker/Podman + Compose
- VirtualBox / VMWare Workstation / Hyper-V
- JMeter 5 / Gatling 3
- VisualVM 2
- JMC 9

Agenda
------

## JVM Threads Monitoring and Troubleshooting
- Application architecture patterns: where does the threading happen?
- Thread states
- Stack traces
- Exceptions and Stack traces: sync vs async design
- Native threads and Virtual threads
- Threading Patterns: Pools, ForkJoin, Reactive
- Parallelism vs Concurrency
- Typical application design issues
## Hands-on research: Threads monitoring and troubleshooting
- Common Metrics
- Common Issues

---

## CPU Profiling
- Application architecture patterns: What's the CPU doing while running threads?
- Profiling: CPU, Memory, IO, sync events, ...
- Timings: Wall time vs CPU time, method time vs self time, user time vs system time
- Simple Profiler Tools: JConsole, VisualVM
- Modern Profiler Tools: async profiler, JMC
- Typical application design issues
## Hands-on research: Application workload monitoring and profiling
- Common Metrics
- Common Issues

---

## JVM IO Monitoring and Troubleshooting
- Application architecture patterns: where does the IO happen?
- IO architecture styles: sync vs async
- IO architecture patterns: Connection Pools
- Typical application design issues
## Hands-on research: HTTP connections and DB connections monitoring, profiling and troubleshooting
- Common Metrics
- Common Issues

---

## JVM Memory Monitoring and Troubleshooting
- Application architecture patterns: when and where does the memory allocation happen?
- JVM Memory Architecture: Memory regions
- Heap and its structure
- Heap Dumps and Analyser Tools: VisualVM, JMC, IDEA
- Heap profiling: what and who? 
- Core GC concepts and ergonomics
- Core GC algorithms
- Off-heap memory and its structure
## Hands-on research: Application Memory monitoring, profiling and troubleshooting
- Common Metrics
- Common Issues

---

## Persistence Monitoring and Troubleshooting
- Application architecture patterns: persistence layer
- JDBC subsystem architecture
- DB Connection pooling
- JPA architecture
- JPA Caching Level(s)
- Spring Data Repositories
- Typical data access issues
## Hands-on research: Application Persistence monitoring, profiling and troubleshooting
- Common Metrics
- Common Issues
