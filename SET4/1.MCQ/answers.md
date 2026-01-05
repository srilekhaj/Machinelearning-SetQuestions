
Which machine learning technique allows models to continuously learn from new data?

0/1
a) Transfer Learning
 
b) Online Learning
c) Semi-Supervised Learning
d) K-Means Clustering
Correct answer
b) Online Learning

You're correct! The right answer is:

**b) Online Learning**

**Online learning** allows models to continuously learn from new data, typically in a sequential manner. This technique updates the model incrementally as new data arrives, which makes it suitable for situations where data is constantly being generated or updated (like in real-time systems).

Here’s a quick explanation of the other options:

* **a) Transfer Learning**: This involves transferring knowledge from one model (trained on a related task) to another task, usually to save on training time or resources. It's not focused on continuous learning from new data.
* **c) Semi-Supervised Learning**: This technique uses both labeled and unlabeled data for training, but it doesn’t focus on continuous learning.
* **d) K-Means Clustering**: This is a clustering algorithm, not a technique for continuous learning.

Would you like to dive deeper into any of these?


Which algorithm is commonly used in real-time fraud detection systems?

0/1
a) K-Means Clustering
b) Random Forest
 
c) Naïve Bayes
d) One-Class SVM
Correct answer
d) One-Class SVM
You're spot on! The correct answer is:

**d) One-Class SVM**

**One-Class SVM (Support Vector Machine)** is particularly effective in real-time fraud detection systems, as it is designed to identify outliers or anomalies in data. In fraud detection, normal transactions are abundant, but fraudulent ones are rare, making this algorithm ideal for detecting deviations from normal behavior.

Here’s a quick breakdown of the other options:

* **a) K-Means Clustering**: This algorithm is used for clustering and not typically suited for anomaly detection or fraud detection.
* **b) Random Forest**: While Random Forest is a powerful classifier and can be used for fraud detection, it’s not as commonly used for real-time anomaly detection compared to One-Class SVM.
* **c) Naïve Bayes**: This algorithm is based on probability and works well for classification tasks, but it's generally not the best choice for detecting rare fraud patterns.

One-Class SVM is ideal for cases where the majority of data is "normal," and you want to spot rare anomalies.

Are you working on a fraud detection project or just exploring this?


What is the role of a validation set in machine learning?

0/1
a) To test the final model before deployment
 
b) To tune hyperparameters and select the best model
c) To train the model
d) To replace the need for a test set
Correct answer
b) To tune hyperparameters and select the best model

The correct answer is:

**b) To tune hyperparameters and select the best model**

**Explanation:**
The **validation set** is used during model development to evaluate different models and **tune hyperparameters** (such as learning rate, number of layers, or regularization strength). It helps in selecting the model that performs best **without touching the test set**, which must remain unseen until final evaluation.

Why the others are incorrect:

* **a) To test the final model before deployment** → That is the role of the **test set**.
* **c) To train the model** → Training is done using the **training set**.
* **d) To replace the need for a test set** → A test set is still required for unbiased final evaluation.

✔️ Validation set = model selection and tuning
✔️ Test set = final performance check

Which algorithm is commonly used in real-time fraud detection systems?

0/1
a) K-Means Clustering
b) Random Forest
 
c) Naïve Bayes
d) One-Class SVM
Correct answer
d) One-Class SVM

The correct answer is:

**d) One-Class SVM**

**Explanation:**
**One-Class Support Vector Machine (SVM)** is widely used in real-time fraud detection because it is designed for **anomaly detection**. In fraud detection, most transactions are legitimate, and fraudulent ones are rare. One-Class SVM learns the pattern of normal behavior and flags deviations as potential fraud.

Why the other options are less suitable:

* **a) K-Means Clustering** → Primarily used for clustering, not real-time anomaly detection.
* **b) Random Forest** → Can be used for fraud detection, but it typically requires labeled fraud data and is not as specialized for anomaly detection.
* **c) Naïve Bayes** → Works well for classification but is less effective for detecting rare anomalies in real-time systems.

✅ **Correct answer: d) One-Class SVM**

Which machine learning algorithm is best suited for handling imbalanced datasets?

0/1
a) K-Means
 
b) Decision Trees
c) Random Forest with class weighting
d) Support Vector Machines with SMOTE
Correct answer
d) Support Vector Machines with SMOTE

The correct answer is:

**d) Support Vector Machines with SMOTE**

**Explanation:**
Imbalanced datasets occur when one class significantly outnumbers the other (common in fraud detection, medical diagnosis, etc.).

**SMOTE (Synthetic Minority Over-sampling Technique)** addresses this by generating synthetic samples for the minority class, helping balance the dataset. When combined with **Support Vector Machines (SVMs)**, it improves the model’s ability to correctly classify minority-class instances.

Why the other options are less suitable:

* **a) K-Means** → An unsupervised algorithm and not designed to handle class imbalance.
* **b) Decision Trees** → Can handle imbalance to some extent but often become biased toward the majority class.
* **c) Random Forest with class weighting** → This is a strong approach, but the question specifies the *best suited* option, and SVM with SMOTE directly addresses imbalance at the data level.

✅ **Correct answer: d) Support Vector Machines with SMOTE**
