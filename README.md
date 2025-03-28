# 📊 Customer Revenue & Churn Analysis Platform


[![Live App](https://img.shields.io/badge/LIVE%20APP-CLICK%20TO%20VIEW-green?style=for-the-badge)](https://hotelappanalysis.streamlit.app)

This project is a **Streamlit-based data analysis and visualization platform** designed to process and analyze hotel customer data. It highlights key insights such as revenue trends, customer segmentation, and churn prediction. The platform reads an Excel file, processes the data, and provides a set of dynamic and interactive visual dashboards, making it easy for users to explore data insights and generate actionable business decisions.

---

## 🎯 **Project Objectives**

This application demonstrates the capability to:

✅ Analyze and visualize data from Excel files dynamically.  
✅ Provide insightful and interactive data dashboards for business users.  
✅ Predict customer churn with a machine learning model.  
✅ Enable self-service analytics through a user-friendly interface.  
✅ Export processed data for further analysis.

The project is built to showcase expertise in:  
- **Python & Pandas:** Data manipulation and transformation.  
- **SQL & Data Modeling:** Defining business logic and segmentation.  
- **Machine Learning:** Churn prediction using Logistic Regression.  
- **Data Visualization:** Interactive visual reports with Plotly and Seaborn.  
- **Streamlit:** Building custom web applications for data analysis.

---

## 📚 **Technical Overview**

### 1. **Data Pipeline**
- Loads customer data from an Excel file located in the `data` folder.
- Performs data wrangling, including:
  - Handling missing values.
  - Converting categorical data to numerical values.
  - Adding segmentation labels based on revenue.

### 2. **Churn Prediction Model**
- A **Logistic Regression Model** is trained to predict customer churn based on:
  - Total Transactions
  - Total Revenue
  - Subscription Length (in months)
- Model performance is evaluated using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report**

### 3. **Visual Dashboards**
- **Revenue Analysis:** Analyzes and visualizes total revenue by region.
- **Churn Analysis:** Displays churn distribution and heatmaps by region.
- **Customer Segmentation:** Segments customers into High, Medium, and Low value groups.
- **Model Performance:** Displays accuracy, confusion matrix, and classification report.

---

## 🚀 **How to Run the Application**

### Prerequisites

1. **Python 3.9+**
2. **Virtual Environment (venv)**

### 1. **Clone the Repository**
```bash
git clone https://github.com/Yeuner/machine-learning-hotel-Customer-Revenue-Churn-Analysis-Platform
cd machine-learning-hotel-Customer-Revenue-Churn-Analysis-Platform
```

### 2. **Set Up Virtual Environment**
```bash
# Create virtual environment
python -m venv venv

# Activate the environment
# Windows
env\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. **Install Required Packages**
```bash
pip install -r requirements.txt
```

### 4. **Run the Streamlit App**
```bash
streamlit run app.py
```

### 5. **Open the Application**
Go to `http://localhost:8501/` in your browser.

---

## 📥 **Input Data Requirements**

The application processes data from an Excel file named `hotel_customer_data.xlsx` located in the `data` folder. The file should contain the following columns:

- `Customer_ID` – Unique identifier for each customer.
- `Region` – Customer's geographical region.
- `Total_Transactions` – Total number of transactions.
- `Total_Revenue` – Total revenue generated.
- `Subscription_Length_Months` – Duration of the subscription.
- `Churn` – Indicates whether the customer has churned (`Yes` or `No`).

---

## 📊 **How the Dashboards Are Generated**

### 1. **Revenue Analysis**
- Aggregates and visualizes total revenue by region using Plotly.
- Provides insights into high-revenue regions and customer behavior.

### 2. **Churn Analysis**
- Displays the distribution of churned and active customers.
- Generates a heatmap to show churn rate by region.

### 3. **Customer Segmentation**
- Segments customers based on total revenue:
  - High Value: Revenue >= $4000
  - Medium Value: Revenue between $2000 and $4000
  - Low Value: Revenue < $2000

### 4. **Churn Prediction Model**
- Trains a Logistic Regression model to predict churn likelihood.
- Displays model performance metrics to assess accuracy.

---

## 📦 **Exporting Processed Data**

Users can download the processed data as a CSV file using the **Download Processed Data** button provided within the app.

---

## ⚡️ **Customization**

This platform can be customized to:
- Include additional data sources.
- Enhance machine learning models with more features.
- Integrate with cloud-based platforms such as AWS S3 or Google Cloud.

---

## 📝 **About This Project**

This project was built to demonstrate my ability to:
- Develop customized web applications for **data visualization** from Excel files.
- Build predictive models and interactive dashboards tailored to business needs.

For any inquiries, please contact **[yeuner13@gmail.com](mailto:yeuner13@gmail.com)**.

Happy analyzing! 🎉

