---
name: design-md
description: Improve developer-facing landing pages, README files, docs homepages, and markdown-based product presentation. Use when Claude Code or Codex needs to critique or rewrite website copy, restructure a README, sharpen hero messaging, improve CTA hierarchy, or turn technical/project text into clearer product-oriented presentation. Especially useful for open-source projects, AI tools, devtools, local-first products, and GitHub-first launches.
---

# design-md

Use this skill to turn technically correct but flat product text into stronger developer-facing presentation.

## Core job

Diagnose and improve how a product is presented in:
- `README.md`
- landing pages
- docs homepages
- launch pages
- feature overview pages
- markdown-first product pages

Focus on:
- clarity in the first 5 seconds
- stronger information hierarchy
- cleaner headline / subheadline / CTA structure
- better proof placement
- developer-friendly product framing

Do not treat this as a pure visual design skill. It is mainly for:
- messaging
- structure
- markdown presentation
- section ordering
- product framing
- developer-facing copy

## Default workflow

### 1. Classify the page
First determine what kind of page or file you are improving:
- open-source README
- product landing page
- docs homepage
- feature page
- launch announcement page

Then determine the primary audience:
- developers
- technical buyers
- operators
- founders
- general users

Then identify the main conversion goal:
- understand the product
- install / try it
- star the repo
- sign up
- book a demo
- continue reading docs

### 2. Diagnose the current problems
Check for the most common failures:
- unclear one-line value proposition
- headline says what it is, but not why it matters
- feature list appears before the user understands the problem
- too much engineering detail too early
- weak or missing CTA
- no proof, examples, screenshots, or benchmark signal
- no obvious audience
- README reads like internal notes instead of a product entry point
- markdown sections are present but not in a persuasive order

### 3. Restructure before rewriting
Prefer fixing structure before polishing lines.

Typical high-performing order for a README:
1. name + one-line value
2. visual proof or concise product snapshot
3. why it matters
4. key features / differentiators
5. quick start
6. examples / use cases
7. deeper technical details
8. FAQ or limitations

Typical high-performing order for a landing page:
1. hero
2. problem
3. solution / product mechanism
4. proof
5. use cases
6. differentiation
7. CTA

### 4. Rewrite the critical blocks
Prioritize these elements:
- headline
- subheadline
- primary CTA
- supporting proof line
- first section after hero
- section titles
- quick start intro

When rewriting:
- prefer concrete value over abstract hype
- prefer outcome over capability lists
- prefer plain language over jargon stacks
- keep developer trust high
- do not oversell beyond available proof

### 5. Align to the product type
Adjust the tone and structure for the product:
- devtools: direct, crisp, proof-heavy
- AI products: avoid generic magic claims; explain mechanism and use case
- open-source: make README both informative and star-worthy
- local-first/privacy tools: foreground trust, control, and data boundaries
- infrastructure products: explain what layer they replace or improve

## Output modes

Choose one of these output styles based on the request.

### Mode A — critique only
Return:
- top problems
- why they matter
- prioritized fixes

### Mode B — rewrite plan
Return:
- proposed new structure
- replacement headline/subheadline/CTA
- section-by-section rewrite guidance

### Mode C — direct rewrite
Edit the relevant markdown, copy, or page files directly.
When doing this, preserve factual accuracy and avoid inventing proof.

## Guardrails

- Do not fabricate benchmarks, testimonials, users, logos, or numbers.
- Do not imitate a reference project line-for-line.
- Do not optimize for hype at the expense of trust.
- Do not turn technical pages into vague marketing fluff.
- Do not bury installation or quick-start content if the audience is developer-first.

## Heuristics

Use these heuristics by default:
- if the user cannot explain the product in one sentence after reading the top section, the page is failing
- if the first CTA appears too late, the page is under-converting
- if every section is feature-centric, add problem and proof framing
- if the copy sounds like internal architecture notes, translate it into user-facing value
- if the page is for developers, a little specificity beats a lot of polish

## Reference files

Read these only when needed:
- `references/readme-structures.md` for reusable markdown and README page skeletons
- `references/headline-patterns.md` for headline, subheadline, and proof-line patterns
- `references/cta-patterns.md` for CTA selection and placement
- `references/evaluation-rubric.md` for scoring and critique dimensions

## Good usage examples

Use this skill for requests like:
- “Rewrite this README so it feels like a strong product page.”
- “Improve the landing page copy for this open-source AI tool.”
- “Why does this homepage feel weak?”
- “Restructure this docs homepage for better conversion.”
- “Make this GitHub repo presentation more polished and developer-friendly.”
- “Turn this technical description into a better hero + feature narrative.”

## Working style

Be concrete.
Prefer before/after suggestions over vague advice.
When possible, give 2–3 headline options with different positioning angles.
If the current draft lacks proof, explicitly call that out and adjust the copy to remain credible.
If asked to edit files, make the smallest set of changes that materially improves clarity and conversion.
