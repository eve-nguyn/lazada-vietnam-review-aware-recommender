# Lazada Vietnam — Review-Aware Recommendation System

## Comparative Retrieval Architecture Study for Vietnamese E-Commerce

This project presents a comparative study of multiple retrieval architectures for Vietnamese e-commerce recommendation systems using Lazada product reviews and metadata.

The system explores lexical, semantic, and hybrid retrieval methods combined with business-aware reranking strategies to improve recommendation relevance, diversity, and trustworthiness.

---

## Research Objectives

- Build a Vietnamese recommendation pipeline for e-commerce products
- Compare lexical vs semantic retrieval architectures
- Investigate hybrid retrieval using Reciprocal Rank Fusion (RRF)
- Apply business-aware reranking using trust and product quality signals
- Evaluate recommendation quality across multiple metrics

---

## Retrieval Architectures

The notebook compares:

1. TF-IDF Retrieval
2. SBERT Semantic Retrieval
3. PhoBERT Semantic Retrieval
4. Hybrid TF-IDF + SBERT (RRF)
5. Hybrid TF-IDF + PhoBERT (RRF)

---

## Key Features

- Vietnamese NLP preprocessing
- Review-aware semantic retrieval
- Hybrid retrieval architecture
- Business-aware reranking
- Comparative evaluation framework
- Semantic coherence analysis
- Diversity and coverage metrics
- Trust-aware recommendation scoring

---

## Project Structure

```text
notebooks/     → Main experimentation notebooks
src/           → Reusable pipeline modules
data/          → Dataset storage
models/        → Saved embeddings and artifacts
outputs/       → Evaluation results and visualizations
```
## Evaluation Metrics

- Precision@K
- Semantic Coherence
- Diversity
- Coverage
- Average Trust Score
- Average Product Rating
- Mall Ratio

## Pipeline

Vietnamese Reviews
        ↓
NLP Preprocessing
        ↓
Embedding Generation
        ↓
Retrieval Architecture
        ↓
Hybrid Fusion (RRF)
        ↓
Business-Aware Reranking
        ↓
Evaluation Framework

## Dataset

The dataset contains Vietnamese e-commerce product information including:
- Product titles
- Product descriptions
- Ratings
- Reviews
- Brand information
- Price information
- Trust-related metadata

# Future Improvements

- Real-time recommendation serving
- FAISS vector search integration
- User-personalized recommendation
- Session-aware recommendation
- Multimodal recommendation with images
- LLM-based recommendation explanation
