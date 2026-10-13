# Mission Control

Mission Control is a polished, responsive personal AI command center MVP. It turns unstructured brain dumps into organized tasks, ideas, important information, and opportunity signals.

## Included

- Brain Dump capture with local simulated AI classification
- Today's Top 3 prioritization and daily briefing
- Inbox, tasks, ideas, and opportunity views
- Priority changes, completion, archiving, and manual task creation
- Mission Mode with a five-step launch plan
- Neglect detector actions: keep, reschedule, archive
- Opportunity Radar and connection scan interaction
- Vault-grounded assistant panel with suggested questions
- Global search feedback, dark/light mode, responsive mobile layout
- LocalStorage persistence with demo reset

## Run locally

```bash
npm start
```

Then open `http://localhost:4173`.

This first MVP uses a deterministic local simulation for AI interactions so it works without API keys or a backend. The UI is structured so a real model and persistent database can be connected later.
