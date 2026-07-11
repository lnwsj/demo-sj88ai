# demo-sj88ai — Apps Showcase

## Brand & Context
- **Owner:** lnwsj (Thai developer)
- **Concept:** "ผลงานจาก AI" — AI-built & AI-augmented apps
- **Audience:** fellow devs, recruiters, Thai tech community
- **Promise:** every card has a *real, working* demo button — not just screenshots

## Layout
- **Hero:** Large gradient title, subtitle, scroll cue. No video (perf).
- **Web Apps section:** 2 large cards (FitCheck, Karaoke) — full screenshot + Launch Demo (opens in modal iframe) + View Source.
- **Desktop Tools section:** 4 cards (MiniCut, PNG→JPG, RemoveBG, BatchRename) — interactive in-page demo (works in browser) + GitHub Source link + Run command snippet.
- **Footer:** GitHub link, built-with.

## Tech
- Single-file HTML/CSS/JS (no build step)
- All 4 desktop apps have working in-browser ports:
  - MiniCut → HTML5 `<video>` + trim timeline
  - PNG→JPG → Canvas + file API
  - Remove BG → @imgly/background-removal CDN
  - Batch Rename → File System Access API + natural sort
- 2 web apps launch in fullscreen iframe modal (sandbox-isolated)

## Color & Type
- Dark navy backdrop (#0a0e1a → #111827)
- Accent: warm amber (#f59e0b) + emerald (#10b981) — anti-SaaS-blue
- Highlight: rose accent (#f43f5e) for interactive buttons
- Type: Inter (UI) + JetBrains Mono (code)
- Bilingual: Thai + English mixed where natural

## Motion
- Card hover: lift + glow + screenshot zoom
- Modal: scale + fade in
- Buttons: subtle gradient sweep on hover

## Honest Scope
- Live demos for web apps: link to existing codehub.sj88ai.com URLs
- Web ports of desktop tools: simplified (not 1:1) but functional
- Source links: real GitHub URLs to lnwsj/* repos
