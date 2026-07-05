---
name: starline-landing
description: Build, refine, or review Starline one-page landing pages for e-commerce growth services. Use when Codex needs to create a local prototype, extract Starline positioning from materials, apply the Starline visual system, prepare landing copy, or verify a Starline landing page in browser without deploying.
---

# Starline Landing

## Overview

Use this skill to produce practical Starline landing pages, not generic agency pages. The default output is a local one-page landing prototype for e-commerce growth services, grounded in available Starline materials and verified in a browser before delivery.

## Core Workflow

1. **Find source materials first.**
   - Prefer `landing/materials/Starline-Креды.pdf` when available.
   - Extract text from the PDF with `pdfplumber`, `pypdf`, or another available PDF tool.
   - Render useful PDF pages to PNG when the landing needs visual assets or style reference.
   - Do not invent clients, case numbers, awards, guarantees, or results.

2. **Use the Starline positioning.**
   - Primary claim: `Starline - оператор роста для электронной коммерции`.
   - Supporting claim: Starline manages new customer acquisition, analytics, and sales channels for e-commerce businesses.
   - Strategic angle: Starline is not just a performance contractor; it focuses on growth of the latest customer cohort and business-level GMV.

3. **Build the one-page structure.**
   - Hero with offer and CTA.
   - About/credibility block.
   - Market problem: CPA and attribution can look good while GMV does not grow.
   - Cohort approach.
   - Services grouped around growth, not as a generic catalog.
   - Expected outcome/trade-offs.
   - Process: audit, pilot, scaling.
   - Cases with disclaimers when source data requires confirmation.
   - Team.
   - Lead form.

4. **Apply the Starline visual system.**
   - Dark violet/plum background.
   - White large bold typography.
   - Lime accent for CTA, cohort highlight, and key metrics.
   - Subtle violet wave/orbital line motifs.
   - Star mark as a brand accent.
   - Avoid stock-like agency imagery and generic SaaS card-heavy layouts.

5. **Verify locally before reporting.**
   - Serve static pages from localhost when browser `file://` access is blocked.
   - Check that all images load.
   - Check desktop and mobile breakpoints.
   - Fix horizontal overflow and clipped text before delivery.
   - Do not deploy unless the user explicitly asks.

## Copy Rules

Use:
- `новые клиенты`
- `последняя когорта`
- `GMV`
- `когортная экономика`
- `прогнозируемая экономика`
- `снижение зависимости от ретаргетинга`
- `аудит - пилот - масштабирование`

Avoid:
- unconditional guarantees;
- over-promising `+20-50% GMV` without caveat;
- making contextual advertising the main offer;
- publishing case/client claims without source confirmation;
- hidden placeholder text.

## References And Assets

- Read `references/starline-brand.md` when details of positioning, structure, services, and caveats are needed.
- Use `assets/starter/` as a copyable static landing starter when building a quick prototype.
