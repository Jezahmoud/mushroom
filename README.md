# **Mushroom Classification**

The goal of this work is to use classification models to predict the class of mushroom, either poisonous or edible

### **Description**

The data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like ``leaflets three, let it be'' for Poisonous Oak and Ivy.

### Target Variable

classes: edible=e, poisonous=p

## **Dataset**

The dataset is collected from [kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification)

## The project outline

* Introduction
* Data Preprocessing
* EDA
* Machine Learning Models
* Model Evaluation
* Results and Conclusion

## Initial results

The outputs of machine learning models using the **One Hot Encoding** techniquewith **80/20** and **70/30** split strategy
| **Classification model** | **Accuracy (80/20)** | **Accuracy (70/30)** |
|---|---|---|
| **K-nearest Neighbors** | 100.0% | 100.0% |
| **Logistic Regression** | 99.88% | 99.92% |



The outputs of machine learning models using the **LabelEncoder** technique with **80/20** and **70/20** split strategy
| **Classification model** | **Accuracy (80/20)** | **Accuracy (70/30)** |
|---|---|---|
| **K-nearest Neighbors** | 99.88% | 99.88% |
| **Logistic Regression** | 93.85% | 94.3% |


## Authors

- [Jeza Allohibi](https://github.com/Jezahmoud)
- [Rehab Alaswad](https://github.com/rehabalaswad)
