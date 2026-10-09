# ANN Classification - Breast Cancer Prediction

## 📌 Project Overview

This project uses an Artificial Neural Network (ANN) to classify breast tumors as **malignant (cancerous) or benign (non-cancerous)** using the Breast Cancer Wisconsin dataset from Scikit-learn.

The project demonstrates the main steps of a Machine Learning workflow, from data exploration and preprocessing to model training, evaluation, and improvement.

## 🎯 Project Objectives

* Understand and explore the dataset.
* Check for missing values, duplicates, and outliers.
* Visualize the data and analyze feature correlations.
* Prepare features and target labels.
* Split the dataset into training and testing sets.
* Scale numerical features using StandardScaler.
* Build and train an ANN classification model.
* Evaluate the model using classification metrics.
* Experiment with different ANN configurations.
* Visualize training and validation performance.

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin dataset** available through Scikit-learn.

* **Number of samples:** 569
* **Number of features:** 30 numerical features
* **Number of classes:** 2
* **Target classes:** Malignant and Benign

The features describe characteristics of cell nuclei computed from digitized images of breast masses.

## 🛠️ Technologies and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

## ⚙️ Project Workflow

1. **Data Loading:** Load the dataset and inspect its structure.
2. **Data Cleaning:** Check missing values, duplicates, and data types.
3. **Exploratory Data Analysis (EDA):** Visualize class distribution, feature correlations, distributions, and potential outliers.
4. **Data Preparation:** Separate input features (X) from the target (y).
5. **Train-Test Split:** Split the data into training and testing sets.
6. **Feature Scaling:** Apply StandardScaler to numerical features.
7. **ANN Model Building:** Create a neural network using Dense layers, ReLU activation, Dropout, and a Sigmoid output layer.
8. **Model Training:** Train the model using Adam optimizer and Binary Cross-Entropy loss.
9. **Model Evaluation:** Evaluate performance using Accuracy, Precision, Recall, F1-score, and a Confusion Matrix.
10. **Model Improvement:** Compare different activation functions, optimizers, learning rates, network sizes, and regularization techniques.
11. **Visualization:** Plot training and validation loss and accuracy.

## 📈 Model Evaluation

The models are evaluated using:

* **Accuracy:** Measures the overall proportion of correct predictions.
* **Precision:** Measures the proportion of positive predictions that are correct.
* **Recall:** Measures how many actual positive cases are correctly identified.
* **F1-score:** Balances Precision and Recall.
* **Confusion Matrix:** Shows correct and incorrect classifications.

The notebook compares different ANN experiments to identify a promising model configuration.

## 📂 Project Structure

```text
ANN-Classification/
│
├── ANN_Assigment.ipynb
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download this repository.

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow jupyter
   ```

3. Open the notebook:

   ```bash
   jupyter notebook ANN_Assigment.ipynb
   ```

4. Run the notebook cells in order.

## ⚠️ Disclaimer

This project is for educational purposes only. It is not intended to provide medical diagnoses or replace professional medical advice.

## 👨‍💻 Author

**Marwan Tamer**

AI & Machine Learning Student

Interested in Machine Learning, Deep Learning, and Artificial Intelligence.
