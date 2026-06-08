Global context: C:\the_vault\knowledge\travis-context.md
Client context: C:\the_vault\projects\clients\PJs-Tree-Service\PJs-Tree-Service.md

# PJ's Tree Service — Proposal Demo

## What This Is

Single-page HTML proposal for Josh Allen / PJ's Tree Service. Built for Travis Smith / Outfox Consulting.  
Hosted on Vercel. Sent to Josh before the Tuesday June 9, 2026 follow-up call.

## Directory Layout

```
pjstreeservice-demo/
├── CLAUDE.md          — this file
├── index.html         — the entire proposal (HTML + CSS + JS inline, single file)
└── vercel.json        — Vercel static site config
```

## Design System

- **Palette:** Black/white/gray only — #0a0a0a, #ffffff, #f2f2f2, #4a4a4a, #e0e0e0
- **Fonts:** Inter 700–900 (headings) + Inter 400–500 (body) via Google Fonts
- **Logo:** Styled text fallback ("PJ's Tree Service" bold + "Missoula, MT" subtitle) — swap in PNG when available
- **Layout:** Single scrolling page, max-width 880px centered, mobile responsive

## Key Content Decisions

- Demo phone number: **406-926-7130** (Bland.ai agent)
- Offer name: **The Background Office**
- Pricing: $1,500 setup / $500/month
- CTA framing: "Looking forward to Tuesday" — no hard close
- No Anthropic API — this is a static proposal, no chat interface

## Reference Builds

- MPS Proposal — same single-page scrolling format, hosted Vercel (see travis-context.md)
- Outfox website — same Vercel deploy pattern

## Source Files (Vault)

- Build spec: `C:\the_vault\projects\clients\PJs-Tree-Service\proposal-build-spec.md`
- Offer design: `C:\the_vault\projects\clients\PJs-Tree-Service\offer-summary-v1.md`
- Client file: `C:\the_vault\projects\clients\PJs-Tree-Service\PJs-Tree-Service.md`

## Deploy

```
vercel --prod
```

Static site — no build step required. Vercel serves index.html directly.

## Status

- Phase: Built and deployed
- Logo: Styled text fallback (clean PNG not yet obtained)
- Demo number: Live — 406-926-7130
