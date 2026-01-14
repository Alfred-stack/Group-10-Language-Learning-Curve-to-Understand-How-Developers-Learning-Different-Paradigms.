# Group-10- Analysis of the Language Learning Curves: Empirical Study of How Developers Learn Different Programming Paradigms

This repository contains the complete analysis pipeline, dataset structure, and reproducible code for the empirical research project titled:

“Language Learning Curves: An Empirical Study of How Developers Learn Different Programming Paradigms.”

The study investigates how developers learn various programming paradigms (Procedural/Imperative, Object-Oriented, Functional, Concurrent/Parallel, and Reactive/Event-Driven) using survey-based empirical data. The analysis was performed in Google Colab using Python, with fully documented steps for data cleaning, exploratory data analysis (EDA), statistical testing, learning-curve visualization, and qualitative thematic analysis.

Structure of the Repo
├── data/
│   ├── survey_responses.xlsx      # Raw survey data (17 responses)
│
├── notebooks/
│   ├── analysis.ipynb             # Full Google Colab notebook (analysis pipeline)
│
├── figures/
│   ├── *.png                      # Exported plots and visualizations
│
├── README.md                      # Project overview and documentation

Research Overview

Developers adopt programming paradigms at different speeds and with varying levels of difficulty. While much literature focuses on programming languages, very few studies examine learning curves associated with paradigms themselves.

This study aims to:

- Understand how developers begin learning new paradigms

- Quantify the difficulty, time investment, and proficiency progression

- Explore which resources and motivations drive successful learning

- Evaluate how experience with other paradigms influences learning

- Identify cross-paradigm patterns in developer learning curves

The dataset reflects a cross-sectional survey of 17 developers across multiple countries and roles.

## Analysis Features

The notebook performs:

### 1. Data Loading & Cleaning

Handling of inconsistent labels

Mapping ordinal responses to numerical scales

Normalizing categorical values

### 2. Exploratory Data Analysis (EDA)

Frequency distributions

Roles, education, experience

Resources used

Learning difficulty

### 3. Statistical Analysis

Suitable for small-sample non-parametric research:

Spearman Correlation between paradigm experience and learning difficulty

Kruskal–Wallis Test across groups

Mann–Whitney U Test for pairwise comparisons

Cross-tabulations examining relationships between variables

### 4. Learning Curve Construction

Plots of self-rated proficiency over time:

1 week

1 month

3 months

6 months

Present-day

### 5. Visualization

Includes:

Bar charts

Boxplots

Kernel density plots

Heatmaps

Comparative learning curve graphs

All plots are exportable to the figures/ directory.

### 6. Qualitative Analysis

Open-ended responses undergo:

Text cleaning

Tokenization

Thematic clustering

Frequency analysis of common themes

## Technologies Used

Python 3.x

Pandas (data manipulation)

NumPy (numeric operations)

Matplotlib / Seaborn (visualization)

SciPy (statistical tests)

NLTK / spaCy (text processing)

The project runs seamlessly in Google Colab, with no local installation required.

## How to Run the Analysis
Option 1 — Open in Google Colab (Recommended)

Upload the notebook (analysis.ipynb) to Google Colab

Upload the dataset to /content/

Run all cells sequentially

Export figures and results as needed

## Option 2 — Run Locally

Install dependencies:
pip install -r requirements.txt

then run: jupyter notebook notebooks/analysis.ipynb

## Reproducibility

The analysis is fully deterministic and reproducible.
All transformation steps are:

Explicit

Transparent

Sequentially documented in the notebook

No hidden preprocessing steps are applied.


## Citation

If you use this code or dataset, cite:

Alfred and Syia (2026). Language Learning Curves: An Empirical Study of How Developers Learn Different Programming Paradigms. 

Contact

For questions, suggestions, or collaborations:

Corresponding Author: Alfred Bobmanuel
Email: alfred_bob-manuel@uniport.edu.ng.

