# Bargaining-Power-Along-Contract-Wage

**An Empirical Analysis of Wage Determinants and Bargaining Dynamics**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/PhysTony/Bargaining-Power-Along-Contract-Wage)
[![Quarto](https://img.shields.io/badge/Made%20with-Quarto-1D4ED8?logo=quarto)](https://quarto.org/)
[![R](https://img.shields.io/badge/Analysis-R-276DC3?logo=r)](https://www.r-project.org/)

## 📌 Overview

This project represents the **first empirical attempt** to measure changes in bargaining power across the deciles of MLB free agents. Using a novel econometric approach, we estimate how negotiation leverage varies across the wage distribution, providing new insights into labor market dynamics in professional baseball.

The analysis combines **quantile regression with instrumental variables** and a **within-estimator (fixed effects)** framework to identify causal effects while accounting for endogeneity. The project is structured as a fully reproducible research pipeline using **Quarto** documents.

The analysis is structured as a reproducible research pipeline using **Quarto** documents, ensuring transparency and clarity in every step—from data processing to final econometric estimation.

## 📊 Project Structure

```
├── Input-data/ # Raw and processed datasets
│ └── Free agents data # Player/contract information (hitters, pitchers, fielders)
├── Output-data/ # Generated results and tables
├── data-processing.qmd # Data cleaning, integration, and panel construction
├── model.qmd # Variable construction and model specification
├── econometric-analysis.qmd # Quantile IV fixed effects estimation and diagnostics
└── README.md # Project overview (this file)
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

*   **R** (version 4.0 or later)
*   **Quarto** (version 1.3 or later)
*   Required R packages: `tidyverse`, `fixest`, `modelsummary`, `ggplot2`

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/PhysTony/Bargaining-Power-Along-Contract-Wage.git
    cd Bargaining-Power-Along-Contract-Wage
    ```
2.  Open the project in RStudio or your preferred R environment.

### Running the Analysis

Execute the Quarto documents in the following order to reproduce the full study:

1.  `data-processing.qmd`
2.  `descriptive-statistics.qmd`
3.  `econometric-analysis.qmd`

You can render each file individually using:
```bash
quarto render data-processing.qmd
```

## 📈 Methodology

The project employs a combination of:

*   **Descriptive Analysis**: To understand the distribution of wages and key covariates.
*   **Econometric Modeling**: Using regression techniques (e.g., OLS, fixed effects) to estimate the impact of bargaining power and other factors on contract wages.
*   **Theoretical Model**: A conceptual framework that guides the empirical specification.

## 📁 Data

The `Input-data` folder contains the raw data on free agents. Due to the nature of the data, please refer to the original sources for replication. The `Output-data` folder stores all generated datasets and regression results.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## 📧 Contact

**PhysTony** - [GitHub Profile](https://github.com/PhysTony)

Project Link: [https://github.com/PhysTony/Bargaining-Power-Along-Contract-Wage](https://github.com/PhysTony/Bargaining-Power-Along-Contract-Wage)

---
