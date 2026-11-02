# Student Helper 🎀

**English** | [Български](README.bg.md)

A personal all-in-one app for everyday student life: budget, class schedule and deadlines, shopping list, and a wardrobe with outfit suggestions. Works on both phone and desktop. The interface is in Bulgarian.

## Sections

- **Today** — today's classes, the nearest deadlines, this month's spending, and an outfit suggestion based on the weather and on whether there are classes that day.
- **Budget** — quick expense logging by category (food, transport, coffee, entertainment, university, clothes, bills), a breakdown of where the money goes, and a monthly limit. Amounts are in euros.
- **Uni** — a weekly schedule of lectures and lab sessions (room, lecturer) and a list of exams, lab reports and tests with a countdown in days.
- **Shopping** — a checklist for groceries; tapping “Done shopping” sends the total straight to the budget.
- **Wardrobe** — clothes with photos, categories, season and style; a “Forgotten” filter for items not worn in a month; and an **Outfit builder** for putting together and saving complete outfits.

## Tech

- A single HTML file with plain JavaScript and CSS, no external libraries.
- Fonts: Unbounded, Manrope, Caveat and JetBrains Mono from Google Fonts.
- Light and dark themes.

## Data storage

In this version, data (including photos) is stored using Claude Artifacts' built-in storage, in a private space only the owner can access. Because of that, opening `index.html` outside of Claude shows the interface but does not save changes.

## Roadmap

- [ ] Standalone version with Supabase (database, email sign-in, photo storage) and Row Level Security, so each user can only access their own data
- [ ] PWA: manifest, custom icon and service worker for installation and offline use
- [ ] Hosting on GitHub Pages
- [ ] Optional: Android app
