# SillyTavern V4 Card Builder

An Astro-based local workspace for building SillyTavern character cards, worldbooks, regex injections, and variable-card data in one place.

## Features

- Character card editor with draft autosave in `localStorage`
- Worldbook creation, trigger-key generation, and parameter tuning
- Status bar and regex script injection helpers
- Variable card graph editing and preview tools
- JSON export for SillyTavern-compatible card data

## Local Development

Install dependencies and start the Astro dev server:

```bash
npm install
npm run dev
```

The app runs at [http://localhost:4321](http://localhost:4321) by default.

For Windows, you can also double-click [start-app.bat](/C:/Users/yunqi/Desktop/st-card-builder/start-app.bat) after it has been created in this repo.

## Environment Variables

No environment variables are required for local startup.

The app lets you enter an API base URL, API key, and model in the UI at runtime. Those values are stored in the browser, not read from `.env` files.
