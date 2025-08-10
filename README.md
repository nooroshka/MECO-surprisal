# Lexical vs. Syntactic Surprisal in Native and L2 Reading

Code + paper source for the structured (OneStop) and open-ended (MECO) analyses.
**Figures are managed on Overleaf** (not stored in this repo).

---

## What’s here
- `notebooks/structured.ipynb` – OneStop analyses (surprisal comparison, GAM controls, disagreements).
- `notebooks/open_ended.ipynb` – MECO L1/L2 analyses (lexical vs. syntactic surprisal).
- `reports/CogSci_Template.bib`

> Not included: datasets (OneStop/MECO), heavy caches (e.g., `surprisals.csv`), figures (on Overleaf).

---

## Environment (Python 3.10+)
```bash
python -m venv .venv && source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
python -m spacy download en_core_web_sm
