# 🎬 Netflix Content Classifier: Movie vs. TV Show Prediction

A high-performance Machine Learning pipeline designed to classify Netflix titles using metadata-driven features. 

---

## 🚀 Project Overview
Can we predict if a Netflix title is a Movie or a TV Show based on its metadata? This project explores that question by implementing an end-to-end ML workflow, achieving **99%+ accuracy** through careful feature engineering and classification.

## 📊 Model Performance

| Algorithm | Accuracy |
| :--- | :--- |
| **Logistic Regression** | 99.8% |
| **K-Nearest Neighbors (KNN)** | 99.7% |

> **Note:** High accuracy was achieved by extracting the `duration` feature and applying Label Encoding to categorical variables.

## ⚙️ The ML Pipeline
1. **Data Cleaning**: Handled null values in 'Director' and 'Cast' to maintain dataset integrity.
2. **Feature Engineering**: 
   - Converted string-based durations (e.g., "90 min") into **numerical integers**.
   - Applied **Label Encoding** to transform categories like 'Rating' into machine-readable data.
3. **Algorithm Implementation**: Compared a linear model (Logistic Regression) against a distance-based model (KNN).
4. **Validation**: Evaluated using **Confusion Matrices** and real-world sample testing.

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn)
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Google Colab

---
**Maintained by:** [Om Vegula]  
**Connect with me:** [www.linkedin.com/in/om-vegula-3a073a367]
