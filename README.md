# Kepler

**1. Why did you choose the particular algorithm?**
LightGBM was selected for its efficient processing of large-scale datasets and its ability to achieve high accuracy with minimal data preprocessing. Furthermore, its strong performance with categorical features could be advantageous for this particular dataset.

**2. What are the different tuning methods used for the algorithm?**
In this analysis, I chose not to use any specific hyperparameter tuning techniques for the model. Instead, I utilized the algorithm's default settings. This choice was based on the initial data exploration and the dataset's complexity. While hyperparameter tuning could improve the model's performance, it typically requires more computational resources and time. Therefore, I focused on efficiency and simplicity in this case, aiming to establish a baseline evaluation of the model before considering more advanced optimization methods.

**3. What are the different tuning methods used for the algorithm?**
I contemplated utilizing the random forest classifier which reached an accuracy of 92%, but it took around 1.5 seconds to train. In addition, I explored the gradient boosting classifier, which also had an accuracy of 92%, but required significantly more time to train at about 15.6 seconds.

**4. What are the different types of metrics that can be used to evaluate the model?**
Confusion Matrix: A table summarizing correct and incorrect predictions by a classifier, including True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN).

Classification Report: A detailed report of classification metrics for each class in the dataset, including Precision, Recall, F1-Score, and Support.

Precision: The ratio of true positive predictions to all positive predictions.

Recall: The ratio of true positive predictions to all actual positive instances.

F1-Score: The harmonic mean of precision and recall, offering a balanced measure of classifier performance.

Support: The number of instances of each class in the true dataset.


