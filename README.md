# Assignment 5: Data Cleaning and Predictive Modeling  
**Author:** Yukta Sanjiv Chavan  
**Date:** 12/04/2023  

---

## Project Overview  
This project focuses on cleaning, preprocessing, and building a predictive model to classify whether individuals have had an affair using the `affairs.csv` dataset. The workflow includes data inspection, balancing classes via downsampling, feature engineering, model tuning, and evaluation using a K-Nearest Neighbors (KNN) classifier.

---

## Dataset  
- **Name:** `affairs.csv`  
- **Description:** Contains 601 observations and 9 variables including demographic data and the outcome variable `affair` indicating whether an individual has had an affair.  
- **Variables:**  
  - affair (target variable)  
  - sex  
  - age  
  - ym (years married)  
  - child (yes/no)  
  - religious (scale)  
  - education  
  - occupation  
  - rate (marriage rating)

---

## Analysis Summary  
- Converted the `affair` variable from numeric (0/1) to categorical ("yes"/"no").  
- Performed exploratory data analysis to understand variable distributions and relationships.  
- Addressed class imbalance with downsampling of the majority class.  
- Used `tidymodels` for preprocessing, dummy encoding categorical variables, and normalizing numeric features.  
- Tuned KNN classifier, finding optimal neighbors (k=37).  
- Evaluated model on test data with confusion matrix, sensitivity, and specificity metrics.  
- Highlighted ethical considerations regarding predictive modeling of sensitive data.

---

## Project Structure  
- `affairs.csv` — Dataset file  
- `Data Cleaning and Predictive Modeling.pdf` — Detailed project report  
- `README.md` — Project overview and instructions  

---

## How to Run  
1. Load the dataset `affairs.csv` into R.  
3. Install required packages: `tidyverse`, `tidymodels`, `themis`, `skimr`, `kknn`.  
4. Knit the Rmd file or run the scripts sequentially in RStudio.

---

## Project Report  
A detailed project report titled **Data Cleaning and Predictive Modeling.pdf** is included. It documents the full analysis workflow, methodology, and results.

---


## Contact  
For any queries, please contact:  
**Yukta Chavan**  
Email: chavanyukta@gmail.com 
