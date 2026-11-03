# CanvasOS documentation

Architecture and system design for CanvasOS: a platform where agents prepare useful tools and workspaces around the work people need to do.

**[Read the documentation →](https://intentionality-software.mintlify.app)**

## What's inside

- **System map:** the major parts of CanvasOS and how they connect.
- **Discovery and preparation:** how requests and observations become useful workspaces.
- **Applications and agents:** how tools are built, connected and used across interfaces.
- **Knowledge and learning:** how context, feedback and simulation improve future work.
- **Operating foundations:** identity, access, customer installations and platform management.
- **Delivery and open choices:** the intended sequence and decisions still to resolve.

Start with the system map, then follow discovery and preparation into building and using a tool. The remaining chapters explain the supporting systems.

## Local development

This site uses [Mintlify](https://www.mintlify.com). Pages are written in MDX, with navigation and site settings in `docs.json`.

1. Run `mint dev --no-open` from this directory.
2. Open the local URL printed by the CLI.

## Contributing

Read [AGENTS.md](AGENTS.md) for writing guidance. Keep pages understandable on their own, define necessary terms, and use examples and diagrams to explain relationships.

Run these checks after changing documentation:

```bash
mint validate
mint broken-links --check-anchors
```

[CANON-SOURCES.md](CANON-SOURCES.md) maps the chapters to supporting design material. Maintainer files are excluded from the site through `.mintignore`.

## Publishing

Changes pushed to the connected deployment branch are built and published by Mintlify. Review the deployment result before treating a change as live.
