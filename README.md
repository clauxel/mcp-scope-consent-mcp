# MCP Scope Consent

MCP Scope Consent is a hosted remote MCP for MCP consent scope receipt.

This repository is a public documentation project for MCP Scope Consent. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://mcpscopeconsent.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=readme_home
- Pricing: https://mcpscopeconsent.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=readme_pricing
- Checkout: https://mcpscopeconsent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://mcpscopeconsent.clauxel.com/mcp
- Server card: https://mcpscopeconsent.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpscopeconsent/mcpscopeconsent-mcp`
- Tools: `check_scope_consent`, `issue_consent_receipt`, `explain_scope_policy`, `log_tool_call`, `export_scope_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI governance teams, policy reviewers, trust and safety leads, and compliance operators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_scope_consent
- MCP tool: issue_consent_receipt
- MCP tool: explain_scope_policy
- MCP tool: log_tool_call
- MCP tool: export_scope_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
