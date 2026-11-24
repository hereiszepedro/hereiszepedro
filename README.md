# Zé Pedro

Developer based in Portugal. I build web apps, internal tools and machine software for a small
industrial company (watchmaking equipment), and my own products on the side. Almost all of it lives
in private repositories, so here is what it covers.

### Industrial work
- **Machine programming (Schneider):** ladder logic for a Modicon M221 and the Harmony ST6 HMI of a
  pneumatic press for watchmaking, with force measurement over Modbus, safety relay integration and
  manual/maintenance modes with access levels.
- **Bar Dispensing machine:** HMI parameter and text fixes with versioned deploy packages, CE
  nameplate and EU Declaration of Conformity generators, user manual figures and 3D-printed
  identification labels.
- **Internal tools:** a Flask app that tracks customer orders from entry through production, quality
  control and delivery (PDF storage, Excel export, Docker).

### Web
- **Website and back office for a guesthouse:** multilingual Astro site with scroll-driven hero,
  PHP back office with booking-engine (Beds24) integration and payments, Playwright behaviour and
  visual tests, and CI with security checks.

### My own products (in development)
- **IronPass:** multi-tenant SaaS for personal trainers: program builder, client PWA for logging
  workouts, Stripe subscriptions and AI progress summaries (Claude API). Next.js, Supabase
  (Postgres with row-level security), Vitest and Playwright.
- **Celestius:** asynchronous strategy MMO for the web (mobile planned): deterministic combat and wind
  engine in a shared rules package, Hono + PostgreSQL server, PixiJS client, and a bot simulator
  to check game balance.
- **WorkoutTracker:** offline-first training-log PWA that tracks progression per exercise, flags
  plateaus and suggests fixes. React, IndexedDB (Dexie), Vitest.

### Other fields I've worked in
- Hardware prototyping: ESP32 firmware and a CadQuery-modelled enclosure for a Bluetooth audio card
- Game development: a Roblox farming RPG in Luau, and the Celestius game engine above
- Technical documentation: CE conformity paperwork, machine user manuals, HMI texts in two languages
- AI tooling: a dashboard and Android client to monitor and answer AI coding agent sessions on a VPS

### What I work with
- Python: Flask, FastAPI, SQLAlchemy, Jinja2, pytest
- TypeScript: Next.js, React, Astro, Supabase, Vitest, Playwright
- Infra: Docker/Compose, Nginx, Gunicorn, Linux (VPS), Vercel, GitHub Actions
- Industrial: Schneider Modicon M221, Harmony HMI, Modbus serial
- Other: ESP32/Arduino, Swift (SwiftUI), Luau, CadQuery

### Open source
- [home-assistant/core#193698](https://github.com/home-assistant/core/pull/193698): Modbus, make the `hub` field of the `stop` action optional
