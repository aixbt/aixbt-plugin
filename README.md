# AIXBT plugin

Research live crypto narratives, projects, developments, attention context, audience clusters, and published reports with AIXBT.

The plugin bundles:

- the read-only AIXBT remote MCP connector at `https://api.aixbt.tech/mcp`
- a research skill for concise crypto market analysis
- shared AIXBT brand assets and metadata

## Use the connector

Add `https://api.aixbt.tech/mcp` as a custom remote connector in Claude. Public topic discovery works without an account. When a protected tool is needed, Claude will prompt you to authenticate with AIXBT through OAuth.

## Test the plugin locally

Clone this repository and start Claude Code with the plugin directory:

```sh
claude --plugin-dir ./aixbt-plugin
```

Then ask a crypto research question or invoke `/aixbt:research-crypto-market` directly. Validate the package before contributing:

```sh
claude plugin validate . --strict
```

## Boundaries

The connector provides market research only. It cannot trade, transfer assets, manage wallets, publish posts, or change external accounts. AIXBT output is not personalized financial advice.

## Links

- [MCP documentation](https://docs.aixbt.tech/developers/mcp)
- [Research skill](https://docs.aixbt.tech/developers/skill)
- [Privacy policy](https://docs.aixbt.tech/legal/privacy-policy)
- [Terms and conditions](https://docs.aixbt.tech/legal/terms-and-conditions)
- Support: support@aixbt.tech
