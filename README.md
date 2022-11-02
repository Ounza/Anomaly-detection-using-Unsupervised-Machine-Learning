# Anomaly-detection-using-Unsupervised-Machine-Learning

Financial fraud is a growing problem that poses a major threat to the security of the financial sector with severe consequences in the financial industry. 


The ability to apply machine learning to detect fraudulent transactions is a challenging process due to two major reasons–first, profiles of normal and fraudulent behaviors change frequently and second, financial fraud datasets are highly skewed.


This project focuses primarily on unsupervised machine learning techniques to solve the task of anomaly detection in financial data. In this study Autoencoder Neural Networks (AENNs), Principal Component Analysis (PCA), and Isolation Forest Algorithms were compared for their ability to detect anomalies in financial datasets.


One dataset was used throughout the study, namely "Synthetic Financial Dataset for Fraud Detection" by Lopez-Rojas publicly available in kaggle website. This dataset underwent detailed preprocessing to ensure the data was correctly formatted for the unsupervised machine learning models. These unsupervised learning techniques were applied on the preprocessed data. 


The performance of the techniques was evaluated based on accuracy, sensitivity, specificity, and precision. The results indicate that the AENN performed the best with an F1 score of 88%when predicting fraud in financial transactions with the greatest amount if training time whereas the PCA model performed second best with an F1 score of 79% while using a shorter amount of training time and a simpler implementation. A composite prediction system using both these models is suggested.

