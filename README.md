## Projects

Special thanks to, [@kying18](https://github.com/kying18).

## 1. Supervised Learning (Classification) – MAGIC Gamma Telescope

### Description
A binary classification project built using the MAGIC Gamma Telescope dataset. The objective is to classify whether an observed event is a Gamma particle (signal) or a Hadron particle (background) using supervised machine learning techniques.

### Dataset
* **Name:** MAGIC Gamma Telescope Dataset
* **Source:** UCI Machine Learning Repository
* **Link:** https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope

### Models & Results

Five classification models were trained and evaluated on the same train/test split. Accuracy and per-class metrics are summarized below.

| Model | Accuracy | Precision (avg) | Recall (avg) | F1-score (avg) |
|---|---|---|---|---|
| K-Nearest Neighbors (k=5) | 0.82 | 0.82 | 0.80 | 0.80 |
| Logistic Regression | 0.77 | 0.78 | 0.76 | 0.75 |
| Naive Bayes | 0.72 | 0.71 | 0.64 | 0.65 |
| Support Vector Machine (SVM) | 0.86 | 0.86 | 0.84 | 0.84 |
| Neural Network | 0.87 | 0.87 | 0.87 | 0.87 |

The **Neural Network** achieved the best overall performance, closely followed by the **SVM**.

#### K-Nearest Neighbors
![KNN Results](images/kNN.jpg)

#### Logistic Regression
![Logistic Regression Results](images/Logistic_Regression.jpg)

#### Naive Bayes
![Naive Bayes Results](images/Naive_Bayes.jpg)

#### Support Vector Machine (SVM)
![SVM Results](images/SVM_s.jpg)

#### Neural Network
![Neural Network Results](images/Neural_Network.jpg)