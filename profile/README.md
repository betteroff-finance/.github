# BetterOff

**BetterOff is a financial platform for tracking, investing, and trading money across banks, brokerages, wallets, and exchanges.**

See where you stand, check the records behind each number, and act from the same record. Your banks, brokerages, exchanges, and wallets sit in one view, and your property, vehicles, private assets, and debts sit next to them.

BetterOff watches your accounts through read-only connections. Those connections cannot touch them.

[**Open BetterOff**](https://betteroff.finance) · [For AI agents](https://betteroff.finance/agents) · [Developers](https://betteroff.finance/developers)

## Use BetterOff from your terminal or your AI client

Two open source projects live here. Both read your BetterOff household, and both ask you to sign in with BetterOff first.

| Project | What it is | Start here |
| --- | --- | --- |
| [**betteroff.cli**](https://github.com/betteroff-finance/betteroff.cli) | Read accounts, net worth, and spending from the terminal. It is read-only and prints JSON for scripts. | `brew install raintree-technology/tap/betteroff` |
| [**betteroff.connectors**](https://github.com/betteroff-finance/betteroff.connectors) | A plugin and MCP connector for AI clients, with 11 skills such as a monthly review, a debt payoff plan, and upcoming bills. | `claude plugin marketplace add betteroff-finance/betteroff.connectors` |

### CLI

```sh
brew install raintree-technology/tap/betteroff
betteroff accounts
```

The CLI runs on macOS and Linux. Releases carry SHA-256 checksums and build provenance, and the install script checks each binary against them.

### Connectors

```sh
claude plugin marketplace add betteroff-finance/betteroff.connectors
claude plugin install betteroff@betteroff
```

Then start a new session and sign in to BetterOff. The repository has setup guides for Codex, Claude Code, GitHub Copilot, Cursor, Gemini CLI, Devin, Hermes Agent, and more. For any other MCP client, add `https://api.betteroff.finance/mcp` as a remote server with OAuth sign-in.

The connector prepares corrections for your review. It cannot apply a correction, approve a request, or execute one. Every household member has to turn on Chat data access in BetterOff settings before an agent can read household data.

## Find BetterOff

| | |
| --- | --- |
| Website | [betteroff.finance](https://betteroff.finance) |
| App | [app.betteroff.finance](https://app.betteroff.finance) |
| AI agents and plugins | [betteroff.finance/agents](https://betteroff.finance/agents) |
| Developer docs | [betteroff.finance/developers](https://betteroff.finance/developers) |
| X | [@betteroff_app](https://x.com/betteroff_app) |
| LinkedIn | [company/betteroff.finance](https://www.linkedin.com/company/betteroff.finance) |
| Instagram | [@betteroff.finance](https://www.instagram.com/betteroff.finance) |
| Facebook | [BetterOffFinance](https://www.facebook.com/BetterOffFinance) |
| Email | [hello@betteroff.finance](mailto:hello@betteroff.finance) |

## Security and contributions

Report a vulnerability through the `SECURITY.md` in the affected repository, and please do not open a public issue for it. For anything else, open an issue in the repository it concerns. Each project's `CONTRIBUTING.md` explains how to propose a change.

Both projects are MIT licensed.

BetterOff is operated by FinSync LLC, operating as Raintree Technology.
