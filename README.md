# Nopine

**Sweden's digital receipt and loyalty platform.** Nopine turns receipts into an AI agentic loyalty engine: LLM agents that personalize rewards on top of real purchase data, with a consumer app and a retailer and brand dashboard around it.

Live: [nopine.io](https://nopine.io/en)

> This repo is a public overview. The application source is private. Product access and demo on request.

## What it is

- **AI agentic loyalty** (current focus): LLM agents that personalize rewards, offers, and engagement on top of receipt and purchase data. This is where most of the active development is right now.
- **Consumer app**: digital receipts, loyalty, brand cashback, and BankID sign-in.
- **Retailer and brand dashboard**: a web console for merchants to manage stores, offers, and cashback campaigns.

Built as a monorepo: an LLM agent layer for loyalty, an Expo / React Native consumer app, a Next.js dashboard and marketing site, and a shared Supabase backend.

## Stack

| Layer | Tech |
|---|---|
| Consumer app | Expo SDK 51+, React Native, native dev client |
| Dashboard / web | Next.js 16 (App Router), React 19, Tailwind v4 |
| Auth | Supabase Auth, BankID, magic links + OAuth |
| Backend | Supabase Postgres with RLS, Deno edge functions, Realtime |
| AI | Anthropic (Claude, primary) and OpenAI, driving the agentic loyalty layer |
| Notifications | Expo Push, Resend (transactional email) |
| Hosting | Vercel (web), Supabase (DB + edge functions), Apple TestFlight (app) |

## Role

Founder and engineer. I built the product across mobile, web, and backend, and I run the retailer pilot.

## Links

- Site: [nopine.io](https://nopine.io/en)
- Author: [Emanuel Annvik](https://github.com/emanuelannvik)
- Contact: emanuel.annvik@gmail.com
