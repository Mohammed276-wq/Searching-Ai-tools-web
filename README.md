# ToolMatch AI

**Find the perfect AI tool, instantly.** Describe what you're trying to do in plain language, and ToolMatch AI matches you with the best AI tools for the job — powered by the Claude API.

## Overview

ToolMatch AI is a single-page, client-side web app. You describe a task (e.g. *"I want to generate AI images for my brand"*), and the app sends your request to Claude, which returns a ranked list of matching AI tools with pricing, features, and a plain-language explanation of why each tool fits.

## Features

- 🔍 **Natural language search** — describe your need instead of picking from categories
- 🤖 **Claude-powered matching** — results are ranked and explained by the Claude API
- 🎯 **Filters** — narrow results by price (Free / Freemium / Paid), skill level, or platform (Web / API / Mobile)
- 🌗 **Light & dark theme** — toggle with preference saved locally
- 🔐 **Local sign in / sign up** — lightweight demo auth stored in the browser (no backend)
- 🧪 **Demo mode** — try the app with sample data, no API key required
- 📱 **Responsive design** — works across desktop and mobile

## Getting Started

This is a static, dependency-free app — no build step or server required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohammed276-wq/Searching-Ai-tools-web.git
   cd Searching-Ai-tools-web
   ```
2. Open `index.html` directly in your browser, or serve it locally:
   ```bash
   npx serve .
   ```
3. On first load, you'll be prompted to enter an [Anthropic API key](https://console.anthropic.com/) — or click **"Skip — Try Demo Data instead"** to explore with sample results.

## How It Works

1. **Describe your task** — tell the app what you're trying to accomplish, in your own words.
2. **Claude analyzes your need** — your request is matched against a wide range of AI tools.
3. **Get matched instantly** — ranked results are returned with clear reasons why each tool fits.

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript (no frameworks or build tooling)
- [Claude API](https://www.anthropic.com/api) (Anthropic) for tool matching
- Browser `localStorage` / `sessionStorage` for theme, demo mode, and local account data

## Privacy & API Keys

Your Anthropic API key is stored **only in your browser's local storage** and is sent directly from your browser to the Claude API — it is never transmitted to or stored on any third-party server.

## License

No license has been specified for this project yet.
