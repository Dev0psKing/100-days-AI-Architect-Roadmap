# Week 4 — RAG v1

**Days 22–30**

## Learn

- Retrieval and grounding
- Context selection
- Answer generation
- Citations
- The explicit “I don't know” behavior

## Read

- [Microsoft RAG Concepts](https://learn.microsoft.com/en-us/azure/foundry/concepts/retrieval-augmented-generation)
- [LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/)
- [LlamaIndex Starter Tutorial](https://developers.llamaindex.ai/python/framework/getting_started/starter_example/)

## Build

Turn semantic search into a chat application. It must:

- Accept a user question
- Retrieve the top relevant chunks
- Pass only relevant context to the model
- Answer with source citations
- Say **not found in provided docs** when the answer is unsupported

## Day 30 output

A working local **Chat with My Docs** application, plus a short note explaining one retrieval failure and how you diagnosed it.
