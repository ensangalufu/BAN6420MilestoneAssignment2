BAN6420MilestoneAssignment2
Submission for milestone assignment 2 On BAN6420 Course
Ernest Amon Nsangalufu
Msc in Data Analytics
Leaner ID :144867

PCA on Breast Cancer Dataset with Logistic Regression 
Overview
This project demonstrates how to apply Principal Component Analysis (PCA) to the breast cancer dataset from scikit-learn, reducing it to two components for dimensionality reduction. Optionally, logistic regression is used to classify tumors as malignant or benign based on the reduced data.

Prerequisites
Ensure you have the following Python libraries installed:
[ pip install numpy pandas scikit-learn matplotlib ]

>Steps
Load Dataset: Breast cancer data is loaded using load_breast_cancer().
Standardize Features: The features are scaled using StandardScaler to have zero mean and unit variance.
Apply PCA: Reduce data to two principal components using PCA(n_components=2).
Logistic Regression (Optional): A logistic regression model is trained on the reduced data and evaluated using accuracy.
Visualization (Optional): Plot the two PCA components in a 2D scatter plot.

>Running the Code
To execute the script:
[ python main.py ]

>Example Output:
Accuracy of Logistic Regression with PCA: 0.9123
A scatter plot showing the PCA components is displayed if the optional visualization step is enabled.

>File Structure
main.py: Main script containing the code for PCA and optional logistic regression.
README.md: Documentation.

>Dataset
The breast cancer dataset includes:
569 samples with 30 features.
2 target classes: Malignant (1) and Benign (0).

>Conclusion
This project showcases PCA for dimensionality reduction and logistic regression for classification, offering insights into applying these techniques to high-dimensional datasets.


