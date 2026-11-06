### Hi, I'm Ornella 👋

Solo builder and AI engineer. I ship products end-to-end — from the Claude-powered backend to the pixel-pushed frontend to the Vercel deploy.

Published in **[IJACSA 2026](https://github.com/ornellabahidika/when-agents-delegate-supplement)** on multi-agent delegation patterns.

📍 Based in the US · 📫 [bahidikaornella@gmail.com](mailto:bahidikaornella@gmail.com)

---

## What I'm building

### 🧳 VoyPilot &nbsp;·&nbsp; _live product_

**The travel planner you wish existed.** Tell it your budget, dates, and vibe, and in ~30 seconds you get a complete trip — 4-5 destinations matched to your constraints, real-priced flights and hotels (sourced live from Google Flights and Google Hotels via SerpAPI, not AI guesses), a day-by-day itinerary, events happening during your stay, local transport options, real traveler reviews, and even group trips of other people heading the same way.

### 🌐 **Try it live → [voypilot.com](https://voypilot.com)**

**Why it's different**
- 🎯 **Real prices, real bookings** — click "Book" and land on the exact offer at the exact price (Google Flights for flights, Google Hotels for stays, with affiliate links)
- ⚡ **Streaming UI** — first destination card appears in ~12 seconds via Server-Sent Events while Claude keeps generating the rest
- 🧩 **End-to-end in one page** — flights, hotels, itinerary, transport, events, group trips, insider tips
- 🌍 **8 languages** — English, Spanish, French, German, Italian, Portuguese, Japanese, Chinese
- 📊 **Instrumented with PostHog** — session replays, funnel tracking, conversion analytics

**Stack**: Next.js 16 (App Router + Turbopack) · React 19 · TypeScript · Tailwind v4 · Claude Haiku 4.5 streaming with Zod structured output · Anthropic SDK · Tavily (web search grounding) · SerpAPI (live flight/hotel data) · Photon/OpenStreetMap (edge-cached location autocomplete) · PostHog · Vercel

**Status**: in production · **Code**: private

---

### 🍜 orneEat &nbsp;·&nbsp; _live product_

**Snap your fridge, get dinner ideas.** Standing in front of your fridge with no idea what to cook? Open your phone, take a photo of what's inside, and orneEat's vision AI identifies the ingredients and suggests recipes you can actually make tonight — filtered by your food preferences.

### 🌐 **Try it live → [orneeats.lovable.app](https://orneeats.lovable.app)**

**Why it's different**
- 📸 **Vision-powered** — upload a photo, ingredients detected automatically
- 🥗 **Preference-aware** — filter by dietary needs and cuisine style
- 📱 **Mobile-first** — built for the phone-in-hand moment at the fridge

**Stack**: Vite · React 19 · TypeScript · Tailwind · shadcn/ui · Supabase (image-analysis edge function + recipe search)

**Status**: live, actively iterating · **Code**: private

---

### 🤖 Agent Builder &nbsp;·&nbsp; _in development_

Workspace for experimenting with AI agent orchestration patterns — building on the ideas from my IJACSA paper on how agents delegate subtasks and where it breaks down.

**Status**: early scaffolding · **Code**: private

---

### 📄 [When Agents Delegate — Supplement](https://github.com/ornellabahidika/when-agents-delegate-supplement) &nbsp;·&nbsp; _published research_

Supplementary materials (S1 audit working notes, S2 audit evidence) from my **IJACSA 2026** paper on multi-agent delegation patterns — how AI agents hand off subtasks to each other and what goes wrong when they do.

**Stack**: Python · **Status**: public, cited in paper

---

## Stack I reach for

**Frontend**: Next.js · React · TypeScript · Tailwind · shadcn/ui · Vite
**AI**: Claude (Haiku 4.5, Sonnet 5) · Anthropic SDK with streaming + Zod structured output · vision models for image→data flows
**Search & data**: Tavily · SerpAPI · Photon (OpenStreetMap) · Supabase
**Infra**: Vercel · Lovable · GitHub · PostHog
**Workflow**: single-dev, ship fast, measure with PostHog, iterate until it's right

---

*Most product code is private while I'm iterating. Want a demo of anything? Email me — happy to screen-share.*
