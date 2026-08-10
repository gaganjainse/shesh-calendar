# 📅 shesha-calendar

Local-first calendar/agenda over an iCalendar **vdir** (as used by
vdirsyncer/khal). Reads upcoming events, searches, lists calendars — no
network, sync delegated to vdirsyncer.

- License: GPL-3.0
- Layer: Mind
- Part of: [Shesha ecosystem](https://github.com/gaganjainse/shesha-ecosystem)

## MCP tools
`upcoming_events`, `search_calendar`, `list_calendars`, `calendar_status`

## Develop
```bash
uv run pytest -q
uv run ruff check .
uv run shesha-calendar-mcp
```
