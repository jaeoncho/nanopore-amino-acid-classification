## README — Nanopore-Based Amino Acid Analysis

## Overview

This repository contains the Python code developed for the analysis of nanopore sensing data involving amino acids (AAs) and gamma-cyclodextrin (γ-CD) using alpha-hemolysin (α-HL) nanopores.

The code was developed as part of a research study investigating the identification and classification of amino acids based on their characteristic ionic current blockade signals.

## Code Description

The repository includes Python scripts and Jupyter notebooks for:

1. **Signal Processing:** Processing raw nanopore recordings, identifying current blockade events, and extracting signal features.
2. **Amino Acid Classification:** Classifying amino acids based on extracted nanopore signal characteristics.
3. **Clustering Analysis:** Exploring similarities and differences among amino acid signals using unsupervised learning.
4. **Mixture Classification:** Analyzing and classifying amino acids in mixed samples.
5. **Data Visualization:** Generating scatter plots, distributions, and other figures for evaluating nanopore sensing results.

## Requirements

The analysis was performed using Python and commonly available scientific computing libraries, including:

- NumPy
- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- Statsmodels
- PyABF
- Plotly

Specific package versions and dependencies should be installed according to the provided environment configuration, where available.

## Usage

The Jupyter notebooks can be executed to reproduce the corresponding signal processing, classification, clustering, and visualization workflows.

Users should update input and output directory paths as necessary to match their local file organization.

## Data Availability

The availability of raw and processed nanopore data is described in the associated publication.

## Citation

If you use this code in your research, please cite the associated publication:

[Authors, Article Title, Journal, Year, DOI]

