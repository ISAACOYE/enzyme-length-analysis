# Enzyme Periodicity Analysis

This project investigates whether eukaryotic enzyme lengths exhibit statistically significant periodicity, using large-scale protein data and advanced spectral/statistical modeling techniques.

## Overview

The analysis explores evolutionary and structural constraints on protein lengths by applying signal processing and mixture modeling techniques to a dataset of 18,000+ eukaryotic enzyme sequences.

## Key Methods

- **Spectral Analysis of Distributions (SAD)** to detect hidden periodic patterns
- **Cosine Fourier Transform** to confirm periodicity and smooth signal noise
- **Gamma + Normal Mixture Modeling** to fit length distributions and estimate significance
- **Custom Filtering Rules** to remove redundancy and enforce sequence diversity

## Dataset

- Source: UniProt enzyme sequences
- Final filtered dataset: 4 versions using protein name and sequence similarity rules

## Key Finding

A robust periodicity around **121.4 amino acids** was identified and supported by AIC/BIC model selection criteria and bootstrap confidence testing.

## Files

- `enzyme_periodicity_pipeline.ipynb`: Main notebook containing data cleaning, SAD, Fourier transform, and modeling
- `filtered_sequences/`: Sequence files used in different rule variants
- `plots/`: Visualizations of SAD and model fits
- `results/`: Statistical summaries and hypothesis test outputs

## Status

Complete. This project was conducted as part of an advanced bioinformatics course at NYU.

## Contact

Isaac Oyediran  
isaacoyediran@gmail.com  
[LinkedIn](https://linkedin.com/in/isaac-oyediran)
