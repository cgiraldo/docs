---
title: "Score implementation (CLI)"
linkTitle: "Score implementation"
weight: 4
---

A _platform_ is a container orchestration and management system.

<!-- more -->

For example, Kubernetes, which typically comes along with an ecosystem of technology and tooling that supports the surrounding software delivery process - such as helm, Humanitec, or ArgoCD.

<!-- more -->

The Score implementation (CLI), is a tool to convert the Score Specification into the target platform configuration file of your choice.

Following Unix philosophy, each Score implementation (CLI) has a distinct and focused purpose.
For example, each of the following tools are used to generate a corresponding configuration.

- `score-compose`, is used to generate Docker Compose files.
- `score-helm`, is used to generate a Helm Chart.
- `score-humanitec`, is used to generate a Humanitec delta.
