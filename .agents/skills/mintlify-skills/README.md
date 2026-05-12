# Mintlfy Skills

Install with:

```bash
npx skills add evansso/mintlify-skills
```

`Mintlfy Skills` is a model-agnostic skill package for writing better Mintlify documentation. It is not tied to a specific model. You can use these skills anywhere you want structured help drafting, rewriting, reviewing, and organizing Mintlify docs.

## What Mintlfy Skills helps with

- drafting new Mintlify pages from rough notes or product context
- rewriting unclear or overly product-centric docs
- reviewing pages and docs sets for the highest-impact issues
- reorganizing navigation and multi-page documentation structure
- improving metadata, headings, and page quality for both readers and AI retrieval

## How Mintlfy Skills works

Mintlfy Skills is built around a simple documentation workflow:

1. Identify the primary audience.
2. Define the reader's immediate goal.
3. Choose one main page type: tutorial, how-to, explanation, or reference.
4. Draft or revise the page using clear structure and direct language.
5. Run a final Mintlify-focused quality pass for metadata, headings, links, and maintainability.

## Best use cases

Use this package when you need help with:

- `.md` or `.mdx` pages in a Mintlify docs site
- `docs.json` organization and navigation changes
- onboarding guides, how-to guides, tutorials, explanation pages, and reference docs
- documentation cleanup work before publishing
- making docs easier for AI systems to retrieve and summarize accurately

## Included guidance

This package includes supporting references for:

- choosing the right page type
- starting from documentation templates
- checking Mintlify-specific quality, SEO, GEO, and `llms.txt` implications

## Example prompts

- `Use write-mintlify-docs to turn these notes into a Mintlify how-to guide.`
- `Rewrite this page for developers integrating our API.`
- `Review this docs section and list the highest-impact problems first.`
- `Help reorganize this Mintlify docs structure around user journeys.`

## Package contents

- `SKILL.md`: the core instructions for `write-mintlify-docs`
- `references/page-types.md`: guidance for choosing one primary content type
- `references/templates.md`: starter templates for common Mintlify page types
- `references/mintlify-quality-checklist.md`: final review checklist for page quality and retrieval readiness
- `agents/openai.yaml`: package metadata used by compatible tooling

## Notes

Mintlfy Skills is intentionally opinionated:

- It pushes each page toward one primary audience and one primary purpose.
- It favors concise, scannable structure over broad, unfocused prose.
- It treats `title`, `description`, headings, and links as core documentation quality signals.
- It assumes Mintlify AI outputs are only as strong as the source pages behind them.

Use it as a writing and review aid, not as a replacement for accurate product facts.
