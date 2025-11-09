# Pitch Deck (≤6 slides)

## Slide 1: Problem & Who Cares

**The Problem:** 95% of retail investors lose money. Traditional platforms offer data, not intelligence. Individual investors lack access to institutional-grade AI that can analyze 100+ factors across Indian and US markets in real-time.

**Who Cares:**
- 50M+ retail investors in India seeking 2%+ weekly returns
- 100M+ US retail investors underserved by robo-advisors
- $3T+ global retail trading market growing 15% YoY

---

## Slide 2: Insight & Why Now

**Insight:** AI can democratize institutional trading intelligence. By combining momentum scoring, risk algorithms, and multi-model consensus, we can predict 2% weekly returns with 60%+ accuracy—previously only available to hedge funds.

**Why Now:**
- LLMs enable natural language stock analysis at scale
- Real-time market APIs (Yahoo Finance, Alpha Vantage) are free/cheap
- Retail investors demand AI-powered tools (ChatGPT era)
- Indian market liberalization + US market accessibility = perfect timing

---

## Slide 3: Solution Demo

**Kiraak AI** - Your AI Personal Investor

**Core Features:**
- **AI Recommendations Engine**: BUY/SELL/HOLD with confidence scores (0-10)
- **2% Weekly Returns Algorithm**: Filters stocks with 2%+ expected returns
- **Risk Scoring (0-100)**: 9-factor algorithm (Beta, Sharpe, Volatility, Financial Health)
- **Sector Analysis**: Real-time momentum scoring across Technology, Healthcare, Finance, Energy
- **Portfolio Management**: Multi-portfolio tracking with P/L analytics
- **Trading Recommendations**: Entry zones, targets (conservative/moderate/aggressive), stop-loss

**Tech Stack:** Next.js 14, TypeScript, SQLite, Real-time market data APIs

---

## Slide 4: Tech Architecture

**Models & Data:**
- **Momentum Scoring Algorithm**: Price + Volume momentum (0-1 scale)
- **Risk Scoring Algorithm**: 9-factor model (Beta, Sharpe, Sortino, IV, Current Ratio, Short Interest, etc.)
- **AI Recommendation Engine**: Multi-factor decision tree (momentum >0.6, price change >2%, volume >1M = BUY)
- **Data Sources**: Yahoo Finance API (primary), Alpha Vantage (fallback), Proprietary stock analysis JSON

**Stack:**
- Frontend: Next.js 14 (App Router), React 19, Tailwind CSS
- Backend: Next.js API Routes, SQLite database
- AI/ML: Real-time market data processing, momentum calculations, risk algorithms
- Infrastructure: Unix server deployment, PM2 process management

---

## Slide 5: Value & GTM

**Who Pays:**
- **Freemium Model**: Free tier (limited recommendations), Premium ($29/month) for unlimited AI analysis
- **B2B Licensing**: White-label AI engine to brokerages ($10K-$100K/year)
- **Data Insights**: Aggregated anonymized trading patterns to institutions

**How to Reach:**
- **Direct**: SEO-optimized landing page, content marketing (investment blogs)
- **Partnerships**: Integrate with Zerodha, Upstox, Robinhood APIs
- **Viral**: Share weekly returns dashboard, referral program
- **B2B**: Direct sales to Indian/US brokerages, fintech platforms

**TAM:** $50B+ (retail trading tools market)

---

## Slide 6: Roadmap & Risks

**Roadmap:**
- **Q1 2025**: Launch MVP, 1K beta users, 60% recommendation accuracy
- **Q2 2025**: Add LSTM price prediction models, sentiment analysis, 10K users
- **Q3 2025**: B2B partnerships, white-label licensing, $1M ARR
- **Q4 2025**: Expand to commodities, options, international markets, $5M ARR

**Risks:**
- **Regulatory**: Financial advice regulations (mitigated: educational tool, disclaimers)
- **Market Volatility**: AI accuracy drops in bear markets (mitigated: risk scoring, stop-loss)
- **Competition**: Robinhood, Zerodha adding AI (mitigated: first-mover in India, superior algorithms)
- **Data Quality**: API rate limits, data accuracy (mitigated: multiple sources, caching)

**Exit Strategy:** Acquisition by Zerodha/Upstox ($100M+) or IPO ($1B+ valuation at 10M users)

