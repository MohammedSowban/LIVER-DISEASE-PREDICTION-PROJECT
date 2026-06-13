# LIVER-DISEASE-PREDICTION-PROJECT
A machine learning-based liver disease prediction system developed using the Indian Liver Patient Dataset (ILPD). The project includes data cleaning, feature engineering, model training, and performance evaluation to assist in early disease detection.



## Problem Statement
**Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. This dataset was used to evaluate prediction algorithms in an effort to reduce burden on doctors.**
**Liver diseases are a major global health concern and can lead to severe complications if not detected early. Each patient’s health risk varies depending on several biological indicators such as bilirubin levels, enzyme activities, and protein ratios.
The goal of this project is to predict whether a patient is likely to have a liver disease based on their medical test results and demographic details.**

## Dataset

*   "Age" --> patient age
*  "Gender"--> male or female
*  "Total Bilirubin",
           "Direct Bilirubin" --> Bilirubin
*  "Alkaline Phosphotase","Alamine Aminotransferase","Aspartate Aminotransferase"--> Enzymes
* "Total Protiens"--> proteins
* "Albumin"-->to check how well the liver is working because the liver produces this protein
* "Albumin and Globulin Ratio"
* Target --> field used to split the data into two sets (1 : patient with  liver disease and 2: patient with no liver disease disease)



## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Workflow
1. Data Collection
2. Data Cleaning
3. EDA
4. Model Training
5. Evaluation

## Results
- Accuracy: 76%
- F1 Score: 84%

## Screenshots
<img src="image dashboard 1.png" width="800">
<img src="image dashboard.png" width="800">


## Future Improvements
The dataset was very small, containing only 583 observations, and a few outliers were removed or capped to retain valuable information.

It was highly imbalanced, with positive cases nearly three times the number of negative ones, affecting model generalization.

Although the model achieved a perfect score, its performance on larger and more diverse datasets is expected to decline due to overfitting and limited data diversity.

## Author
Mohammed Sowban
