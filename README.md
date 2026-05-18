# Analytics Hub — Positive Partnerships

A prototype single-page analytics dashboard that brings workshop, social, search and AI-mention data into one Claude-connected view.

**Live site:** _to be enabled via GitHub Pages_
**Status:** prototype, mock data
**Built:** 18 May 2026

## What it shows

- **Workshops** (Arlo + Jotform) — upcoming sessions, fill rate, source split
- **Social** (Facebook, Instagram, Threads, LinkedIn) — top posts, reach, engagement, promo tagging
- **Website & Search** (GA4, Google Ads) — traffic sources, top pages, paid performance
- **AI visibility** (AEO / GEO) — mentions in ChatGPT, Perplexity, Claude, Gemini
- **Cross-reference chart** — overlays social activity against registration events so you can see what a campaign actually did
- **Integration roadmap** — honest status of what speaks to Claude today, what needs a bridge, what's still manual

## Why a prototype

This is a conversation-starter for the PP team and AutismCRC. It uses realistic mock data so we can agree on shape, priorities and the order to build integrations in — before committing to a build.

## Integration status

| Platform | Method | Status |
|---|---|---|
| Meta Ads (FB + IG) | Native MCP | Live |
| Arlo | Native MCP (Zapier) | Live |
| Jotform | Native MCP | Live |
| Google Drive | Native MCP | Live |
| Later.com | API bridge | To build |
| Google Analytics 4 | API bridge | To build |
| Google Ads | API bridge | To build |
| LinkedIn (Marketing) | API bridge | Pending app approval |
| Threads | API bridge | To build |
| AEO / GEO | Manual / Emerging | Manual export |

## Running locally

It's a single self-contained HTML file. Open `index.html` directly, or serve the folder with any static server.

## Hosting

Designed to work on GitHub Pages out of the box. Once Pages is enabled on this repo (Settings → Pages → deploy from `main`), the dashboard will be live at the repo's GitHub Pages URL.
