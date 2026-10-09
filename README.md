## Hi, I'm Denys

I build low-latency trading bots, automation and data pipelines on Solana, EVM chains and prediction markets.

My live trading code stays private. What is public here: tools that run on their own, data collectors, and honest write-ups of strategies I stopped.

### What I build

- **Trading bots and execution.** Event-driven bots on Solana and EVM L2s, built around latency: streaming feeds, transaction landing, reconnects that do not get you rate-limited or banned. My Robinhood Chain bot goes from decision to a signed, sent transaction in about 0.18 ms (measured inside the bot on a small cloud server; the code is private).
- **Data pipelines.** On-chain event decoders, order-book and price collectors, wallet analytics, alerts.
- **Automation.** Telegram bots, e-mail and LLM pipelines, monitoring.

### Start here

- [prediction-market-postmortems](https://github.com/Dennim89/prediction-market-postmortems): three prediction-market strategies that did not survive their audits, with a tested Polymarket data collector and evaluation harnesses.
- [polymarket-wallet-analyzer](https://github.com/Dennim89/polymarket-wallet-analyzer): Go library and CLI that checks whether a Polymarket wallet beats the prices it paid, trades like a bot or farms near-certain outcomes.
- [upwork-alert-triage](https://github.com/Dennim89/upwork-alert-triage): reads Upwork job-alert e-mails, scores the jobs and sends Telegram cards with a draft. You press Send yourself.
- [hyperliquid-copytrade-study](https://github.com/Dennim89/hyperliquid-copytrade-study): a pre-registered test of whether Hyperliquid leaderboard winners stay winners. They did not.
- [agent-trust-gate](https://github.com/Dennim89/agent-trust-gate): a permission check for AI-agent tool calls that does not ask the model.

### Rules I keep

- A claim in a README comes with a command that checks it, or it says "not verified".
- Every number says where it comes from: a test in the repo, a published result file, or notes written at the time.
- No profit screenshots. No "passive income".

### Work with me

[Upwork profile](https://www.upwork.com/freelancers/~01f7a3cf84e792f019). Built with AI coding agents (Claude, Codex).
