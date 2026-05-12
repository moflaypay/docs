# Page Types

Use this guide to choose one primary content type before drafting or rewriting a page.

## Choose a type

Ask these questions in order:

1. Is the user trying to learn by doing from zero?
Use a tutorial.

2. Is the user trying to complete a specific task and likely already has some context?
Use a how-to guide.

3. Is the user trying to look up exact behavior, parameters, limits, or options?
Use a reference page.

4. Is the user trying to understand a concept, design choice, tradeoff, or mental model?
Use an explanation page.

If a page answers "yes" to more than one of these, the page probably needs to be split or narrowed.

## Apply the types

### Tutorial

Use for onboarding and guided learning.

- Reader goal: Learn through a complete, linear exercise.
- Reader knowledge: Beginner.
- Shape: Sequential steps with few choices.
- Emphasis: Concrete actions, milestones, and what the reader will achieve.
- Avoid: Dense theory and option-heavy branches.

### How-to guide

Use for a specific task such as enabling a feature, integrating a provider, or fixing a known workflow problem.

- Reader goal: Complete one task correctly.
- Reader knowledge: Usually intermediate.
- Shape: Goal-driven steps with only necessary context.
- Emphasis: Fast path to outcome.
- Avoid: Long conceptual detours and obvious filler steps.

### Reference

Use for APIs, config fields, CLI flags, limits, supported values, and feature behavior that must be precise and scannable.

- Reader goal: Find accurate details quickly.
- Reader knowledge: Usually experienced or task-focused.
- Shape: Organized facts, tables, examples, and constraints.
- Emphasis: Consistency and easy scanning.
- Avoid: Opinionated explanation and narrative walkthroughs.

### Explanation

Use for architecture, mental models, tradeoffs, "why" questions, and relationships between features.

- Reader goal: Build understanding.
- Reader knowledge: Any level.
- Shape: Concept-first sections that connect ideas.
- Emphasis: Context, reasoning, alternatives, and constraints.
- Avoid: Pretending to be a task guide when the real goal is understanding.

## Check the audience

Before finalizing the type, state the primary audience explicitly:

- Decision makers want architecture, tradeoffs, and high-level framing.
- New users want orientation, prerequisites, and confidence-building steps.
- Integrators want concise instructions, exact requirements, and runnable examples.
- AI agents and retrieval systems want unambiguous headings, explicit nouns, complete metadata, and self-contained pages.

Do not write one page for all audiences if it weakens clarity.

## Keep pages evergreen

Prefer content that stays useful beyond one release. Move rapidly changing announcements, screenshots tied to a moment in time, or release-specific details into changelogs or blog-style updates when appropriate.

## Source pages

- https://www.mintlify.com/docs/guides/content-types
- https://www.mintlify.com/docs/guides/understand-your-audience
