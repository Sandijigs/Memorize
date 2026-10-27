# Decisions

- **Monorepo** — engine, app and content change together; one commit keeps them in step.
- **Event log is the source of truth** — progress is rebuilt from events, so sync is just sending events.
- **Engine in pure Rust, compiled to WebAssembly** — one implementation for app and API, so they always agree.
- **Static content bundle** — lessons ship as versioned files; the API stores only progress.
- **A day starts at 4 a.m. local time** — late-night study counts for the evening it belongs to.
- **No AI at runtime** — the app can grow without per-user AI costs.