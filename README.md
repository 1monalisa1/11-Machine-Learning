# FinTech • Unit 11 • Machine Learning
#### Columbia University • Fu Foundation School of Engineering & Applied Science
##### Contributor:  Lisa Esberger
##### Published:  March 8, 2021

## Risky Business


### Resampling
#### Naive Oversampling
![Oversampling-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report-Oversamplng.jpeg)

#### SMOTE Oversampling
![SMOTE-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_SMOTE-Oversampling.jpeg)

#### Undersampling
![Undersampling-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_Undersampling.jpeg)

#### Combination (Over & Under Sampling)
![Combination-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_Combination.jpeg)

##### *Which model had the best balanced accuracy score?*
* Naive Oversampling: 64.52%
* SMOTE Oversampling: 65.97%
* Undersampling: 65.97%
* Combination: 55.24%

##### *Which model had the best recall score?*
* Naive Oversampling: 66%
* SMOTE Oversampling: 65%
* Undersampling: 41%
* Combination: 56%

##### *Which model had the best geometric mean score?*
* Naive Oversampling: 65%
* SMOTE Oversampling: 66%
* Undersampling: 51%
* Combination: 61%

-----------------------------------------------------
### Ensemble Learning
#### Balanced Random Forest Classifier
![BRFC-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_BRFC.jpeg)

#### Ensemble Learning
![Ensemble-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_Ensemble.jpeg)

##### *Which model had the best balanced accuracy score?*
* Balanced Random Forest Classifier: 74.62%
* Ensemble Learning: 91.16%

##### *Which model had the best recall score?*
* Balanced Random Forest Classifier: 87%
* Ensemble Learning: 94%

##### *Which model had the best geometric mean score?*
* Balanced Random Forest Classifier: 74%
* Ensemble Learning: 91%

##### *What are the top 3 features?*
* "total_rec_pmcp"
* "total_pymnt"
* "total_pymnt_inv"
![BRFC-Chart](https://github.com/1monalisa1/11-Machine-Learning/blob/8d7da45a818299c6896b30e19f8dcf5e3ecf5b17/Resources/11-BRFC.jpeg)
