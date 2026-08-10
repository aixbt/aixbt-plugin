---
name: research-crypto-market
description: Research live crypto narratives, projects, market attention, evidence-graded developments, and AIXBT reports. Use when the user asks what is trending, why a project is gaining attention, how narratives compare, or wants evidence-backed crypto market research.
compatibility: Requires the bundled AIXBT remote MCP connector and network access. Protected intelligence requires AIXBT authentication.
metadata:
  author: AIXBT
  version: '0.1.0'
---

# Research crypto markets with AIXBT

Use the AIXBT connector as the source of current market intelligence. Discover the available AIXBT tools at runtime instead of assuming a fixed inventory.

## Workflow

1. Clarify the asset, narrative, comparison set, and time horizon from the request. If the request is broad, begin with the current topic landscape.
2. Select the narrowest AIXBT tools that answer the question. Start with topic discovery for market-wide orientation, then use project, development, attention-history, audience, or report data when the question needs it and those tools are available.
3. If a protected tool requests authentication, explain that deeper AIXBT intelligence requires connecting an AIXBT account, let the user complete OAuth, and retry the request. Do not ask the user to paste credentials into the conversation.
4. Prefer the freshest relevant observations. Preserve source timestamps, links, evidence grades, and uncertainty from the tool results.
5. Separate reported evidence from inference. Treat attention and momentum as research signals, not as proof of price direction or a prediction.
6. Cross-check material conclusions with more than one relevant observation when the connector provides enough evidence. Say when coverage is sparse, stale, conflicting, or unavailable.

## Response shape

Lead with the answer or thesis, then provide the strongest supporting evidence, important counterevidence or caveats, and what to monitor next. Include source links and timestamps returned by AIXBT when available. Keep the level of detail proportional to the request.

## Safety boundary

AIXBT is a read-only research connector. Never claim to trade, transfer assets, manage wallets, publish posts, or mutate an external account. Do not turn missing data into invented facts or present research output as personalized financial advice.
