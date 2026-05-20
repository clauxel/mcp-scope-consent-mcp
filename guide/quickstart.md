# Quickstart

MCP Scope Consent is a hosted remote MCP for MCP consent scope receipt.

## Fast Path

1. Open MCP Scope Consent and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://mcpscopeconsent.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_scope_consent with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://mcpscopeconsent.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=quickstart_home
- https://mcpscopeconsent.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=quickstart_pricing
- https://mcpscopeconsent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpscopeconsent_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://mcpscopeconsent.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
