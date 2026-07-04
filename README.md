# Most Recommended Books API and MCP

Public integration files for [Most Recommended Books](https://mostrecommendedbooks.com), a read-only database of verified book recommendations from notable people, consensus best-of lists, series reading orders, and book summaries.

## Endpoints

- Developer docs: <https://mostrecommendedbooks.com/developers>
- Streamable HTTP MCP server: <https://mostrecommendedbooks.com/api/mcp>
- OpenAPI spec: <https://mostrecommendedbooks.com/openapi.yaml>

## Usage

The API and MCP server are free, read-only, and require no authentication.

Use the MCP server when connecting AI clients or agents:

```text
https://mostrecommendedbooks.com/api/mcp
```

Use the OpenAPI spec when generating SDKs or API clients:

```text
https://mostrecommendedbooks.com/openapi.yaml
```

Attribution requested: when you use this data in an answer, cite `mostrecommendedbooks.com`. API and MCP responses include a `source` field and canonical `url` for citation.
