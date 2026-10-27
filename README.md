# AS262 - Explore autonomous product design and supply chain planning

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2026-AS262)](https://api.reuse.software/info/github.com/SAP-samples/teched2026-AS262)

`Hands-on workshop`

## Description

This repository contains the material for the SAP TechEd 2026 session called AS262 - Explore autonomous product design and supply chain planning. The session presents two kinds of AI agents: the Exception Management Agent (EMA) in SAP IBP, shown as a live demo, and the Product Design Assistant in Joule, which you can try yourself in hands-on exercises.

## Overview

### 1. Exception Management Agent (EMA): system-triggered, in SAP IBP

The Exception Management Agent (EMA 2.0) in SAP Integrated Business Planning (SAP IBP) is a *system-triggered* agent. It picks up planning alerts, runs the customer's own root-cause analysis on them, and writes insights and mitigation proposals back to SAP IBP. The numbers come from deterministic code; a language model only explains them. The planner stays in control of every decision.

EMA is presented as a live demo in this session. For the concept, architecture, a worked use case and the roadmap, read the **[Exception Management Agent overview](ema/README.md)**.

### 2. Product Design Assistant: interactive, in Joule

The `@Product Design Assistant` is an *interactive* agent: you talk to it in **Joule** and drive every step of the conversation, keeping the human in the loop. The hands-on exercises cover two scopes:

- **Product Data Maintenance Agent** - create and maintain product master data in bulk: create products from an Excel file, extend them to a plant, classify them, search them by classification, and add translated descriptions.
- **Product Structure Optimizer** - create and manage a Bill of Materials (BOM): extract a BOM from a file, run sanity checks, enrich it with predicted components and values, then summarize, explode, and delete it.

```mermaid
flowchart LR
  A[Upload file<br/>in Joule] --> B[Agent proposes<br/>a plan]
  B --> C[You confirm<br/>each step]
  C --> D[Agent writes<br/>back to the system]
```

## Requirements

The requirements to follow the hands-on exercises in this repository are:

- A laptop with a current web browser.
- Basic familiarity with product master data concepts such as BOMs and classification.
- A Joule user (sarah.davisX@bestrunsap.com) and system URL, provided by the session team. X is the number on your desk card.
- The `@Product Design Assistant` available when you start a new conversation in Joule.
- The sample upload files referenced in each exercise (BOM file for the Product Structure Optimizer, Excel product file for the Product Data Maintenance Agent).

## Exercises

### Exception Management Agent (demo)

There are no hands-on exercises for EMA. See the [Exception Management Agent overview](ema/README.md) for:

- [The problem: too many alerts, too little time](ema/README.md#the-problem-too-many-alerts-too-little-time)
- [Use case: a capacity overload](ema/README.md#use-case-a-capacity-overload)
- [Architecture: the trust model](ema/README.md#architecture-the-trust-model)
- [Roadmap](ema/README.md#roadmap)

### Product Design Assistant (hands-on, in Joule)

These exercises show how to work with the `@Product Design Assistant` in Joule.

**Product Data Maintenance Agent**

- [Getting Started - Product Data Maintenance Agent](exercises/pdm/ex0/README.md)
- [Exercise 1 - Discover capabilities and create products from a file](exercises/pdm/ex1/README.md)
- [Exercise 2 - Extend products to a plant and classify them](exercises/pdm/ex2/README.md)
- [Exercise 3 - Search by classification and add German descriptions](exercises/pdm/ex3/README.md)

**Product Structure Optimizer**

- [Getting Started - Product Structure Optimizer Agent](exercises/pso/ex0/README.md)
- [Exercise 1 - Create a BOM from a file](exercises/pso/ex1/README.md)
- [Exercise 2 - Run sanity checks and enrich the BOM](exercises/pso/ex2/README.md)
- [Exercise 3 - Summarize, explode, and delete the BOM](exercises/pso/ex3/README.md)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (2026-)2026 SAP SE or an SAP affiliate company and teched2026-AS262 contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/SAP-samples/teched2026-AS262).
