# HumBets Elway Edge

Public Streamlit deployment for the HumBets Elway Edge browser.

## What belongs in this repository

- `humbets_browser_elway_edge.py`
- `requirements.txt`
- `.gitignore`
- `data/processed/humbets_historical_2023_2025.parquet`
- `data/processed/humbets_2026_governed.parquet`

The two parquet files should be the **sanitized public copies** created by
`prepare_humbets_public_data.py`. Do not copy the full development datasets
into this repository.

## Local test

From this folder:

    streamlit run humbets_browser_elway_edge.py

## Streamlit Community Cloud

Point the app at:

    humbets_browser_elway_edge.py

## Privacy

This deployment intentionally excludes raw nflverse data, feature tables,
training scripts, model-development experiments, diagnostics, audits,
frozen prediction ledgers, and other proprietary HumBets research files.
