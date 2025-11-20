# Vino-Drafting-Code-Compliance-Agent

This repository contains a minimal static web UI for the "Vino Permit AI" dashboard. Use the included Node.js static server to run the UI locally.

Quick start
1. Install dependencies:

```bash
npm install
```

2. Run the server:

```bash
npm start
```

3. Open your browser at `http://localhost:3000` to view the dashboard.

Notes
- The UI expects Firebase configuration to be injected into the page via global variables (see `public/index.html`). Without Firebase config the UI will show a placeholder message, but the static assets will still load.
- To stop the server, press `Ctrl+C` in the terminal running `npm start`.

Files added
- `package.json` — Node dependency manifest and scripts
- `server.js` — Minimal Express server to serve `public/`
- `public/index.html` — Dashboard HTML you provided

If you'd like a different stack (TypeScript, Vite dev server, or a Dockerfile), tell me and I can scaffold that next.
# Vino-Drafting-Code-Compliance-Agent