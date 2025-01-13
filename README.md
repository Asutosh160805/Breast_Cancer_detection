Breast Cancer Prediction Using Support Vector Machine (SVM)
This project demonstrates a machine learning approach to predict breast cancer diagnosis using the Breast Cancer Wisconsin dataset. The analysis includes feature visualization through heatmaps and bar graphs, as well as a Support Vector Machine (SVM) classifier to classify tumors as malignant or benign.

Features
Dataset: Breast Cancer Wisconsin dataset from sklearn.datasets.
Visualization:
Heatmaps to visualize feature correlations.
Bar graphs to display the distribution of malignant and benign tumors.
Model: Support Vector Machine (SVM) with a linear kernel.
Evaluation: Accuracy score and a detailed classification report.
Key Steps
Data Loading: The dataset is loaded using sklearn.datasets.load_breast_cancer.
Exploratory Data Analysis (EDA):
A heatmap is created to analyze the correlations between features.
Bar graphs display the class distribution in the dataset.
Data Splitting: The data is split into training and testing sets (80-20 split).
Model Training: An SVM classifier is trained on the training data.
Prediction: Predictions are made on the test set.
Evaluation: Model performance is evaluated using accuracy and a classification report.
Dependencies
Python 3.x
matplotlib (for plotting graphs)
seaborn (for heatmaps and advanced visualizations)
scikit-learn (for dataset, model, and evaluation)

Visualizations
Heatmap: Displays correlations between features to understand the relationships and identify the most significant ones for classification.
Bar Graph: Illustrates the distribution of malignant and benign cases in the dataset.
Results
The trained SVM achieves high accuracy in classifying tumors as malignant or benign. The visualizations help in understanding the data and identifying patterns that aid in model training.

Acknowledgments
This project uses the Breast Cancer Wisconsin dataset provided by scikit-learn.
