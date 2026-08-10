---
name: html-slide-template-library
description: Select and route HTML slide work through a six-family presentation template system. Use when Codex needs to recommend or choose a template direction for academic defense, policy and governance, engineering and technical talks, theory coursework, innovation roadshows, or community portfolio decks; when the user asks to use this personal slide system instead of generic templates; or when Codex should shortlist 3 to 6 candidate directions and explain which one is the safe default before generation.
---

# HTML Slide Template Library

Use this skill as a **template-routing layer**, not as a slide generator.

This skill does three things:

1. classify the task into one of six stable slide families
2. recommend 3 to 6 candidate template directions from this library
3. produce a concrete design brief that another slide-generation workflow can execute

## Scope

This skill covers:

- template selection
- template recommendation
- style routing
- page grammar guidance
- scenario-to-template mapping

This skill does not cover:

- full HTML slide generation by itself
- PPTX conversion
- deployment
- third-party template packs

If the user asks to generate slides after choosing a direction, hand the chosen direction to the active generation workflow, such as `frontend-slides`.

## Required Reading

For every task, read:

- [references/selection-workflow.md](references/selection-workflow.md)
- [references/template-families.md](references/template-families.md)

If the user asks to follow the owner's established style, also read:

- [references/style-dna.md](references/style-dna.md)

## Workflow

1. Classify the task into one primary family:
   - academic-defense
   - policy-and-governance
   - engineering-and-technology
   - theory-and-coursework
   - innovation-roadshow
   - community-portfolio
2. Shortlist 3 to 6 directions from this library only.
3. Explain each candidate in this format:
   - `Template`
   - `Why it fits`
   - `What it will look like`
   - `Risk`
4. Mark one option as the safe default unless the task is ambiguous.
5. Ask the user to:
   - choose one direction
   - choose one primary plus one secondary
   - or let Codex pick the safest default
6. After a direction is chosen, output a compact build brief:
   - family
   - subtemplate
   - palette
   - cover syntax
   - section-page syntax
   - content-page grammar
   - image guidance
   - density guidance

## Selection Rules

- Prefer this library's own six families and subtemplates. Do not pull in third-party template systems unless the user explicitly asks for them.
- If the task spans multiple families, choose one primary and at most one secondary.
- Prefer evidence-first structures over decorative layouts.
- Use declarative titles that state the point directly.
- Prefer real screenshots, charts, certificates, diagrams, and photos over stock decoration.
- Do not default to generic business-plan, generic red academic, or stock-photo corporate styles.

## Safe Defaults

- Honor, scholarship, growth report: `academic-defense / blue-white-evidence`
- Policy interpretation, formal briefing: `policy-and-governance / red-gold-outline`
- Technical topic, engineering explanation, system report: `engineering-and-technology / light-blue-system`
- Classroom theory, concept-heavy report: `theory-and-coursework / black-white-argument`
- Product or competition pitch: `innovation-roadshow / tech-launch`
- Catalog, fandom, community showcase: `community-portfolio / atlas-card`

## Output Contract

When recommending directions, keep the answer compact and concrete. Avoid vague labels like "modern" or "clean" without saying what the screen will actually contain.

When handing off to a generator, give it:

- the chosen family and subtemplate
- the page grammar
- the palette and emphasis colors
- what kinds of images are acceptable
- what to avoid visually

## Repository Assumption

This repository is the skill body itself. Treat files in `references/` and `assets/previews/` as the source of truth for routing and preview explanation.
