# Tarun B | Data Engineer Portfolio

> Live at: **[tarun-b-12.github.io/tarun-portfolio](https://tarun-b-12.github.io/tarun-portfolio)**

Personal portfolio site for Tarun B, Data Engineer and Analytics Engineer with 6 years of experience building ELT platforms, real-time streaming systems, AI-assisted data pipelines, and cloud data infrastructure across banking, retail, insurance, and HR tech.

---

## What is this

A single-file, zero-dependency portfolio built with vanilla HTML, CSS, and JavaScript. No framework, no build step, no node_modules. Opens directly in a browser and deploys instantly via GitHub Pages.

## Featured projects

| Project | Stack | Key metric |
|---|---|---|
| Revenue Leakage and Margin Analysis | Python, DuckDB, SQL, Tableau, Streamlit | $566K leakage identified across 9,994 transactions |
| Financial Document RAG Pipeline | AWS EC2, S3, Python, RAG, Vector DB | Live demo deployed on AWS |
| LLM Transaction Classifier | Claude API, Python, eval framework | 91.2% accuracy vs rule-based baseline |
| Ecommerce KPI Mart | dbt Core, DuckDB, star schema | 100K+ rows modeled with full dbt tests and docs |
| RetailStream Kafka Pipeline | Kafka, Confluent Cloud, Python, DuckDB, Streamlit | Full producer to live dashboard stack |
| Retail Data Quality Observability | Great Expectations, Python, SQL | Pre-delivery validation and anomaly monitoring |

## Tech stack (portfolio site itself)

- Vanilla HTML5, CSS3, JavaScript
- Bebas Neue (display) + Instrument Sans (body) + JetBrains Mono (code) via Google Fonts
- CSS custom properties for full theming
- IntersectionObserver for scroll-triggered reveals
- Zero dependencies, zero build tools

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings > Pages**
3. Set source to **main branch, root folder**
4. GitHub will publish at `https://tarun-b-12.github.io/tarun-portfolio`

That is it. No CI/CD config needed.

## Local preview

```bash
# Any static server works. Simplest options:
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000` in your browser.

## Project structure

```
tarun-portfolio/
  index.html       # entire site, single file
  README.md        # this file
  .nojekyll        # tells GitHub Pages to skip Jekyll processing
```

## Contact

- Email: buildwithtarun@gmail.com
- LinkedIn: linkedin.com/in/tarun-b-k
- GitHub: github.com/Tarun-B-12
- Location: Dallas, TX
