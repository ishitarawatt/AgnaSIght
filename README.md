# 📊 AgnaSight — AI Deal Intelligence Platform

> Turn raw sales data into clear signals: which deals are at risk, what to do next, and where revenue is heading.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**[🔗 Live demo → agnasight.com](https://agnasight.com)**

## Overview

AgnaSight is an AI-powered deal intelligence platform for sales teams. It analyses pipeline health, flags risky deals early and recommends what to do next, with the goal of improving win rates.

**Goals**
- Identify risky deals early
- Track pipeline health
- Improve conversion
- Support data-driven decisions

## Features

| Feature | What it does |
|---|---|
| 🧠 **AI deal intelligence** | Deal probability and engagement signals |
| 🚨 **Risk detection** | Flags high-risk deals and alerts the team |
| 📈 **Pipeline analytics** | Dashboards for pipeline performance |
| ✅ **Actionable recommendations** | Suggested next actions per deal |
| 👥 **Sales performance insights** | Team performance and deal outcomes |
| 🔮 **Revenue forecasting** | Predictions based on pipeline data |

## Architecture

```
Data sources            Data processing          AI engine
CRM · calls · email ──▶ ETL / data pipeline ──▶ risk scoring · deal prediction
```

## Tech stack

TypeScript · Vite · Tailwind CSS · shadcn/ui-style components · Vitest · ESLint

## Getting started

```bash
git clone https://github.com/ishitarawatt/AgnaSIght.git
cd AgnaSIght
npm install
npm run dev        # start the dev server
npm run test       # run unit tests (Vitest)
```

Copy your environment values into a local `.env` file. Never commit real keys.

## Roadmap

- [ ] Live CRM integrations
- [ ] Model evaluation and accuracy tracking
- [ ] Team-level alerting

## License

MIT, see [LICENSE](LICENSE).
