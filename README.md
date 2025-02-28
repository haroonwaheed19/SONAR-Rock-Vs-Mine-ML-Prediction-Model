SONAR Rock vs Mine Prediction Model

This repository contains an ML model for classifying SONAR signals as either Rock or Mine using Logistic Regression. The model is trained on the SONAR dataset, which contains 60 feature values extracted from reflected sound waves.

📌 Project Overview

Underwater objects, such as rocks and metal mines, reflect sonar waves differently. This project applies Machine Learning (ML) techniques to classify sonar signals based on their frequency response patterns.

🔹 Dataset

    The dataset contains 208 samples with 60 numerical features.
    Each sample is labeled as either:
        Rock (R) – if the sonar signal reflects off a rock.
        Mine (M) – if the sonar signal reflects off a metal mine.

🔹 Machine Learning Model Used

The primary model used for classification is Logistic Regression, but other models can also be implemented.

🛠️ Tech Stack

    Python
    NumPy
    Pandas
    Scikit-Learn

📊 Model Training Process

    Load and preprocess data
        Read the dataset using pandas.
        Normalize feature values for better training performance.

    Train-Test Split
        The dataset is split into training (80%) and testing (20%) sets using train_test_split().

    Feature Scaling
        Standardize features using StandardScaler to improve model efficiency.

    Model Selection & Training
        Train a Logistic Regression model.

    Model Evaluation
        Measure accuracy

📂 Project Structure

📂 SONAR-Rock-vs-Mine

│── 📄 dataset.csv            # SONAR dataset file

│── 📄 sonar_model.ipynb       # Jupyter Notebook with model training & evaluation

│── 📄 README.md               # Project Documentation


📈 Model Performance

Metric	Score

Accuracy	83%

🚀 Future Enhancements

✅ Implement Random Forest and SVM for comparison.

✅ Use GridSearchCV for hyperparameter tuning.

✅ Deploy the model using Flask API or Streamlit.

📌 References

    UCI Machine Learning Repository - SONAR Dataset
    Scikit-learn Documentation

