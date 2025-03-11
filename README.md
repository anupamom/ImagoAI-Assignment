# ImagoAI Internship Assignment

## 📌 Objective
Predict **DON concentration (vomitoxin level)** in corn using **hyperspectral imaging**.

## 📂 Dataset
- **Inputs**: Hyperspectral imaging data (spectral bands).
- **Target**: DON concentration (`vomitoxin_ppb`).
- **Preprocessing**: Missing value handling, MinMax scaling, PCA for dimensionality reduction.

## 🛠️ Model & Approach
- **Used CNN (Conv1D) model** for regression.
- **Loss Function**: Mean Squared Error (MSE) for better regression accuracy.
- **Evaluation Metrics**: MAE, RMSE, R² Score.
- **Hyperparameters Optimized**: Kernel sizes, filters, dropout rates, learning rate.

## 📊 Results
- **Mean Absolute Error (MAE):** 0.0338  
- **Root Mean Squared Error (RMSE):** 0.0798  
- **R² Score:** 0.6092  

## 🚀 How to Run
### **1️⃣ Install Dependencies**
Run the following command to install required libraries:
```bash
pip install -r requirements.txt
```

### **2️⃣ Run the Jupyter Notebook**
1. Open the Jupyter Notebook (`ImagoAI.ipynb`).
2. Run all cells sequentially (`Kernel → Restart & Run All`).
3. Check final evaluation metrics and visualization.

## 📂 Repository Structure
```
ImagoAI-Intern-Assignment/
│-- ImagoAI.ipynb  # Jupyter Notebook with full implementation
│-- Report.pdf                # Short report covering preprocessing & results
│-- README.md                 # Project overview & execution guide
│-- TASK-ML-INTERN.csv        # Provided dataset
│-- requirements.txt          # Dependencies for running the project
```




