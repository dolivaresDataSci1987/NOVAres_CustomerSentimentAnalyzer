# NOVAres Customer Sentiment Analyzer  
### Comparative Text & Perception Analysis — Logitech vs Razer

---

## Overview

This project presents a structured end-to-end Natural Language Processing (NLP) analysis of Amazon customer reviews to compare two competing hardware brands: **Logitech** and **Razer**.

The objective is to move beyond star ratings and model how customers *actually express* satisfaction and dissatisfaction through written reviews.

The analysis integrates:

- Exploratory Data Analysis (EDA)
- Transformer-based sentiment modeling
- Rating–sentiment alignment diagnostics
- Semantic contextual mapping (Gaming ↔ Office axis)
- Lexical driver analysis (distinctive term extraction)

<p align="center">
  <img src="/novares_customer_sentiment_banner.png" alt="NOVAres Customer Sentiment Analyzer Banner" width="50%">
</p>

---

## Methodological Framework

### 1. Data Preparation
- Filtering for brand-specific reviews
- Text cleaning and preprocessing
- Feature engineering (review length, date, verification status)

### 2. Exploratory Data Analysis
- Review volume comparison
- Rating distribution
- Review length distribution
- Verified purchase ratio

### 3. Transformer Sentiment Modeling
A pre-trained `distilbert-base-uncased-finetuned-sst-2-english` model is used to classify textual sentiment into:

- POSITIVE
- NEGATIVE

A signed sentiment score is constructed to enable continuous polarity analysis.

### 4. Rating–Sentiment Alignment
Heatmaps and cross-tabulations reveal divergence between:

- Explicit star ratings
- Implicit linguistic tone

### 5. Semantic Context Mapping
A custom semantic axis positions reviews along:
