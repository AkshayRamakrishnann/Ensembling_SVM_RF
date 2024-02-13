# Enhancing Classification Accuracy using Ensemble Learning: A Case Study with SVM and Random Forest
![git](https://github.com/AkshayRamakrishnann/Ensembling_SVM_RF/assets/111365771/57d1b038-4589-44a4-9f2e-1254a21e8d03)

This repository delves into the realm of ensemble learning, showcasing how we can harness the combined power of Support Vector Machines (SVM) and Random Forest classifiers to predict the occurrence of death events in the Heart Failure Clinical Records dataset. By leveraging their individual strengths, we aim to surpass the predictive accuracy achievable by either model alone.

## Project Goals:

**1. Dive Deeper into the Data:** We'll embark on a journey of exploration, unveiling patterns and hidden gems within the Heart Failure Clinical Records dataset. Statistical summaries and insightful visualizations will be our tools to decipher the characteristics of patients and the intricacies of the death event variable.

**2. Model Training Powerhouse:** We'll establish two formidable models – an SVM, renowned for its decision boundary prowess, and a Random Forest, boasting an ensemble of decision trees. Both will be meticulously trained on the carefully prepared training data, absorbing valuable knowledge about predicting death events.

**3. Prediction Fusion:** Harnessing the wisdom of both models, we'll employ a cunning strategy – taking the mode (most frequent prediction) of their individual outputs for each test sample. This fusion aims to capitalize on their complementary strengths, potentially leading to enhanced predictive accuracy.

**4. Performance Evaluation under the Microscope:** We won't leave any stone unturned when assessing our combined model's performance. A battery of metrics will be deployed, including accuracy, precision, recall, F1-score, ROC AUC, Cohen's kappa, and Matthews correlation coefficient, providing a comprehensive evaluation of its effectiveness.

**5. Visualizing the Journey:** To gain a deeper understanding of the model's decision-making process and classification trends, we'll create a confusion matrix, revealing the distribution of true and predicted labels, and an ROC curve, depicting the trade-off between true positive and false positive rates.

## Introduction

Cardiovascular diseases, specifically heart failure, pose a significant global health burden. Accurately predicting death events associated with heart failure is crucial for early intervention and improved patient outcomes. Machine learning offers promising tools for achieving this aim by leveraging complex relationships within clinical data. This study explores the potential of ensemble learning, combining Support Vector Machines (SVMs) and Random Forests, to enhance the accuracy of death event prediction in the Heart Failure Clinical Records dataset.

## Methods and Materials
### Data:
The Heart Failure Clinical Records dataset was utilized, containing comprehensive clinical information on patients. The target variable was the binary indicator of death event occurrence (0 or 1).

### Preprocessing:
Data cleaning and preprocessing were performed to handle missing values and ensure data quality. Feature engineering techniques were considered to improve feature representation.

### Model Development:
#### Individual Models:

##### SVM: 
An SVM with a linear kernel was trained to learn a hyperplane separating patient data based on death event occurrence.

##### Random Forest:
A Random Forest with 100 decision trees was constructed, capturing diverse prediction perspectives based on randomly selected feature subsets.
Ensemble Learning: Predictions from both models were combined using the mode (most frequent prediction) for each test sample, aiming to leverage their complementary strengths.

## Evaluation:
Performance was evaluated using standard classification metrics: accuracy, precision, recall, F1-score, ROC AUC, Cohen's kappa, and Matthews correlation coefficient. Confusion matrix and ROC curve were visualized for further analysis.

![confusion](https://github.com/AkshayRamakrishnann/Ensembling_SVM_RF/assets/111365771/e4b87111-350b-4796-b001-3791faa631f5)


## Results and Discussion:
The combined model achieved an accuracy of 71.66%, exceeding the individual performances of SVM and Random Forest. Other metrics also demonstrated improvements, suggesting the effectiveness of ensemble learning. Confusion matrix and ROC curve provided deeper insights into the model's decision-making and classification trends.

## Conclusion:
This study demonstrated the potential of ensemble learning to enhance the accuracy of death event prediction in the Heart Failure Clinical Records dataset. Combining SVM and Random Forest offered improved performance compared to individual models. Further exploration of diverse ensemble techniques and feature engineering strategies can potentially lead to even more accurate and insightful models. These findings contribute to the advancement of machine learning applications in predicting critical clinical outcomes, potentially aiding in early intervention and better patient care.


