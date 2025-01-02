Architectural decisions
==

**All architectural decisions must be documented in form of [ADRs](https://adr.github.io/) in the [knowledge base](../sprint-0/knowledge-base.md#technical-documentation)**

Most decisions related to the architecture of your systems and applications involve some level of tradeoffs.
It's very important to discuss and document what architectural attribute are we trading off in favor of what other qualities (which are more important at the point when the decision is being made).

Some decisions (this is not meant to be an exhaustive list of decisions):

- Deployment strategy
  - Modular Monolith a.k.a. "Modulith"
  - Microservices
  - Blue/green deployment
  - Zero downtime deployments
- Fully consistent vs eventual consistency
- Synchronous vs Asynchronous communication style
- Recovering from failures
- Availability
- Fault tolerance
- Disaster recovery
- Scalability
- Major design decisions