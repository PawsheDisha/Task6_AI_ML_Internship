# Task6_AI_ML_Internship

**K-Nearest Neighbors (KNN) Classification**

**Objective**

To understand and implement the K-Nearest Neighbors (KNN) algorithm for solving a classification problem using Scikit-learn.


**Tools & Technologies Used**

    -Python

    -Pandas

    -NumPy

    -Matplotlib

    -Scikit-learn


**Dataset**

The project uses a CSV dataset where:

Independent variables are feature columns.

The last column is considered the target (class label).


**Steps Performed**

1️⃣ Import Libraries

Necessary libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn were imported for data handling, visualization, and model building.

2️⃣ Load Dataset

The dataset was loaded from a CSV file using Pandas and converted into a DataFrame for processing.

3️⃣ Separate Features and Target

Feature columns (X) and the target column (y) were separated to prepare the data for training.

4️⃣ Train-Test Split

The dataset was divided into training and testing sets to evaluate the model on unseen data.

5️⃣ Feature Scaling

StandardScaler was applied to normalize the features since KNN is a distance-based algorithm and sensitive to scale.

6️⃣ Train KNN Model

KNeighborsClassifier was used to train the model by selecting a value of K (number of neighbors).

7️⃣ Make Predictions

The trained model was used to predict class labels for the test dataset.

8️⃣ Model Evaluation

The model’s performance was evaluated using accuracy score and confusion matrix.

9️⃣ Hyperparameter Tuning

Different values of K were tested to determine the optimal number of neighbors.

🔟 Decision Boundary Visualization

A decision boundary was plotted (for 2 features or using PCA) to visualize how the model classifies data points.


**Evaluation Metrics**

Accuracy Score

Confusion Matrix

Accuracy vs K Graph

Decision Boundary Plot


**Conclusion**

The KNN model was successfully implemented and evaluated. Proper feature scaling and selecting the right value of K significantly improve model performance.
