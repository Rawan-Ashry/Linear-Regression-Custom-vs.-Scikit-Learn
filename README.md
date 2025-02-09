# 🚀 Linear Regression: Custom vs. Scikit-Learn

## 📌 Project Overview
This project implements **Linear Regression from scratch** using **NumPy** and compares its performance with **Scikit-Learn's** `LinearRegression`. The goal is to understand how gradient descent works and how well a custom implementation performs against an optimized library.

---

## 📊 Dataset
- **File:** `salary_data.csv`
- **Description:** The dataset contains salary information based on experience.
---

## 🛠️ Features & Implementation

### ✅ Custom Linear Regression
- **Gradient Descent Algorithm** for weight updates
- Tracks **cost function reduction** over iterations
- Uses **Mean Squared Error (MSE)** for loss calculation

### ✅ Scikit-Learn Model
- Implements **optimized Linear Regression** using closed-form solution or gradient descent
- **No manual hyperparameter tuning required**

### ✅ Visualization
- 📉 **Cost Function Plot**: Tracks gradient descent convergence
- 📈 **Regression Line Plot**: Compares actual vs. predicted values

### ✅ Performance Evaluation
- 🔍 **MSE & R² Score Comparison** between both models
- ✅ **Insights on computational efficiency**

---

## 🔹 Results & Comparison

### 🔹 Mean Squared Error (MSE)
| Model                | MSE        |
|----------------------|------------|
| 🛠️ Custom Model     | 50,064,732.56 |
| ⚡ Scikit-Learn Model | 49,830,096.86 |

🔴 **Scikit-Learn has slightly lower error, making it more optimized.**

### 🔹 R² Score (Goodness of Fit)
| Model                | R² Score   |
|----------------------|------------|
| 🛠️ Custom Model     | 0.9020      |
| ⚡ Scikit-Learn Model | 0.9024      |

🔴 **Scikit-Learn fits the data slightly better.**

---

## 📌 Conclusion
✅ Our custom model **performs well**, proving the implementation is correct.  
⚡ However, **Scikit-Learn is more optimized** due to efficient computation.  
📈 The difference is **minimal**, meaning our approach is solid but could be improved with:
- **More iterations** to enhance convergence
- **Optimized learning rate** for better performance
- **Polynomial features** for handling non-linear patterns

🚀 **This project serves as a great learning experience in understanding Linear Regression!**

---

## 🔧 How to Run the Code
```bash
# Install required dependencies
pip install numpy pandas matplotlib scikit-learn

# Run the Jupyter Notebook
jupyter notebook
```

🎯 **Modify and experiment with the code to enhance your understanding!** 🚀
