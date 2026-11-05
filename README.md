# Intel Image Classification Project (HCCDA-AI)

An end-to-end image classification system built using Machine Learning algorithms, OpenCV for feature extraction (Color Histograms), and deployed interactively via Streamlit.

## 📌 Project Overview
This project classifies images from the Intel Image Dataset into 6 distinct categories using Support Vector Machines (SVM). It includes data preprocessing, feature extraction, model training, performance evaluation, and a real-time web application interface.

## 📂 Dataset
- **Name:** Intel Image Classification Dataset (Kaggle)
- **Size & Classes:** ~25,000 labeled images divided into 6 classes:
  1. Buildings
  2. Forest
  3. Glacier
  4. Mountain
  5. Sea
  6. Street

## 🛠️ Tools & Technologies Used
- **Python**
- **OpenCV** (Image processing and Color Histogram extraction)
- **Scikit-Learn** (SVM Machine Learning Model)
- **Streamlit** (Web application deployment)
- **Joblib** (Model saving and loading)

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Razo-code/Intel-Image-Classification-HCCDA-AI.git
cd Intel-Image-Classification-HCCDA-AI
pip install opencv-python scikit-learn streamlit joblib numpy
streamlit run app.py

## 📊 Model Performance
Algorithm: Support Vector Machine (SVM with Linear Kernel)

Feature Extraction: Color Histogram (32x32x32 bins)

Accuracy: ~52.50%
