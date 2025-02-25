# Predicting Death Events From Clinical Data Using Statistical Control Charts

## Authors  
**Muhammad Hamza Motiwala, Muhammad Adeel, Ahmed Bilal Nazim**  
Faculty of Computer Science, GIK Institute of Engineering Sciences and Technology  
Emails: u2022331@giki.edu.pk, u2022380@giki.edu.pk, u2022064@giki.edu.pk  

## Abstract  
This study applies statistical techniques, including covariance matrices, control charts (CUSUM, EWMA, Shewhart), and dimensionality reduction (SVD) to clinical data to predict mortality risk in heart disease patients. By analyzing variables like serum creatinine, ejection fraction, and survival time, we identify key mortality predictors and enhance patient monitoring.

## Keywords  
Linear Algebra, Control Charts, Process Monitoring, Dimensionality Reduction, Covariance Matrix, Mortality Prediction, Clinical Data Analysis.  

## Introduction  
Heart failure is a critical health concern, and early risk prediction improves clinical outcomes. This study explores patterns in heart failure patient data and uses control charts and dimensionality reduction to enhance mortality prediction.

## Methodology  
1. **Data Cleaning:** Handling missing values and standardizing data.  
2. **Covariance Analysis:** Identifying linear relationships between clinical variables.  
3. **Control Charts:** Monitoring trends using CUSUM (Platelets), EWMA (Serum Creatinine), and Shewhart (Ejection Fraction).  
4. **Dimensionality Reduction:** Using SVD to visualize high-dimensional data.

## Results and Discussion  
- **Covariance Matrix:** Identifies key predictors like serum creatinine (0.30 correlation with mortality) and ejection fraction (-0.27).  
- **CUSUM Chart:** Detects platelet count variability.  
- **EWMA Chart:** Monitors serum creatinine for kidney health issues.  
- **Shewhart Chart:** Assesses ejection fraction trends.  
- **SVD Visualization:** Shows clear separation between survival and non-survival groups.

## Conclusion  
Statistical tools effectively predict mortality in heart failure patients. Future work includes integrating machine learning for improved risk assessment.

## References  
1. Montgomery, D. C. (2009). *Introduction to Statistical Quality Control.* John Wiley & Sons.  
2. Jolliffe, I. T. (2011). *Principal Component Analysis.* Springer.  
3. UCI Machine Learning Repository – Heart Failure Dataset.  
4. Rousseeuw, P. J., & Leroy, A. M. (2003). *Robust Regression and Outlier Detection.* Wiley.
