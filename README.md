# Agora — hero page concepts

**Agora** is an internal platform concept — "a dating service mixed with GitHub" for engineering teams. An onboarding agent reads a team's repos, API specs, and architecture docs to build a searchable capability profile, so other teams can discover prior art instead of rebuilding it.

This repo holds three hero-page design directions for the landing page, each a self-contained HTML file (no build step, no dependencies) with an animated graph of teams/tech that fires like synapses, plus supporting sections showing the onboarding pipeline and sample team profiles.

**Live:** once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch `main` / root), the gallery will be at `https://ewoo.github.io/telp-agora/`.

- [`index.html`](index.html) — gallery linking all three concepts
- [`hero-constellation.html`](hero-constellation.html) — Concept A: full-bleed neural mesh, cyan/violet
- [`hero-console.html`](hero-console.html) — Concept B: split console with domain-clustered graph, amber/teal
- [`hero-radial.html`](hero-radial.html) — Concept C: orbital rings around a central search hub, gold/lime

Open any file directly in a browser, or serve the folder locally:

```bash
npx -y serve . -l 4321
```
