# Ultrasound-image-analysis-Project
This project focuses on breast ultrasound image analysis using machine learning models for anomaly detection and lesion segmentation. Implemented techniques include CNN, U-Net, VGG16, and ANN, with unsupervised and semi-supervised learning to achieve high accuracy in abnormality detection. Data preprocessing, augmentation, and model optimization are emphasized for improved patient care outcomes.
<br>
Background:
Early diagnosis of breast cancer through ultrasound images can significantly improve patient outcomes. Segmentation is crucial for identifying lesions within breast tissue, enabling precise anomaly detection. This project leverages both supervised and unsupervised learning for detecting anomalies in breast ultrasound images.

Project Objectives:-
Lesion Segmentation: Using the U-Net architecture to perform lesion segmentation on breast ultrasound images.
Unsupervised Learning for Anomaly Detection: Identify patterns within breast ultrasound images to detect anomalies without labeled data.
Semi-supervised Learning: Use limited labeled data to enhance model accuracy.
Model Training and Optimization: Deploy CNN, U-Net, VGG16, and ANN models to achieve high accuracy.
Data Preprocessing
Data preprocessing includes:

Cleaning and Normalization: Ensuring quality and consistency.
Augmentation: Applying techniques such as rotation, flipping, and scaling to increase data diversity.
Dimensionality Reduction: Using PCA for feature reduction and KMeans for clustering.
Model Architecture
U-Net: Used for lesion segmentation.
CNN and VGG16: For classification with feature extraction.
ANN: Applied for general anomaly detection.
Ensemble Models: Random Forest, AdaBoost, KNN, XGBoost, and Bagging were also tested to maximize accuracy.
Performance Metrics
The following metrics were used to evaluate the models:

Accuracy: Overall correctness.
F1 Score: Balance of precision and recall, crucial for medical contexts.
Kappa Score: Agreement between predictions and actual classifications.
Precision and Recall: Evaluated for each model, especially in detecting malignant cases.
Results
The models achieved high accuracy, with notable results:

U-Net and CNN: High accuracy for lesion segmentation.
VGG16 and PCA with KMeans: Revealed structural patterns in the data clusters.
Ensemble Methods: Random Forest, Bagging, and ANN stood out with high accuracy in anomaly detection.

Contributors
Khushita Milind Joshi
