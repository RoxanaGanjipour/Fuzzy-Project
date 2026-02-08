# Fuzzy-Project
Early prediction of student performance using ANFIS (Fuzzy Logic &amp; Neural Networks) by comparing training epochs and sensitivity analysis.
# Student Performance Prediction System (ANFIS-based)

This project implements an **Adaptive Neuro-Fuzzy Inference System (ANFIS)** to predict student final grades based on their activities during the semester. 

## 🚀 Key Features
- **Early Prediction:** The model predicts final results *without* requiring the final exam score.
- **Epoch Comparison:** Comprehensive analysis of model behavior across **20, 50, and 1000 training epochs**.
- **Sensitivity Analysis:** Identified which factor (Attendance, Assignment, Midterm, or Attitude) has the most impact on success.
- **Error Distribution:** Visualization of the learning curve and prediction accuracy.

## 📊 Methodology
The system uses 4 key inputs:
1. Attendance
2. Assignments
3. Midterm Grade
4. Student Attitude

The model was trained using an MLP-based fuzzy approach to minimize MSE (Mean Squared Error).

## 📈 Results
- In **20 and 50 epochs**, the model showed a `ConvergenceWarning`, indicating insufficient training.
- At **1000 epochs**, the model reached high stability with minimal error.
- **Sensitivity Analysis** revealed that [نام مهم‌ترین عامل اینجا بنویس] is the primary predictor of success.

## 🛠 Tools Used
- Python (Google Colab)
- Scikit-Learn (MLPRegressor)
- Matplotlib & Seaborn (Data Visualization)
- Pandas & NumPy
