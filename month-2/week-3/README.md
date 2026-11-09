# 🤖 Week 7 - Agent Workflows

> **Days 45–51 · Systems · Progress:** 🟦🟦🟦🟦🟦🟦🟦

## 🎯 Mission

Design a predictable stateful workflow instead of wrapping one prompt in an “agent” label.

## ✅ Outcomes

You can model state, route work, limit retries, add human approval, and explain every transition in the workflow.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 45 | Workflow design | Draw nodes, edges, state, and failure paths. |
| 46 | Intent routing | Implement data, action, and direct-answer routes. |
| 47 | Retrieval loop | Add retrieval, generation, and quality checks. |
| 48 | State and memory | Define typed state and bounded history. |
| 49 | Retries and recovery | Add retry limits and fallback behavior. |
| 50 | Human approval | Pause before risky actions. |
| 51 | Trace review | Inspect runs and document tradeoffs. |

## 📚 Learn

- Deterministic routing and state machines
- Stateful graph execution
- Planning versus execution
- Retry budgets and recovery
- Human-in-the-loop workflows
- Long-running jobs and resumability

## 🔗 Core resources

- [LangGraph - Overview](https://docs.langchain.com/oss/python/langgraph/overview)
- [LangGraph - Workflows and Agents](https://docs.langchain.com/oss/python/langgraph/workflows-agents)
- [Hugging Face - Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)
- [Microsoft - AutoGen](https://microsoft.github.io/autogen/stable/)
- [Temporal - Durable Execution](https://docs.temporal.io/)
- [OpenAI - Agents SDK](https://openai.github.io/openai-agents-python/)

## 🧪 Build lab: quality-gated LangGraph flow

Implement: query → classify intent → retrieve or reason → generate → check quality → retry or finalize. Track question, route, context, answer, quality result, retry count, tool calls, citations, and approval state.

## 📦 Deliverables

- Workflow diagram
- Typed state model
- Node and transition implementation
- Retry and fallback policy
- Human approval example
- Trace screenshots or exported run records

## 🚀 Stretch roadmap

- Add parallel retrieval branches
- Add resumable long-running execution
- Add queue-backed background jobs
- Compare graph workflow with a simple router

## 🏁 Definition of done

For any run, you can explain what happened, why each route was selected, where it failed, and how the workflow stopped safely.

---

[← Previous: Week 2 - Tool Calling and MCP](../week-2/README.md) | [Next: Week 4 - Evals and Reliability →](../week-4/README.md)
