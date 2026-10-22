# Book Market Analytics – Books to Scrape

**Data Science 500 Assignment**  
Richfield Graduate Institute of Technology

---

## Project Overview

This project implements a complete end-to-end data science workflow for analysing book catalogue trends and predicting pricing patterns on the [Books to Scrape](https://books.toscrape.com) sandbox website.

The solution covers:

1. **Data Acquisition** – Web scraping with BeautifulSoup  
2. **Data Cleaning & Preparation**  
3. **Exploratory Data Analysis & Visualisation**  
4. **Predictive Modelling** – Linear Regression for book price estimation  
5. **Professional Reporting** – Insights and recommendations for retailers and publishers

---

## Objectives

- Scrape at least 200 books from the full catalogue (or a selected genre).  
- Extract key product attributes: title, price (GBP), star rating, and stock availability.  
- Clean and structure the raw data into an analytical dataset.  
- Explore relationships between price, rating, availability, and genre.  
- Build and evaluate a linear regression model that estimates book price from available features.  
- Deliver clear, actionable insights suitable for a consulting audience.

---

## Project Structure

```
.
├── notebooks/
│   └── book_market_analytics.ipynb   # Full pipeline (scraping → modelling)
├── data/
│   ├── raw/                          # Raw scraped data
│   └── processed/                    # Cleaned analytical dataset
├── reports/
│   └── project_report.pdf            # Professional project report
├── src/                              # Optional reusable scripts
├── requirements.txt
└── README.md
```

---

## Requirements

### Required Fields (per book)
- Book title  
- Price (in GBP)  
- Star rating (1–5, expressed as a word: “One” to “Five”)  
- Stock availability (In stock / Out of stock + quantity where available)

### Minimum Dataset Size
- At least **200 books** (full catalogue contains 1 000 books across 50 genres)

### Modelling
- Linear Regression model predicting book price  
- Feature selection and justification  
- Evaluation with appropriate metrics (e.g., MAE, RMSE, R²)  
- Discussion of model limitations

---

## Setup Instructions

1. **Clone / download the project**

2. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate        # Linux / macOS
   # or
   venv\Scripts\activate           # Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook notebooks/book_market_analytics.ipynb
   ```

---

## Dependencies

Typical packages used:

```
beautifulsoup4
requests
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

See `requirements.txt` for the exact versions used.

---

## Workflow Summary

| Stage                    | Description                                      | Marks |
|--------------------------|--------------------------------------------------|-------|
| 1. Data Acquisition      | BeautifulSoup scraping of Books to Scrape        | 20    |
| 2. Data Cleaning         | Handling missing values, formatting, structuring | 20    |
| 3. Visualisation         | Price, rating, genre trends & relationships      | 20    |
| 4. Predictive Modelling  | Linear Regression + evaluation                   | 20    |
| 5. Report Quality        | Clear methodology, insights & recommendations    | 20    |
| **Total**                |                                                  | **100** |

---

## Deliverables

1. **Jupyter Notebook** – Complete, well-documented pipeline from acquisition to interpretation.  
2. **Final Dataset** – Clean structured dataset produced from the scraping process.  
3. **Professional Project Report** – Methodology, key insights, modelling outcomes, practical implications, and recommendations.

---

## Academic Integrity

This submission is original work. All sources have been properly cited using the Harvard Referencing Style. The declaration of originality is included in the project report.

---

## Author

- **Name:** [Timothy mosima]  
- **Student ITS No:** [402600795]  
- **Qualification:** [Data science]  
- **Year of Study / Semester:** [e.g. 2026 / Semester 2]

---

*Richfield Graduate Institute of Technology*  
*Data Science 500 Assignment – Book Market Analytics*
