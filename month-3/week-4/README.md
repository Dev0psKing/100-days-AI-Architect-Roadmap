# 🔐 Week 12 - Security and Guardrails

> **Days 82–100 · Production · Progress:** 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦

## 🎯 Mission

Reduce the blast radius of model mistakes, malicious inputs, unsafe tools, data leakage, and operational failures before launch.

## ✅ Outcomes

You can threat-model an AI application, test prompt injection, restrict tools, protect secrets, rate-limit access, and document residual risk.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 82 | Threat model | Map assets, actors, trust boundaries, and abuse cases. |
| 83 | Prompt injection | Build direct and indirect injection tests. |
| 84 | Tool safety | Add allowlists, validation, confirmation, and audit logs. |
| 85 | Data protection | Add redaction, isolation, and access checks. |
| 86 | Abuse controls | Add rate limits, budgets, and safe fallbacks. |
| 87 | Release hardening | Run security and regression suites. |
| 88 | Deployment verification | Test health, rollback, secrets, and monitoring. |
| 89 | Case study draft | Write architecture, tradeoffs, failures, and limits. |
| 90 | Integration review | Run the complete application and evaluation flow. |
| 91 | Documentation polish | Finalize setup instructions and troubleshooting guidance. |
| 92 | Accessibility review | Check headings, links, diagrams, and learner clarity. |
| 93 | Performance review | Record latency, cost, and quality baselines. |
| 94 | Security review | Resolve release-blocking security findings. |
| 95 | Demo preparation | Prepare the live walkthrough and supporting examples. |
| 96 | Architecture presentation | Finalize the architecture diagram and design decisions. |
| 97 | Evaluation report | Publish final metrics, limitations, and known failures. |
| 98 | Case study finalization | Complete the lessons learned and next-version roadmap. |
| 99 | Release rehearsal | Verify deployment, monitoring, rollback, and links. |
| 100 | Launch | Publish the demo, report, and next roadmap. |

## 📚 Learn

- Prompt injection and indirect prompt injection
- Sensitive data disclosure and insecure output handling
- Excessive agency and tool abuse
- Authentication, authorization, and tenant isolation
- Rate limiting, quotas, and budget controls
- Auditability, incident response, and residual risk

## 🔗 Core resources

- [OWASP - Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)
- [OWASP - GenAI Security Project](https://genai.owasp.org/)
- [OpenAI - Safety Best Practices](https://platform.openai.com/docs/guides/safety-best-practices)
- [Microsoft - AI Red Teaming](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-team)
- [Google - Secure AI Framework](https://saif.google/)
- [NIST - AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [PyRIT - AI Red Teaming](https://github.com/Azure/PyRIT)
- [Garak - LLM Vulnerability Scanner](https://github.com/NVIDIA/garak)

## 🧪 Build lab: security and launch gate

Add a prompt-injection test set, tool allowlist, confirmation before writes, context isolation, secret redaction, safe fallback, rate limiting, and audit logs. Run the full evaluation and deployment checks before launch.

## 📦 Deliverables

- Threat model and trust-boundary diagram
- Security test suite and results
- Tool permission matrix
- Redaction and rate-limit tests
- Incident and rollback notes
- Live demo, architecture diagram, evaluation report, case study, limitations, and next-version roadmap

## 🚀 Stretch roadmap

- Add adversarial testing to CI
- Add tenant-level authorization and data filters
- Add human review queues for sensitive actions
- Perform an external security review

## 🏁 Definition of done

The application has explicit defenses, measurable security tests, documented limitations, and a launch decision supported by evidence rather than optimism.

---

[← Previous: Week 3 - Observability and Cost Tracking](../week-3/README.md) | [Capstone: Production AI Assistant →](../../capstone/README.md)
