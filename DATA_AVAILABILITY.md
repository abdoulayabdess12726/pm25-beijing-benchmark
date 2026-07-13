# Data Availability Statement

The data used in this study are openly available from a public third-party
repository. The code used to download, preprocess, train, and evaluate all
models is publicly available in this repository.

## Air quality monitoring data

- **Beijing Multi-Site Air-Quality Data Set** — UCI Machine Learning Repository
  (dataset #501), 12 monitoring stations, 2013–2017. Openly available at
  <https://archive.ics.uci.edu/dataset/501>.

## Reproducibility

All preprocessing and modeling scripts, configuration, and the random seeds
({42, 123, 777}) required to reproduce the reported results are included in this
repository. No new data were created in this study; the processed dataset can be
regenerated from the raw source using the provided download script
(`01_download_beijing.py`).
