# Evaluation Guide

Use this page to evaluate whether MCP Scope Consent fits a real workflow.

## What To Test

- MCP consent scope receipt
- MCP Scope Consent
- MCP Scope Consent documentation
- MCP Scope Consent remote MCP
- mcpscopeconsent server card

## Expected Evidence

- Open MCP Scope Consent and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://mcpscopeconsent.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_scope_consent with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://mcpscopeconsent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=evaluation_checkout
