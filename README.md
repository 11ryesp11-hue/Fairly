# Fairly ⚖️

**Every argument deserves a verdict.**

Fairly is a lighthearted web app for settling petty arguments between couples, roommates, and friends. Both sides write their version of events, and Fairly hands down a ruling — a blame split, a headline verdict, and a bit of reasoning to back it up.

## How it works

1. Each side writes what happened, from their point of view
2. Tap **Reach a verdict**
3. Fairly returns a blame-split percentage, a one-line ruling, and the reasoning behind it — no more going in circles about who started it

## Features

- **Instant rulings** — no sign-up required to use the core app
- **Copy verdict** — share the ruling as text with one tap
- **Pro waitlist** — sign up to be notified when Fairly Pro launches, with saved verdict history, customizable judge tone, and multi-person disputes

## Tech

- Single self-contained HTML file — no backend, no external API calls
- All judging logic runs client-side (rule-based, not AI), so it's free to host and fast to load
- Fonts loaded from Google Fonts (Source Serif 4, Inter)

## Deployment

Fairly is a static site — deploy it anywhere that serves plain HTML:

- **Render**: New → Static Site → connect this repo → build command blank → publish directory `.`
- **GitHub Pages**: enable Pages on this repo, serving from `main` / root

## Disclaimer

Fairly gives a fast, lighthearted read on petty disputes. It isn't legal or relationship advice.
