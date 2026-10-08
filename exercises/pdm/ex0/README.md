# Getting Started - Product Data Maintenance Agent

In this track, you will use the **Product Data Maintenance Agent** for the first time. Like the Product Structure Optimizer Agent, this agent is *interactive*: you talk to it in **Joule** and drive every step of the conversation. Unlike the Exception Management Agent (EMA), which is triggered by a system job, this agent works with you in real time to maintain product master data in bulk.

Over three exercises you discover what the agent can do, create products from an Excel file, extend them to a plant, classify them, search them by classification, and add German descriptions - all without leaving Joule.

<!-- TODO: confirm how the Product Data Maintenance Agent is invoked in Joule. The test script reaches it through the `@Product Design Assistant`; verify whether it is a separate @ mention. -->

> [!NOTE]
> This is a separate track from the Exception Management Agent (EMA) and the Product Structure Optimizer Agent exercises. You do not need to have completed those tracks to follow along here.

## Session details

<!-- TODO: fill in session ID, date and room, and the system URL. -->

| Item | Value |
| --- | --- |
| Event | SAP TechEd Berlin 2026, hands-on session (session ID: TBD) |
| Date and room | TBD |
| System | myXXXXXX (URL: TBD) |
| Your user | PLANNER_XX, where XX is the number on your desk card |
| Assistant | `@Product Design Assistant` (Product Data Maintenance Agent) in Joule |
| Classification class | PUMP_TECH_DATA |

## Prerequisites

Before you start, make sure that:

- **Joule** is enabled and reachable for your user.
- The `@Product Design Assistant` is available when you start a new conversation.
- You have the sample Excel product file to upload in Exercise 1.
  <!-- TODO: confirm the exact file name and format of the sample product file, then link it from exercises/pdm/ex1/files/. -->
- The classification class **PUMP_TECH_DATA** and its characteristics (for example PUMP_TYPE and HOUSING_MATERIAL) exist in the system.
- Plant **001** is available for product extension.

> [!IMPORTANT]
> During the hands-on session, only create, change or classify the products that you create yourself. Do not touch products created by other participants.

## Scenario

You are a product data steward. Instead of maintaining product master data record by record, you let the Product Data Maintenance Agent do it in bulk: it reads an Excel file, maps the columns, creates the products, extends them to a plant, classifies them against a class, finds them by their classification values, and even proposes translated descriptions. You stay in control: the agent proposes a plan and you confirm each step with `Yes, please proceed` before anything is written.

```mermaid
flowchart LR
  A[Discover<br/>capabilities] --> B[Create products<br/>from Excel file]
  B --> C[Extend to<br/>plant 001]
  C --> D[Classify with<br/>PUMP_TECH_DATA]
  D --> E[Search by<br/>classification]
  E --> F[Add German<br/>descriptions]
```

The exercises follow this flow from left to right.

## Summary

You now know the scenario, your user, and the assistant you will work with.

Continue to - [Exercise 1 - Discover capabilities and create products from a file](../ex1/README.md)
