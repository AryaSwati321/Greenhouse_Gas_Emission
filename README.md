#*Emissions Classification using Machine Learning & Deep Learning*


📌 Overview

Project applies Machine Learning (ML) and Artificial Neural Networks (ANNs) to classify greenhouse gas emissions as high or low based on historical data. It includes:
>K-Means Clustering for emissions grouping.
>Logistic Regression for binary classification.
>Artificial Neural Network (ANN) for enhanced classification accuracy.



📂 Dataset
The dataset contains emissions data for the EU27/EU28 regions.
It includes emission levels across different years.



🛠️ Setup Instructions


1️⃣ Install Dependencies
-Ensure you have Python 3.8+ installed, then install the required libraries:
-pip install pandas numpy matplotlib seaborn scikit-learn tensorflow joblib

2️⃣ Clone the Repository

git clone https://github.com/AryaSwati321/Greenhouse_Gas_Emission


cd emissions-classification

3️⃣ Prepare the Dataset

Place your dataset files (emissions_EU27.csv, emissions_EU28.csv) inside the project folder.


##ANN MODEL
🔹 Trains an Artificial Neural Network for classification and saves the model.

💾 Model Saving & Loading

Logistic Regression Model: emissions_logistic_model.pkl

ANN Model: emissions_ann_model.h5



#To Load a Saved Model

import joblib
model = joblib.load('emissions_logistic_model.pkl')

from tensorflow.keras.models import load_model
model = load_model('emissions_ann_model.h5')



📊 Results & Evaluation
-Each model provides:
-Accuracy Score
-Classification Report
-Visualization of Clusters & Predictions




📧 Contact Team:


Arya Walse - aryaswati1907@gmail.com


Asmita Khatavkar - asmita.arnav.2501@gmail.com


Rituja Sonawane - ritujasonawane2004@gmail.com


Priya Kumari - sociallypriya@gmail.com


Siddhi Borawake - siddhiborawake2004@gmail.com


