# Student Helper 🎀

**English** | [Български](README.bg.md)

A personal all-in-one app for everyday student life: budget and monthly payments, a calendar, class schedule and deadlines, shopping list, student deals, and a wardrobe with outfit suggestions. Works on both phone and desktop. The interface is in Bulgarian.

## Sections

- **Today** — reminders for upcoming payments and today's events, deals that are live right now, today's classes, the nearest deadlines, this month's spending, and an outfit suggestion based on the weather and on whether there are classes that day.
- **Calendar** — a month view with your own events (time, note, type; birthdays can repeat every year). Dots under each date show events, exam and lab report deadlines, and monthly payments; tapping a day lists everything on it.
- **Budget** — quick expense logging by category, a breakdown of where the money goes, and a monthly limit. **Monthly payments** (rent, transport card, phone, subscriptions) are recorded automatically on their day each month, with a reminder a few days before. Amounts are in euros.
- **Uni** — a weekly schedule of lectures and lab sessions (room, lecturer) and a list of exams, lab reports and tests with a countdown in days.
- **Shopping** — a checklist for groceries; tapping “Done shopping” sends the total straight to the budget.
- **Deals** — happy hours, lunch menus, student nights and other discounts, weekly or one-off, with “Now”, “Later today” and day-by-day views, favourites and category filters.
- **Wardrobe** — clothes with photos, categories, season and style; a “Forgotten” filter for items not worn in a month; and an **Outfit builder** for putting together and saving complete outfits.

## Themes

Six ready-made colour themes (including pink & blue) or two colours of your own choice, plus automatic, light or dark mode.

## Tech

- A single HTML file with plain JavaScript and CSS, no external libraries.
- Fonts: Unbounded, Manrope, Caveat and JetBrains Mono from Google Fonts.
- Light and dark themes built from two user-chosen colours with CSS `color-mix()`.

## Data storage

In this version, data (including photos) is stored using Claude Artifacts' built-in storage, in a private space only the owner can access. Because of that, opening `index.html` outside of Claude shows the interface but does not save changes. Reminders appear inside the app; this version cannot send push notifications.

## Roadmap

- [ ] Standalone multi-user version with Supabase (database, email sign-in, photo storage) and Row Level Security, so each user can only access their own data
- [ ] PWA: manifest, custom icon and service worker for installation and offline use
- [ ] Hosting on GitHub Pages, shared with others by link
- [ ] Automatic weekly update of the Deals section every Monday with current offers from the internet
- [ ] Push notifications for monthly payments, happy hours and new deals
- [ ] Optional: Android app
