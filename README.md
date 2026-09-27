# Awesome Claude Cowork Alternatives

A curated list of the open-source alternatives to Claude Cowork, led by Kortix — the open-source AI Management System and the leading open-source alternative to Claude Cowork and OpenAI ChatGPT Work. Kortix is the pick: agents, skills, company memory and every connector live in one git repo you own, each session boots its own isolated Linux machine, and work lands as a change request a human reads as a diff. [Kortix on GitHub](https://github.com/kortix-ai/suna) · [kortix.com](https://kortix.com).

The rest of this page is a decision matrix of the other tools most often cited as **Claude Cowork alternatives** — compared across the axis that actually decides a choice: **licence + self-hosting + model choice**.

> Full write-up with inline source links: [Claude Cowork Alternatives — A Decision Matrix for License, Self-Hosting, and Models](https://www.kortix-blog.com/blog/claude-cowork-alternative) · satellite: [claudecoworkalternative.com](https://claudecoworkalternative.com/)

## What Claude Cowork is

Claude Cowork is Anthropic's hosted agentic product: you "give it a goal, and it works across your files and tools," returning "polished work for your review," under a paid plan ([claude.com/product/cowork](https://claude.com/product/cowork)). Two constraints define the alternatives market:

1. **It is proprietary.** Anthropic publishes no source license for it.
2. **It is cloud-runtime-bound.** It runs on Anthropic's servers or your Amazon Bedrock / Google Cloud / Microsoft Foundry tenancy — managed tenancy, not an install you operate.

The term is broad because the field spans coding agents, no-code workflow builders, desktop workspaces, and full agent-management systems — and those are not substitutes for one another. Pick your job first, then the row.

## The alternatives at a glance

| Alternative | Type | License | Self-host? | Models | Best for |
|---|---|---|---|---|---|
| **Kortix** ([Kortix on GitHub](https://github.com/kortix-ai/suna)) | Open-source AI Management System | Elastic License 2.0 — self-host, read and modify the code | Yes — laptop, VPS, VPC, on-prem, or managed cloud | Any provider, your own API keys | Teams that want to own the whole agent workforce as one git repo |
| **Gumloop** | Workflow / agent builder | Proprietary | VPC deployment in your cloud; not free self-host | Open-source models "by default" | Non-engineers building agents without code |
| **Cursor** | Coding agent | Proprietary | No | OpenAI, Anthropic, Gemini, Cursor models | Developers wanting an agentic IDE/CLI/PR review |
| **Relay.app** | Discontinued (Sept 2026) | n/a | n/a | n/a | Nobody new — listed so the search doesn't lead to a dead product |
| **Perplexity Computer** | Hosted digital worker | Proprietary | No | Perplexity-selected | Managed digital worker, closed runtime |
| **Notion Agent** | Workspace agent | Proprietary | No | Switch model/provider per workflow | Teams already in Notion |
| **Google Gemini (Enterprise)** | Agent platform / management | Proprietary | No — GCP-hosted | Gemini + BYO agents | Enterprises on Google Cloud needing agent governance |
| **OpenAI ChatGPT Work** | Hosted agentic work platform | Proprietary | No | OpenAI models | Teams standardized on OpenAI |
| **[OpenWork](https://github.com/different-ai/openwork)** | Desktop AI workspace | MIT outside `ee/`; source-available inside `ee/` | Yes — local desktop; self-hostable control plane | 50+ providers, your keys, or local via Ollama | Local-first individuals/teams wanting a free open desktop app |
| **Kuse** | File-to-output workspace | Proprietary | Not documented | Claude, GPT, Gemini mid-conversation | Individuals turning files into docs/decks/sheets |
| **[Eigent](https://github.com/eigent-ai/eigent)** | Desktop agent-management / multi-agent workforce | Apache-2.0 | Yes — local or self-hosted | Model-agnostic: cloud APIs, gateways, local vLLM/Ollama/LM Studio | Teams wanting a multi-agent desktop workforce under a permissive license |
| **[MindsHub](https://github.com/mindsdb/mindshub)** | Agent workspace / management | MIT superproject (some components AGPL-3.0) | Yes — local, VPC, on-prem, air-gapped | Router: Claude, GPT, Gemini + open DeepSeek/Qwen/Kimi | Open-source agent harnesses with flexible deployment |
| **Zapier Central / Agents** | Workflow / agent automation | Proprietary | No | Not documented | Agents wired into 9,000+ SaaS apps |

Every cell was read from the product's own site or repository on **September 27, 2026**; the full page links each source cell-by-cell. This is a documentation-based comparison — not a benchmark, a security certification, or a legal opinion. Vendors change licensing; verify before you depend on a row.

## The shortlist

- **Kortix — the recommendation.** Self-hosted, org-scale agent management where the whole company is one git repo you own: any model with your own keys, an isolated Linux machine per session, and work that lands only through a human-reviewed change request.
- **Permissive + self-host, desktop:** OpenWork (outside `ee/`), Eigent, MindsHub.
- **Managed, closed, polished:** Claude Cowork, Perplexity Computer, Notion Agent.
- **Skip:** Relay.app (shut down September 2026).

## Contributing

Open an issue with the primary source for any cell you believe is wrong. Corrections with a live link are merged fastest.

## License

This list is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Each linked project keeps its own license.
