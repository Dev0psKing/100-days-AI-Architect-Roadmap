# 🔎 Week 3 — Embeddings and Semantic Search

> **Days 15–21 · Foundations · Progress:** 🟦🟦🟦⬜⬜⬜⬜

## 🎯 Mission

Turn a document collection into a searchable knowledge layer and understand why retrieval succeeds or fails.

## ✅ Outcomes

You can ingest documents, split them into meaningful chunks, embed them, store metadata, search semantically, and inspect retrieval quality.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 15 | Embedding intuition | Compare similar and unrelated text vectors. |
| 16 | Document loading | Load Markdown, PDF, and text files. |
| 17 | Chunking | Compare fixed, semantic, and heading-aware chunks. |
| 18 | Vector storage | Create a collection with metadata. |
| 19 | Search API | Implement `GET /search?q=`. |
| 20 | Retrieval inspection | Review top-k results for 15 questions. |
| 21 | Pipeline hardening | Add idempotency, logging, and a rebuild command. |

## 📚 Learn

- Dense vectors and semantic similarity
- Chunk size, overlap, and document structure
- Metadata filters and source traceability
- Vector databases and approximate nearest neighbors
- Top-k retrieval and similarity thresholds
- Indexing, updates, deletes, and reproducibility

## 🔗 Core resources

- [OpenAI — Embeddings](https://developers.openai.com/api/docs/guides/embeddings)
- [Qdrant — Documentation](https://qdrant.tech/documentation/)
- [Pinecone — Vector Database Learning Center](https://www.pinecone.io/learn/)
- [Weaviate — Vector Search Concepts](https://weaviate.io/developers/weaviate/concepts/vector-index)
- [LlamaIndex — Document Management](https://developers.llamaindex.ai/python/framework/module_guides/loading/documents_and_nodes/)
- [LangChain — Text Splitters](https://python.langchain.com/docs/concepts/text_splitters/)

## 🧪 Build lab: ingestion and search pipeline

Use 50–100 documents from the capstone domain. Build a loader, normalizer, chunker, embedder, vector collection, metadata model, and search endpoint. Return source path, title, section, chunk index, and score for every result.

## 📦 Deliverables

- `ingestion/` pipeline with a repeatable rebuild command
- `search/` endpoint and CLI
- Chunking experiment report
- Search examples showing good and bad results
- Source metadata contract

## 🚀 Stretch roadmap

- [Qdrant — Filtering](https://qdrant.tech/documentation/concepts/filtering/)
- [Qdrant — Hybrid Queries](https://qdrant.tech/documentation/concepts/hybrid-queries/)
- [Voyage AI — Embeddings](https://docs.voyageai.com/docs/embeddings)
- [NVIDIA — Retrieval-Augmented Generation](https://developer.nvidia.com/blog/retrieval-augmented-generation-connecting-large-language-models-to-external-knowledge/)

## 🏁 Definition of done

A teammate can run one documented command to ingest the corpus, search it, and trace every result back to an exact source location.

---

[← Previous: Week 2 — Prompting and Structured Outputs](../week-2/README.md) | [Next: Week 4 — RAG v1 →](../week-4/README.md)
