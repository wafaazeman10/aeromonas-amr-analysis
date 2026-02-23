## 🧠 Key Insights: Antimicrobial Resistance in Aeromonas (Malaysia, 2014–2020)
This document summarizes the key analytical insights derived from the exploratory data analysis (EDA) and Generalized Linear Model (GLM) applied to Aeromonas antimicrobial resistance data from clinical specimens in Malaysia between 2014 and 2020. The analysis focuses on resistance patterns across species, specimen types, antibiotic classes, and time, with the aim of supporting informed clinical decision-making and surveillance efforts.

### 1️⃣ Species Distribution and Prevalence

A total of 24,120 Aeromonas isolates were analyzed. Among these:
Aeromonas hydrophila was the most predominant species, accounting for 81.27% of isolates.
Aeromonas caviae represented 9.52% of isolates.
Aeromonas sobria accounted for 9.21% of isolates.
The dominance of A. hydrophila suggests its significant role in clinical Aeromonas-related infections in Malaysia during the study period. As such, resistance patterns observed in this species have important implications for treatment strategies and public health monitoring.

### 2️⃣ Specimen-Based Resistance Patterns
Clinical isolates were obtained from four main specimen sources:
- Blood – 49.19%
- Tissue – 20.66%
- Stool – 16.91%
- Swab – 13.24%

Although blood samples constituted nearly half of all isolates, resistance patterns varied considerably by specimen type.

#### Key observations:
- **Stool specimens** were consistently associated with higher resistance levels, particularly for Penicillins and Tetracyclines.
- **Tissue specimens** generally showed lower resistance, a finding later supported by GLM results.
- **Swab specimens** exhibited wide variability, including very high resistance to Penicillins.
- **Blood specimens** demonstrated relatively lower resistance to several antibiotic classes, including Aminoglycosides and Quinolones.

These findings highlight the importance of considering the infection site when selecting antibiotic therapy, as resistance profiles differ substantially across specimen types.

### 3️⃣ Antibiotic Class Effectiveness
Resistance rates varied markedly across antibiotic classes:

#### High resistance:
- Penicillins showed the highest resistance rates across all species and specimen types, often exceeding 90% in stool and swab samples.
- Beta-lactam + Inhibitors and Cephems also demonstrated consistently elevated resistance levels.

#### Low resistance:
- Aminoglycosides and Quinolones consistently exhibited low resistance across all specimen types and species.
- These classes remain among the most effective treatment options for Aeromonas infections during the study period.
  
The persistently high resistance to Penicillins raises concerns regarding their continued effectiveness and underscores the need for alternative therapeutic options.

#### 4️⃣ Species-Specific Resistance Profiles

Distinct resistance patterns were observed across Aeromonas species:

- Aeromonas hydrophila exhibited the highest resistance rates across multiple antibiotic classes, particularly Penicillins.
- Aeromonas caviae showed moderate resistance across most classes.
- Aeromonas sobria consistently demonstrated lower resistance, especially to Folate pathway inhibitors.

The lower resistance observed in A. sobria suggests that species-level identification can play a crucial role in guiding more targeted and effective antimicrobial therapy.

### 5️⃣ Resistance Trends Over Time (2014–2020)

Analysis of resistance trends over time revealed that:
- Resistance rates for most antibiotic classes remained relatively stable throughout the study period.
- Aminoglycosides and Quinolones maintained low resistance consistently, reinforcing their clinical reliability.
- Penicillins and Cephems showed a gradual decline in resistance, potentially reflecting changes in prescribing practices or resistance management strategies.
- Phenicols exhibited an increasing resistance trend, particularly in 2019–2020, raising concerns about emerging resistance risks.

While overall resistance stability is reassuring, the upward trend in Phenicols highlights the importance of continuous surveillance to detect early warning signs of resistance escalation.

### 6️⃣ Statistical Insights from Generalized Linear Models (GLM)
A binomial GLM was applied to identify significant predictors of antimicrobial resistance.

#### Significant predictors:
- **Antibiotic class** – Strongly associated with resistance outcomes.
- **Specimen type** – Stool specimens were associated with higher resistance, while tissue specimens were associated with lower resistance.
- **Species** – Aeromonas sobria was significantly associated with a lower probability of resistance.

#### Non-significant predictor:

- **Year of isolation** – Not statistically significant, indicating that resistance patterns did not change substantially over time.

Model refinement (removal of the year variable) resulted in:

- **Lower residual deviance**
- **Substantially reduced AIC**, indicating improved model fit without loss of explanatory power.

Residual diagnostic plots showed no major systematic patterns, suggesting that the GLM provided a reasonable and robust fit to the data.

### 7️⃣ Implications and Recommendations

Based on the findings:

- Penicillins should be prescribed with caution for Aeromonas infections due to consistently high resistance.
- Aminoglycosides and Quinolones remain reliable treatment options and should be considered where clinically appropriate.
- Species-specific and specimen-based treatment strategies can improve therapeutic effectiveness.
- The increasing resistance trend observed in Phenicols warrants closer monitoring.
- Continuous and comprehensive antimicrobial resistance surveillance programs are essential to detect emerging threats early.

### 📌 Final Takeaway

This analysis demonstrates that antimicrobial resistance in Aeromonas species is not uniform and is strongly influenced by antibiotic class, specimen type, and species. While resistance trends were largely stable between 2014 and 2020, the emergence of increasing resistance in certain antibiotic classes highlights the ongoing need for targeted research, improved diagnostics, and sustained surveillance to mitigate future risks.
