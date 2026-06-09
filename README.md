# Nike Brand Intelligence — Customer Voice Analytics

> Turning **687 unstructured customer comments** across Nike.com, YouTube, Reddit, and social media into a board-ready strategic narrative — using NLP, sentiment analysis, and topic modeling in R.

**📊 [View the full interactive report →](https://valentinedube.github.io/nike-brand-intelligence/)**

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Text%20Mining-blue)
![Sentiment Analysis](https://img.shields.io/badge/Sentiment-Bing%20%7C%20AFINN%20%7C%20NRC-green)
![Topic Modeling](https://img.shields.io/badge/Topic%20Modeling-LDA-orange)

---

## 🎯 The Business Question

Nike's leadership (CMO & VP of Consumer Insights) observed rising online chatter about sustainability, mixed sentiment on pricing, and growing pressure from challenger brands. They needed one question answered:

> **"What are customers *really* saying about Nike — and how should we respond strategically?"**

This project answers it with evidence, not opinion.

---

## 💡 Key Findings (What the Data Revealed)

**Sentiment is winnable, not hostile** — of 687 comments: **32.9% positive, 47.3% neutral, 19.8% negative.** Most customers are persuadable; the neutral majority is the growth opportunity.

**Comfort is Nike's strongest moat** — the #1 theme (96 mentions, 14% of corpus) and consistently tied to positive language. It should anchor both product and messaging.

**Quality is an emerging brand risk** — complaints about glue, durability, and early wear appear across *multiple* techniques and sources — a brand-protection issue, not an isolated ops problem.

**Premium icons are under pressure** — product-level sentiment shows **Jordan (−0.50), Air Force 1 (−0.17), and Dunk (−0.14)** trending negative, while **Cortez (+1.0), Metcon (+0.75), and Air Max (+0.67)** lead. Even flagship lines aren't immune.

| Top Themes by Mentions | % of Corpus |
|------------------------|-------------|
| Comfort | 14.0% |
| Design | 12.2% |
| Quality | 7.7% |
| Sizing | 6.0% |
| Pricing | 5.2% |
| Durability | 4.9% |
| Sustainability | 1.9% |

---

## 🧭 Strategic Recommendation

> Nike shouldn't get cheaper everywhere or lean only on hype. The winning play: **fix manufacturing & sizing consistency, defend premium lines where emotional equity is strong, improve value delivery on everyday models, and stand up text analytics as a permanent listening system.**
>
> *Customers still want to believe in Nike — the opportunity is closing the gap between brand promise and product experience.*

The full report includes a phased roadmap: **Immediate (0–30 days), Short-term (30–90), Brand protection (90–180),** and a dedicated **competitive defense against Adidas.**

---

## 🛠 Methods & Techniques

| Area | Techniques Applied |
|------|--------------------|
| **Text preprocessing** | Tokenization, stop-word removal, cleaning, documented preprocessing decisions |
| **Frequency analysis** | Word frequency, bigram extraction & visualization, Zipf's Law verification |
| **Sentiment analysis** | Bing (binary), AFINN (valence), NRC (8-emotion breakdown), comment-level classification |
| **Aspect & topic modeling** | Aspect-based sentiment, Latent Dirichlet Allocation (LDA) |
| **Importance weighting** | TF-IDF by product line |
| **Network analysis** | Keyword co-occurrence network |
| **Competitive intelligence** | Nike vs. Adidas threat & sustainability analysis |

## 📦 Tech Stack

**R** · `tidytext` · `dplyr` · `ggplot2` · `topicmodels` · `igraph`/`ggraph` · Bing/AFINN/NRC lexicons · R Markdown → self-contained HTML

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `index.html` | Complete rendered report (interactive, self-contained) |
| `README.md` | This overview |
| `LICENSE` | MIT License |

## 👀 How to View

- **Online (recommended):** [valentinedube.github.io/nike-brand-intelligence](https://valentinedube.github.io/nike-brand-intelligence/)
- **Locally:** download `index.html` and open in any browser.

---

## 👤 Author

**Valentine Dube** — Data & Business Analyst
📧 valentinedube01@gmail.com · 🔗 [GitHub](https://github.com/ValentineDube)

*Completed as part of the Business Analysis with Unstructured Data course.*
