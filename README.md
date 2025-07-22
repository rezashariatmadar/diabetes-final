# Diabetes Health Indicators Analysis

A comprehensive data science project analyzing the **Diabetes Binary Health Indicators BRFSS 2015** dataset to identify key risk factors for diabetes and build predictive models.

## 📊 Project Overview

This project implements a complete data science pipeline including:
- **Exploratory Data Analysis**: Univariate, bivariate, and multivariate analysis
- **Statistical Testing**: Comprehensive hypothesis testing and effect size calculations
- **Machine Learning**: Multiple models with feature selection and interpretation
- **Visualization**: 50+ plots covering all aspects of the analysis

## 📁 Repository Structure

```
├── main.ipynb                    # Main analysis notebook
├── visualizations/               # Generated plots and charts
├── data/                        # Data directory
├── NOTEBOOK_DOCUMENTATION.md    # Comprehensive documentation
└── README.md                    # This file
```

## 🚀 Quick Start

1. **Download the dataset**:
   - Source: [Kaggle - Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
   - Place `diabetes_binary_health_indicators_BRFSS2015.csv` in the project root

2. **Install dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost shap statsmodels
   ```

3. **Run the analysis**:
   - Open `main.ipynb` in Jupyter Notebook/Lab
   - Run all cells sequentially
   - Check `visualizations/` directory for generated plots

## 📋 Key Features

- **Dataset Size**: 229,474 records with 22 health indicators
- **Analysis Scope**: Complete EDA to ML pipeline
- **Models**: Logistic Regression, Random Forest, XGBoost
- **Performance**: Best model achieves ~0.89 AUC
- **Interpretability**: SHAP values and partial dependence plots

## 📖 Documentation

### 📚 Complete Documentation
For detailed documentation including cell-by-cell explanations, usage examples, troubleshooting, and medical insights:
**→ [NOTEBOOK_DOCUMENTATION.md](NOTEBOOK_DOCUMENTATION.md)**

### ⚡ Quick Reference
For a concise overview, runtime estimates, and common customizations:
**→ [QUICK_REFERENCE.md](QUICK_REFERENCE.md)**

## 🔍 Key Findings

- **Primary Risk Factors**: BMI, Age, High Blood Pressure, General Health Status
- **Population Prevalence**: 13.4% overall, ranging from 7.5% (18-24) to 23% (70-74)
- **Model Utility**: High predictive accuracy suggests practical screening applications

## 🛠 Requirements

- Python 3.7+
- Jupyter Notebook/Lab
- 4GB+ RAM recommended
- ~15 minutes runtime for complete analysis

## 📊 Sample Output

The analysis generates comprehensive visualizations including:
- Distribution plots for all features
- Correlation heatmaps and VIF analysis
- PCA and t-SNE dimensionality reduction
- Model performance curves
- SHAP feature importance plots

---

*For detailed usage instructions, examples, and technical documentation, please refer to [NOTEBOOK_DOCUMENTATION.md](NOTEBOOK_DOCUMENTATION.md).*

