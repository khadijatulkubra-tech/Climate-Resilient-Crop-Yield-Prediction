# 🌱 Climate-Resilient Crop Yield Prediction Using CNN

> A Computer Vision Course Project that predicts crop yield using a Convolutional Neural Network (CNN) and agricultural data.

---

## 📌 Project Overview

Crop yield prediction is an important application of Artificial Intelligence in smart agriculture. Accurate prediction helps farmers and agricultural organizations make informed decisions regarding crop planning, irrigation, and resource management.

This project develops a **CNN-based crop yield prediction model** using an agricultural dataset containing environmental and farming-related features. The complete pipeline includes data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 🎯 Objectives

- Perform data preprocessing on agricultural data.
- Convert categorical features into numerical values.
- Normalize numerical features using Min-Max Scaling.
- Develop a CNN-based prediction model.
- Evaluate model performance using RMSE.
- Visualize prediction results and training performance.

---

## 📂 Dataset

**Source:** Kaggle Crop Yield Dataset

The dataset contains agricultural and environmental attributes such as:

- Region
- Soil Type
- Crop
- Rainfall (mm)
- Temperature (°C)
- Fertilizer Usage
- Irrigation Usage
- Weather Condition
- Days to Harvest
- Crop Yield (tons/hectare)

> **Note:** The dataset is not included in this repository due to GitHub file size limitations. It can be downloaded from Kaggle.

---

## 🛠 Data Preprocessing

The following preprocessing techniques were applied:

- Missing value handling
- Duplicate removal
- Label Encoding
- Feature Scaling (Min-Max Normalization)
- Feature and Target Separation
- Train-Test Split (80:20)

---

## 🧠 Proposed CNN Architecture

The proposed model consists of:

- Conv1D Layer
- Flatten Layer
- Dense Layer (64 Neurons)
- Output Layer

Total Trainable Parameters:

```
16,609
```

---

## 🔄 Project Workflow

```
Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Label Encoding
      │
      ▼
Min-Max Scaling
      │
      ▼
Train-Test Split
      │
      ▼
CNN Model Training
      │
      ▼
Prediction
      │
      ▼
Performance Evaluation
```

---

## 📊 Results

### Model Performance

| Metric | Value |
|---------|--------|
| RMSE | **0.0459** |

The CNN model achieved a low RMSE value, demonstrating high prediction accuracy on the crop yield dataset.

---

## 📈 Visualizations

The repository includes:

- Actual vs Predicted Crop Yield
- Training vs Validation Loss

These graphs illustrate the learning behavior and prediction capability of the CNN model.

---

## 💻 Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📁 Repository Structure

```
Climate-Resilient-Crop-Yield-Prediction
│
├── Crop_Yield_Prediction.ipynb
├── Final_Report.pdf
├── README.md
├── requirements.txt
│
└── Images
      ├── actual_vs_predicted.png
      ├── training_validation_loss.png
      ├── architecture.png
      └── flowchart.png
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/YourUsername/Climate-Resilient-Crop-Yield-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Download the Kaggle dataset.

4. Place the dataset inside the project directory.

5. Open the notebook in Google Colab or Jupyter Notebook.

6. Run all cells sequentially.

---

## 📚 Course Information

**Course:** Computer Vision

**Project Type:** Academic Course Project

---

## 👨‍💻 Author

KHADIJA TUL KUBRA
Artifical Intelligence Student

---

## 📄 License

This project is developed for educational purposes as part of a Computer Vision course.

---

## ⭐ Acknowledgements

- Kaggle (Dataset Provider)
- TensorFlow
- Scikit-learn
- Google Colab
