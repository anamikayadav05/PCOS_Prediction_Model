# PCOS Prediction Model
This is a machine learning model that can be used to predict the likelihood of a patient having Polycystic Ovary Syndrome (PCOS).

## Background
PCOS is a common hormonal disorder among women of reproductive age. It affects approximately 5-10% of women worldwide and is one of the leading causes of infertility. Early detection of PCOS is crucial for effective management and treatment. This model aims to predict the likelihood of a patient having PCOS based on their clinical and biochemical parameters.

## Data
The model was trained on a dataset of 500 patients, which included their demographic information, clinical features, and biochemical parameters. The data was collected from patients who had been diagnosed with PCOS as well as those who were healthy.

## Model
In this project, we initially employed feature selection methods to handle different types of features. For categorical features, we utilized the chi-square test, while for continuous features, we applied the Lasso regression method.

Following the feature selection stage, we proceeded with feature extraction using Principal Component Analysis (PCA). PCA helps in reducing the dimensionality of the dataset while retaining the most relevant information.

Once the feature extraction was completed, we moved on to the classification phase. We implemented various classification algorithms, including logistic regression, random forest, K-nearest neighbors (KNN), and Gaussian naive Bayes. These algorithms were employed to predict and classify the target variable based on the selected features.

Overall, the project involved a comprehensive pipeline that encompassed feature selection, feature extraction, and classification using a range of algorithms to achieve accurate predictions.


## Usage
To use the model, simply input the patient's clinical and biochemical parameters into the model, and it will output a prediction of the likelihood of the patient having PCOS. The model can be integrated into clinical decision support systems or used as a standalone tool for PCOS diagnosis and management.

## Limitations
It is important to note that this model is not a substitute for a clinical diagnosis by a healthcare professional. It should be used as an aid to support clinical decision-making and not as a definitive diagnosis of PCOS.

## Conclusion
The PCOS Prediction Model is a powerful tool for predicting the likelihood of a patient having PCOS based on their clinical and biochemical parameters. With further validation and refinement, it has the potential to significantly improve the accuracy and efficiency of PCOS diagnosis and management.

## Source Of Dataset
https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos


