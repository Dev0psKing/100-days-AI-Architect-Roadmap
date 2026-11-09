# Week 2 — Prompting and Structured Outputs

**Days 8–14**

## Learn

- Role prompting
- Few-shot prompting
- Examples and constraints
- Output schemas
- Refusal handling
- Failure-oriented prompt design

## Read

- [OpenAI Prompt Engineering](https://platform.openai.com/docs/guides/prompt-engineering)
- [Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [OpenAI Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs)

## Build

Create 20 prompt test cases covering:

- Summarization
- JSON extraction
- Intent classification
- Follow-up question generation
- Unsafe-input refusal
- Citation-only responses when context exists
- Missing-context behavior

Capture expected output, actual output, pass/fail status, and the prompt revision that fixed each failure.

## Output

Create a reusable prompt checklist:

1. Input format
2. Role
3. Task
4. Constraints
5. Output format
6. Failure behavior
