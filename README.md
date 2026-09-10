# real-time-ecommerce-analytics
MSc Business Analytics dissertation — real-time analytics system for demand forecasting and customer churn detection in e-commerce


# Real-Time Analytics for Agile Decision-Making in E-Commerce

**MSc Business Analytics Dissertation**
Robert Gordon University, Aberdeen | August 2026
**Author:** Kavya Bhardwaj | **Supervisor:** Dr Pascal Ezenkwu

---

## Project Overview

This project investigates whether real-time analytics produces 
measurably faster operational decisions in e-commerce compared 
to traditional batch-processing approaches.

A real-time analytics pipeline was built in Python using the 
UCI Online Retail Dataset — 503,897 clean transactions spanning 
373 days from a UK-based online gift retailer.

Two machine learning modules were developed and evaluated:

- **Module 1 — Demand Forecasting:** Linear Regression and 
  Random Forest models with real-time spike detection
- **Module 2 — Customer Churn Detection:** RFM analysis 
  combined with Logistic Regression classification

---

## Key Results

| Metric | Result |
|--------|--------|
| Demand spike detection — RT vs weekly batch | **4.5 days earlier** |
| Churn detection — RT vs monthly batch | **66.4 days earlier** |
| Best demand model | Linear Regression (MAE: 6.46 units) |
| Churn classifier accuracy | 99.08% (ROC-AUC: 0.9998) |

---

## Tech Stack

- **Python** — pandas, numpy, scikit-learn, matplotlib, seaborn
- **Machine Learning** — Linear Regression, Random Forest, 
  Logistic Regression
- **Visualisation** — Tableau Public
- **Methodology** — Design Science Research (DSR)

---

## Dataset

UCI Online Retail Dataset — publicly available at:
https://archive.ics.uci.edu/dataset/352/online+retail

Download and place in the `/data` folder before running 
the notebook.

---

## How to Run

1. Clone this repository
2. Install dependencies:
   pip install -r requirements.txt
3. Download the UCI dataset into /data
4. Open and run the notebook in /notebooks

---

## Project Structure

notebooks/     Jupyter notebook with full pipeline
outputs/       Generated charts and visualisations
README.md      Project overview
requirements.txt  Python dependencies
Tableau Workbook.twbx  Dashboard file

---

## Acknowledgements

Supervised by Dr Pascal Ezenkwu, Senior Lecturer,
School of Computing, Engineering and Technology,
Robert Gordon University, Aberdeen.
