# Week 3 — Observability and Cost Tracking

**Days 75–81**

## Learn

- Traces
- Logs
- Metrics
- Token usage
- Latency
- Cost per request
- Failure reasons

## Read

- [LangSmith Observability](https://docs.langchain.com/langsmith/observability)
- [OpenTelemetry Documentation](https://opentelemetry.io/docs/)

## Build

Track:

- Prompt tokens
- Completion tokens
- Total cost
- Tool calls
- Retrieval latency
- Model latency
- Failed requests
- Evaluation score per response

Use correlation IDs so one request can be followed across retrieval, model calls, tools, evaluation, and the final response. Redact secrets and sensitive document content from logs.

## Output

A dashboard or log view that explains what happened inside the AI system and how much each request cost.

---

[← Previous: Week 2 — Docker and CI/CD](../week-2/README.md) | [Next: Week 4 — Security and Guardrails →](../week-4/README.md)
