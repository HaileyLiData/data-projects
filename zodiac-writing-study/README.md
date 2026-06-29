# Zodiac & Writing Style Study

Can Sun Signs Influence Writing Style? A Large-Scale Computational Analysis

## Overview

This study examines whether zodiac signs (sun signs) are associated with language expression patterns, analyzing both **semantic content** ("what authors write about") and **writing style** ("how authors write").

## Key Findings

| Analysis | Features | Significant (p<0.05) | Bonferroni Significant | Max Effect Size |
|----------|----------|---------------------|----------------------|-----------------|
| Empath × 12 Signs | 194 | 13 | **0** | 0.0009 |
| Style × 12 Signs | 37 | 3 | **0** | 0.0008 |
| Empath × 4 Elements | 194 | 10 | **0** | <0.001 |
| Style × 4 Elements | 37 | 2 | **0** | <0.001 |

**Conclusion**: No statistically significant association between sun signs and writing style.

## Data

- **Sample**: 17,872 authors from Project Gutenberg
- **Text**: ~50,000 characters per author (~8,000-10,000 words)
- **Source**: Wikidata (birth dates) + Project Gutenberg (texts)

## Methods

- **Semantic Analysis**: Empath (194 categories, similar to LIWC)
- **Style Analysis**: 37 features (sentence length, TTR, function words, punctuation)
- **Statistics**: Kruskal-Wallis test, Bonferroni correction, effect size (η²)
- **Clustering**: K-means (k=4), Chi-square test

## Report

[View Full Interactive Report](./index.html)

## Author

Hailey Li | University of Waterloo
