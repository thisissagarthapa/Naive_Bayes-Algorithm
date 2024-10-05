# Naive Bayes Algorithm

## Project Overview
This project implements the Naive Bayes algorithm for predicting lung cancer based on patient age and smoking status using a dataset. The project explores both the Gaussian Naive Bayes and Multinomial Naive Bayes classifiers and evaluates their performance.

## Dataset
The dataset used in this project is named `large_health_data.csv` and contains the following columns:

- **Patient_ID**: Unique identifier for each patient (not used in modeling).
- **Age**: Age of the patient (numerical).
- **Smoking_Status**: Indicates whether the patient is a smoker or non-smoker (categorical).
- **Lung_Cancer**: Target variable indicating the presence (1) or absence (0) of lung cancer.

### Sample Data
| Patient_ID | Age | Smoking_Status | Lung_Cancer |
|------------|-----|----------------|-------------|
| 1          | 56  | Non-Smoker     | 0           |
| 2          | 69  | Non-Smoker     | 0           |
| 3          | 46  | Non-Smoker     | 0           |
| 4          | 32  | Non-Smoker     | 0           |
| 5          | 60  | Smoker         | 1           |

## Installation
Make sure you have the following libraries installed:
## Installation


```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend
