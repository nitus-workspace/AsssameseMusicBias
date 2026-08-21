# AsssameseMusicBias

# Algorithmic Inequity in Music Streaming: Investigating Recommendation Bias Against Assamese Music

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Research%20Paper%20Submitted-green.svg)]()
[![Data](https://img.shields.io/badge/Data-Last.fm%20API-orange.svg)]()

> Empirical investigation of algorithmic recommendation bias against Assamese music using Last.fm engagement data, statistical hypothesis testing, recommendation simulation, machine learning, and SHAP explainability analysis.

---

## 📖 Overview

Music streaming platforms rely on algorithmic recommendation systems that can systematically under-represent regional and linguistically marginalized content. This repository contains the complete research pipeline for quantifying **recommendation bias against Assamese music** — a culturally rich tradition from Northeast India with limited global digital representation.

### Key Findings

| Metric | Value | Interpretation |
|--------|------:|----------------|
| **Recommendation Frequency Ratio (RFR)** | 0.678 | 32.2% under-recommended |
| **Cross-Group Bleed** | 72.43% | Most recs leave Assamese content |
| **Catalog Coverage** | 6.39% | 93.6% of catalog never recommended |
| **Popularity Gap** | ~1,244× | Mainstream mean popularity ≫ Assamese |
| **Best Model ROC-AUC** | 0.984 | Gradient Boosting |
| **Top Bias Driver** | Listeners (28.1%) | Engagement signals dominate |

**Main result:** When an Assamese track is used as a seed, only **27.57%** of recommendations are Assamese versus a dataset baseline of **40.66%**. Increasing popularity weight in hybrid recommenders collapses Assamese representation toward **0%**.

---
