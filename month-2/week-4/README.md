# 📊 Week 8 - Evals and Reliability

> **Days 52–60 · Systems · Progress:** 🟦🟦🟦🟦🟦🟦🟦🟦

## 🎯 Mission

Make quality measurable so prompt, model, retrieval, and workflow changes can be tested instead of guessed.

## ✅ Outcomes

You can create evaluation cases, choose metrics, separate deterministic tests from judge-based tests, and block regressions in CI.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 52 | Eval design | Define capabilities, risks, and pass criteria. |
| 53 | Dataset curation | Expand the golden set with edge cases. |
| 54 | Retrieval metrics | Run retrieval and citation checks. |
| 55 | Generation metrics | Test groundedness and answer relevance. |
| 56 | Tool and safety tests | Test routing, refusal, and permissions. |
| 57 | Latency and cost | Capture p50, p95, tokens, and cost. |
| 58 | Judge calibration | Compare judge output with human review. |
| 59 | Regression gate | Fail a run below minimum thresholds. |
| 60 | Reliability review | Publish the baseline and roadmap. |

## 📚 Learn

- Golden datasets and test case design
- Retrieval correctness and citation quality
- Groundedness, relevance, and completeness
- LLM-as-judge limitations and calibration
- Latency, token, and cost budgets
- Regression testing and release gates

## 🔗 Core resources

- [OpenAI - Evals](https://platform.openai.com/docs/guides/evals)
- [LangSmith - Evaluation](https://docs.langchain.com/langsmith/evaluation)
- [DeepEval - Getting Started](https://deepeval.com/docs/getting-started)
- [Ragas - Metrics](https://docs.ragas.io/en/stable/concepts/metrics/)
- [MLflow - LLM Evaluation](https://mlflow.org/docs/latest/llms/llm-evaluate/)
- [Promptfoo - Red Teaming](https://www.promptfoo.dev/docs/red-team/)

## 🧪 Build lab: evaluation suite

Automate retrieval correctness, groundedness, citation quality, tool selection, refusal behavior, latency, and token cost. Store every run with commit SHA, model, prompt version, dataset version, and scores.

## 📦 Deliverables

- Evaluation dataset and schema
- Metric definitions and thresholds
- Human-reviewed calibration sample
- Regression report
- CI evaluation command
- Day 60 system review

## 🚀 Stretch roadmap

- Add pairwise model comparisons
- Add adversarial and multilingual cases
- Add statistical confidence intervals
- Add production feedback sampling

## 🏁 Definition of done

A release can be accepted or rejected using documented quality, safety, latency, and cost thresholds.

---

[← Previous: Week 3 - Agent Workflows](../week-3/README.md) | [Next: Month 3, Week 1 - Backend and API →](../../month-3/week-1/README.md)
