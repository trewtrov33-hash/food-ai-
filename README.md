# ReWire — Self-Aversion Hypnosis & Daily Habit Conditioning

A single-file, responsive web app that helps you build a strong, unconscious
disgust response toward a chosen trigger food (white flour, sugar, deep-fried
foods, etc.) through daily guided conditioning sessions.

Everything lives in **`index.html`** — HTML, Tailwind CSS (via CDN), and
vanilla JavaScript, no build step or dependencies required. Just open the
file in a browser, or serve it statically.

## Features

- **Dashboard & Habit Tracker** — set your target food (name + optional
  photo), track a 21-day rewiring streak with a progress ring, log daily
  sessions, and review recent activity.
- **Guided Session module** — an interactive 5-minute timer split into four
  phases (Induction → Sensory Visualization → Repulsion Superimposition →
  Anchor Installation & Clean Refresh), each with its own visuals, color
  theme, and text prompts. Optional text-to-speech narration via the Web
  Speech API.
- **Alerts** — request browser notification permission, schedule up to 3
  daily reminder times, and trigger a 30-second "Pre-Meal Flash Alert"
  before eating.
- **Persistence** — target food, streak, session log, TTS preference, and
  reminder schedule are all saved to `localStorage` and survive refreshes.
- **Dark, mobile-responsive UI** with an emerald "fresh" theme and a
  crimson/purple "aversion" theme for the repulsion phase.

## Running it

Just open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000/`.

## Notes

- All data stays in your browser's local storage — nothing is sent to a
  server.
- This tool is a self-guided habit-conditioning aid, not a medical or
  psychological treatment.
