# Heart-Disease-Prediction
Heart Disease Prediction using Machine Learning

This is my IMLA MiniProject

<hr />

## About Dataset
Context:
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

Content:
Attribute Information: > 1. age > 2. sex > 3. chest pain type (4 values) > 4. resting blood pressure > 5. serum cholestoral in mg/dl > 6. fasting blood sugar > 120 mg/dl > 7. resting electrocardiographic results (values 0,1,2) > 8. maximum heart rate achieved > 9. exercise induced angina > 10. oldpeak = ST depression induced by exercise relative to rest > 11. the slope of the peak exercise ST segment > 12. number of major vessels (0-3) colored by flourosopy > 13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

<hr />

## Exploratory Data Analysis

### Correlation Matrix
![Heatmap](/Images/CorrelationMatrix.png?raw=true "Graph")


![EDA](/Images/EDA.png?raw=true "Graph")

## K-Nearest
![K-Nearest](/Images/knearest.png?raw=true "Graph")

## K-Means Clustering
![K-Means](/Images/Kmeans.png?raw=true "Graph")

## Decision Tree
![Decision Tree](/Images/decisiontree.png?raw=true "Graph")

## Random Forest
![Random Forest](/Images/randomforest.png?raw=true "Graph")

## Comparison
```
k-Nearest Neighbours test recall: 1.0
k-Nearest Neighbours test precision: 0.9798657718120806
k-Nearest Neighbours test accuracy: 0.9902597402597403
Decision Tree test recall: 1.0
Decision Tree test precision: 0.959731543624161
Decision Tree test accuracy: 0.9805194805194806
Random Forest test recall: 1.0
Random Forest test precision: 0.9261744966442953
Random Forest test accuracy: 0.9642857142857143
Classifier with best recall: k-Nearest Neighbours
```
