# K-Nearest Neighbors (KNN) Comparison Project

## 📌 Overview
This project compares two implementations of the **K-Nearest Neighbors (KNN) algorithm**:
1. **Using Scikit-Learn**: Optimized and efficient implementation.
2. **Manual Implementation**: KNN from scratch using NumPy.

The project evaluates performance based on:
- Execution time ⏳
- Accuracy 🔢
- Precision, Recall, and F1-score 📊
- Confusion Matrix 🟦
- Decision Boundaries 🎨

## 📂 Project Structure
```
K-Nearest-Neighbors-KNN/
│── scrtips  # folder with files
    │── KNN.py   # KNN using Scikit-Learn and Manual KNN implementation
│── README.md       # Documentation
```

## 🛠️ Installation
Ensure you have Python installed (>=3.8). Install the required libraries:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## 🚀 How to Run
1️⃣ Run the **Scikit-Learn KNN** script:
```bash
python knn_sklearn.py
```
2️⃣ Run the **Manual KNN** script:
```bash
python knn_manual.py
```

## 📊 Expected Results
Both implementations should achieve similar accuracy (~95%), but Sklearn KNN will be significantly faster.

| Model           | Execution Time (sec) | Accuracy |
|----------------|---------------------|----------|
| **Sklearn KNN** | **Fast ⚡ (~0.001s)** | **High ✅ (~95%)** |
| **Manual KNN**  | **Slower 🐢 (~0.1-1s)** | **Similar ✅ (~95%)** |

## 📈 Visualization
- **Confusion Matrix** (Shows classification performance)
- **Decision Boundary Plot** (Shows how data is classified)

## 🔍 Next Steps
- Optimize manual KNN using NumPy vectorization.
- Test with larger datasets like **MNIST** or **Titanic**.
- Tune `k` value using `GridSearchCV`.

---
💡 **Author:** Luca Garcia  
📅 **Date:** 2025  
🚀 **Enjoy coding KNN!**

