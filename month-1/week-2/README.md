# ✍️ Week 2 - Prompting and Structured Outputs

> **Days 8–14 · Foundations · Progress:** 🟦🟦⬜⬜⬜⬜⬜

## 🎯 Mission

Design prompts as testable interfaces: explicit inputs, constrained behavior, predictable outputs, and safe failure modes.

## ✅ Outcomes

You can write reusable prompts, select examples, validate structured responses, and handle refusals or missing context without hiding failures.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 8 | Prompt anatomy | Rewrite one vague prompt into a specification. |
| 9 | Roles and context | Test instruction hierarchy and context placement. |
| 10 | Few-shot examples | Build examples for three edge cases. |
| 11 | Structured output | Define and validate a JSON schema. |
| 12 | Refusals and uncertainty | Add safe responses for unsafe or unsupported input. |
| 13 | Prompt test suite | Create 20 cases with expected outcomes. |
| 14 | Review and versioning | Publish a prompt checklist and changelog. |

## 📚 Learn

- Role prompting and instruction hierarchy
- Few-shot examples and counterexamples
- Delimiters, context boundaries, and injection resistance
- JSON Schema and structured outputs
- Refusal, abstention, and clarification behavior
- Prompt versioning and regression testing

## 🔗 Core resources

- [OpenAI - Prompt Engineering](https://platform.openai.com/docs/guides/prompt-engineering)
- [OpenAI - Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs)
- [Anthropic - Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [Google - Prompt Design](https://ai.google.dev/gemini-api/docs/prompting-strategies)
- [Microsoft - Prompt Engineering Techniques](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering)
- [JSON Schema](https://json-schema.org/learn/getting-started-step-by-step)

## 🧪 Build lab: prompt test harness

Create 20 cases covering summarization, extraction, classification, follow-up questions, unsafe input, missing context, malformed input, long input, and citation requirements. Store input, expected output shape, actual output, pass/fail, and prompt version.

## 📦 Deliverables

- `prompts/` with versioned templates
- `tests/prompt_cases.json`
- JSON schemas and validation code
- A reusable prompt checklist
- A failure log with at least five prompt revisions

## 🚀 Stretch roadmap

- [Promptfoo](https://www.promptfoo.dev/docs/intro/)
- [DSPy](https://dspy.ai/)
- [OpenAI Cookbook](https://cookbook.openai.com/)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)

## 🏁 Definition of done

A new prompt can be reviewed like code: its contract, examples, schema, failure behavior, and regression cases are all explicit.

---

[← Previous: Week 1 - LLM Mental Model](../week-1/README.md) | [Next: Week 3 - Embeddings and Semantic Search →](../week-3/README.md)
