# Iris_flower_classification

# PROJECT BACKGROUND
This project aims to classify iris flowers into three species (Iris Setosa, Iris Virginica, and Iris Versicolor) based on four key botanical measurements:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Using machine learning classification algorithms, the models analyze these four variables to accurately predict the iris species. The project compares two different classification algorithms and evaluates their performance.



# DATA STRUCTURE AND INITIAL CHECKS
<img width="595" height="143" alt="Screenshot 2025-07-28 at 8 06 22 AM" src="https://github.com/user-attachments/assets/43ab3505-ab2d-4d17-b267-75534b3087a8" />


# EXECUTIVE SUMMARY
Exploratory data analysis reveals distinct patterns in the iris dataset:

Iris Setosa is easily distinguishable from the other two species based on its measurements
Iris Virginica and Iris Versicolor show some overlap in characteristics, making them more challenging to differentiate in certain cases
The dataset contains 150 balanced samples (50 per species) with no missing values

<img width="825" height="714" alt="Screenshot 2025-07-28 at 8 16 08 AM" src="https://github.com/user-attachments/assets/64c8a04c-1f9a-40ff-9467-3ed2dd1fad11" />




# MODEL 1 -> K-NEAREST NEIGHBORS CLASSIFIER (KNN)
### What is KNN
KNN is a distance-based algorithm that classifies samples based on similarity
When predicting a new sample, it finds the 'k' most similar training samples (neighbors)
The majority class among these neighbors becomes the predicted class
In this implementation, the optimal k-value was determined through experimentation

### Accuracy -> 100%

# MODEL 2 -> SUPPORT VECTOR CLASSIFIER (SVC)
### What is SVC
SVC finds the optimal hyperplane that maximally separates different classes
It transforms the input space to a higher dimension to handle non-linear relationships
Uses kernel functions to efficiently compute separation boundaries
Margin maximization helps with generalization to new data

### Accuracy -> 98%

# CONCLUSION
The K-Nearest Neighbors algorithm achieved perfect classification accuracy (100%) on the iris dataset, demonstrating that iris species can be reliably predicted using these four botanical measurements. This simple yet powerful model outperformed the Support Vector Classifier (98% accuracy) for this particular classification task.




