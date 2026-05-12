---
name: mintlify-skills
description: Draft, rewrite, review, and organize Mintlify documentation using Mintlify's guidance for audience, content types, templates, navigation, style, SEO, GEO, and llms.txt. Use when Codex needs to improve `.md`, `.mdx`, `docs.json`, API docs, onboarding guides, tutorials, how-to guides, reference pages, conceptual docs, or documentation information architecture for a Mintlify site.
---

# Write Mintlify Docs

## Overview

Use this skill to turn rough notes, existing pages, or scattered product context into clearer Mintlify documentation. Favor user goals, strong structure, and AI-retrievable metadata over verbose prose.

## Choose the job

Match the work to one of these modes before writing:

- Draft a new page when the user has a clear topic but no finished documentation.
- Rewrite a page when the existing content is mixed, unclear, too product-centric, or missing Mintlify-friendly structure.
- Review a page or docs set when the user wants gaps, risks, or a prioritized improvement plan.
- Reorganize navigation when the user is working on `docs.json`, section labels, or multi-page information architecture.

## Identify the audience and page type

Start every task by answering two questions:

1. Who is the primary reader?
2. What is that reader trying to accomplish right now?

Pick exactly one primary content type for each page. Read [references/page-types.md](./references/page-types.md) when the type is unclear or the page currently mixes multiple goals.

Split or tighten pages that try to teach, explain, and reference everything at once.

## Draft or rewrite the page

When writing page content:

- Start with a descriptive `title` and `description`.
- Open with the main takeaway, task outcome, or definition instead of a long warm-up.
- Use active voice, second person, and direct instructions.
- Keep terminology consistent and prefer the user's language over internal product jargon.
- Use headings that describe what the reader will find or do.
- Use numbered steps for tasks, tables or lists for scannable reference material, and short paragraphs for explanations.
- Include explicit prerequisites, success checks, and troubleshooting only when they materially help the reader finish the task.
- Keep code examples copyable, labeled with a language, and complete enough to run or adapt.

Read [references/templates.md](./references/templates.md) before drafting if the user needs a tutorial, how-to, explanation, or reference page from scratch.

## Optimize for Mintlify and AI retrieval

Run a final pass with [references/mintlify-quality-checklist.md](./references/mintlify-quality-checklist.md) when the work affects published docs.

Pay special attention to:

- Clear frontmatter because Mintlify uses page titles and descriptions for discovery.
- Strong heading hierarchy because both readers and AI tools depend on it.
- Descriptive internal links because "click here" is weak for both humans and search systems.
- Explicit nouns instead of vague references like "this" or "it" when ambiguity is possible.
- Descriptive alt text for diagrams and screenshots.

Remember that Mintlify auto-generates `llms.txt` and `llms-full.txt`. The quality of each page's `description` directly affects how that page is summarized in `llms.txt`.

## Organize multi-page docs

When the task spans multiple pages or `docs.json`:

- Group content around user journeys, not internal org charts.
- Keep "get started", task guides, conceptual docs, and reference material distinct.
- Prefer descriptive labels that match search terms and support language.
- Put high-value pages where users naturally start.
- Flag overloaded groups, buried essentials, inconsistent naming, and stale sections.

## Review output

When reviewing existing docs, report the highest-impact problems first. Focus on:

1. Audience mismatch
2. Wrong page type or mixed purpose
3. Missing or weak metadata
4. Structural or navigation problems
5. Style, clarity, and consistency issues
6. Freshness and maintenance risks

If product facts are missing, state the assumption or leave a precise placeholder instead of inventing details.

## References

- [references/page-types.md](./references/page-types.md)
- [references/templates.md](./references/templates.md)
- [references/mintlify-quality-checklist.md](./references/mintlify-quality-checklist.md)
