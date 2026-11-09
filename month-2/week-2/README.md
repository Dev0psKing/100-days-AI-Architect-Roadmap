# 🛠️ Week 6 - Tool Calling and MCP

> **Days 38–44 · Systems · Progress:** 🟦🟦🟦🟦🟦🟦⬜

## 🎯 Mission

Give the assistant carefully bounded capabilities without allowing model output to become uncontrolled authority.

## ✅ Outcomes

You can define typed tools, validate arguments, distinguish data from instructions, require confirmation, and expose or consume MCP tools safely.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 38 | Function calling | Add one read-only tool. |
| 39 | Schemas | Validate required, optional, and enum fields. |
| 40 | Tool routing | Test retrieval versus tool decisions. |
| 41 | Permission model | Add allowlists and confirmation states. |
| 42 | MCP concepts | Run a local MCP server or inspect an example. |
| 43 | Abuse testing | Test prompt injection through tool output. |
| 44 | Integration review | Publish tool contracts and traces. |

## 📚 Learn

- Tool schemas and argument validation
- Tool selection and routing
- Read-only versus write actions
- Confirmation and human approval
- Timeouts, retries, idempotency, and auditability
- Model Context Protocol concepts and transports

## 🔗 Core resources

- [OpenAI - Function Calling](https://developers.openai.com/api/docs/guides/function-calling)
- [OpenAI - Tools Guide](https://developers.openai.com/api/docs/guides/tools)
- [Model Context Protocol - Introduction](https://modelcontextprotocol.io/introduction)
- [MCP - Official Documentation](https://modelcontextprotocol.io/docs)
- [MCP - Example Servers](https://github.com/modelcontextprotocol/servers)
- [Anthropic - Tool Use](https://docs.anthropic.com/en/docs/agents-and-tools/tool-use/overview)

## 🧪 Build lab: safe assistant tools

Implement `search_docs(query)`, `get_document(id)`, `summarize_document(id)`, `create_ticket(summary)`, and `calculate_cost(input)`. Treat tool output as untrusted data. Write tests for invalid arguments, denied actions, confirmation, timeout, and retry behavior.

## 📦 Deliverables

- Tool registry and JSON schemas
- Permission matrix
- Confirmation flow for writes
- Tool error contract
- Tool-choice evaluation cases
- MCP integration note

## 🚀 Stretch roadmap

- Add OAuth or scoped service credentials
- Add idempotency keys for writes
- Add approval expiry and cancellation
- Add tool latency and cost budgets

## 🏁 Definition of done

Every tool has a clear contract, limited permissions, observable execution, explicit failure behavior, and no destructive action without approval.

---

[← Previous: Week 1 - RAG Quality](../week-1/README.md) | [Next: Week 3 - Agent Workflows →](../week-3/README.md)
