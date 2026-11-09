# Week 3 — Agent Workflows

**Days 45–51**

## Learn

- Routing
- State
- Planning
- Retries
- Human approval
- Failure handling

## Read

- [LangGraph Overview](https://docs.langchain.com/oss/python/langgraph/overview)
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)

## Build

Create a LangGraph flow:

1. Receive the user query.
2. Classify intent.
3. Decide whether data is needed.
4. Retrieve context or reason directly.
5. Generate an answer.
6. Check answer quality.
7. Retry retrieval when quality is insufficient.
8. Return a final answer or request human approval.

Add explicit state fields for the question, route, retrieved context, answer, quality result, retry count, and citations.

## Output

A real multi-step assistant, not a single prompt wrapper. Document its nodes, transitions, retry limit, and failure paths.

---

[← Previous: Week 2 — Tool Calling and MCP](../week-2/README.md) | [Next: Week 4 — Evals and Reliability →](../week-4/README.md)
