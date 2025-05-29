# Structural Equation Modeling with Latent Interactions (R Portfolio Example)

This project demonstrates the use of **structural equation modeling (SEM)** with **latent variable interactions** in R to evaluate how acculturation moderates the relationship between sleep disorder symptoms and depression in a national Latinx adult sample.

## ✨ Key Features
- **Latent variable modeling** with `lavaan`
- **Moderation via product indicators**
- **Interaction effect probing** using `semTools::probe2WayMC`
- **Missing data handled** using Full Information Maximum Likelihood (FIML)
- **Non-normality addressed** using MLR (robust standard errors)
- **Model fit evaluation** with RMSEA, CFI, χ²
- **Visualization** with `lavaanPlot` and `semPaths`

## 📁 Files
- `latent_moderation.Rmd`: Cleaned and anonymized R Markdown file

## 🧠 Relevance to Applied Data Science
This project mirrors real-world experimentation frameworks, like those used in product messaging and A/B testing. The interaction modeling approach shows how treatment effects (e.g., sleep symptoms) can vary across user segments (e.g., acculturation level)—similar to personalization or subgroup analysis.

## 🔧 Tools Used
- R, R Markdown, lavaan, semTools, modelsummary, MVN, kableExtra

## 🏁 Getting Started
To reproduce:
1. Clone this repository.
2. Open the `.Rmd` file in RStudio.
3. Download data from: This analysis uses publicly available data from Budd & Smith (2020), hosted on Harvard Dataverse: https://doi.org/10.7910/DVN/NABLZX
4. Knit to HTML or PDF (ensure you've read in data and required packages are installed).

## 📬 Contact
For questions, contact the author via GitHub or email (available on portfolio site).
