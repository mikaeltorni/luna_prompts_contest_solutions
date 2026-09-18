# AGENTS.md — luna_prompts_contest_solutions

Project instructions for any agent working in this repository. They outrank
generic agent defaults and any skill, including discoverability/SEO skills.

## What this repository is

Weekly Luna Prompts contest solutions, one directory per contest week (`2025_week41` … `2025_week45`), kept as a public record of the submitted prompts and their reasoning.

## Never add a static docs site

This repository is read on GitHub itself; it is not published as a website.
Do not create — and do not restore — any of:

- `docs/index.html` or any other HTML page,
- `sitemap.xml` or `robots.txt` anywhere in the tree,
- `_config.yml`, `.nojekyll`, Jekyll/Pages scaffolding, or a GitHub Pages
  deployment,
- README badges or links that point at a `github.io` site.

A missing published site is not a gap to fix. SEO or discoverability audits
score the published-site and crawlability rows
`N/A — static docs site out of scope by owner policy` and compute the
normalized total without them. Never enable GitHub Pages here.

## Never add an `llms.txt`

No `llms.txt` belongs in this repository — not at the root and not under
`docs/`. Never add or restore one. The README and the GitHub About text carry
the one-line definitional sentence on their own; audits score the `llms.txt`
row `N/A — llms.txt out of scope by owner policy` and evidence the
definitional-sentence row from the README and About text only.

## Repository assets are not a site

`docs/reference-flow.svg` is the flow diagram. These are repository assets that the README
embeds — keep them.

## No CI

Do not add `.github/workflows/` or any other CI/CD pipeline, and do not add a
build-status badge. Verification runs locally.
