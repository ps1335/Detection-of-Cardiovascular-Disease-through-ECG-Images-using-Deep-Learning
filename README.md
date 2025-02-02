# Detection-of-Cardiovascular-Disease-through-ECG-Images-using-Deep-Learning
This project detects cardiovascular diseases from ECG images using machine learning. It classifies ECGs into Normal, Myocardial Infarction (MI), Abnormal Heartbeat (HB), and History of MI. The model applies PCA for feature extraction and a Voting Ensemble Classifier (KNeighborsClassifier, SVC, LogisticRegression, XGBClassifier) to enhance accuracy.
Cardiovascular diseases (CVDs) are among the leading causes of mortality worldwide, necessitating early and accurate diagnosis. This project presents a machine learning-based approach for automated detection of cardiovascular diseases from ECG images. The system classifies ECGs into four categories: Normal, Myocardial Infarction (MI), Abnormal Heartbeat (HB), and History of MI.
To achieve high accuracy, the project leverages Principal Component Analysis (PCA) for feature extraction and a Voting Ensemble Classifier combining KNeighborsClassifier, SVC, LogisticRegression, and XGBClassifier. The classification model is integrated into a user-friendly web application using Streamlit and FastAPI, allowing real-time ECG analysis and visualization.
This approach aims to assist medical professionals in early detection and diagnosis of CVDs, improving patient outcomes and reducing diagnostic errors. Future work includes enhancing model performance, incorporating additional datasets, and deploying the solution as a cloud-based service for broader accessibility.

Approach -  The project follows a structured pipeline to detect cardiovascular diseases from ECG images using machine learning techniques. The key steps include:
1. Data Collection & Preprocessing

ECG images are collected from relevant datasets.
Image preprocessing techniques such as grayscale conversion, noise reduction, and lead segmentation are applied.

2. Feature Extraction & Dimensionality Reduction

Principal Component Analysis (PCA) is used to extract meaningful features and reduce dimensionality, improving model efficiency.

3. Machine Learning Classification

A Voting Ensemble Classifier is employed, combining multiple machine learning models:
KNeighborsClassifier (KNN) for pattern recognition
Support Vector Classifier (SVC) for decision boundary optimization
Logistic Regression for probability-based classification
XGBClassifier for handling complex patterns and boosting accuracy

4. Web Application for Real-time Analysis

A Streamlit-based interface allows users to upload ECG images for analysis.
The system processes and classifies ECGs, displaying results including preprocessing steps, extracted features, and final predictions.

5. Evaluation & Performance Optimization

Model accuracy is assessed using metrics such as precision, recall, and F1-score.
Further improvements involve hyperparameter tuning, additional datasets, and deployment as a cloud-based service.

This systematic approach ensures efficient ECG image classification, enabling early and reliable cardiovascular disease detection. 🚀
