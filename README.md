# Financial-Health-Prediction-and-Feature-Importance-Analysis-for-Enterprises
# Bankruptcy Prediction
## Version 1:
1. Used all features of the data, i.e., 96.
2. Conducted data exploration, cleaning, and preprocessing.
3. Trained various classification models (Logistic Regression, Random Forest, Decision Tree, Gradient Boosting) with high accuracy but low precision and recall due to class imbalance.
4. Best model is Gradient Boosting classifier with accuracy 0.97 
## Version 2:
1. Addressed class imbalance using random oversampling (ROS).
2. Achieved better evaluation metrics.
3. Best model is still GBC with accuracy 0.97 but with improved precision and recall scores.

## Version 3:
1. Train a Random Forest Classifier (RFC).
2. Performed feature importance analysis and selected the top 20 important features (Feature Selection Method 1).
3. Re-trained models with the selected features and achieved good results.
4. GBC performed well with accuracy 0.96 and excellent precision and recall scores.
5. F1 scores for both the classes of tharget variable is 0.96
6. Then, we considered features with a correlation > 0.7 (Feature Selection Method 2).
7. This reduced the feature set to 51 features.
8. Trained models with this reduced feature set and achieved good results.
