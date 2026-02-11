# Flipper Zero BadUSB (DuckyScript) – Node/Express + React (Vite) Demo

Scripts for a staged demo on macOS Terminal.

## Requirements
- Node.js + npm installed
- Terminal focused before running payloads
- Higher DEFAULT_DELAY to avoid dropped characters

## Scripts
- `macos/01_create_fullstack_myapp.txt` – create `~/Dev/myapp` (server + client)
- `macos/02_sanity_check.txt` – verify structure and scripts
- `macos/03_showtime.txt` – start server, health check, start client

## Notes
- API default port: 3001
- Health check: `curl -s http://localhost:3001/api/health`
