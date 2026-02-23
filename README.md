## Antimicrobial Resistance Profiling of Aeromonas Isolates in Malaysia (2014–2020)
This project explores antimicrobial resistance (AMR) trends of Aeromonas species isolated from clinical specimens in Malaysia (2014–2020). The goal is to identify specimen sources and antibiotic classes with high resistance, compare resistance profiles between species, and determine significant predictors of resistance using Exploratory Data Analysis (EDA) and a Binomial Generalized Linear Model (GLM).

## 📂 Project Structure
- /data – Not publicly shared (restricted dataset from NIH Malaysia).
- /analysis – PNG charts generated during EDA and GLM reporting.
- /screenshots – Screenshots of pivot tables / Excel cleaning / transformation steps (non-sensitive).
- insights.md – Markdown summary of all key insights extracted from the analysis.

⚠️ Raw dataset is not uploaded due to data ownership and confidentiality restrictions (NIH Malaysia / IMR).

## 📊 Tools Used
- Microsoft Excel (Data cleaning & filtering)
- R / RStudio (EDA, GLM modelling, plots)
- GitHub (Documentation)

## 🎯 SMART Questions Answered
1. How do resistance rates vary by specimen type (blood, tissue, stool, swab)?
2. Which antibiotic classes show the highest and lowest resistance?
3. How do AMR profiles differ across species (A. caviae, A. hydrophila, A. sobria)?
4. Do resistance patterns change over time (2014–2020)?
5. Which predictors (species, specimen type, antibiotic class, year) are significant in a binomial GLM?

## ✅ Key Insights (Summary)
📌 Detailed interpretations and figures are provided in insights.md.
Aeromonas hydrophila accounted for over 80% of isolates. Penicillins showed the highest resistance across all species and specimen types, while Aminoglycosides and Quinolones remained effective. Stool specimens were associated with higher resistance, whereas tissue samples showed lower resistance. GLM results identified species, specimen type, and antibiotic class as significant predictors, while year was not significant. An increasing resistance trend in Phenicols highlights the need for continued monitoring.
