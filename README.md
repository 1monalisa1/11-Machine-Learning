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

#### *Which model had the best balanced accuracy score (arithmetic mean)?*
* Balanced Accuracy Score = (True Positive + True Negative) / (True Positive + True Negative + False Positive + False Negative)
  * SMOTE Oversampling: 65.97% (tied for best)
  * Undersampling: 65.97% (tied for best)
  * Naive Oversampling: 64.52%
  * Combination: 55.24%

#### *Which model had the best recall score?*
* Recall = (True Positives) / (True Positives + False Negatives)
  * Naive Oversampling: 66% (best)
  * SMOTE Oversampling: 65%
  * Undersampling: 41%
  * Combination: 56%

#### *Which model had the best geometric mean score (f-score)?*
* F-score = The geometric mean of precision and recall
  * SMOTE Oversampling: 66% (best)
  * Naive Oversampling: 65%
  * Combination: 61%
  * Undersampling: 51%

-----------------------------------------------------
### Ensemble Learning
#### Balanced Random Forest Classifier
![BRFC-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_BRFC.jpeg)

#### Ensemble Learning
![Ensemble-Report](https://github.com/1monalisa1/11-Machine-Learning/blob/23e4a1d279d9acf753e27b1fbc8b040f12e053ec/Resources/11-Report_Ensemble.jpeg)

#### *Which model had the best balanced accuracy score (arithmetic mean)?*
* Balanced Accuracy Score = (True Positive + True Negative) / (True Positive + True Negative + False Positive + False Negative)
  * Ensemble Learning: 91.16% (best)
  * Balanced Random Forest Classifier: 74.62%

#### *Which model had the best recall score?*
* Recall = (True Positives) / (True Positives + False Negatives)
  * Ensemble Learning: 94% (best)
  * Balanced Random Forest Classifier: 87%

#### *Which model had the best geometric mean score (f-score)?*
* F-score = The geometric mean of precision and recall
  * Ensemble Learning: 91% (best)
  * Balanced Random Forest Classifier: 74%

#### *What are the top 3 features?*
* "total_rec_pmcp"
* "total_pymnt"
* "total_pymnt_inv"

![BRFC-Chart](https://github.com/1monalisa1/11-Machine-Learning/blob/8d7da45a818299c6896b30e19f8dcf5e3ecf5b17/Resources/11-BRFC.jpeg)


-----------------------------------------------------
![Mona-Random-Forest](https://github.com/1monalisa1/11-Machine-Learning/blob/2baf96b044064bd46e50624bb0aca9a9de9dbbca/Resources/11-Mona-RandomForest.jpeg)
