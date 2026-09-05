# CLAUDE.md — jorgedelacruz07

Claude Code working rules for the GitHub profile README repo. See `AGENTS.md` and
`.ai/` for context, workflows, and prompts. This is a **content repo** (Markdown only).

## Working rules

- No code, no build. Edits are content/editorial only.
- Keep all claims truthful; never fabricate experience, employers, or credentials.
- `README.md` is canonical; touch `README.alternative.md` only when asked.
- Clear technical English; concise, skimmable Markdown.

## "Bug" fixes (broken badge / link / rendering / stale claim)

1. Reproduce (dead link target, malformed Markdown, wrong fact).
2. Apply the minimal fix; edit the alternative only when the request includes it; otherwise report the drift.
3. Verify badges/links resolve and Markdown renders. Summarize changed lines.

## "Refactors" (restructure / rewrite)

1. List the facts/links/badges that must be preserved.
2. Propose the new structure before rewriting large sections.
3. Rewrite for clarity; preserve every fact. Provide a before/after summary.

## Feature work (new section / widget)

1. Confirm the addition is truthful and adds value (e.g., contact, highlights, stats).
2. Prefer lightweight, reliable elements; avoid flaky dynamic widgets.
3. Keep structure coherent with the canonical README.

## Updating Obsidian after decisions

Record editorial decisions (e.g., which README is canonical) as an ADR in
`Jorge's Vault/02-Projects/jorgedelacruz07/Decisions/` (from `ADR-0002`); capture
voice/structure guidelines in `References/`.

## Guardrails

- Do not invent facts. Do not delete sections without confirmation.
- Do not let the two READMEs drift apart in facts/tone.

## Final response format

End each task with: **Summary** · **Files changed** · **Verification** (links/badges
checked, render confirmed) · **Preserved facts** (for rewrites) · **Follow-ups**.
