# Terpene literature discovery and evidence intake

**Category:** Research infrastructure  
**Version:** 0.1.0  
**Status:** Operational tooling

## Abstract

This package organizes an existing Terpedia research track into a reproducible study repository. The present version documents the research question, available artifacts, and evidence boundaries. It does not report new experimental results.

## Research question

How can query coverage and retrieval provenance be made inspectable across terpene and topic searches in PubMed?

## Data and provenance

See [`../data/manifest.tsv`](../data/manifest.tsv). Each source must retain its accession or URL, publication, license, retrieval date, checksum, and processing notes.

## Methods

The accompanying notebook inventories the declared sources and provides the execution entry point. Any quantitative analysis must specify the sampling/design unit, inclusion criteria, software versions, parameters, and uncertainty model.

## Results

No new quantitative result is reported in this release. Existing source conclusions remain limited to the original artifacts and their stated methods.

## Limitations and next steps

Resolve source provenance, permissions, and reproducibility before generating pooled conclusions. Separate observed measurements from model predictions and hypotheses.

## Reproducibility

- Notebook: [`../notebooks/analysis.ipynb`](../notebooks/analysis.ipynb)
- Environment: [`../environment.yml`](../environment.yml)
- Data manifest: [`../data/manifest.tsv`](../data/manifest.tsv)

## References

- Canonical project repository: https://github.com/Terpedia/terpmed
