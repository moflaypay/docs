# Mintlify Quality Checklist

Use this checklist for final review, audits, or rewrite plans.

## Check audience and scope

- State one primary audience.
- State the reader's immediate goal.
- Confirm the page has one primary content type.
- Remove material that belongs in a different page type.

## Check writing quality

- Lead with the answer, outcome, or definition.
- Use active voice and second person.
- Keep paragraphs short and skimmable.
- Prefer clear nouns over vague references.
- Use consistent terminology across the page and neighboring pages.
- Remove internal-team language that readers would not use.

## Check structure

- Use a strong `title` and `description` in frontmatter.
- Keep heading levels sequential.
- Make headings descriptive enough to stand alone in search or an LLM chunk.
- Use numbered steps for procedures.
- Use lists and tables where scanning matters more than prose.
- Label every code block with a language.

## Check links and navigation

- Link to related tasks, concepts, and reference pages with descriptive anchor text.
- Keep the page understandable even when opened directly from search.
- Place pages in navigation based on user journeys, not team ownership.
- Flag overloaded groups, buried key pages, and inconsistent labels.

## Check SEO and GEO

- Write a title that is specific and human-readable.
- Write a description that summarizes the page clearly in one sentence.
- Add descriptive alt text for images and diagrams.
- Make common user questions discoverable through headings and opening sentences.
- Add comparison tables or explicit tradeoffs when users need to choose between options.

## Check Mintlify AI retrieval

Mintlify automatically generates `llms.txt` and `llms-full.txt`.

Treat these as implications for page quality:

- Missing `description` means weaker page summaries in `llms.txt`.
- Ambiguous headings make retrieval and chunk matching worse.
- Incomplete prerequisites cause bad AI-generated guidance.
- Inconsistent naming reduces answer accuracy.
- Self-contained pages help both human readers and AI tools that land on a single page without prior context.

If the user asks for custom `llms.txt` or `llms-full.txt` files:

- Put the file at the project root.
- Start with the site title as an H1.
- Keep the rest optional unless the project needs custom structure.
- Remember that a custom file overrides Mintlify's auto-generated file until removed.

## Check maintenance risk

- Identify content that will go stale quickly.
- Prefer evergreen docs over release-specific prose when possible.
- Recommend changelogs for fast-moving product updates.
- Flag pages that need periodic review, ownership, or automated checks.
- Suggest automation such as linting, metadata checks, and stale-content audits when the docs set is large.

## Source pages

- https://www.mintlify.com/docs/guides/style-and-tone
- https://www.mintlify.com/docs/guides/navigation
- https://www.mintlify.com/docs/guides/seo
- https://www.mintlify.com/docs/guides/geo
- https://www.mintlify.com/docs/guides/maintenance
- https://www.mintlify.com/docs/ai/llmstxt
- https://www.mintlify.com/docs/guides/developer-documentation
