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
- 2026-06-26 — `97b05ea` site-wide `noindex, nofollow` added to Base.astro:24, live now, part of the June 2026 spam-update portfolio sweep (see `spam-update-jun26-sweep.md` in claude-memory). Marked DEAD alongside seo-birmingham/leeds/seo-furniture; seo-guildford + seoreading were SPARED because they were growing impressions at the time. Retire-vs-reactivate decision explicitly deferred to Sunny, never resolved.
- 2026-07-07 — Ran as an autonomous "recovery" pass under the brief's assumption this was early-ramp striking-distance growth, same playbook as seo-guildford. That assumption is wrong for this site: confirmed live via curl that the noindex from 97b05ea is still active. Zero clicks despite impressions 205 to 524 growth is fully explained by the deliberate noindex, not weak content or lost rankings, impressions are Google's lagging catch-up on a URL it has been told to drop. On-page content is already strong (Quick Answer blocks, full FAQPage/Service/BreadcrumbList JSON-LD on index and seo-audit-swansea, real internal linking, no thin pages) so no content edits were made. Reversing a deliberate portfolio-level spam-de-risk decision without Sunny's sign-off is out of scope for an autonomous pass. Decision needed: (a) reactivate by removing Base.astro:24 if Sunny wants to keep competing here, or (b) leave parked/retire fully to close the deferred item from spam-update-jun26-sweep.md.
