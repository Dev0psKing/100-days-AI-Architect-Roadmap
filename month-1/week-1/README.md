# 🧠 Week 1 - LLM Mental Model

> **Days 1-7 · Foundations · Progress:** 🟦⬜⬜⬜⬜⬜⬜

## 🎯 Mission

Understand what an LLM does, what it cannot do, and how model settings change behavior before building application logic around it.

## ✅ Outcomes

By the end of this week you can explain tokens, context windows, next-token prediction, temperature, sampling, system prompts, hallucinations, and model limits in practical engineering language.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 1 | Tokens and tokenization | Tokenize ten prompts and compare token counts. |
| 2 | Next-token prediction | Write a plain-language explanation and test completions. |
| 3 | Context windows | Compare short, medium, and overflowing contexts. |
| 4 | Sampling | Run temperature and top-p experiments. |
| 5 | Instructions and roles | Compare system, developer, and user instructions. |
| 6 | Limits and hallucinations | Create questions the model cannot answer reliably. |
| 7 | Synthesis | Publish your experiment notes and engineering rules. |

## 📚 Learn

- Tokens, token IDs, token budgets, and cost
- Context limits and lost-in-the-middle behavior
- Probabilistic generation and sampling
- Temperature, top-p, and deterministic testing
- System prompts and instruction hierarchy
- Knowledge cutoff, uncertainty, and hallucination patterns

## 🔗 Core resources

- [DeepLearning.AI - How Transformer LLMs Work](https://www.deeplearning.ai/short-courses/how-transformer-llms-work/)
- [Andrej Karpathy - Deep Dive into LLMs](https://www.youtube.com/watch?v=7xTGNNLPyMI)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/en/chapter1/1)
- [OpenAI - Key Concepts](https://platform.openai.com/docs/concepts)
- [Anthropic - Models Overview](https://docs.anthropic.com/en/docs/about-claude/models)
- [tiktoken tokenizer](https://github.com/openai/tiktoken)

## 🧪 Build lab: `llm-playground`

Create a repeatable script or notebook that records model, prompt, parameters, token counts, latency, output, and observations. Test:

- The same prompt with two models
- Short, relevant, and excessive context
- Temperature 0 versus higher temperature
- JSON output failures
- Ambiguous questions
- Unsupported factual questions
- Conflicting instructions

## 📦 Deliverables

- `experiments/llm-playground`
- `notes/how-llms-work.md`
- A comparison table of at least two models
- Five observed failure modes
- A token and latency snapshot

## 🚀 Stretch roadmap

- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [Stanford CS25 - Transformers United](https://web.stanford.edu/class/cs25/)
- [Full Stack Deep Learning - LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/)

## 🏁 Definition of done

You can predict how context length, sampling, and instructions will affect an output, and you have evidence rather than assumptions from your own experiments.

---

[Next: Week 2 - Prompting and Structured Outputs →](../week-2/README.md)
