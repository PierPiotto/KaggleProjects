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
* Built data ingestion framework using albumentations;
* Built model architecture using Pytorch and transfer learning notion (with ResNet50 as source model);
* Trained the model using cross validation, adaptive learning rate and autocast for performance improvement;
* Built an ensemble model using the output model of each fold;

## Project 3: [Geographical Analysis of NY House Dataset](https://www.kaggle.com/pier994/geographical-analysis-and-geopandas)
This is pretty much an EDA project, with no Machine or Deep Learning algorithms.
* Explored and cleaned the dataset;
* Visualized data using seaborn and geopandas;
* Performed various geographical like intersection and proximity to subways;
* Visualized plots of house prices according to variables built above (neighborhood or subway proximity aggregation).
