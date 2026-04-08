# design-md-skill

A public skill for Claude Code / Codex to improve developer-facing landing pages, README files, docs homepages, and markdown-based product presentation.

This repo is for people who want an agent to do more than “make it sound better.”
It gives the agent a practical workflow for:

- diagnosing weak README and landing-page structure
- rewriting hero, subheadline, and CTA copy
- improving markdown-first product presentation
- making technical products feel clearer, sharper, and more credible
- staying persuasive without turning into vague marketing fluff

## What this skill is for

Use `design-md` when you want Claude Code or Codex to help with:

- open-source README rewrites
- product landing page messaging
- docs homepage structure
- launch page copy
- developer-facing product positioning
- turning technical description into clearer product presentation

It is especially useful for:
- AI products
- devtools
- local-first tools
- infrastructure products
- GitHub-first launches

## What this skill is not

This is **not** a pure visual design skill.
It does not replace:
- high-end brand design
- motion design
- custom UI art direction
- original visual systems work from a product designer

It is mainly a skill for:
- messaging
- structure
- markdown presentation
- section order
- product framing
- developer-trust-preserving rewrites

## Included files

- `SKILL.md` — main skill instructions
- `references/readme-structures.md` — reusable page and README skeletons
- `references/headline-patterns.md` — headline and subheadline patterns
- `references/cta-patterns.md` — CTA placement and wording guidance
- `references/evaluation-rubric.md` — critique and scoring rubric
- `examples/` — simple before/after examples

## Example prompts

Use prompts like:

- “Rewrite this README so it feels like a stronger product page.”
- “Critique this landing page for clarity and conversion.”
- “Make this docs homepage more useful for first-time developers.”
- “Give me three better hero options for this open-source AI tool.”
- “Restructure this markdown page before rewriting the copy.”

## Working style of the skill

The skill pushes the agent to:

1. classify the page type and audience
2. diagnose the biggest conversion and clarity problems
3. fix structure before polishing lines
4. rewrite critical blocks first
5. preserve trust and avoid fabricated proof

## Installation / usage

Use this repository as a reference skill source for your own Claude Code / Codex setup.

If your environment supports skill directories, copy the `design-md` skill contents into your local skills folder, or adapt the files into the format expected by your toolchain.

## Why this exists

A lot of technical projects are strong on substance but weak on presentation.
Their README or homepage is accurate, but flat:
- too much architecture, too early
- weak hero copy
- unclear audience
- poor CTA hierarchy
- not enough proof near the top

This skill exists to help agents systematically fix that.

## Codex-oriented usage

This repo is especially useful when you want Codex or Claude Code to work in one of three modes:

- **Critique mode**: review the current page and identify the biggest clarity or conversion problems
- **Rewrite-plan mode**: propose a new structure plus improved hero, CTA, and section hierarchy
- **Direct-edit mode**: edit the actual markdown or page file and summarize the change

Recommended prompt patterns:

- `Use design-md in critique mode on this README.`
- `Use design-md to propose a rewrite plan for this landing page.`
- `Use design-md in direct-edit mode and improve this homepage copy.`
- `Read SKILL.md and references, then rewrite the hero and CTA only.`

If the request is broad, start with critique mode. If the file is already close, direct-edit mode is usually faster.
