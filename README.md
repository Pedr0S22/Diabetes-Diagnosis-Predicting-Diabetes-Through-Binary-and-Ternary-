# Diabetes Diagnosis - Predicting Diabetes Through Binary and Ternary Classification Approaches

Diabetes is a widespread chronic disease affecting hundreds of millions globally, with early detection playing a vital role in preventing severe complications. In 2021, approximately 537 million adults had diabetes, a figure expected to rise to 783 million by 2045. Type 2 diabetes, in particular, is linked to serious health issues such as cardiovascular disease, kidney failure, and neuropathy. Even prediabetes poses significant health risks. Despite its importance, early and accurate diagnosis remains challenging, especially at the population level.  

This project aims to develop tools and methods to support early detection and improve diagnostic accuracy for diabetes, ultimately contributing to better health outcomes.

## Project Overview

This project utilizes two preprocessed datasets, made available by [Alex Teboul](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset). The original data is sourced from the CDC’s Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey and can be found on [Kaggle](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system).

The datasets include responses from 253,680 U.S. adults, with 21 features related to demographics, lifestyle, and health indicators. These features are used to classify individuals as either:

- **Healthy** or **Diabetic** (binary classification dataset)
- **Healthy**, **Prediabetic**, or **Diabetic** (ternary classification dataset)

The primary distinction between the two datasets is the target labels, which vary depending on the classification type.


## Dataset Sources

- **[Project Datasets (Alex Teboul)](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)**
- **[Original Dataset (CDC BRFSS 2015)](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system)**

## Run Instructions

You must have python 3.11.5 version and jupyter kernel for this version installed. You will also need the following packages:

- **Scikit-Learn, TensorFlow, Optuna:** Utilized for constructing, training, optimizing, and evaluating machine learning models.
- **Pandas, NumPy, Itertools, Collections, Imblearn:** Used for data manipulation, preprocessing, and feature engineering tasks.
- **Copy:** Used for copying lists without conflicts.
- **SciPy (stats):** Utilized for statistical analysis in exploratory data analysis (EDA).
- **Matplotlib, Seaborn:** Used for visualizing data and understanding trends in EDA.

Additionally, download the datasets from the link provided above and place them in the same directory as this project.

## Further Information

Check the final report file for more informations about what was done and explored in this project

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
