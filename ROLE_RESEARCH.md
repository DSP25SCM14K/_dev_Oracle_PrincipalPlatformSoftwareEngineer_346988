# Oracle role and company research

**Prepared:** October 8, 2026  
**Resume analyzed:** `_dev_Oracle_PrincipalPlatformSoftwareEngineer_346988.docx`  
**Target:** Oracle Principal Platform Software Engineer (requisition 346988)

## Role analysis

The role title and resume point to senior platform engineering across distributed data, customer workflows, AI/ML integrations, and production operations. At principal level, the work is likely to combine hands-on service design with decisions that shape reusable platform interfaces, operating standards, and technical direction across teams. The exact balance between customer-facing cloud platform work and Oracle's internal developer platform work cannot be confirmed from the requisition number alone.

Two public Oracle postings provide useful adjacent context. Requisition 342714 describes OCI's Developer Platform Builder Tools organization, which builds developer productivity platforms and AI-powered engineering workflows; its principal engineer defines architecture for scalable services across platform engineering, distributed systems, cloud-native technology, ML/LLMs, and developer tools. Requisition 345650 is a different platform role centered on Oracle database fleet engineering and operations. Neither should be read as the full description for requisition 346988.

A reasonable interpretation of principal platform scope is ownership beyond an individual service: turn ambiguous workflows into stable abstractions, define reliability and security expectations, measure adoption and quality, work through API and data ownership boundaries, and align product, platform, data, AI/ML, and operations partners. The resume provides evidence for this shape of work through pilots, reusable platform components, multi-tenant APIs, governed data flows, evaluation tooling, and measurable operational outcomes.

## Oracle and product context

Oracle's current AI Data Platform positioning joins enterprise data, analytics, AI, and governance so teams can move from source data to AI-ready assets and production workflows. Official materials describe cataloging and lineage, Spark-based preparation, workflows and notebooks, model and agent development, and integration with OCI Object Storage, OCI Generative AI, Autonomous AI services, and Oracle Analytics. The platform supports visual and code-first agent construction, including open frameworks such as LangGraph and connections to MCP servers.

For platform engineers, this is a systems problem as much as a model problem. Data needs stable ingestion and normalization; metadata and lineage make assets discoverable and reviewable; identity and policy constrain use; orchestration joins data, tools, and models; evaluation catches quality regressions; and observability makes the result supportable. Oracle's public platform material emphasizes role-based access, audit trails, lineage, traceability, and operation alongside the AI workflows themselves.

OCI's physical architecture also matters for multi-region resilience and data placement. Oracle describes regions as geographic areas and availability domains as isolated data-center groupings; most OCI resources are scoped either regionally or to an availability domain. These boundaries affect failure domains, service design, data locality, and operations.

## Resume-to-role evidence

- **Platform architecture and customer delivery:** Designed a modular, multi-tenant platform with APIs, ingestion, normalization, metadata, and workflow execution. Delivered five strategic pilots in four months with 80% component reuse.
- **Distributed data:** Built Kafka streaming and normalization for more than two billion events per day, under five seconds of lag, with idempotent writes and replication; also developed Spark/Airflow processing across 20+ data sources.
- **Governance and security:** Implemented metadata cataloging, lineage, privacy controls, policy enforcement, audit logs, IAM, and tenant-scoped permissions; reports 100% pass rate in security reviews.
- **AI platform capabilities:** Built RAG and LangGraph agent integrations, MCP servers, model serving, and an evaluation harness. The resume reports more than one million monthly AI requests and a harness that blocked all measured quality regressions.
- **Production ownership:** Describes 99.99% availability for a 12K+ node fleet, 5× surge handling, telemetry and device connectivity, alerting and runbooks, and a 45% MTTR reduction.
- **Technical leadership:** Cross-functional delivery with platform, QA, product, backend, cloud, and AI/ML teams; design and code reviews, architectural decisions, mentoring, incident follow-through, automated testing, and CI/CD.

The strongest portfolio story is a governed path from enterprise data to useful action: reusable APIs and integrations, well-defined workflows, AI features with quality gates, and visible operations. Resume metrics are preserved as supplied; intended reductions remain described as targets where applicable.

## Preparation themes

These are preparation inferences from the resume, Oracle's platform materials, and adjacent postings—not confirmed interview questions for requisition 346988:

1. **Platform boundaries:** Explain how to shape a multi-tenant API and data model, version contracts, make workflows composable, and avoid customer-specific logic leaking into shared services.
2. **Data integrity at scale:** Discuss idempotency, ordering, replay, backpressure, schema evolution, replication, late or duplicate events, and how the five-second lag objective is measured.
3. **Governance that is usable:** Walk through tenant-scoped authorization, lineage and audit semantics, privacy controls, and how policies apply consistently to catalogs, APIs, AI tools, and execution.
4. **AI quality and operations:** Explain evaluation design, representative datasets, regression gates, traceability, failure handling, model changes, retrieval quality, and safe tool permissions for RAG, agents, and MCP integrations.
5. **Availability and capacity:** Be ready to unpack the 12K-node / 5× surge context, Kafka partitioning and load shedding, SLOs, capacity forecasts, observability signals, and incident corrective actions.
6. **Principal-level influence:** Present an architecture tradeoff, alternatives, migration path, adoption evidence, cross-team alignment, and how the platform was made reusable after an initial pilot.

## Public sources

- [Oracle Careers — Principal Platform Software Engineer, AI (Req. 342714)](https://careers.oracle.com/en/sites/jobsearch/job/342714/)
- [Oracle Careers — Principal Platform Software Engineer (Req. 345650)](https://careers.oracle.com/en/sites/jobsearch/job/345650)
- [Oracle AI Data Platform](https://www.oracle.com/ai-data-platform/)
- [Oracle AI Data Platform agents](https://www.oracle.com/ai-data-platform/agents/)
- [Oracle AI Data Platform security and governance](https://www.oracle.com/ai-data-platform/security-governance/)
- [Oracle documentation — Introduction to Oracle AI Data Platform](https://docs.oracle.com/en/cloud/paas/ai-data-platform/aidug/introduction-oracle-ai-data-platform.html)
- [Oracle documentation — OCI regions and availability domains](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/regions.htm)

## Requisition limitation

The supplied DOCX contains resume material and links to the portfolio, GitHub, LeetCode, paper, demo, and certificate; it does not contain a job-description URL or the full text of requisition **346988**. A direct public search did not surface that exact requisition. This analysis therefore uses the resume, Oracle's official AI Data Platform material, and adjacent Oracle job postings for context; those postings do not confirm the responsibilities of requisition 346988.
