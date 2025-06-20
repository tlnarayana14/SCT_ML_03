# SCT_ML_03
Support Vector Machine (SVM) is a powerful and widely-used supervised machine learning algorithm that is primarily used for classification tasks, though it can also be adapted for regression.

SVM works by finding the optimal hyperplane (decision boundary) that best separates data points of different classes. The main goal is to maximize the margin between the closest data points of each class, known as support vectors.

Key Points :

Hyperplane: A decision boundary that separates different classes. In 2D, it’s a line; in 3D, it’s a plane; and in higher dimensions, it's a hyperplane.

Margin: The distance between the hyperplane and the nearest data points from each class. SVM aims to maximize this margin.

Support Vectors: The critical data points closest to the hyperplane; they “support” or define the decision boundary.

Kernels: SVM can handle linearly and non-linearly separable data using different kernel functions like:

linear (default for linearly separable data)

rbf (Radial Basis Function)

poly (polynomial)

sigmoid


Uses : 
Works well in high-dimensional spaces (e.g., text classification using TF-IDF).

Effective when there’s a clear margin of separation between classes.

Robust to overfitting, especially in high-dimensional feature spaces.
