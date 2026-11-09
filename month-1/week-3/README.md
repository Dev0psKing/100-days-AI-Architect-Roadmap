# Week 3 — Embeddings and Semantic Search

**Days 15–21**

## Learn

- Embeddings
- Vector search
- Document chunking
- Metadata
- Cosine similarity
- Retrieval quality

## Read

- [OpenAI Embeddings](https://developers.openai.com/api/docs/guides/embeddings)
- [Qdrant Documentation](https://qdrant.tech/documentation/)

## Build

Use 50–100 documents or markdown files from the capstone domain. Create:

- A document loader
- A chunker with configurable size and overlap
- An embedding pipeline
- A vector database collection
- Metadata containing source name, path, section, and chunk index
- A semantic search endpoint

The endpoint should be `GET /search?q=` and return the top matching chunks with source names and similarity scores.

## Output

Document the ingestion pipeline, chunking decisions, vector database choice, and examples of good and bad search results.

---

[← Previous: Week 2 — Prompting and Structured Outputs](../week-2/README.md) | [Next: Week 4 — RAG v1 →](../week-4/README.md)
