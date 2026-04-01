# Stellar_Classification
Bagging, Random Forest, and Gradient Boosting for stellar classification

## 🛠️ Keywords & Skills

**Skills Applied:**  
`Random Forest` `Bagging` `Gradient Boosting` `Machine learning` `Classification`

**Main Libraries Used in R:**  
`randomForest` `gbm` 

## 🌳 Applied methods

This project addresses a **classification problem** using three **tree-based methods**: **Bagging**, **Random Forest**, and **Gradient Boosting**. These methods are widely used in machine learning for their ability to capture complex relationships in data and provide robust predictions.

- **Bagging (Bootstrap Aggregating):** This method builds multiple decision trees independently on randomly sampled subsets of the data and aggregates their predictions. Bagging primarily reduces model variance and improves stability.

- **Random Forest:** An extension of bagging, Random Forest introduces additional randomness by selecting a random subset of features at each split of each tree. This increases the diversity of trees and enhances the generalization of the model.

- **Gradient Boosting:** Unlike bagging and Random Forest, Gradient Boosting builds trees **sequentially**, where each new tree attempts to correct the errors of the previous ones. This approach reduces bias and can achieve high predictive accuracy, though it requires careful tuning to avoid overfitting.

## ⭐ Dataset & Results

This work explores the application of tree-based statistical learning methods for the **classification of stars**, using the dataset *Star Dataset for Stellar Classification* ([dataset](https://www.kaggle.com/code/faradayy/star-classification-giants-and-dwarfs/data)). The main goal is to classify stars as either **Dwarf** or **Giant**.

Three machine learning algorithms are introduced and compared: **Bagging**, **Random Forest**, and **Gradient Boosting**. The results show that **Random Forest** slightly improves accuracy compared to Bagging, but the difference is not substantial. **Gradient Boosting** achieves a similar accuracy to Random Forest.

The analysis also highlights that the most common classification error occurs when **Giant stars** are incorrectly classified as **Dwarf stars**.
