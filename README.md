# 🧠 Support Vector Machine (SVM) Kernel Regression Project

## 📌 Project Overview
This project demonstrates how Support Vector Machines (SVM) work on non-linear data using kernel techniques.  
We generate circular datasets and apply feature engineering and SVM models to understand decision boundaries.

---

## 📊 What I Did

- Created synthetic circular dataset
- Visualized data using 2D and 3D plots
- Applied feature engineering:
  - X1² (X1 squared)
  - X2² (X2 squared)
  - X1 * X2
- Trained Linear SVM model
- Compared performance with transformed features
- Understood kernel trick concept

---

## 📈 Key Concepts Learned

- Support Vector Machines (SVM)
- Linear vs Non-linear classification
- Kernel Trick (Polynomial idea)
- Feature Engineering
- Data Visualization (Plotly 3D plots)

---

## 🛠️ Tech Stack

- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- Plotly

---

## 🎯 Results

- Linear SVM struggles with circular data ❌
- Feature transformation improves separability ✅
- Helps understand why kernels are powerful

---

## 📷 Visualizations

- 2D scatter plots of circular data
- 3D transformed feature space visualization

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
