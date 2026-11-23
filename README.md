# IT6117---project
Prosjektoppgave helsedata og KI, NTNU IT 6117

## Classifying Historical Hysteria Diagnoses Using a Local LLM

This project classifies historical free-text hysteria diagnoses from the 
Norwegian Health Archive Registry (NHAR) using a local large language model (Gemma4).

## Pipeline
1. `01_clean.ipynb` — Data preprocessing
2. `02_explore.ipynb` — Semantic embeddings and t-SNE visualisation
3. `03_classify.ipynb` — LLM classification (Gemma4 via Ollama)
4. `04_evaluate.ipynb` — Evaluation against gold-standard sample

## Requirements
- Python 3.15+
- Ollama with Gemma4:12b
- See dependencies in `.venv`

## Setup
```bash
source .venv/bin/activate