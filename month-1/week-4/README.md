# 📚 Week 4 - RAG v1

> **Days 22–30 · Foundations · Progress:** 🟦🟦🟦🟦⬜⬜⬜

## 🎯 Mission

Combine retrieval and generation into a grounded assistant that cites evidence and refuses to invent answers.

## ✅ Outcomes

You can design a RAG request path, select context, generate citations, handle no-result questions, and debug unsupported answers.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 22 | RAG architecture | Draw the request and data flows. |
| 23 | Retrieval-to-prompt | Build a context assembler. |
| 24 | Grounded generation | Add answer and citation instructions. |
| 25 | Abstention | Test unknown and conflicting questions. |
| 26 | Chat interface | Add conversation history carefully. |
| 27 | Failure analysis | Label retrieval, context, and generation failures. |
| 28 | Quality pass | Improve the ten worst queries. |
| 29 | Documentation | Add setup, architecture, and limitations. |
| 30 | Demo day | Record the local milestone demo. |

## 📚 Learn

- Retrieval-augmented generation architecture
- Context windows and context selection
- Grounding, citations, and answer faithfulness
- Conversation memory versus source context
- “Not found in provided docs” behavior
- RAG failure taxonomy

## 🔗 Core resources

- [Microsoft - RAG Concepts](https://learn.microsoft.com/en-us/azure/foundry/concepts/retrieval-augmented-generation)
- [LangChain - Build a RAG Agent](https://python.langchain.com/docs/tutorials/rag/)
- [LlamaIndex - Starter Tutorial](https://developers.llamaindex.ai/python/framework/getting_started/starter_example/)
- [Anthropic - Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval)
- [OpenAI Cookbook - Question Answering with Embeddings](https://cookbook.openai.com/examples/question_answering_using_embeddings)
- [RAGAS - RAG Evaluation](https://docs.ragas.io/en/stable/getstarted/rag_eval/)

## 🧪 Build lab: Chat with My Docs

The app must accept a question, retrieve top chunks, pass only relevant context, answer with citations, and explicitly say when the answer is unsupported. Include source links or source names in every grounded response.

## 📦 Deliverables

- Local chat app
- RAG architecture diagram
- Citation format and source contract
- Ten-question smoke-test set
- One retrieval failure investigation
- Day 30 demo and README update

## 🚀 Stretch roadmap

- Add query rewriting
- Compare contextual retrieval and parent-child chunking
- Add conversation summarization
- Add streaming responses
- Add answer faithfulness checks

## 🏁 Definition of done

A user can ask questions about the selected corpus and receive a useful answer with inspectable evidence-or a clear, honest not-found response.

---

[← Previous: Week 3 - Embeddings and Semantic Search](../week-3/README.md) | [Next: Month 2, Week 1 - RAG Quality →](../../month-2/week-1/README.md)
