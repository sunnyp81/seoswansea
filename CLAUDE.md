# seoswansea — Project Brain

Per-repo brain, migrated from central claude-memory 2026-06-20. Canonical project memory now lives here.

## Current state
- seoswansea.uk — local SEO agency portfolio site (Swansea). Built + visually redesigned May 24 2026.
- 12 pages. Stack: Astro 5 + Tailwind 4. Palette: slate #334155 + coral #FB7185. Typography: Bricolage Grotesque headings + Inter body. SVG favicon (upward trend line).
- Repo: `sunnyp81/seoswansea` (branch `master`). Local: `C:\Users\sunny\repos\seoswansea\`.
- Deploy: Cloudflare Pages (build `npm run build`, output `dist`, NODE_VERSION=22). Custom domain seoswansea.uk + DNS + GSC/Bing verify pending.
- Revenue: £0. Purpose: attract Swansea business-owner leads, demonstrate SEO capability, and serve as a backlink source for sunnypatel.co.uk.

## Key facts & warnings
- 🔴 DE-FOOTPRINTED: NO "Sunny Patel" references anywhere. Brand entity = "SEO Swansea" = the domain. `sameAs: []` on all Organization schemas. No Person schema. Keep it this way.
- Visual redesign (`7f5a21d`): glass cards, aurora blobs, dot-grid background, animated SVG growth chart, stats bar, bento service grid, staggered fade-up scroll animations (IntersectionObserver), shimmer CTA buttons, dark gradient CTA with noise texture. Layout max-w-5xl.
- Inner pages (services, areas, industries) still use the OLD plain design — apply the glass-card/fade-up treatment to them.

## History
- 2026-05-24 — Built (12 pages) + full homepage visual redesign (`7f5a21d`).
- Open next steps: confirm CF Pages connect, connect domain + DNS, GSC + Bing verify + submit sitemap-index.xml, redesign inner pages.
