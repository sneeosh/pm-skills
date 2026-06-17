# Curated PM Skills — for corporate review

A hand-picked subset of the most impactful skills from this marketplace, extracted as
standalone markdown so they can be reviewed and copied into a corporate Claude Code config.

Each file is a verbatim copy of the original `SKILL.md`, renamed `<plugin>__<skill>.md` so the
source is traceable. Original content is unchanged — including the YAML frontmatter
(`name` + `description`) and any "Further Reading" links.

Curated for a senior PM working inside a technical/code environment. Selection biased toward
code-native and daily-driver PM work; personal/legal tools (resume, NDA, privacy policy) and
marketing-org-owned skills were intentionally left out.

## What's here

### pm-ai-shipping — code-native, security-flavored (highest relevance)
- `pm-ai-shipping__intended-vs-implemented.md` — audit the gap between documented intent and what the code actually enforces (cite file+line; the standout skill)
- `pm-ai-shipping__shipping-artifacts.md` — the durable doc set that makes an AI-built app reviewable before shipping

### pm-execution — daily-driver PM work
- `pm-execution__create-prd.md` — 8-section PRD template
- `pm-execution__brainstorm-okrs.md` — draft objectives and key results
- `pm-execution__outcome-roadmap.md` — outcome-oriented roadmap
- `pm-execution__pre-mortem.md` — surface failure modes before they happen
- `pm-execution__strategy-red-team.md` — adversarially stress-test a plan
- `pm-execution__prioritization-frameworks.md` — RICE/ICE/etc. prioritization
- `pm-execution__user-stories.md` — user stories with acceptance criteria

### pm-product-discovery — discovery rigor
- `pm-product-discovery__opportunity-solution-tree.md` — connect outcomes to opportunities to solutions
- `pm-product-discovery__identify-assumptions-new.md` — surface riskiest assumptions for a new idea
- `pm-product-discovery__prioritize-assumptions.md` — rank assumptions by risk/uncertainty
- `pm-product-discovery__interview-script.md` — generate a customer-interview script

### pm-data-analytics — self-serve data work (adopt if you write SQL yourself)
- `pm-data-analytics__sql-queries.md` — natural language → SQL (BigQuery/Postgres/MySQL/Snowflake)
- `pm-data-analytics__cohort-analysis.md` — cohort/retention analysis
- `pm-data-analytics__ab-test-analysis.md` — analyze A/B test results

## Notes before adopting
- These are public, third-party skills (owner: Paweł Huryn / Product Compass). Vet content and
  pin a version before putting them in a shared corporate config.
- "Further Reading" links point to external articles. Neutral in tone, but present — check
  against any policy on external links.
