# Design Decisions

## 1. Reusable template over one-off generation

The recurring business problem is not "make one interesting video."

It is "produce many promotional variations without rebuilding the entire workflow."

That makes reusable layout and motion logic more valuable than relying only on one-off text-to-video generation.

## 2. Structured inputs over free-form prompts

Price, product name, dates and approved copy are business data.

Representing them as structured inputs makes the workflow easier to validate, reuse and eventually expose through a simple interface.

## 3. Authoritative assets over generated substitutes

A generative model should not invent:

- prices
- product packaging
- logos
- promotional dates
- factual claims

Those should enter the system through approved business data and source assets.

## 4. AI for acceleration, not invisible authorship

AI is used to accelerate:

- technical implementation
- visual exploration
- iteration
- copy options
- debugging

The project still requires human decisions about the business problem, constraints, workflow, acceptance and final output.

## 5. Human approval before distribution

The final campaign is public-facing commercial material.

Human review remains a release gate for:

- price accuracy
- dates
- brand accuracy
- claims
- visual quality
- campaign suitability

## 6. Honest roadmap states

The repository distinguishes:

- completed discovery
- working prototype
- in-progress template work
- future self-service interface
- future production automation

This prevents a prototype from being presented as a deployed platform.
