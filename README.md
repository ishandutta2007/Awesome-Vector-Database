# Awesome-Vector-Database

# Top Vector Database Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Embedding Stores, ANN Indexes, RAG Backends, Multimodal Vectors & AI-Native Data Layers*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vector Databases**. These systems persist embeddings, run similarity search, and support metadata filters—the storage layer behind RAG, semantic search, and AI agents.

**Examples** include Weaviate Cloud, Pinecone, Qdrant Cloud, Zilliz Cloud, Chroma Cloud, managed Milvus, Vespa Cloud, Elastic Cloud, Marqo Cloud, Redis Cloud, and **Chroma** (`chroma-core/chroma`)—the AI-native open-source embedding database.

**Open-source emphasis**: Vector databases are led by open source. **Chroma**, **Milvus**, **Qdrant**, **Weaviate**, **LanceDB**, **pgvector**, and **Faiss**-based stacks are production standards. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pinecone, Zilliz Cloud, Weaviate Cloud, Qdrant Cloud, Chroma Cloud](https://www.pinecone.io/)**  
  Managed vector databases—hosted indexes, scaling, backups, and APIs purpose-built for embeddings.

- **[Elastic Cloud, Redis Cloud, Vespa Cloud, Marqo Cloud](https://www.elastic.co/)**  
  Managed data platforms with first-class vector fields alongside search, cache, or hybrid query engines.

- **[Cloud provider vector services (AWS, Azure, GCP)](https://aws.amazon.com/)**  
  Native cloud vector and hybrid search offerings integrated with each provider’s AI stack.

- **[Other commercial vector database platforms](https://zilliz.com/)**  
  Additional managed ANN and embedding-store services.

## Open-Source GitHub Projects

### Dedicated Vector Databases

- **[Chroma](https://github.com/chroma-core/chroma)**  
  AI-native open-source embedding database—simple API for documents, embeddings, and collections; popular for LLM applications.

- **[Milvus](https://github.com/milvus-io/milvus)**  
  Open distributed vector database—cloud-native scale, multiple index types, and a large ecosystem (Zilliz commercial).

- **[Qdrant](https://github.com/qdrant/qdrant)**  
  Open vector database in Rust—payload filtering, high performance, and production-oriented ops features.

- **[Weaviate](https://github.com/weaviate/weaviate)**  
  Open vector search engine/database—hybrid search, modules for vectorization, and flexible schemas.

- **[LanceDB](https://github.com/lancedb/lancedb)**  
  Open embedded vector database on the Lance columnar format—strong for local and analytics-friendly workloads.

- **[Vald](https://github.com/vdaas/vald)**  
  Open distributed vector search system designed for Kubernetes.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open big-data serving engine with native vector ranking for search and recommendation.

### Libraries & Extensions

- **[Faiss](https://github.com/facebookresearch/faiss)**  
  Open similarity search library from Meta—industry-standard in-process and GPU indexes.

- **[hnswlib](https://github.com/nmslib/hnswlib)**  
  Open header-only HNSW library—core algorithm behind many vector stores.

- **[pgvector](https://github.com/pgvector/pgvector)**  
  Open PostgreSQL extension—store and query vectors next to relational application data.

- **[sqlite-vec / embedded SQLite vector](https://github.com/asg017/sqlite-vec)**  
  Open vector search in SQLite for lightweight and edge deployments.

- **[OpenSearch k-NN / Elasticsearch vectors](https://github.com/opensearch-project/k-NN)**  
  Open search engines with vector index plugins for hybrid retrieval.

### Additional Strong Open-Source Options

- **App-friendly embedding DB**: Chroma.
- **Scale-out production**: Milvus or Qdrant.
- **Hybrid AI search**: Weaviate or Vespa.
- **Embedded / local**: LanceDB, Chroma persistent, or sqlite-vec.
- **Postgres-centric apps**: pgvector.
- **Composable stacks**: Embedding model → Chroma/Qdrant/Milvus → RAG framework (LangChain, LlamaIndex, etc.).
- Managed vector DBs still lead for zero-ops elasticity and enterprise support contracts.

**Frameworks for building custom systems**:  
**Chroma** for fast AI-app iteration; **Qdrant** or **Milvus** for dedicated production vector stores; **pgvector** when you want one database; **Faiss**/**hnswlib** when you embed search inside your process.  
Fully open vector databases are production-proven for RAG and semantic applications at every scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vector indexes approximate nearest neighbors—measure recall and latency on your data. Embeddings may encode sensitive content; apply the same access controls you would for the source documents.
- Open-source vector DBs offer portability and control. Managed services shift operations to the vendor. Neither replaces evaluation of retrieval quality and responsible data handling.

---

**Made for AI engineers, data platform teams, and builders of embedding-powered products.**  
Let's expand open vector databases while recognizing the managed convenience that leading commercial vector platforms deliver.
