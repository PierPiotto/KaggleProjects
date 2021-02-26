# Piotto Pierfrancesco - Data Science Portfolio

### Recent Projects

## Project 1: [Customer Churn Analysis and Explanation - Project Overview](https://www.kaggle.com/pier994/interpretable-customer-churn-analysis)
* Created an algorithm that predicts which customers are churn-prone in a banking framework;
* Preliminary EDA performed using seaborn and matplotlib for visualization, scipy for statistical methods (such as $\chi^2$ and paired t test) and apriori algorithm;
* Cleaned and engineered features according to evidence gained and intuition;
* Built a first machine learning pipeline using decision trees. The choice for this particular algorithm is due to interpretability and various imbalance handling techniques are exploited;
* Built a second Machine Learning pipeline with XGBoost optimized using Random Search Cross Validation to reach the best model;
* Explained the latter model using SHAP techniques to understand the output and to allow business decisions.

## Project 2: [CNN for Leaf Desease classification competition](https://www.kaggle.com/pier994/how-to-build-a-simple-cnn-for-image-recognition)
This notebook is built on top of [Cassava Leaf Disease](https://www.kaggle.com/c/cassava-leaf-disease-classification) Kaggle competition. A convolutional neural network way built using PyTorch and by exploiting data augmentation, transfer learning and ensemble methods.  
All these features and capabilities are developed using ad-hoc Python classes and eventually assembled in the training stage.
Other features:
* Used a cross validation strategy using to train 5 base learners in the same script;
* Model trained using adaptive learning rate and autocast for performance improvement;
* Final accuracy $\sim 87%$ (winning solution $\sim 90%$).

## Project 3: [Geographical Analysis of NY House Dataset](https://www.kaggle.com/pier994/geographical-analysis-and-geopandas)
This is an EDA project, with no Machine or Deep Learning algorithms.
* Explored and cleaned the dataset;
* Visualized data using seaborn and geopandas;
* Performed various geographical like intersection and proximity to subways;
* Visualized plots of house prices according to variables built above (neighborhood or subway proximity aggregation).
