# Week 1 — RAG Quality

**Days 31–37**

## Learn

- Chunk size and overlap
- Metadata filters
- Hybrid search
- Reranking
- Retrieval evaluation

## Read

- [Qdrant Documentation](https://qdrant.tech/documentation/)
- [Ragas RAG Evaluation](https://docs.ragas.io/en/stable/getstarted/rag_eval/)

## Build

Create `tests/test_queries.json`. Each test must include:

- Question
- Expected source
- Expected answer points
- Difficulty level

Measure:

- Recall@K
- Precision@K
- Mean Reciprocal Rank
- Answer relevance
- Citation correctness

Compare at least two chunking or retrieval configurations and record the tradeoffs.

## Output

Produce a basic retrieval evaluation report with failures, likely causes, and the next improvement to make.

---

[← Previous: Month 1, Week 4 — RAG v1](../../month-1/week-4/README.md) | [Next: Week 2 — Tool Calling and MCP →](../week-2/README.md)
