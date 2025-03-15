# 📌 Matrix Factorization-Based Recommender System with Differential Privacy

This project explores **Matrix Factorization-based Recommender Systems** with **Differential Privacy (DP)**.  
Using **Netflix Prize Dataset**, we implemented a **Stochastic Gradient Langevin Dynamics (SGLD)** algorithm  
to ensure privacy while maintaining high recommendation accuracy.  
We also compared the SGLD model with **SGD (Stochastic Gradient Descent)** and **ALS (Alternating Least Squares)**.

---

## 📂 Dataset

We use the **Netflix Prize Dataset**, which contains user-movie rating data.  
This dataset is widely used in recommender system research.

🔗 **Dataset Link**: [Netflix Prize Dataset](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)

---

## 🛠 Tech Stack

✅ **Programming Language**: Python  
✅ **Libraries Used**: NumPy, SciPy, Scikit-learn  
✅ **Development Environment**: Google Colab, Jupyter Notebook  
✅ **Data Storage**: Sparse Matrix Optimization, Google Drive Integration  

---

## 🚀 Implemented Models

### 🔹 **SGLD (Stochastic Gradient Langevin Dynamics) Recommender**
✔ Ensures **Differential Privacy** while maintaining high recommendation accuracy  
✔ Adds **stochastic noise** to improve standard SGD training  

### 🔹 **SGD (Stochastic Gradient Descent) Recommender**
✔ Uses **basic gradient descent** for matrix factorization  
✔ Faster than SGLD but **does not ensure Differential Privacy**  

### 🔹 **ALS (Alternating Least Squares) Recommender**
✔ Alternates between **optimizing U (User Matrix) and V (Movie Matrix)**  
✔ Works well with **Sparse Matrices** and is **parallelizable**  

---

## 📊 Model Evaluation

To compare **SGD, ALS, and SGLD**, we use the following metrics:

🔹 **RMSE (Root Mean Squared Error)**  
🔹 **MAE (Mean Absolute Error)**  
🔹 **Precision@K (Top-K Recommendation Accuracy)**  

| Model | RMSE ↓ | MAE ↓ | Precision@10 ↑ |  
|-------|--------|--------|----------------|  
| **SGLD** | 0.9671 | 0.7289 | 0.0250 |  
| **SGD** | TBD | TBD | TBD |  
| **ALS** | TBD | TBD | TBD |  

---

## 💾 File Structure

