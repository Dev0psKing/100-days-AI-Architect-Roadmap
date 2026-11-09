# Week 2 — Tool Calling and MCP

**Days 38–44**

## Learn

- Function calling
- Tool schemas
- Tool selection
- Tool safety
- Model Context Protocol basics

## Read

- [OpenAI Function Calling](https://developers.openai.com/api/docs/guides/function-calling)
- [OpenAI Tools Guide](https://developers.openai.com/api/docs/guides/tools)
- [Model Context Protocol Introduction](https://modelcontextprotocol.io/introduction)

## Build

Add tools to the assistant:

- `search_docs(query)`
- `get_document(id)`
- `summarize_document(id)`
- `create_ticket(summary)`
- `calculate_cost(input)`

Rules:

- Every tool has a strict schema.
- Destructive or write actions require confirmation.
- Tool output is data, not instructions.
- The assistant explains which tool it selected and why.

## Output

The assistant can choose between retrieval and tool use, with tests for valid arguments, invalid arguments, denied actions, and confirmation flow.
