# Data Science Nanodegree Project – Nutrient Analysis and Energy Prediction

## Introduction

This repository contains the first project of the **Data Science Nanodegree (DSND)** program.  
The goal is to explore and model nutritional data, performing data analysis, preprocessing, and predictive modeling to understand how different nutrients contribute to total energy content.

## Dataset

The dataset comes from [FoodData Central](https://fdc.nal.usda.gov/download-datasets), an open database that provides detailed information about food composition, including macro and micronutrients, for a wide range of food categories.

## Goals

- To perform exploratory data analysis (EDA) to understand feature distributions and relationships with the target variable.  
- To clean and preprocess the data (handle missing values, outliers, and feature transformations).  
- To train and evaluate predictive models for estimating total energy.  
- To document methods, modeling decisions, and results in structured notebooks and reports.  
- To communicate findings in a clear, non-technical way through a public article.  

## Repository structure

- `data/`
  - `raw/` — original unmodified data.  
  - `processed/` — cleaned and feature-engineered data ready for analysis.  
- `/data_analysis.ipynb` — Jupyter notebooks for EDA, experiments and reporting.  
- `models/` — trained models ans checkpoints.
- `README.md` — project overview and documentation.  

## Getting Started

### Dependencies

```
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 1.0.0
matplotlib >= 3.4.0
joblib >= 1.4.0
seaborn >= 0.13.0
scipy >= 1.13.0
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/viniciusagsa/dsnd-project-01
cd dsnd-project-01
```

2. Install Python packages:
```bash
pip install pandas numpy scikit-learn matplotlib joblib seaborn scipy
```

3. Launch notebook:
```bash
jupyter notebook starter/data_analysis.ipynb
```

---

## Results and metrics

- Model performance metrics (e.g., MSE, RMSE, R²) are reported in `data_analysis.ipynb`.  
- Save trained models in `models/`.
- The non-technical summary and stakeholder communication are available in the accompanying article: [How Machine Learning Reveals What Really Powers Our Food](https://medium.com/@viniciusagsa/how-machine-learning-reveals-what-really-powers-our-food-e206945138a3).

## Final comments

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/viniciusagsa/) or through my [GitHub profile](https://github.com/viniciusagsa) if you’d like to discuss the project or collaborate on similar topics.

### Acknowledgements

I would like to express my gratitude to all the open-source developers and data providers who made this project possible.  
Special thanks to the contributors of Python libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn, which were fundamental to the implementation of this analysis.

- Data Source: [FoodData Central](https://fdc.nal.usda.gov/download-datasets)
- This project was inspired by the [Udacity Data Science Nanodegree Program](https://www.udacity.com/).

### License

[License](LICENSE)
