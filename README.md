# From Disrupting to Driving — Slidev Deck (SSUSD Branded)

A Slidev presentation on Amy Berry's continuum of student engagement, styled
to match Sierra Sands Unified School District's official visual identity
(sampled from the district's own branded PowerPoint template). Companion to
the matching PowerPoint version.

## Brand assets used
- **Colors** (sampled directly from SSUSD's template): deep navy `#022760`,
  secondary navy-blue `#0F5687`, sky blue `#4FA5D7`, sand/tan `#B19E88`,
  jet gray `#76797A` — defined as CSS custom properties in `style.css`.
- **Logo**: `public/ssusd_logo.png` (full-color, transparent, with the
  "Engaging All Learners" tagline), extracted from the district's own
  template file.
- **Title & discussion-slide backgrounds**: `public/ssusd_title_bg.png` and
  `public/ssusd_quote_bg.png` are the district's own background art,
  reused directly for maximum brand fidelity.
- **Font**: SSUSD's template uses Century Gothic (embedded as a
  non-web-safe font in their PPTX). Century Gothic isn't available as a
  web font, so this deck substitutes **Poppins** — a freely-licensed
  geometric sans with similar proportions — for on-screen/web display.
  If you have a licensed web-font version of Century Gothic, swap the
  `@import` and `font-family` rules in `style.css`.

## Run locally
```
npm install
npm run dev
```
Opens at http://localhost:3030. Press `o` for slide overview, `d` for dark mode.

## Build for deployment
```
npm run build
```
Outputs static site to `dist/`.

## Deploying to Vercel (Git-to-Vercel)
This project intentionally avoids `@iconify-json/lucide` as an external
dependency (it fails to resolve in Vercel's build sandbox). Instead, all
Lucide icon paths are baked directly into `components/Icon.vue`, which
Slidev auto-registers — no additional icon package needed.

Global styles (fonts, CSS custom properties for the SSUSD palette) live in
the project-root `style.css`, not in per-slide `<style>` blocks, so they
load correctly on every route regardless of entry slide.

Just connect the repo to Vercel with the default Vite/Slidev build command
(`npm run build`, output directory `dist`) — no extra configuration needed.
Make sure the `public/` folder (logo + background images) is committed;
Slidev serves it automatically at the site root.

## Speaker notes
Full narration is included as HTML comments under each slide (visible in
presenter mode — press `p` during `npm run dev`, or in the exported PDF
speaker-note view).

## Sources & licensing
- Content adapted from Berry (2023) and Berry & Picker (2025a, 2025b) —
  full APA references on the final slide.
- Icons: Lucide (ISC License), https://lucide.dev — used under license,
  attributed on the References slide.
- SSUSD logo and background art: property of Sierra Sands Unified School
  District, used per the district's own template file.

## Fixes applied (this revision)
- Fixed a Slidev static-export bug where the internal "go to slide" dialog
  stayed permanently visible over every slide — added a CSS override to
  force it hidden by default.
- Fixed a Slidev bug where `background:` set as a hex color in a slide's
  frontmatter didn't reliably apply on slides after the first, leaving
  white text invisible on a white background. Worked around it by painting
  the background with a full-bleed `<div>` in the slide body instead.
- Replaced fragile inch-based absolute positioning (which doesn't scale
  correctly with Slidev's internal canvas system) with a flow-based
  layout using a negative-margin technique for full-bleed header bands,
  and percentage/rem-based positioning for the image-background slides.
- **Rebuilt the title slide**: the accent stripe from the background image
  was cutting directly through the title text, and the session label was
  overlapping the logo's "Unified School District" subtitle. Repositioned
  the whole text block below the navy band with proper clearance, and
  fixed a case where a heading's font-size utility class was being
  silently overridden by the theme's own CSS (forced via inline style).
- Removed redundant double bullet markers.
- Tightened padding, font sizes, and line-height throughout so every
  slide fits within a standard 1280×720 presentation screen with no
  clipping, overflow, or overlapping elements.

All 14 slides have been visually verified via automated browser
screenshots at 1280×720 (a standard 16:9 presentation resolution).
