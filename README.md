# Digital Persuasion: Influencer Study

This repository contains the data analysis for a project exploring how social media influencers impact consumer purchasing decisions on short-video platforms.

## 📁 Folder Structure

- `code/` — R Markdown script for data cleaning, analysis, and visualization (`data_analysis_influencer_study.rmd`)
- `data/` — Original dataset (`latest_data_set.csv`)
- `outputs/` — To store generated graphs, tables, or processed data
- `reports/` — For storing the final academic paper or summary reports

## 📊 Project Summary

This study explores:
- The demographic makeup of short-video platform users
- Their interaction with influencers
- Purchase behavior influenced by these interactions

## 📜 Key Findings

- Influencer-followers are significantly more likely to make purchases (Chi-Squared p < 0.001)
- Emotional engagement is also significantly associated with following influencers
- Logistic regression confirms influencer-followers are **17x** more likely to buy a product

## ⚙️ How to Run the Analysis

1. Open `code/data_analysis_influencer_study.rmd` in RStudio or VS Code with R extensions.
2. Ensure the dataset is located at `data/latest_data_set.csv`.
3. Knit the file to generate the HTML report.

## 📦 Requirements

Install the following R packages if not already installed:

```r
install.packages(c("readr", "dplyr", "ggplot2"))
```  

## 📊 Outputs

This folder contains visualizations and charts generated from the analysis.  
These outputs were created while knitting the R Markdown file and include JPEGs and PNGs used in the final report or presentation.

## 📝 Report

The final academic paper is located in:  
`/reports/digital_persuasion_influencer_study_report.pdf`