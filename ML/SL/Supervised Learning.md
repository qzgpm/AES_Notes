- It is a type of machine learning where a model learns from **labeled data**, meaning each **input has a correct output**.
- The model compares its predictions with actual results and improves over time to increase accuracy.

### Features :
- Each input has a known output
- Adjusts itself to reduce prediction errors
- Make accurate predictions on new data
- *eg*: AES([[Automated Essay Scorer]]) in ASAP Data Set.

### Types of Supervised Learning:
#### 1. Classification:
- Where the output is a categorical variable
#### 2. Regression:
- Where the output is a continuous variable

### Working of Supervised Machine Learning:
#### 1. Collect Labeled Data
- Gather a data set where each input has a known correct output (label).
#### 2. Split the Data set
- Divide the data into training data (about 80%) and testing data (about 20%).
- The model will learn from the training data and be evaluated on the testing data.
#### 3. Train the Model
- Feed the training data (inputs and their labels) to a suitable supervised learning algorithm (like Decision Trees, SVM or Linear Regression).
- The model tries to find patterns that map inputs to correct outputs.
#### 4. Validate and Test the Model
- Evaluate the model using testing data it has never seen before.
- The model predicts outputs and these predictions are compared with the actual labels to calculate accuracy or error.
#### 5. Deploy and Predict on New Data
- Once the model performs well, it can be used to predict outputs for completely new, unseen data.

### Supervised Machine Learning Algorithms:
#### 1. [[Linear Regression]]:
- Used to predict continuous values (e.g., price, temperature).
- It is simple and widely used.
#### 2.  [[Logistic Regression]]:
- Logistic regression is a type of supervised learning classification algorithm that is used to predict a binary output variable.
#### 3.  [[Decision Trees]]:
- Uses a tree-like structure where each node represents a decision and each leaf represents an outcome.
#### 4. [[Random Forests]]:
- Combines multiple decision trees to improve accuracy and reduce over-fitting.
#### 5. [[Support Vector Machine]]:
- Separates data into classes using a boundary (hyperplane). Support vectors help define this boundary.
#### 6. [[K-Nearest Neighbors]]:
- Predicts based on the closest data points. Results depend on the value of k and distance measure.
#### 7. [[Gradient Boosting]]:
- Builds models step-by-step by correcting errors of previous models, creating a strong model.
#### 8. [[Naive Bayes Algorithm]]:
- Based on probability and Bayes’ Theorem, assuming features are independent of each other.
