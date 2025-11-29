# Statistical Data Analysis: Penicillin, Butterfat, and Wealth Datasets

Welcome! This repository contains my Statistical Data Analysis assignment completed at the University of Toronto. The report was created using **R Markdown** and knitted to **HTML**, allowing all analyses, tables, and graphics to be viewed directly in a web browser.

---

## How to View

Click the link below to open the HTML file via GitHub Pages. You do not need GitHub to view the files; they will open in your browser like a regular website.

**→ _[Insert GitHub Pages link here]_**

---

## About the Project

This assignment explores classical statistical modeling, analysis of variance (ANOVA), linear modeling, interaction effects, and regression diagnostics using multiple real-world datasets:

- **Penicillin production data**  
- **Butterfat content of milk**  
- **Wealth of global billionaires**

All analyses are performed using **R**, with an emphasis on data visualization, model comparison, assumptions checking, and interpretation.

---

# Assignment Overview

## Q1. Penicillin Production Study

The penicillin data examine yield variability caused by four production processes (A, B, C, D) and blends of the raw material (corn steep liquor).

### Key Tasks

- **(a)** Produce visualizations exploring the distribution of penicillin yields across treatments and blends.  
- **(b)** Conduct hypothesis tests to determine whether treatment processes differ significantly.  
- **(c)** Assess blend effects and explain how blocking by blend improves precision and reduces variability.  
- **(d)** Examine model diagnostics to evaluate assumptions such as constant variance and normality.

---

## Q2. Butterfat Content in Canadian Cows

The butterfat dataset records butterfat percentage across five breeds and two age groups (young vs. mature cows).

### Key Tasks

- **(a)** Create appropriate plots to visualize differences by breed and age.  
- **(b)** Test for a **breed × age interaction**.  
- **(c)** Determine whether breeds and ages differ significantly on average.  
- **(d)** Present regression/ANOVA diagnostics and assess whether model assumptions are reasonable.  
- **(e)** Evaluate whether the top butterfat-producing breed is clearly superior or if uncertainty overlaps with the second-best breed.

---

## Q3. Butterfat Data (Mature Cows Only)

A subset of the butterfat dataset is analyzed to isolate the effect of breed among mature cows.

### Key Tasks

- **(a)** Plot and interpret differences in butterfat across breeds.  
- **(b)** Perform an ANOVA or linear model test for breed effects.  
- **(c)** Check diagnostics for violations of modeling assumptions.  
- **(d)** Generate pairwise comparison plots and identify which breed differences are not statistically significant.

---

## Q4. Fortune Billionaire Wealth

This dataset contains the wealth (in billions of dollars) of 232 billionaires.

### Key Tasks

- **(a)** Plot wealth vs. age with distinct plotting symbols for each geographic region.  
- **(b)** Re-plot wealth vs. age using **faceted panels**, one per region.  
- **(c)** Identify a suitable transformation of the wealth response (e.g., log) to support linear modeling.  
- **(d)** Determine the relationship between age, region, and wealth using regression.  
- **(e)** Check assumptions (linearity, residual variance, outliers) using diagnostic plots.

---

## Purpose of the Assignment

This assignment demonstrates:

- ANOVA and linear model construction  
- Use of blocking (blends) to reduce variability  
- Interaction assessment  
- Model diagnostics and assumption checking  
- Data visualization using base R and tidyverse  
- Transformation techniques for non-linear relationships  
- Interpretation of model outputs and uncertainty

---

## Thank You for Visiting!

Feel free to explore the HTML report and source code.  
If you have questions or suggestions, I’d be happy to connect!
