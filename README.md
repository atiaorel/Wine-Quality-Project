# 🍷 Digital Sommelier: Wine Quality Prediction

### 📌 Project Overview
This end-to-end Machine Learning project aims to predict wine quality based on physicochemical test data.
The goal is to build a robust classifier that can assist wineries in identifying premium wines automatically, optimizing both revenue and operational efficiency.

### ⚙️ Technical Approach
* **Data Cleaning:** Utilized **Isolation Forest** algorithm to detect and remove multivariate outliers, ensuring data integrity.
* **Feature Engineering:** Transformed the regression task into a binary classification problem (Premium vs. Regular wine).
* **Modeling:** Trained and optimized a **Random Forest Classifier**.
* **Optimization:** Applied **Threshold Tuning** (adjusting the decision boundary to 0.40) to solve the class imbalance problem.

### 🚀 Key Results
* **Accuracy:** 93%
* **Recall (Premium Wines):** Increased significantly from 56% to **74%** after optimization.
* **Strategic Impact:** The model successfully balances between catching high-value inventory and minimizing false alarms.

### 📊 Model Comparison (Benchmarking)
We conducted a rigorous comparison between two leading architectures:
| Model | Precision | Recall | Verdict |
| :--- | :--- | :--- | :--- |
| **XGBoost** | 69% | 79% | Aggressive, but less reliable (High False Positives). |
| **Random Forest** | **74%** | **74%** | **Selected for production** due to superior stability and balance. |

### 🛠️ Tools Used
* **Language:** Python
* **Libraries:** Scikit-Learn, XGBoost, Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib

---
*Created by [Your Name]*
