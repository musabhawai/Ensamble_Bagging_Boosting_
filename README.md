# Ensemble Learning – Bagging & Boosting Examples

## 📌 Overview
This repository demonstrates the use of *Ensemble Learning* techniques — specifically *Bagging* and *Boosting* — to improve the performance of Decision Tree models.  
Both examples use the *Diabetes dataset* for prediction.

## 📖 About Ensemble Learning
Ensemble methods combine predictions from multiple models to create a more robust and accurate final model.  
- *Bagging (Bootstrap Aggregating)* – Reduces variance by training multiple models on different random samples and averaging predictions.
- *Boosting* – Reduces bias by sequentially training models, giving more weight to previously misclassified data points.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Decision Tree with Bagging
- Uses multiple Decision Tree classifiers trained on random subsets of data.
- Aggregates predictions for better stability and reduced overfitting.

### 2️⃣ Decision Tree with Boosting
- Trains Decision Trees sequentially.
- Adjusts sample weights to focus on misclassified data for improved accuracy.
