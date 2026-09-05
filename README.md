# AIXBT plugin

Research live crypto narratives, projects, developments, attention context, audience clusters, and published reports with AIXBT.

The plugin bundles the read-only [MCP connector](https://docs.aixbt.tech/developers/mcp)
and [research skill](https://docs.aixbt.tech/developers/skill).

## Install

- [ChatGPT setup](https://docs.aixbt.tech/chatgpt)
- [Claude setup](https://docs.aixbt.tech/claude)
- [Grok Bot setup](https://docs.aixbt.tech/grok-bot)
- [Hermes Agent setup](https://docs.aixbt.tech/hermes)

### Claude Code

1. Run inside Claude Code:

   ```text
   /plugin marketplace add aixbt/aixbt-plugin
   /plugin install aixbt@aixbt
   ```

2. Start a new session and use /mcp to authenticate AIXBT when prompted.
3. Invoke /aixbt:research-crypto-market.

### Grok Build

1. Run in your terminal:

   ```sh
   grok plugin install aixbt/aixbt-plugin --trust
   ```

2. Start a new session and authenticate AIXBT from /mcps when prompted.

### Cursor marketplace

Import this repository through a [Cursor team marketplace](https://cursor.com/docs/plugins#add-a-team-marketplace).

The public listing requires [Cursor marketplace review](https://cursor.com/marketplace/publish).

## Test the plugin locally

Clone this repository and start Claude Code with the plugin directory:

```sh
claude --plugin-dir ./aixbt-plugin
```

Then ask a crypto research question or invoke `/aixbt:research-crypto-market` directly. From the repository root, validate the package and marketplace before contributing:

```sh
claude plugin validate .claude-plugin/plugin.json --strict
claude plugin validate .claude-plugin/marketplace.json --strict
```

## Boundaries

The connector provides market research only. It cannot trade, transfer assets, manage wallets, publish posts, or change external accounts. AIXBT output is not personalized financial advice.

## Links

- [Privacy policy](https://docs.aixbt.tech/legal/privacy-policy)
- [Terms and conditions](https://docs.aixbt.tech/legal/terms-and-conditions)
- Support: support@aixbt.tech
