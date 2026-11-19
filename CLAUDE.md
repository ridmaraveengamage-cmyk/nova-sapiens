# CLAUDE.md — Nova Sapiens portfolio

Guidance for Claude Code when working in this repository.

## Project

Static portfolio site for Nova Sapiens (Sri Lanka): Branding & Marketing, Content Development, Digital Marketing, Corporate Communication, Tech Solutions. Owner: Ridma. Hosted on GitHub Pages from `main` (root).

## Structure

- `index.html` — the whole site: CSS in `<style>`, data and rendering in one `<script>` at the end of `<body>`. No build step, no framework.
- `.nojekyll` — tells GitHub Pages to serve files as-is.

Key parts of the script:
- `A` — SVG artwork library (`gcar`, `gtip`, `gmyth`, `greel`, `ggrid`, `gads`, `gcover`, `ahero`, `alogo`, `asoc`, `areel`, `wposter`, `wdoc`, `wstage`, `nsite`, `nbrand`). `art(id)` and `phone(id)` render them.
- `services`, `cases` (keys `genova`, `avishka`, `awakaasha`), `gallery`, `steps`, `quotes`, `vals` — content data.
- Case studies are routed on the URL hash (`#genova` etc.) and rendered into `#cs`.

## Brand

- Colours: Midnight `#0B1020`, Midnight 2 `#141B30`, Paper `#F5F3EE`, Sand `#EBE7DD`, Nova Gold `#F2B33D`, Slate `#4A5063`.
- Type: Space Grotesk (headings), Inter (body), Noto Sans Sinhala (Sinhala).
- Primary logo: four-point Nova Star with a small spark + "NOVA SAPIENS". Secondary: "NS" monogram badge.
- Tagline: "Ideas that think. Brands that shine."

## Rules

- Never present invented results or testimonials as real. Sample figures/quotes must keep the visible "Sample" label until the owner supplies real, approved ones.
- Don't hotlink images from Pinterest or other sites; add images to `images/` in the repo.
- Keep motion wrapped so `prefers-reduced-motion` still works.
- Keep everything working at 360px wide.
- Test by opening `index.html` locally (`python3 -m http.server`) before pushing to `main`.

## Open to-dos

- Real results, client quotes, contact details and social links
- Real project images to replace the SVG artwork
- Client permission for each case study
