# Hybrid Search Workshop

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Marc-Demoustier/hybrid_search_hacknroll/blob/main/hybrid_search_workshop.ipynb)

A hands-on workshop exploring how modern search engines combine **lexical** (BM25) and **semantic** (embeddings) search to build powerful hybrid search systems.

**Slides:** [https://marc-demoustier.github.io/hybrid_search_hacknroll/](https://marc-demoustier.github.io/hybrid_search_hacknroll/)

## What You'll Build

A **Smart Flashcard Generator** that:
1. Crawls Wikipedia pages to build a document corpus
2. Indexes documents with BM25 and semantic embeddings
3. Searches using hybrid approach (Reciprocal Rank Fusion)
4. Generates flashcards using RAG + LLM

## Workshop Contents

| Part | Topic |
|------|-------|
| 1 | Setup & Introduction |
| 2 | Web Crawling (building a corpus) |
| 3 | BM25 Lexical Search |
| 4 | Semantic Search with Embeddings |
| 5 | Hybrid Search (RRF) |
| 6 | When to Use What |
| 7 | Document Chunking for RAG |
| 8 | LLM-Powered Flashcard Generation |
| 9 | Export to Anki & CSV |

## Key Concepts

- **BM25**: Classic keyword-based ranking using term frequency and document length normalization
- **Semantic Search**: Dense vector embeddings that capture meaning and synonyms
- **Hybrid Search**: Combining both approaches with Reciprocal Rank Fusion (RRF)
- **RAG**: Retrieval-Augmented Generation for grounding LLM responses

## Requirements

- Python 3.10+
- ~4GB RAM for embedding model
- GPU optional (CPU works fine)

## Quick Start

```bash
# Clone the repo
git clone https://github.com/Marc-Demoustier/hybrid_search_hacknroll.git
cd hybrid_search_hacknroll

# Open the notebook
jupyter notebook hybrid_search_workshop.ipynb
```

The notebook will install all required packages automatically.

## Presented At

**Hack&Roll 2026** - by [Ahrefs](https://ahrefs.com)

## Author

Marc Demoustier - Backend Engineer @ Ahrefs
