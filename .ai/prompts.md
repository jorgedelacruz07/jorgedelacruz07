# jorgedelacruz07 — Reusable Agent Prompts

> Content repo (Markdown only). Keep all claims truthful; never fabricate facts.

## 1. Project audit (content)
```
Audit the profile content (README.md + README.alternative.md), read-only. Check every
badge/link, compare the two READMEs and flag drift, flag stale/inconsistent claims
(stack, role, employer), and assess structure/skimmability/tone. Recommend a canonical
README. Output a prioritized improvement backlog. Do not fabricate facts.
```

## 2. Safe refactor (rewrite)
```
Restructure/rewrite <section or whole README> while preserving all facts, links, and
badges. List what must be preserved, propose the new structure first, then rewrite for
clarity. Keep README.md canonical. Verify rendering + links. Provide a preserved-facts
before/after summary.
```

## 3. Bugfix (content)
```
Fix this content issue: <broken badge / dead link / rendering glitch / stale claim>.
Reproduce, apply the minimal fix, and fix both READMEs if both are affected. Verify
Markdown renders and links resolve. Don't touch unrelated sections. Summarize changes.
```

## 4. Performance review (rendering & SEO)
```
Ensure the profile renders fast and reliably on GitHub and reads well in search.
Inventory images/badges and flag heavy/flaky ones (dynamic stats widgets). Confirm
GFM renders (tables, HTML, alignment). Assess keyword/heading clarity. Recommend
lightweight alternatives. Prioritized list.
```

## 5. Architecture review (structure)
```
Review the information architecture: section order and hierarchy, and how well it tells
a coherent story for recruiters/peers in a 10-second skim. Map both READMEs, recommend a
canonical structure, and suggest editorial guidelines. Analysis only; keep claims truthful.
```
