# Jev & computer-use illustrations

Three self-contained SVGs for the Jev / computer-use blog series:

- `01-general-agent-loop.svg` — the familiar plan → generate → tool call → observe → re-plan loop.
- `02-jev-decision-workflow.svg` — state + typed questions → Jev → choice / score / noul → policy.
- `03-computer-use-example.svg` — a concrete “Click the Search button” flow through Accessibility observation, JEV selection, fresh-state validation, execution, and verification.

The diagrams share a restrained infrastructure/editorial system: near-black canvas, graphite structure, one warm orange accent for the active path, and minimal labels. There are no visible titles, subtitles, or footer copy inside the artwork. They are vector-only and can be embedded directly in Markdown, HTML, or a blog CMS.

Suggested Markdown:

```md
![The general-purpose agent loop](./assets/jev-and-computer-use/01-general-agent-loop.svg)
```

The diagrams are concept illustrations, not screenshots of the sibling runtime. The labels mirror the current implementation vocabulary in `../jev-computer-use`.
