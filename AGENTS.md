# Agent Instructions

This repository is the source of truth for SEO, AEO, and GEO strategy across managed brands.

## Purpose

Help maintain and improve the strategy docs, templates, prompts, query sets, and operating workflows for:

- McEvoy Ranch
- Tech-led.com

## Working Rules

- Treat GitHub as the durable strategy library.
- Treat Linear as the task and review workflow.
- Do not mark work as complete without producing a clear summary and review notes.
- Prefer Markdown and CSV unless a structured format is clearly better.
- Keep brand-specific strategy inside the relevant `brands/` folder.
- Keep reusable models, rubrics, and frameworks inside `frameworks/`.
- Keep prompts inside `prompts/`.
- Keep Linear conventions and issue templates inside `linear/`.
- Keep DataForSEO workflows and query sets inside `dataforseo/`.

## Content Standards

When creating or editing strategy docs:

- Be specific and operational.
- Separate SEO, AEO, and GEO implications where useful.
- Include definitions of done for execution tasks.
- Favor buyer-useful content over thin search-only content.
- Preserve assumptions and open research questions.
- Do not invent brand facts, awards, reviews, pricing, or technical specs.
- Mark unverifiable claims as research tasks.

## Validation

This is a documentation and strategy repo. There is no build step by default.

Before finishing:

- Run `git status --short`.
- Review changed files.
- Ensure Markdown tables render plausibly.
- Summarize what changed, where, and what needs human review.

## Linear Handoff

When responding to a Linear-triggered task:

- Confirm which files you read.
- Link or name files changed.
- Move the issue to human review if Linear workflow supports it.
- Do not assume publication approval.
- Recommend the next issue only when it naturally follows from the work.

