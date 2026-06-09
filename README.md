# Martin DC — Athletica Application Profile
### AI-Native Full-Stack Developer · June 2026

A professional profile and interactive presentation built for Athletica's Full-Stack Developer role application. Built entirely with AI-native tools: Claude, MS Copilot, GitHub, and HTML.

---

## What's inside

```
martindc-athletica/
├── public/
│   └── index.html      ← Full profile + AI Lab demos
├── api/
│   └── chat.js         ← Serverless proxy (for Vercel deployment)
├── vercel.json         ← Vercel routing config
└── README.md
```

---

## Features

- **Cover Letter** — written and formatted for Athletica
- **Why Martin fits** — maps every JD requirement to shipped work
- **Background & Education** — career timeline, degrees, certifications
- **Martin's Stack** — technical skills with JD match highlights
- **Martin's Cases** — PadelEye App and Cão Carioca ERP deep dives
- **AI Lab** — three live interactive demos:
  - 🎾 Live Match Analyst — paste padel scores, get tactical breakdown
  - 🏗️ Stack Recommender — describe a problem, get a dev approach
  - 🎙️ Interview Martin — ask any question, Martin answers in first person
- **Chat Widget** — floating assistant that answers questions about Martin
- **Full CV** — embedded inline, no download needed
- **Fully responsive** — desktop, tablet, and mobile

---

## Deployment

### GitHub Pages (current)
This repo is set to **private** — source code is not publicly browsable.
GitHub Pages serves the live site publicly via the URL below.

1. Settings → Pages → Branch: `main` → Folder: `/public` → Save
2. Live at: `https://[username].github.io/martindc-athletica`

### Vercel (alternative)
Supports the serverless proxy in `api/chat.js` for secure key handling.
Add `ANTHROPIC_API_KEY` as an environment variable in Vercel dashboard.

---

## API Key

This project uses the **Anthropic API** for all AI features.
The key is embedded in `public/index.html` for simplicity.

⚠️ **This repo is private. Do not make it public while the key is embedded.**

**Revoke the key after the application closes (June 15, 2026):**
1. Go to `console.anthropic.com`
2. API Keys → find the key → **Revoke**
3. All AI features on the page will stop working (intentional)

---

## Tech stack

| Layer | Tools |
|---|---|
| Frontend | HTML, CSS, Barlow / Barlow Condensed (Google Fonts) |
| AI features | Anthropic API · claude-sonnet-4-20250514 |
| Hosting | GitHub Pages (private repo) |
| Built with | Claude, MS Copilot, GitHub |

---

## Contact

**Martin DC**
Rio de Janeiro, Brazil
martin.cordoba@yahoo.com
[linkedin.com/in/martin-cordoba-a36a841b](https://www.linkedin.com/in/martin-cordoba-a36a841b)
[github.com/CDNitram](https://github.com/CDNitram)

---

*Built AI-native. Revised with human eyes, every step of the way.*
