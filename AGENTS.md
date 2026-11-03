# CanvasOS architecture documentation

## Audience and purpose

Write for David and Jesse reviewing the shape of CanvasOS. Assume product fluency, but no knowledge of this chat, research identifiers or internal shorthand. Help readers picture how the systems work together.

## Readability is the primary acceptance criterion

- Explain the purpose before the mechanism.
- Use familiar words and concrete examples. Define necessary terms at first use.
- Each page must make sense on its own. Links provide depth rather than missing explanations.
- Explain who does what, what information moves, and what happens next.
- Keep research IDs, test counts, hashes and implementation bookkeeping out of the main reading path.
- Distinguish agreed direction, proposed design and unresolved choices in ordinary language.
- Preserve meaning when simplifying. Do not invent capabilities, promises or architectural decisions.
- Use diagrams for meaningful relationships, sequences or lifetimes. Explain what each diagram shows.
- Use sentence case, active voice and calm prose. Avoid hype and invented terminology.
- For procedures, use one instruction per step and sentences under 20 words. This rule does not constrain architectural analysis.

## Scope and sources

This is a proposed first architecture canon, not a manual for implemented behavior. The source planning library is `/Users/davidturner/Documents/Codex/2026-10-25/we-v/outputs/canvasos-review`.

Use `canonical-drafts/01-DIRECTION.md`, `master-plan/01-SYSTEM-ARCHITECTURE.md` and `master-plan/30-PLACEMENT-AND-CUSTODY-DECISIONS.md` as the direction spine. Use topic chapters for detail. The adopted placement ledger supersedes old unresolved-placement labels.

Keep original research intact. Maintain source mapping in `CANON-SOURCES.md`, outside site navigation. Do not copy the research archive into the site.

## Agent assignments

Writers own explicitly assigned pages and must preserve peers' edits. Reviewers return section-specific findings with suggested corrections. Review readability, architectural coherence and visual usefulness separately. The orchestrator owns integration, navigation, terminology and final checks. Do not expand this pass into implementation, new research or a verification framework.

## Mintlify

Pages use MDX with title and description frontmatter. Use root-relative, extension-free page links. No body H1 or HTML comments. Run `mint instructions <topic>` before relevant work; read `write`, `write components` and `configure navigation` as applicable.

Run `mint validate` and `mint broken-links`, then inspect the local preview. Use the current plan; do not introduce Enterprise-only features. Local editing does not authorize pushing, deploying, changing access settings or creating recurring tasks.
