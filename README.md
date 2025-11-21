# 💻 Web Scraping: Largest Companies Rankings from Wikipedia

---

This repository contains two simple, well-documented Jupyter notebooks that scrape and clean publicly available rankings from Wikipedia:

1. **Top Technology Companies by Revenue**  
   Source: https://en.wikipedia.org/wiki/List_of_largest_technology_companies_by_revenue  
   (2024 fiscal year data, accessed November 2025)

2. **Africa's Largest Companies by Revenue**  
   Source: https://en.wikipedia.org/wiki/List_of_largest_companies_in_Africa_by_revenue  
   (latest available data, accessed November 2025)

---

The notebooks use only `requests` and `BeautifulSoup` for scraping and `pandas` for cleaning/exporting — no Selenium or paid APIs.

## 🗃️ Output Files
Cleaned datasets are saved in the `/data` folder:
- `top_tech_companies_by_revenue_2025.csv`
- `africa_largest_companies_by_revenue_2025.csv`
