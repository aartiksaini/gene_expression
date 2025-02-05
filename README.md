```markdown
# Gene Expression Analysis

## Overview
This project focuses on analyzing gene expression data to explore relationships between gene activity and individual health conditions. The dataset consists of gene expression measurements for multiple individuals, categorized into:

- Healthy Controls
- Stationary Patients
- Chronically Diseased Patients
- Recovered Patients

The goal is to identify patterns and relationships among genes and health conditions using statistical and machine learning techniques.

## Dataset
The dataset includes expression measurements for a large pool of genes across different patient groups. The objective is to conduct exploratory data analysis and apply statistical tests to validate hypotheses about gene expression differences among these groups.

## Analysis Workflow
The complete analysis is documented in `gene_expression.ipynb`, covering:

1. **Exploratory Data Analysis**
   - Data cleaning and preprocessing
   - Summary statistics
   - Visualization of gene expression distributions
   
2. **Correlation Analysis**
   - Investigating relationships between group of patient condition
   
3. **Feature Scaling & Dimensionality Reduction**
   - Standardization of features
   - Principal Component Analysis (PCA)
   
4. **Clustering Analysis**
   - Identifying potential clusters in gene expression patterns
   
5. **Differential Expression Analysis**
   - Identifying significant differences in gene expression across health conditions
   - ANOVA and Tukey HSD as post-hoc ANOVA
   
6. **Phenotype Predictive Modeling**
   - Building models to predict health conditions from gene expression data
   - Techniques used:
     - **Logistic Regression**
     - **Random Forest**
     - **Support Vector Machine (SVM) with a linear kernel**


### General Data Handling
- `numpy`
- `pandas`

### Machine Learning & Statistical Analysis
- `scipy`
- `scikit-learn`
- `statsmodels`

### Visualization
- `matplotlib`
- `seaborn`

```

