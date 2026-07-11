# Hi, I'm Vlada 👋

Fullstack developer based in Aberdeen, Scotland. I build and deploy production web apps — Vue 3 + FastAPI + Docker — not just templates.

🌐 [Mnimi&Baldcat.dev](https://www.baldcat.dev/) · 🔮 [tell.guru](https://tell.guru) · 📩 mnimi.baldcat@gmail.com

---

## Client work

🍀 **[Scotia Lapidary](https://www.scotialapidary.com/)** — custom Drupal site for a Scottish gem-cutting artisan. Full front-end build (Bootstrap 5, SCSS, custom sparkle animation, diamond SVG preloader), client-managed CMS so the owner edits all content without touching code.
[repo](https://github.com/MnimiMi/scotialapidary)

💅 **Beauty salon booking platform** — full-stack booking system: multi-step appointment flow, Stripe deposits and gift certificates, Cal.com scheduling, JWT auth, admin panel.
Stack: Vue 3 · PHP · Strapi CMS · Stripe · Cal.com
[repo](https://github.com/MnimiMi/skin_therapist_website)

+ several client projects under NDA

---

## Production systems

🔮 **[tell.guru](https://tell.guru)** — AI-powered tarot & rune readings across a Telegram bot and web app, one shared FastAPI backend. Passwordless magic-link auth with HttpOnly sessions, race-safe daily quotas (atomic Mongo upserts), rate limiting keyed on real client IP behind a proxy, OpenAI budget cap as an abuse backstop.
Stack: Python · FastAPI · Vue 3 · Aiogram · MongoDB · Docker · Traefik · Stripe

🍺 **[PullMyBeer](https://beer.tell.guru)** — same architecture, playful twist: AI "beer prophecies" shaped by location, live weather and time of day. Stampede-guarded geolocation cache (LRU+TTL with in-flight de-duplication), unified identity model across bot/web/anonymous sessions.
Stack: Python · FastAPI · Vue 3 · Aiogram · MongoDB · Docker · Traefik · Stripe

⌨️ **[OopsLayout](https://github.com/MnimiMi/OopsLayout)** — cross-platform keyboard-layout fixer (Windows + macOS), Punto Switcher-style but open source. Detects mis-typed layout with character-bigram language models instead of a dictionary. Windows backend uses a global Win32 hook + SendInput; the native macOS port (Swift) uses CGEventTap and TISSelectInputSource, ships as a signed, notarization-ready universal binary.
Stack: C# · Swift · WinForms · AppKit

---

## Other projects

| Project | What it is | Stack |
|---|---|---|
| [medicare-portal](https://github.com/MnimiMi/medicare-portal) | Role-based hospital dashboard prototype | Vue 3 · Chart.js · Pinia |
| [SmartStockAnalyst](https://github.com/MnimiMi/SmartStockAnalyst) | Inventory management desktop app with AI analysis | Java · JavaFX · PostgreSQL · OpenAI |
| [HospitalMS](https://github.com/MnimiMi/HospitalMS) | Hospital management console app | Java · MariaDB · DAO pattern |
| [RuneAppUI](https://github.com/MnimiMi/RuneAppUI) | Desktop rune reading app with AI predictions | C# · Avalonia · OpenAI |

---

## Stack

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vue 3](https://img.shields.io/badge/Vue_3-42b883?logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646cff?logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-ffd859?logo=pinia&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952b3?logo=bootstrap&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

**Backend & infra**

![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777bb4?logo=php&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-FF4500?logo=traefikproxy&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47a248?logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479a1?logo=mysql&logoColor=white)

**Also working with**

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
