# **Predicting-Customer-Churn-for-a-Subscription-Service**  

## **📌 Project Overview**  
This project aims to predict **customer churn** for a subscription-based video streaming service using **machine learning** techniques. By analyzing customer demographics, subscription details, and usage patterns, we identify key factors driving churn and provide actionable retention strategies.  

## **📂 Dataset**  
The dataset is sourced from **[Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)** and includes:  
- **Customer ID**: Unique identifier  
- **Age, Gender**: Demographic information  
- **Subscription Plan**: Basic, Standard, Premium  
- **Monthly Charges**: Subscription fee  
- **Total Usage Hours**: Hours watched last month  
- **Support Tickets**: Complaints raised in 3 months  
- **Churn**: 1 = Customer left, 0 = Active  

---

## **🛠️ Tech Stack**  
- **Programming Language**: Python  
- **Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`  
- **Machine Learning Models**: Random Forest, Logistic Regression  
- **Visualization Tools**: Seaborn, Matplotlib  

---

## **📊 Workflow**  

### **1️⃣ Exploratory Data Analysis (EDA)**
- Analyzed missing values, outliers, and feature correlations.  
- Visualized churn distribution and subscription plan trends.  

### **2️⃣ Data Preprocessing**
- Converted categorical variables using **Label Encoding & One-Hot Encoding**.  
- Scaled numerical features using **StandardScaler**.  
- Handled missing values in **TotalCharges** column.  

### **3️⃣ Model Development & Training**
- Split data into **80% training & 20% testing** sets.  
- Trained **Random Forest Classifier** for churn prediction.  
- Evaluated model using **accuracy, precision, recall, F1-score**.  

### **4️⃣ Feature Importance & Business Insights**
- Identified key factors influencing churn using feature importance.  
- Analyzed the impact of subscription plans, support tickets, and usage.  
- Provided actionable strategies to improve customer retention.  

---

## **📈 Model Performance**
| Metric   | Score |
|----------|------|
| Accuracy | 85% |
| Precision | 82% |
| Recall   | 78% |
| F1-Score | 80% |

---

## **📌 Key Findings & Business Recommendations**
### **Findings**
✔️ **Monthly subscribers churn more** than annual plan users.  
✔️ Customers with **low engagement (watch time < 10 hours/month) churn frequently**.  
✔️ **Higher support tickets indicate dissatisfaction & lead to churn**.  

### **Recommendations**
✅ **Offer Discounts** on annual plans to retain monthly users.  
✅ **Personalized Engagement** via push notifications to inactive users.  
✅ **Improve Support Services** to reduce complaints and frustration.  

---

## **💻 Installation & Usage**
1. **Clone the repository**  
   ```sh
   git clone https://github.com/your-username/churn-prediction.git
   cd churn-prediction
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Python script**
   ```sh
   python churn_prediction.py
   ```
## 📜 Future Enhancements  
- 🔹 Implement **XGBoost & Hyperparameter Tuning** for better accuracy.  
- 🔹 Deploy the model using **Flask or FastAPI** for real-time predictions.  
- 🔹 Introduce **AI-powered churn prevention strategies**.  
