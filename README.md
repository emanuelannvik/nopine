# Nopine

**Sweden's digital receipt and loyalty platform.** Nopine turns paper receipts into a consumer app, a retailer and brand dashboard, and an AI-driven loyalty pilot.

Live: [nopine.io](https://nopine.io/en)

> This repo is a public overview. The application source is private. Product access and demo on request.

## What it is

- **Consumer app**: digital receipts, loyalty, brand cashback, and BankID sign-in.
- **Retailer and brand dashboard**: a web console for merchants to manage stores, offers, and cashback campaigns.
- **AI loyalty pilot**: LLM-driven personalization on top of receipt and purchase data.

Built as a monorepo: an Expo / React Native consumer app, a Next.js dashboard and marketing site, and a shared Supabase backend.

## Stack

| Layer | Tech |
|---|---|
| Consumer app | Expo SDK 51+, React Native, native dev client |
| Dashboard / web | Next.js 16 (App Router), React 19, Tailwind v4 |
| Auth | Supabase Auth, BankID, magic links + OAuth |
| Backend | Supabase Postgres with RLS, Deno edge functions, Realtime |
| AI | OpenAI (chat + planning) |
| Notifications | Expo Push, Resend (transactional email) |
| Hosting | Vercel (web), Supabase (DB + edge functions), Apple TestFlight (app) |

## Role

Founder and engineer. I built the product across mobile, web, and backend, and I run the retailer pilot.

## Links

- Site: [nopine.io](https://nopine.io/en)
- Author: [Emanuel Annvik](https://github.com/emanuelannvik)
- Contact: emanuel.annvik@gmail.com
