## Machine Learning Algorithms Portfolio

This repository provides a concise overview of essential machine learning algorithms commonly used in various data science tasks. The code and data for these examples are located in the ml_portfolio: [ML Datasets](https://github.com/ericyoc/ml_portfolio/tree/main/ml_data](https://github.com/ericyoc/ml_portfolio/tree/main/ml_data)) directory on GitHub.

**Supervised Learning Algorithms**

* **Multi-Linear Regression (MLR)**

  * **Summary:** Predicts a continuous output value based on a linear relationship with multiple input features.
  * **Dataset:** MLR FuelConsumptionCo2.csv
  * **Importance:** Simple to understand and interpret, efficient for linear data.
  * **Used for:** Sales forecasting, stock price prediction, risk assessment.

* **Logistic Regression**

  * **Summary:** Classifies data points into discrete categories (binary or multi-class) using a sigmoid function.
  * **Dataset:** Logistic Regression ChurnData.csv
  * **Importance:** Widely used for classification problems, handles binary and multi-class scenarios.
  * **Used for:** Spam filtering, image classification, customer churn prediction.

* **K-Nearest Neighbors (KNN)**

  * **Summary:** Classifies data points based on the majority vote of their k nearest neighbors in the training data.
  * **Dataset:** KNN teleCust1000t.csv
  * **Importance:** Easy to implement, performs well with high-dimensional data.
  * **Used for:** Image recognition, handwriting recognition, recommendation systems.

* **Support Vector Machines (SVM)**

  * **Summary:** Creates a hyperplane that maximizes the margin between data points of different classes.
  * **Dataset:** SVM cell_samples.csv
  * **Importance:** Efficient with high-dimensional data, performs well with small datasets.
  * **Used for:** Text classification, image segmentation, anomaly detection.

* **Regression Trees**

  * **Summary:** Tree-like models that make predictions based on a series of decision rules applied to input features.
  * **Dataset:** Regression Trees real_estate_data.csv
  * **Importance:** Easy to interpret, handles non-linear relationships well.
  * **Used for:** Customer segmentation, fraud detection, credit risk assessment.

**Unsupervised Learning Algorithms**

* **K-Means Clustering**

  * **Summary:** Groups data points into k clusters based on their similarity, often measured by distance.
  * **Dataset:** K-Means Clustering Cust_Segmentation.csv
  * **Importance:** Unsupervised learning for data exploration and segmentation.
  * **Used for:** Customer segmentation, market research, image compression.

**Deep Learning**

* **Regression with Keras**

  * **Summary:** Keras, a deep learning framework, can be used to build a variety of neural network architectures for regression tasks, allowing for the modeling of complex relationships between input features and continuous outputs.
  * **Dataset:** Regression with Keras concrete_data.csv
  * **Importance:** Highly flexible and powerful for complex non-linear relationships.
  * **Used for:** Time series forecasting, image recognition, natural language processing.

**Note:** This repository does not include the Iris dataset for multi-class classification. You can find the Iris dataset from various online sources.

**Choosing the Right Algorithm**

The selection of an appropriate machine learning algorithm depends on several factors, including:

* **Problem Type:** Supervised learning for prediction (classification or regression), Unsupervised learning for data exploration (clustering).
* **Data Characteristics:** Linearity, dimensionality, presence of noise or outliers.
* **Interpretability Needs:** Some algorithms offer clearer insights into the relationships between features and outputs.
* **Computational Resources:** Some algorithms require more training
