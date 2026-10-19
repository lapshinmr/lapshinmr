# Mikhail Lapshin

**Senior Frontend Engineer · Vue.js / Nuxt.js · TypeScript**

11+ years in software engineering. I build products end-to-end — architecture, frontend,
backend, payments, deployment.

Started with Python in 2015 (scrapers, NLP pipelines, Flask backends), moved through fullstack,
and consciously specialized in frontend because that's where the product actually meets people.
Since 2021 I've worked as a frontend lead: architecture, standards, testing, hiring, mentorship.

📍 Batumi, Georgia (GMT+4) · open to remote and relocation

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 💼 Duty Refunds — UK import VAT refund platform

**[dutyrefunds.co.uk](https://dutyrefunds.co.uk)** · Vue 3, Nuxt 3, TypeScript, Tailwind, Playwright

As the frontend lead in a team of **8**, designed the frontend architecture from scratch across a
multi-sided platform: a B2C refund claim portal, a B2B merchant onboarding flow, and a Shopify app
(React).

- Built E2E testing with Playwright covering **100+** critical user flows, plus a TypeScript layer
  that auto-generates test code, making new tests **2–3x** faster to write
- Architected a themeable Vue 3 component library on Tailwind CSS and Storybook, shared across
  three applications
- Doubled Lighthouse performance score from **40** to **80** through server-side rendering (SSR),
  image optimization, lazy loading of page sections, and tree shaking
- Migrated legacy Vue 2 Options API architecture to Vue 3 Composition API and implemented native
  TypeScript support for bug reduction
- Cut urgent production fixes from **weekly** to **once every few months** and code review time by
  **50%** by rebuilding the two-week sprint as an overlapping release pipeline and introducing
  shared review standards, team coaching, and a pre-deploy checklist
- Removed mid-sprint blocking between frontend and backend by introducing contract-first API
  development, with the frontend authoring API specifications and building against mocked data
  ahead of backend implementation
- Mentored junior developers up to senior level through code review and pair programming, and took
  part in hiring frontend engineers

<img src="assets/duty-refunds-1.jpg" width="800" alt="Duty Refunds — landing page built on the in-house UI kit">
<img src="assets/duty-refunds-2.png" width="800" alt="Duty Refunds — B2B merchant onboarding flow">

---

## 🌿 Samomes — SaaS Aquarium Care Platform

**[samomes.com](https://samomes.com)** · Nuxt.js, Vuetify, Firebase, PWA

Engineered a subscription SaaS for aquascapers across frontend, backend, and data. Interconnected
calculators turn water-chemistry inputs into fertilizer doses, cutting calculation time by
**95%**, and feed every dose into an aquarium journal that users publish and discuss.

- Architected the frontend as a responsive, installable Progressive Web App (PWA) on Nuxt.js,
  Vuetify, and Firebase, with one codebase for desktop and mobile
- Reached a mobile Lighthouse performance score of **95+**
- Migrated the live platform from **Vue 2 to Vue 3**, including the Nuxt and Vuetify upgrades
- Built multi-currency subscriptions using PayPal and YooKassa, plus bilingual support

<img src="assets/samomes-1.png" width="800" alt="Samomes — landing page">
<img src="assets/samomes-2.png" width="800" alt="Samomes — social layer">
<img src="assets/samomes-3.png" width="800" alt="Samomes — Mobile interfaces">
<img src="assets/samomes-4.png" width="800" alt="Samomes — Lighthouse performance score">

---

## 🧩 Food Puzzle — calorie tracker with real composition math

**[food-puzzle.com](https://food-puzzle.com)** · Nuxt.js, Vuetify, Chart.js, Firebase, PWA

I'd used most of the commercial calorie trackers and kept hitting the same wall: they can log a
banana just fine, but they fall apart the moment you cook. So I built my own — MVP shipped in two
months, and I've been logging in it every day since January 2025.

The core problem it solves is portions of composed dishes. You cook a pot of something from ten
ingredients; it loses or gains weight in the pan; then you eat *some* of it. Most trackers make
you either pre-declare serving sizes or recalculate by hand. Food Puzzle lets you build a recipe
from products with a cooking yield factor, then drop that dish into a meal and just type the grams
you actually ate — it back-solves the nutrition from there. Composing complex dishes is easy, and
reusing them is easier.

- Products → recipes (with cooking yield) → meals, at any arbitrary weight
- Daily protein/fat/carbs and calories against a target, with excess tracked separately
- Body weight logged alongside intake, with a smoothed trend line over the noisy daily readings
- Multi-person tracking — one person can realistically maintain entries for several people
- Installable PWA

<img src="assets/food-puzzle-1.png" width="800" alt="Food Puzzle — weight trend and nutrition analytics">

The multi-person mode wasn't a feature for its own sake — it was the design constraint. I added two
other people to the app — an older man and a young woman — specifically to prove the data entry
stayed fast enough that one person could keep several profiles logged without it becoming a chore.
If it survives that, it survives anything.

It also produced the result I'm most pleased with: the older man lost **5.1 kg in 63 days**
averaging 1,833 kcal a day. Look at the orange bars below: he went over target regularly. Nothing
was forbidden, nothing was weighed in misery; the food was simply structured well enough that the
deficit happened on its own.

<img src="assets/food-puzzle-2.png" width="800" alt="Food Puzzle — 63 days of tracked progress">

---

## 🐟 Rastuchka — marketplace for live aquarium plants

**[rastuchka.com](https://rastuchka.com)** · Nuxt.js, Firebase, Vuetify

A niche marketplace connecting aquarium hobbyists across Russia. The core idea: buyers only ever
see what's actually in stock right now, and can find the nearest seller on a map.

Sellers pick items from a curated catalog instead of uploading their own photos — which solved a
real UX problem, since hobbyist photos of underwater plants are uniformly terrible. I shot most of
the catalog myself.

- Grew a community from **0 to 1,500** members in 3 months
- **80–100** active sellers on the map across Russia
- Built solo: frontend, backend, infrastructure, catalog, and community

<img src="assets/rastuchka-1.jpg" width="800" alt="Rastuchka — catalog and search">

---


## 📦 About the repository list

Most of what I've built isn't here, and that's deliberate. Employer and client work is closed for
the obvious reasons. Rastuchka went private once it picked up payment flows, and Food Puzzle once
it started holding real people's health records.

What's public are older side projects. The links above are where the actual work lives — all of it
in production, all of it something you can go click on right now.

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lapshinmr)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lapshinmr@gmail.com)

Open to senior and lead frontend roles — remote or relocation. I'm most useful on products with
real complexity behind the interface, where frontend is treated as engineering rather than
decoration.
