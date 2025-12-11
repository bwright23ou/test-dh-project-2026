# Digital Humanities Project Template

This repository is a starting point for DH projects that combine:

- A dataset (tabular, usually in `data/`)
- A static website (in `site/` using Eleventy)
- An interactive data exploration app (in `app/` using Streamlit)
- Documentation for sustainability and reuse (in `docs/`)

## Quick Start for a New Project

1. Duplicate this repo using "Use this template" on GitHub.
2. Fill out `docs/00_discovery.md` and `docs/01_project_scope.md`.
3. Place your original dataset(s) in `data/raw/`.
4. Use `scripts/clean_data.py` or a notebook in `data/notebooks/` to create cleaned data in `data/processed/`.
5. Build out the static site in `site/`.
6. Build the Streamlit app in `app/`, pointing it at `data/processed/`.
7. Complete licensing, citation, accessibility, and sustainability docs in `docs/`.

See the documents in `docs/` for a step-by-step workflow.

