 # Parkinson's vs Vascular Parkinsonism Prediction using Naive Bayes and SVM

This project focuses on predicting and classifying **Parkinson's Disease** and **Vascular Parkinsonism (VP)** using synthetically generated medical data. It implements and compares **Naive Bayes** and **Support Vector Machine (SVM)** models to evaluate performance based on classification accuracy and **F1-score**. The dataset was built manually to mimic real-world clinical indicators while maintaining academic integrity and privacy.

---

## 🚀 Features

- ✅ Synthetic dataset simulating clinical biomarkers
- ✅ Preprocessing and standardization of features
- ✅ Binary classification using **Naive Bayes** and **SVM**
- ✅ Evaluation with **Confusion Matrix**, **Accuracy**, and **F1-Score**
- ✅ Comparative analysis and discussion of a **hybrid approach**

---

## 🧬 Dataset (Synthetic)

This dataset simulates diagnostic features relevant to Parkinson’s and Vascular Parkinsonism:
- **UPDRS motor scores**
- **Tremor intensity**
- **White matter lesions**
- **Cognitive scores**
- **Gait abnormalities**
- **Vital signs** like age, blood pressure, etc.

> 📌 **Note:** The dataset is completely synthetic and is intended **only for research and learning purposes**.

---

## ⚙️ Technologies Used

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib & Seaborn**

---

## 🧪 Model Evaluation

| Model       | Accuracy | F1-Score (Weighted) |
|-------------|----------|---------------------|
| Naive Bayes | 85.6%    | 0.86                |
| SVM         | 92.4%    | 0.92                |

The **SVM model** outperformed Naive Bayes in terms of predictive accuracy and F1-score. However, **Naive Bayes** proved faster and more efficient for lighter computational settings. A hybrid model (ensemble approach) could potentially yield even higher accuracy.

---

## 📦 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/parkinson-vp-prediction.git
cd parkinson-vp-prediction
