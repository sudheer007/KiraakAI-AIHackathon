# AI Impact Statement (≤200 words)
currently its human in the loop and once investors build confidence on its recommendations we will be intergarting it to directly execute trades on ur behalf.

## Tasks Automated/Augmented

Kiraak AI automates stock analysis that previously required hours of manual research. The AI augments retail investors by: (1) **Automated stock screening** across 100+ stocks in real-time using momentum and risk algorithms, (2) **Risk assessment** via 9-factor scoring (Beta, Sharpe, Volatility, Financial Health), and (3) **Trading recommendations** with entry zones, targets, and stop-loss levels. This replaces manual technical analysis, fundamental research, and portfolio rebalancing decisions.

## Model(s) Used & Justification

**Three AI engines**: (1) **Momentum Scoring Algorithm** (price + volume momentum, 0-1 scale) identifies trending stocks, (2) **Risk Scoring Algorithm** (9-factor model, 0-100 score) evaluates downside risk, and (3) **AI Recommendation Engine** (decision tree) generates BUY/SELL/HOLD with confidence scores. Justification: Momentum and risk algorithms are proven in quantitative finance; multi-factor models outperform single indicators. Real-time processing enables actionable recommendations.

## Data Provenance & Licenses

**Data sources**: Yahoo Finance API (primary, free, public), Alpha Vantage API (fallback, free tier 5 calls/min), and proprietary stock analysis JSON files (AI-generated). All data is publicly available market data; no personal user data used for training. Licenses: Yahoo Finance (public API, no restrictions), Alpha Vantage (MIT-compatible free tier).

## Guardrails & Evaluation Plan

**Hallucination mitigation**: Multi-source validation (Yahoo + Alpha Vantage), confidence scores (0-10) on all recommendations, mandatory stop-loss levels. **Bias mitigation**: Sector diversification, market-neutral approach, transparent deterministic algorithms. **Evaluation**: Track recommendation accuracy (predicted vs actual returns), risk score accuracy, weekly returns achievement rate, user retention metrics.

## Expected User/Business/Safety Impact

**User impact**: Democratizes institutional-grade analysis, targets 2% weekly returns for 50M+ Indian and 100M+ US retail investors. **Business impact**: Freemium model ($29/month premium), B2B licensing ($10K-$100K/year), $50B+ TAM. **Safety impact**: Risk scoring prevents high-risk trades, stop-loss enforcement limits downside, educational disclaimers ensure informed decisions. Regulatory compliance via "educational tool" positioning.

