# Selection Workflow

## Purpose

This skill exists to help Codex choose the right slide template direction before generating a deck.

## Core Interaction Pattern

Use this sequence:

1. identify the presentation task
2. map it to one primary family
3. shortlist 3 to 6 template directions from this repository
4. explain the shortlist in a fixed comparison format
5. ask the user to confirm one direction
6. emit a concise build brief for the downstream generator

## Six Families

1. `academic-defense`
2. `policy-and-governance`
3. `engineering-and-technology`
4. `theory-and-coursework`
5. `innovation-roadshow`
6. `community-portfolio`

## Recommended Response Format

For each candidate, answer with four fields:

1. `Template`: family plus subtemplate slug
2. `Why it fits`: one sentence on task fit
3. `What it will look like`: concrete on-screen outcome
4. `Risk`: mismatch or tradeoff

Then ask the user to:

- choose one template
- choose one primary plus one secondary
- or let Codex pick the safest default

## Default Mapping

| Task shape | Safe default |
| --- | --- |
| scholarship defense, honor review, personal growth summary | `academic-defense / blue-white-evidence` |
| policy interpretation, planning briefing, governance presentation | `policy-and-governance / red-gold-outline` |
| engineering principle, system architecture, experiment or technical report | `engineering-and-technology / light-blue-system` |
| theory discussion, course presentation, philosophy or social-science report | `theory-and-coursework / black-white-argument` |
| project pitch, competition roadshow, productized innovation story | `innovation-roadshow / tech-launch` |
| pokedex, catalog, collection, community showcase, portfolio-style deck | `community-portfolio / atlas-card` |

## Escalation Rules

- If the user explicitly asks to follow their own prior PPT style, consult `style-dna.md` before recommending directions.
- If the task is ambiguous between two families, shortlist one primary and one adjacent family instead of pretending certainty.
- If the user asks for actual slide production, pass the selected direction into the active generation workflow rather than improvising a new visual system.

## What To Avoid

- Do not recommend third-party template packs by default.
- Do not answer with only mood words like "professional" or "modern".
- Do not skip template confirmation unless the user explicitly asks for direct generation.
- Do not overfit to a single screenshot when the task clearly belongs to one of the six stable families.
