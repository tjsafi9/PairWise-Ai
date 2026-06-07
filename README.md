# PairWise AI — Intelligent Candidate Discovery & Ranking

> India Runs Hackathon 2026 | Track 01: Data & AI Challenge
> Team: PairWise AI | Hack2Skill × Redrob

---

## Problem Statement
Recruiters spend 60–80% of their time manually screening resumes.
PairWise AI automates intelligent candidate discovery and ranking
using semantic similarity and multi-factor scoring.

## How It Works
1. **Parse** — Extract structured data from resumes & job descriptions
2. **Embed** — Convert text to semantic vectors (Sentence Transformers)
3. **Rank** — Score candidates using cosine similarity + weighted factors
4. **Visualize** — Interactive dashboard for recruiter insights

## Tech Stack
| Layer | Technology |
|---|---|
| Embeddings | `sentence-transformers` |
| ML | `scikit-learn` |
| Backend | `FastAPI` |
| Frontend | `Streamlit` |
| Visualization | `Plotly` |
| Data | `Pandas`, `NumPy` |

## Quick Start
```bash
git clone https://github.com/YOUR_USERNAME/pairwise-ai.git
cd pairwise-ai
pip install -r requirements.txt
streamlit run app/streamlit_app.py
