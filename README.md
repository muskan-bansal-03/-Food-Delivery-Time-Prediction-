# 🍔 Food Delivery Time Prediction using Machine Learning

This project predicts food delivery time using Machine Learning techniques based on delivery person details, vehicle type, and geographical distance between restaurant and customer.

The project demonstrates how regression and classification models can be applied to solve real-world logistics problems similar to Zomato/Swiggy delivery systems.

---

## 📂 Dataset
The dataset contains:
- Delivery Person Age & Ratings
- Restaurant & Customer Latitude/Longitude
- Type of Order
- Type of Vehicle
- Time Taken for Delivery (Target)

---

## ⚙️ Feature Engineering
- Calculated real-world distance using **Haversine Formula**
- Encoded categorical features using **Label Encoding**
- Standardized numerical features using **StandardScaler**

---

## 📊 Exploratory Data Analysis
- Correlation heatmap
- Scatter plot (Distance vs Delivery Time)
- Outlier detection using boxplot

---

## 🤖 Models Used

### 🔹 Linear Regression (Predict Exact Time)
- MAE: **6.63 minutes**
- R² Score: **0.18**
> Exact time prediction is difficult due to missing real-world factors.

### 🔹 Logistic Regression (Fast vs Delayed)
- Accuracy: **80%**
- F1 Score: **0.87**
> Classification approach proved more practical and effective.

---

## 💡 Key Insights
- Distance is the most important factor affecting delivery time.
- Higher-rated delivery persons deliver faster.
- Vehicle type impacts delivery efficiency.
- Predicting delay is more reliable than predicting exact time.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📸 Output Visualizations
- Correlation Heatmap
- Scatter Plot
- Confusion Matrix

---

## 🚀 Conclusion
This project shows how Machine Learning can be used for delivery time estimation and delay prediction, providing practical insights for food delivery platforms.

