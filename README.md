# Infinite Reach

*Notes from a fast-moving world.* — a short daily read on the frontier of technology, explained from scratch.

**Live site:** https://amlervishal.github.io/infinite-reach

A new issue is published every morning. Each one is a calm, plain-English few-minute read: the one big
story, a handful of quick hits, a deep dive that explains one idea from scratch, a hand-drawn diagram or
chart, and a "Decoder" glossary for the jargon.

## How it works
- Plain static HTML + CSS on GitHub Pages — no build step, no dependencies.
- `index.html` paginates through `posts.json` (client-side).
- Each issue is one self-contained file in `issues/`.
- Theme adapted from [ThariqS/html-effectiveness](https://github.com/ThariqS/html-effectiveness).
- Issues are written and published daily by a scheduled Claude Code agent following [`AGENT.md`](AGENT.md).
