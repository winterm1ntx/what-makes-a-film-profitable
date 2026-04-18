🎬 What Makes a Film Profitable?
End-to-end analysis of film ROI using TMDB dataset (2000–2023) to help investors identify key factors that drive film profitability

📌 Overview
This project analyzes the TMDB Movies dataset (2000–2023) to answer a core investment question: what factors most influence a film’s Return on Investment (ROI)?
The analysis covers the full data analytics workflow — from data cleaning and exploratory analysis to statistical testing and interactive Tableau dashboards.

❓ Research Questions
 1. How has film ROI trended from 2000 to 2023?
 2. What is the overall distribution of film ROI?
 3. Which production companies consistently deliver high ROI?
 4. Which genres have the highest median ROI?
 5. Is there a relationship between budget and ROI?
 6. Are ROI differences across genres statistically significant?

📂 Dataset
 • Source: TMDB Movies Dataset (Kaggle)
 • Period: 2000–2023
 • Raw records: ~1 million entries
 • After cleaning: ~6,000 films
Cleaning criteria:
 • Budget and revenue minimum $30,000 USD
 • Runtime between 60–300 minutes
 • Removed duplicates and entries where budget equals revenue
 • Manual validation of extreme outliers

🔧 Tools & Tech Stack
  • Data Processing: Python (pandas)
  • Visualization: matplotlib, seaborn, Tableau
  • Statistical Testing: scipy (Kruskal-Wallis, Spearman, Epsilon Squared)
  • Notebook: Jupyter Notebook

📊 Key Findings
Production Company — Significant impact, strong effect size (ε² = 0.226)
Genre — Statistically significant but very small effect (ε² ≈ 0.01)
Budget — Weak positive correlation, not a reliable predictor

Highlights:
 • Blumhouse Productions leads all production companies in median ROI — their low-budget model is highly efficient
 • Documentary and TV Movie genres show the highest median ROI
 • The 2020 ROI drop correlates with COVID-19’s impact on the film industry​​​​​​​​​​​​​​​​

