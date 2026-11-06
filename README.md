### Hi, I'm Ornella 👋

Solo builder and AI engineer. I ship products end-to-end — from the Claude-powered backend to the pixel-pushed frontend to the Vercel deploy.

Published in **[IJACSA 2026](https://github.com/ornellabahidika/when-agents-delegate-supplement)** on multi-agent delegation patterns.

📍 Based in the US · 📫 [bahidikaornella@gmail.com](mailto:bahidikaornella@gmail.com)

---

## What I'm building

### 🧳 [VoyPilot](https://voypilot.com) &nbsp;·&nbsp; _live_

**AI travel advisor.** Tell it your budget, dates, and vibe — it plans the whole trip in ~30 seconds: destinations matched to your constraints, real-priced flights and hotels (sourced from Google Flights/Hotels via SerpAPI), day-by-day itinerary, events during your stay, transport options, and other travelers heading the same way.

**Stack**: Next.js 16 · React 19 · TypeScript · Tailwind · Claude Haiku 4.5 (streaming) · Tavily web search · SerpAPI · PostHog · Vercel
**Features**: 8 languages · live flight pricing with affiliate links · session streaming via SSE · deterministic fare model fallback · PostHog session replays
**Status**: shipped, in production at **[voypilot.com](https://voypilot.com)**
**Code**: private

---

### 🍜 [orneEat](https://orneeats.lovable.app) &nbsp;·&nbsp; _live_

**Snap your fridge, get dinner ideas.** Upload a photo of your ingredients → vision AI identifies what you have → the app suggests recipes you can actually make tonight, filtered by your food preferences. Built for the moment you stand in front of the fridge with no inspiration.

**Stack**: Vite · React 19 · TypeScript · Tailwind · shadcn/ui · Supabase (image-analysis edge function + recipe search)
**Status**: live at **[orneeats.lovable.app](https://orneeats.lovable.app)**, actively iterating
**Code**: private

---

### 🤖 Agent Builder &nbsp;·&nbsp; _in development_

Workspace for experimenting with AI agent orchestration patterns — building on the ideas from my IJACSA paper on how agents delegate and where it breaks down.

**Status**: early scaffolding
**Code**: private

---

### 📄 [When Agents Delegate — Supplement](https://github.com/ornellabahidika/when-agents-delegate-supplement) &nbsp;·&nbsp; _published_

Supplementary materials (S1 audit working notes, S2 audit evidence) from my **IJACSA 2026** paper on multi-agent delegation patterns — how AI agents hand off subtasks to each other and what goes wrong when they do.

**Stack**: Python
**Status**: public, cited in paper

---

## Stack I reach for

**Frontend**: Next.js · React · TypeScript · Tailwind · shadcn/ui · Vite
**AI**: Claude (Haiku 4.5, Sonnet 5) · Anthropic SDK with streaming + Zod structured output · vision models for image→data flows
**Search & data**: Tavily · SerpAPI · Photon (OpenStreetMap) · Supabase
**Infra**: Vercel · Lovable · GitHub · PostHog
**Workflow**: single-dev, ship fast, measure with PostHog, iterate in public (well, selectively public)

---

*Most product code is private while I'm still iterating. Want a demo of anything? Email me — happy to screen-share.*
