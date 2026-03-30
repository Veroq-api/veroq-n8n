# n8n-nodes-veroq

[![npm](https://img.shields.io/npm/v/n8n-nodes-veroq?color=2EE89A&label=npm)](https://www.npmjs.com/package/n8n-nodes-veroq)
[![Downloads](https://img.shields.io/npm/dm/n8n-nodes-veroq?color=2EE89A)](https://www.npmjs.com/package/n8n-nodes-veroq)
[![License](https://img.shields.io/badge/license-MIT-2EE89A)](LICENSE)

n8n community node for the [VEROQ Intelligence API](https://veroq.co).

Verified, bias-scored financial intelligence for AI agents and automation workflows.

## Installation

In your n8n instance, go to **Settings > Community Nodes > Install** and enter:

```
n8n-nodes-veroq
```

## Credentials

Add a **VEROQ API** credential with your API key. Both VEROQ and Polaris API keys are accepted.

Get a free key at [veroq.co/dashboard](https://veroq.co/dashboard).

## Quick Start

The two most useful operations:

1. **Ask > Ask** -- ask any question about markets, companies, or economics in plain English
2. **Ask > Verify** -- fact-check a claim against the intelligence corpus

These handle most use cases. The other resources give you granular access when you need it.

## Operations

| Resource | Operation | Description |
|----------|-----------|-------------|
| **Ask** | **Ask** | **Ask any question about markets, companies, or economics** |
| **Ask** | **Verify** | **Fact-check a claim against the intelligence corpus** |
| Briefs | Get Feed | Get latest published intelligence briefs |
| Briefs | Get Brief | Get a single brief by ID |
| Briefs | Get Timeline | Get story evolution for a living brief |
| Search | Search | Full-text search across all briefs |
| Search | Suggest | Autocomplete suggestions |
| Search | Web Search | Web search with VEROQ trust scoring |
| Intelligence | Verify | Fact-check a claim against the corpus |
| Intelligence | Forecast | Structured predictions for any topic |
| Intelligence | Context | Background intelligence on a topic |
| Market Data | Candles | OHLCV candlestick data |
| Market Data | Technicals | Technical analysis indicators |
| Market Data | Earnings | Earnings data for a ticker |
| Market Data | Market Movers | Top gainers, losers, most active |
| Market Data | Market Summary | Overall market summary and indices |
| Market Data | Forex | Foreign exchange rates |
| Market Data | Commodities | Commodity prices |
| Market Data | Economy | Economic indicators (GDP, CPI, etc.) |
| Market Data | IPO Calendar | Upcoming IPOs |
| Crypto | Get Crypto | Cryptocurrency data |
| Crypto | Top Cryptos | Top cryptocurrencies by market cap |
| Crypto | Chart | Price chart data |
| Crypto | DeFi Protocol | DeFi protocol data |
| Social | Sentiment | Social media sentiment for a ticker |
| Social | Trending | Trending tickers on social media |
| Ticker | Analysis | Full analysis for a ticker |
| Ticker | News | Recent news for a ticker |
| Reports | Generate | Generate a report (Quick/Full/Deep) |
| Reports | Get Report | Retrieve a report by ID |
| Web | Crawl | Extract structured content from URLs |
| Web | Extract | Extract article content from URLs |

## Links

- [API Documentation](https://veroq.co/docs)
- [Get API Key](https://veroq.co/dashboard)
- [GitHub](https://github.com/Polaris-API/polaris-sdks)
