# Terpene literature discovery and evidence intake

- **Category:** Research infrastructure
- **Status:** Operational tooling
- **Canonical project/source:** https://github.com/Terpedia/terpmed

## Research question

How can query coverage and retrieval provenance be made inspectable across terpene and topic searches in PubMed?

## Reproduce

Create the environment with `conda env create -f environment.yml`, activate it, and run `jupyter lab notebooks/analysis.ipynb`. Review the provenance in `data/manifest.tsv` before running any analysis.

## Contents

- `notebooks/analysis.ipynb` — study analysis record.
- `whitepaper/white-paper.md` — scope, methods, results, and limitations.
- `data/manifest.tsv` — source provenance.
- `environment.yml` — analysis dependencies.

This is a local implementation package. A separate GitHub repository has not been created or published from this session.
