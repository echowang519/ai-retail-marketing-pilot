# AI-Assisted Retail Marketing Pilot

> A real-world retail marketing pilot exploring how generative AI and programmatic video can reduce repetitive campaign production work.

**Status:** Active pilot · Prototype stage  
**Context:** Asian grocery retail · Brisbane, Australia  
**Focus:** AI solution design · workflow automation · React / Remotion · product delivery

---

## Business Context

This project started from a real conversation with an experienced Asian grocery retail manager.

The recurring operational problem was simple:

**Promotional posters and short videos take time to produce, while stores need fresh campaign content repeatedly across products, brands and screens.**

The opportunity was not to replace marketing judgment. It was to reduce repetitive production work by turning campaign inputs into a reusable AI-assisted workflow.

To protect commercial and brand-sensitive information, this public repository uses a sanitized case-study format. Private conversations, internal business details, customer assets and unapproved brand materials are intentionally excluded.

---

## The Problem

Retail promotion work often repeats the same pattern:

- collect product and campaign information
- prepare visual assets
- write short promotional copy
- build price and offer treatments
- assemble motion graphics
- resize or re-render for different screens
- repeat again for the next product or campaign

For a store running frequent promotions, this can become expensive in time even when each individual video is simple.

The design question became:

> **Can a small retailer turn a campaign brief into repeatable promotional video variants without manually rebuilding every video from scratch?**

---

## Discovery

The initial discovery focused on the real workflow rather than starting from a model or tool.

Key observations:

- promotional content is recurring rather than one-off
- the store uses in-store screens for looping campaign content
- product, price, campaign period and brand assets change frequently
- visual quality still needs human review
- true logos, product packshots and claims must come from approved source assets
- a reusable template is more valuable than generating a completely different video every time

This pushed the solution toward **structured campaign inputs + reusable programmatic video templates** rather than one-click generative video alone.

---

## Proposed Workflow

```mermaid
flowchart LR
    A[Campaign Brief] --> B[Approved Brand & Product Assets]
    B --> C[Campaign Configuration]
    C --> D[AI-Assisted Creative Assets]
    D --> E[React / Remotion Template]
    E --> F[Preview & Human Review]
    F --> G[Rendered Video Variant]
    G --> H[In-store Screens / Social Outputs]
```

A campaign can be represented as structured inputs such as:

- product name
- price
- campaign theme
- product image
- logo
- promotion dates
- approved copy
- output format

The long-term goal is to make these inputs drive a reusable video system rather than manually editing each campaign from zero.

---

## Prototype

The first prototype used a real retail-style promotional scenario to test the workflow.

The prototype explored:

- animated product presentation
- prominent retail price treatment
- campaign text hierarchy
- reusable timing and motion
- data-driven text and asset replacement
- agent-assisted iteration using Codex
- Remotion as the programmatic video layer

The public repository does **not** publish client-owned product imagery or brand assets. Public demo material will use sanitized or placeholder assets.

---

## Why Programmatic Video

Traditional video editing is flexible, but repeated retail campaigns contain a lot of structured repetition.

A code-driven template makes it possible to separate:

**Campaign data**  
from  
**visual logic**

Conceptually:

```text
Brand
Product
Price
Theme
Product Image
Logo
Dates
      ↓
Campaign configuration
      ↓
Reusable React / Remotion composition
      ↓
Preview → Review → Render
```

That creates a path toward faster iteration, consistent layouts and future multi-format rendering.

---

## Current Status

| Area | Status |
|---|---|
| Real-world business discovery | ✅ Completed |
| Retail promotion use case defined | ✅ Completed |
| Initial promotional video prototype | ✅ Completed |
| React / Remotion workflow selected | ✅ Completed |
| Structured campaign configuration | 🟡 In progress |
| Reusable campaign template | 🟡 In progress |
| Multi-format render validation | 🟡 In progress |
| Self-service campaign interface | ⚪ Concept |
| Automated production pipeline | ⚪ Future |
| Production deployment | ⚪ Not deployed |

The distinction between **working prototype**, **in-progress system** and **future concept** is intentional.

---

## My Role

I drive:

- business problem discovery
- requirements gathering
- solution framing
- workflow and product decisions
- prototype direction
- system constraints
- acceptance criteria
- iteration and review
- commercial use-case thinking
- portfolio evidence and documentation

I use AI extensively as an implementation partner for coding, creative iteration and technical exploration.

I do **not** present the project as if every implementation line or generated asset was manually created by me.

---

## Technologies & Tools

**Programmatic video**  
React · TypeScript · Remotion

**AI-assisted production**  
LLM / coding agents · generative visual workflows · structured prompting

**Delivery concepts**  
requirements discovery · reusable templates · structured campaign data · human-in-the-loop review · multi-format output planning

---

## Key Design Decisions

### Start with the workflow, not the model
The business problem is repetitive campaign production. AI is one component of the solution, not the product definition.

### Approved assets remain authoritative
Logos, packshots, pricing and product claims should come from approved business inputs rather than being hallucinated by a generative model.

### Template what repeats
Price layout, timing, transitions, branding regions and output dimensions are better candidates for reusable programmatic logic.

### Keep human review in the loop
Retail promotions are public-facing commercial material. Human approval remains part of the workflow before final output.

### Separate prototype from production
A successful demo is evidence of direction, not proof of a production-ready campaign system.

More detail: [Design Decisions](docs/DESIGN_DECISIONS.md)

---

## Repository Guide

- [Workflow](docs/WORKFLOW.md)
- [Design Decisions](docs/DESIGN_DECISIONS.md)
- [Example Campaign Configuration](examples/campaign-config.example.json)
- [Public Asset Rules](assets/README.md)
- [Demo Evidence Guide](screenshots/README.md)

---

## What This Project Demonstrates

This project is designed to show more than content creation.

It demonstrates the ability to:

- identify a real operational problem
- translate business needs into an AI-enabled workflow
- distinguish approved source data from generated content
- choose a technical approach based on repeated work
- prototype with React / Remotion and AI coding tools
- keep human review and commercial constraints in the system
- separate current capability from future roadmap
- think about how a prototype could become a repeatable product

That is the kind of work I want to continue doing in **AI Solutions, AI Implementation and Product Delivery** roles.
