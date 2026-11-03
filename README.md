# CanvasOS architecture documentation

A first architecture walkthrough for David and Jesse. Reader-facing pages explain the intended platform in ordinary language, with examples and diagrams. This is a draft for human review, not a statement that the described product exists.

## Read locally

1. Run `mint dev --no-open` from this directory.
2. Open the local URL printed by the CLI.
3. Start with **Understand CanvasOS**.

## Edit and check

Read `AGENTS.md` before editing. Use `mint instructions write` for current Mintlify guidance. Navigation is in `docs.json`.

Run `mint validate` and `mint broken-links` after edits. Inspect the rendered pages and diagrams.

`CANON-SOURCES.md` maps the reader-facing pages to the preserved planning library. Maintainer files and the original starter quickstart are excluded from the documentation build by `.mintignore`.

## Publication

The Git remote is `https://github.com/canvasos/docs`. Pushing a connected production branch can publish changes. This local editorial pass does not push or deploy. Reader access and publishing settings must be verified separately before hosted review.

## First-edition review

The first reading path has nine pages and nine diagrams. Two scoped writers prepared the topic pages. An independent reviewer checked standalone readability, architectural coherence and visual explanations. Four material findings were corrected: workspace meaning, the handoff to connected records/actions, data freshness and unresolved outcomes. The shorter initial reading path and the shared delivery example were also clarified.

Final checks passed: Mintlify build/validation, broken links including section anchors, and Git whitespace checks. Browser review loaded all nine routes, checked diagrams, and found no page errors or desktop horizontal overflow. The discovery page was also inspected at a 390-pixel mobile width. Hosted login, access configuration and publication were not performed.
