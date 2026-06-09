# Nike Brand Intelligence — Text Mining & Sentiment Analysis

> An end-to-end Natural Language Processing (NLP) project analyzing customer voice data to surface actionable brand, product, and competitive insights for Nike.

**📊 [View the full interactive report →](https://valentinedube.github.io/nike-brand-intelligence/)**

---

## Overview

This project applies text-mining and sentiment-analysis techniques to unstructured customer feedback about Nike products. It transforms thousands of raw comments into a structured strategic narrative — identifying what customers love, what drives dissatisfaction, how products perform individually, and where Nike stands against its main competitor, Adidas.

The analysis was built in **R** using the `tidytext` framework and delivered as a fully reproducible R Markdown report.

## Business Questions Addressed

- What are customers actually saying about Nike, and how does sentiment break down across emotions?
- Which product lines drive positive vs. negative sentiment (e.g. the Metcon 10 training shoe)?
- What recurring themes and aspects (fit, durability, sustainability, price) shape brand perception?
- How does Nike compare to Adidas on share of voice and sentiment?
- What strategic actions should Nike prioritize over the next 0–180 days?

## Methods & Techniques

| Area | Techniques Applied |
|------|--------------------|
| **Text preprocessing** | Tokenization, stop-word removal, cleaning, preprocessing decisions |
| **Frequency analysis** | Word frequency, bigram extraction & visualization, Zipf's Law verification |
| **Sentiment analysis** | Bing (binary), AFINN (valence), NRC (emotion breakdown), comment-level classification |
| **Aspect & topic modeling** | Aspect-based sentiment, Latent Dirichlet Allocation (LDA) topic modeling |
| **Importance weighting** | TF-IDF by product line |
| **Network analysis** | Keyword co-occurrence network |
| **Competitive intelligence** | Nike vs. Adidas threat analysis, sustainability analysis |

## Key Deliverables

- **Executive summary** with sentiment distribution, top business themes, and product-line performance tables
- **Product deep-dive** on the Metcon 10 training shoe
- **Strategic recommendations roadmap** segmented by time horizon:
  - Immediate actions (0–30 days)
  - Short-to-medium term (30–90 days)
  - Brand & market protection (90–180 days)
  - Competitive defense against Adidas
- A transparent **limitations & model validity** section

## Tech Stack

- **Language:** R
- **Core libraries:** `tidytext`, `dplyr`, `ggplot2`, `topicmodels`, `igraph`/`ggraph`
- **Sentiment lexicons:** Bing, AFINN, NRC
- **Report:** R Markdown → self-contained HTML (Pandoc)

## Repository Contents

| File | Description |
|------|-------------|
| `index.html` | The complete rendered report (interactive, self-contained) |
| `README.md` | This file |

## How to View

- **Online (recommended):** [valentinedube.github.io/nike-brand-intelligence](https://valentinedube.github.io/nike-brand-intelligence/)
- **Locally:** download `index.html` and open it in any web browser.

---

## Author

**Valentine Dube** — Data & Business Analyst
📧 valentinedube01@gmail.com · 🔗 [GitHub](https://github.com/ValentineDube)

*Completed as part of the Business Analysis with Unstructured Data course.*
