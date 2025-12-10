# the-compounding-creator
Unified analytics dashboard for financial trading, sports betting, digital marketing, health and fitness

# Unified Analytics Dashboard

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

This project is a unified analytics app that aggregates data from multiple domains—**financial trading**, **sports betting**, **digital marketing**, and **health & wellness**—into a single, sleek dashboard. The app surfaces **cross-disciplinary insights** and cause-effect patterns, notifying the user when correlations emerge between behaviors (like workouts) and outcomes (like trading performance or betting results). The UI is minimal, dark, and stylish, with separate screens for dashboards, insights, and an AI assistant for natural-language exploration.

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Core Features](#core-features)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [Development Plan](#development-plan)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

The user connects multiple data sources across four key areas of the internet economy:

- **Financial trading**: MetaTrader, prop firm platforms, TradingView, Polymarket (BTC futures)
- **Sports betting**: Polymarket prediction markets, sportsbooks 
- **Digital marketing**: Google Analytics 4, ad platforms (Meta, Google Ads)
- **Health & wellness**: Apple Health/Apple Watch (steps, running, biking, heart rate)

The system ingests and normalizes this data into a single store. **Backend processes look for patterns across domains**—for example:
- "On days with more than 10k steps, trading results improve by X%"
- "Sports betting activity on a given day correlates with better/worse trading performance the next day"
- "Campaign spend spikes align with changes in other outcome metrics"

When meaningful patterns are detected, the app **pushes insights** to the user (in-app notifications). The goal is to give the user a **multidisciplinary view** of how their behaviors and decisions interact.

## ✨ Core Features

### Dashboards Screen
- Unified overview with domain-specific sections
- **Domain-specific filters**:
  - **Trading**: timeframe, win/loss ratios, profitable/unprofitable days, symbol, strategy
  - **Sports betting**: timeframe, sport, league, bet type, ROI
  - **Marketing**: channel, campaign, spend, conversions, ROAS
  - **Health**: steps, workouts, distance, heart-rate ranges, sleep

### Insights Screen
- Feed of automatically derived **cross-domain correlations**
- Example insights: "Your trading results are significantly better on days without sports bets"
- Each insight includes explanation, visual (small chart), and key metrics

### AI Assistant Screen
- **Hybrid chatbot** for analytics exploration
- Ask: "How did my trading go on days I ran more than 10k steps?" 
- Responds with natural-language + supporting charts/tables

### Design
- **Sleek, thin, dark, clean** - glossy black theme
- Minimal but "hard hitting and stylish"
- High-contrast, focused visuals (no noisy dashboards)

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm/yarn/pnpm
- [Supabase account](https://supabase.com) (free tier)

