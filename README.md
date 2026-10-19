# Matej Bicej

**Solutions Architect | Distributed Systems, Cloud & Applied AI**

I enjoy building systems that do more than work in a demo. My background spans cloud modernization, data platforms, enterprise integration, and applied AI, with experience leading engineering teams and working directly with business stakeholders.

Although much of my career has focused on architecture and technical leadership, I have always enjoyed the hands-on side of engineering. I still build software independently, experiment with new technologies, and spend probably too much time figuring out why something broke.

## Featured Project

### [Durable Media Workflows — Python, SQLite & Restate](https://github.com/Quaeritate/durable-media-workflows)

**What happens when a worker crashes after writing a result but before acknowledging success?**

I built this reference project to explore exactly that problem.

It compares a Python/SQLite job coordinator with Restate's durable execution model, using the same synthetic media-processing workflow and repeat-safe output publication.

The project demonstrates:

- Recovery from worker crashes and interrupted processing.
- Retries, failure handling, and duplicate-request management.
- Idempotent output publication and integrity verification.
- The architectural trade-offs between managing recovery yourself and using a durable execution platform.

**Verification:** 32 passing tests on Windows, 32 on Linux, and a live Restate integration test involving two worker terminations, a transient failure, and successful recovery.

What interests me most is not simply getting Restate to work, but understanding when it makes an architecture better—and when a simpler solution is sufficient.

[**Explore the code**](https://github.com/Quaeritate/durable-media-workflows) · [Architecture comparison](https://github.com/Quaeritate/durable-media-workflows/blob/main/docs/comparison.md) · [Test results](https://github.com/Quaeritate/durable-media-workflows/blob/main/docs/results.md) · [Public CI](https://github.com/Quaeritate/durable-media-workflows/actions/workflows/verify.yml)

## Professional Background

A few projects that shaped how I approach engineering:

- **Enterprise AI:** Led an eight-person team bringing an LLM-enabled insurance-document platform into production, reducing document turnaround time by approximately 34%.
- **Cloud modernization:** Led an architecture workstream within a $21M transformation program, working across engineering teams and business stakeholders to resolve integration challenges, priorities, costs, and technical decisions.
- **Enterprise consulting:** Worked with customers at Microsoft Austria on cloud architecture, Azure migration, and technical proof-of-concept development.

I particularly enjoy the space between identifying a business problem, making architectural decisions, and getting the solution working reliably in production.

## Other Projects I'm Building

These projects are maintained in private repositories while under development.

**Media Workbench — Python**

A local-first media application featuring persistent background jobs, recovery from interrupted processing, media-integrity protections, and automated testing. Its reliability architecture inspired the Durable Media Workflows reference project above.

**Galaxy Remote — Android & Wear OS**

A phone-and-watch companion application involving Bluetooth communication, device integration, camera controls, protocol design, and automated testing.

**Quaeritate — Magic: The Gathering Collection Tracker**

I enjoy playing Magic: The Gathering, which eventually led me to start building my own collection-management application.

Built with Flutter and Supabase, Quaeritate combines my interest in the game with my enjoyment of cross-platform application development, data modeling, and product design.

## Technologies

**Backend & Data:** Python, FastAPI, SQL, SQLite, ETL/ELT

**Cloud & Infrastructure:** Azure, AWS, Docker, Terraform, CI/CD, Git

**Messaging & Reliability:** Azure Service Bus, asynchronous processing, durable workflows, Restate Python SDK

**Applied AI:** Azure OpenAI, Azure AI Search, RAG

**Application Development:** Flutter, Dart, Supabase, Android & Wear OS

---

I enjoy learning new technologies, challenging my own architectural assumptions, and building things that solve real problems.
