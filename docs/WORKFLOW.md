# Workflow

## 1. Business input

The workflow begins with a campaign brief rather than a model prompt.

Typical inputs may include:

- product
- price
- promotion period
- campaign theme
- approved headline or offer
- product packshot
- logo and brand assets
- target screen or output format

## 2. Asset boundary

Assets are split into two categories.

### Approved source assets
These are authoritative business inputs:

- product packshots
- logos
- prices
- legal or promotional claims
- campaign dates
- brand-specific wording

### AI-assisted creative assets
These may be generated or transformed to support the campaign:

- backgrounds
- atmosphere
- decorative motion elements
- non-authoritative visual concepts

Generated material should never silently replace authoritative product or pricing information.

## 3. Campaign configuration

The goal is to convert changing campaign information into structured data.

Example:

```json
{
  "product": "Frozen Dumplings",
  "price": "$4.99",
  "theme": "Winter Hotpot Week",
  "startDate": "YYYY-MM-DD",
  "endDate": "YYYY-MM-DD"
}
```

The template should consume this configuration rather than requiring layout logic to be rewritten for every campaign.

## 4. Programmatic composition

React / Remotion owns repeatable presentation logic such as:

- scene timing
- price treatment
- typography hierarchy
- transitions
- product positioning
- logo region
- campaign date treatment
- output dimensions

## 5. Preview and review

The intended workflow is:

```text
Campaign input
→ preview
→ human review
→ corrections
→ approved render
```

Human review is important because commercial content must be checked for pricing, claims, visual quality and brand accuracy.

## 6. Render and distribution

The production direction is to support multiple output targets from the same campaign configuration.

Potential targets include:

- in-store digital screens
- vertical social video
- landscape promotional video

Multi-format production is still being validated and should not be treated as production-complete.

## 7. Future product direction

A future self-service interface could allow a manager to:

1. upload approved product and brand assets
2. enter campaign information
3. select a template or theme
4. preview the video
5. request a render
6. export approved variants

This remains a product direction, not a completed feature.
