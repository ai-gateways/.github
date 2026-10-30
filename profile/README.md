# AI Gateways

An AI gateway is the layer between applications and the models, tools, and agents they call. It handles routing, failover, authentication, budgets, guardrails, and logging in one place, so each application does not have to rebuild them.

This organization publishes vendor-neutral guides to AI gateways and the controls they enforce. Each guide explains how the technology works, how to evaluate it, and which open-source projects implement it.

## Start here

[**AI gateway**](https://github.com/ai-gateways/ai-gateway): what an AI gateway is, the three kinds of AI traffic it governs, and how to evaluate one.

## Guides by traffic type

| Guide | What it covers |
|---|---|
| [LLM gateway](https://github.com/ai-gateways/llm-gateway) | One API across model providers: routing, fallbacks, caching, budgets, and how an LLM gateway differs from an API gateway |
| [MCP gateway](https://github.com/ai-gateways/mcp-gateway) | Authentication, tool filtering, credential brokering, and audit logs for [Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/architecture#core-components) tool calls |
| [Agent gateway](https://github.com/ai-gateways/agent-gateway) | Discovery, access control, and tracing for [agent-to-agent (A2A)](https://a2a-protocol.org/latest/specification/#11-key-goals-of-a2a) traffic |

## Guides by capability

| Guide | What it covers |
|---|---|
| [AI governance](https://github.com/ai-gateways/ai-governance) | Identity, scoped keys, budgets, audit logs, shadow AI, and mapping to the NIST AI RMF and the EU AI Act |
| [AI guardrails](https://github.com/ai-gateways/ai-guardrails) | Input and output checks for prompt injection, personal data, secrets, and unsafe content, including streaming responses |
| [LLM observability](https://github.com/ai-gateways/llm-observability) | What to capture, OpenTelemetry GenAI conventions, gateway vs SDK capture, cost attribution, and keeping prompts private |

## Curated list

[**Awesome AI Gateways**](https://github.com/ai-gateways/awesome-ai-gateways): open-source and commercial LLM, MCP, and agent gateways, plus model routers, inference gateways, and the specifications they implement.

## How the guides are written

- **Vendor-neutral.** Projects are compared on facts each one publishes in its own repository or documentation.
- **Sourced to the section.** Every spec, standard, and article is linked to the exact section or passage that supports the claim.
- **Kept current.** Each comparison table states the month it reflects; open an issue when a project changes.

## Contributing

Issues and pull requests are welcome in every repository. To propose a new guide or report an outdated fact, [open an issue in `.github`](https://github.com/ai-gateways/.github/issues/new).
