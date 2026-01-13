# IR System: VSM + QLM

This project implements an **Information Retrieval System** using:
- **Vector Space Model (VSM)**
- **Query Likelihood Model (QLM)**

## Folder Structure

- `assets/` → Contains crawled HTML pages
- `app.py` → Dash web interface
- `crawler_and_indexer.py` → Build inverted index from crawled pages
- `merged_inverted_index.json` → Precomputed inverted index
- `requirements.txt` → Python packages

## Run the App

1. Install dependencies:

```bash
pip install -r requirements.txt
