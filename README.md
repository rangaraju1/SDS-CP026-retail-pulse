# Welcome to the SuperDataScience Community Project!
Welcome to the **Retail Pulse - Customer Journey Prediction & Marketing Impact Analysis** repository! 🎉

This project is a collaborative initiative brought to you by SuperDataScience, a thriving community dedicated to advancing the fields of data science, machine learning, and AI. We are excited to have you join us in this journey of learning, experimentation, and growth.

To contribute to this project, please follow the guidelines avilable in our [CONTRIBUTING.md](CONTRIBUTING.md) file.

# Project Scope of Works:

## Project Overview
**Retail Pulse** is a machine learning project designed to extract actionable insights from 10 months of real-world mobile sales data collected by TechCorner, a retail store in Rangamati, Bangladesh. The primary focus is to understand and predict customer journeys—distinguishing between new and returning buyers, evaluating the effectiveness of Facebook marketing, and segmenting customers based on behavioral patterns.

By leveraging classification, clustering, and visual analytics, this project aims to deliver a comprehensive view of customer engagement, digital marketing performance, and purchasing trends. A Streamlit-based web application will serve as an interactive dashboard for business users to explore key insights and make informed decisions.

Link to Dataset: https://www.kaggle.com/datasets/shohinurpervezshohan/techcorner-mobile-purchase-and-engagement-data

## Project Objectives
### Exploratory Data Analysis:
- Analyze geographic distribution of customers (local vs. non-local).
- Assess behavior patterns (new vs. returning, Facebook-origin vs. walk-in, referrals).
- Handle missing values and encode categorical variables.
- Identify patterns in mobile brand preferences and pricing trends.

### Model Development:
- **Classification Models**:
    - Predict whether a customer is likely to return.
    - Predict whether a customer was influenced by Facebook marketing.
- **Clustering Models**:
    - Group customers based on behavior, brand preference, and engagement type.

- Perform feature engineering and model evaluation using metrics such as Accuracy, Precision, Recall, F1-Score, ROC-AUC (for classification), and Silhouette Score (for clustering).
- Apply hyperparameter tuning to optimize performance.

### Model Deployment:
- Build an interactive **Streamlit web app** that allows users to:
    - Input customer attributes and receive predictions.
    - Visualize clusters and customer types.
    - Explore dashboard insights on Facebook reach, word-of-mouth, and repeat purchase behavior.
- Host the app on **Streamlit Community Cloud** or a similar platform.
- Build backend application that serves the frontend using FastAPI and deploying it on Render. (Optional)

## Workflow

### **Phase 1: Setup (1 Week)**
- Setup GitHub repo and project folders
- Setup virtual environment and respective libraries

### **Phase 2: EDA (1 Week)**
- Analyze customer demographics and behavioral trends.
- Visualize relationships between Facebook engagement, referrals, and purchases.
- Clean and preprocess the dataset (e.g., handle missing values, encode categories).

### **Phase 3: Model Development (2 Weeks)**
- Build classification models to predict:
    - Return likelihood of a customer.
    - Impact of Facebook marketing on purchase decisions.

- Implement clustering to identify customer personas based on engagement and purchasing behavior.
- Evaluate all models using appropriate metrics and visualization tools.

### **Phase 4: Deployment (1 Week)**
- Develop a Streamlit app with:
    - Interactive prediction inputs.
    - Cluster visualization and explanation.
    - Dashboards summarizing key customer and marketing insights.

- Deploy the app to a public hosting platform.

## Timeline

| Phase                          | Task                                                | Duration    |
| ------------------------------ | --------------------------------------------------- | ----------- |
| **Phase 1: Setup**             | Project setup, GitHub repo, virtual environment     | Week 1      |
| **Phase 2: EDA**               | Data cleaning, feature engineering, visual analysis | Week 2      |
| **Phase 3: Model Development** | Classification & clustering model design and tuning | Weeks 3 & 4 |
| **Phase 4: Deployment**        | Build and deploy Streamlit dashboard                | Week 5      |
