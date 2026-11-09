# 📈 Week 5 — RAG Quality

> **Days 31–37 · Systems · Progress:** 🟦🟦🟦🟦🟦⬜⬜

## 🎯 Mission

Replace “it seems to work” with measurable retrieval quality and deliberate retrieval improvements.

## ✅ Outcomes

You can build a retrieval dataset, compare strategies, calculate ranking metrics, and explain why a query failed.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 31 | Evaluation dataset | Create 20–30 representative questions. |
| 32 | Baseline | Measure top-k retrieval and record failures. |
| 33 | Chunking experiments | Compare size and overlap configurations. |
| 34 | Metadata and filters | Add source, section, and date filters. |
| 35 | Hybrid and reranking | Compare dense, lexical, and reranked search. |
| 36 | Error analysis | Categorize misses and false positives. |
| 37 | Decision record | Select a strategy and document tradeoffs. |

## 📚 Learn

- Recall@K, Precision@K, MRR, and hit rate
- Answer relevance and citation correctness
- Dense, lexical, hybrid, and reranked retrieval
- Metadata filtering and query rewriting
- Golden datasets and regression thresholds

## 🔗 Core resources

- [Ragas — RAG Evaluation](https://docs.ragas.io/en/stable/getstarted/rag_eval/)
- [Qdrant — Hybrid Queries](https://qdrant.tech/documentation/concepts/hybrid-queries/)
- [Qdrant — Search](https://qdrant.tech/documentation/concepts/search/)
- [Pinecone — RAG Evaluation](https://www.pinecone.io/learn/series/rag/rag-evaluation/)
- [Microsoft — RAG Quality](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)
- [BEIR Benchmark](https://github.com/beir-cellar/beir)

## 🧪 Build lab: retrieval scorecard

Create `tests/test_queries.json` with question, expected source, answer points, difficulty, and tags. Run at least two retrieval configurations and publish a scorecard with failures and likely causes.

## 📦 Deliverables

- Golden query dataset
- Retrieval evaluation command
- Baseline scorecard
- Comparison of two or more strategies
- Error taxonomy and improvement decision record

## 🚀 Stretch roadmap

- Add synthetic question generation with human review
- Test multi-query retrieval
- Add cross-encoder reranking
- Track results by document type and difficulty

## 🏁 Definition of done

You can demonstrate that a retrieval change improved a defined metric without causing unacceptable regressions elsewhere.

---

[← Previous: Month 1, Week 4 — RAG v1](../../month-1/week-4/README.md) | [Next: Week 2 — Tool Calling and MCP →](../week-2/README.md)
