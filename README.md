# SemanticSearchvsKeywordSearch

A simple notebook that compares semantic search (SentenceTransformers + cosine similarity) with a basic keyword search on financial news headlines.

## What this does
- Loads a dataset of analyst ratings headlines
- Builds embeddings with `all-MiniLM-L6-v2`
- Runs semantic search using cosine similarity
- Runs keyword search using token overlap
- Prints top results for a few example queries

## Project structure
- `Main.ipynb` — the notebook with all code and explanations
- `analyst_ratings_processed.csv` — processed dataset (input)
- `raw_analyst_ratings.csv` — raw dataset (input)
- `raw_partner_headlines.csv` — raw dataset (input)

## Quick start

### 1) Install dependencies
```bash
pip install pandas sentence-transformers scikit-learn kagglehub