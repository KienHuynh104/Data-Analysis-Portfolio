# Kien Huynh – Data Analyst Portfolio (Python, SQL, Power BI, Excel)
___

## I.About Me

Hi! I'm Kien Huynh, a data analyst with a background in Economics and Finance, and professional experience in business operations and production planning. I graduated from RMIT University with a strong academic record and developed an interest in using data to solve complex business problems. Over the past few years, I’ve managed supply chains and optimized production schedules across hundreds of SKUs.

My transition into data analytics has been supported by hands-on projects involving Python, SQL, Power BI, and Excel. I’ve applied these tools to tasks like churn prediction, customer segmentation, and performance analysis—translating data into insights that support better decision-making.

This portfolio showcases selected projects that reflect both my analytical skills and my practical experience in operations and business environments.

[Download my CV (PDF)](https://github.com/KienHuynh104/Data-Analysis-Portfolio/blob/main/Kien_Huynh_Data_Analyst_CV.pdf)  
[Connect with me on LinkedIn](https://www.linkedin.com/in/kien-huynh-)
___

## Table of Contents
- [I.About Me](#iabout-me)
- [II.Portfolio Projects](#iiportfolio-projects)
  - [1. Python](#1python)  
    - [1.1 Telco Customer Churn Prediction](#11-telco-customer-churn-prediction)
    - [1.2 Order Cancellation Insights – Ride-hailing Operations](#12-order-cancellation-insights--ride-hailing-operations)
  - [2. SQL](#2sql)
    - [2.1 Customer Segmentation Using RFM Model](#21-customer-segmentation-using-rfm-model)
  - [3. Power BI](#3power-bi)
    - [3.1 Mobile Sales Analysis – Power BI Dashboard](#31-mobile-sales-analysis--power-bi-dashboard)
- [III.Education](#iiieducation)
- [IV.Certificates](#ivcertificates)
- [V.Contacts](#vcontacts)
___
## II.Portfolio Projects
### 1.Python
#### 1.1 Telco Customer Churn Prediction
**Situation**: A telecommunications company faced rising customer churn and needed a way to identify at-risk users and improve retention strategies using customer data.

**Task**: Develop a predictive machine learning model using demographic and service usage data to classify customers likely to churn, and identify key contributing factors.

**Skills**: Data preprocessing, handling missing values, addressing class imbalance with SMOTE, feature selection with SelectKBest, model training, cross-validation, hyperparameter tuning, evaluation using F1 Score, precision, recall, business insight extraction from feature importance.

**Tools**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost, Random Forest, Logistic Regression, SMOTE (imblearn), GridSearchCV.

**Result**:  
- Trained and compared 5 models: Logistic Regression, Decision Tree, Random Forest, SVM, and XGBoost  
- XGBoost performed best:  
  - **F1 Score:** 0.801  
  - **Accuracy:** 79.8%  
- Identified **Contract Type**, **Paperless Billing**, and **Online Security** as key churn indicators  
- Recommended offering long-term contracts and improving service engagement to reduce churn

**Code File**: [Open In Colab](https://colab.research.google.com/drive/12HHqjwyeod5iNBoSuLetoh5sZNpKFJU1?usp=sharing)  
**Report File**: [PDF](https://github.com/KienHuynh104/Portfolio-Projects/blob/81348460446e8369d840eb07a5c1e13f9b1a10ee/Telco-Churn/Churn%20Forecasting%20for%20Telco%20Using%20ML%20Models.pdf)
#### 1.2 Order Cancellation Insights – Ride-hailing Operations
**Situation**: A ride-hailing platform faced a high number of cancelled bookings, leading to operational inefficiencies, poor customer experience, and lost revenue. The company needed a better understanding of cancellation patterns and their root causes.

**Task**: Analyze booking and cancellation data to uncover trends, behaviors, and operational bottlenecks. Provide actionable insights to reduce cancellation rates and improve service reliability.

**Skills**: Data cleaning, merging datasets, exploratory data analysis (EDA), datetime feature engineering, visualization of time-based trends, categorical analysis, root cause identification, business insight generation.

**Tools**: Python, Pandas, NumPy, Seaborn, Matplotlib, Jupyter Notebook.  

**Result**:
- Identified key cancellation triggers such as:
  - Long ETA estimates
  - Peak-hour demand with driver shortages
  - Incomplete driver assignment
- Visualized hourly cancellation patterns and user wait time distribution
- Recommended operational improvements:
  - Dynamic driver allocation during peak hours
  - Better ETA communication
  - Incentives for drivers to accept rides faster

**Code File**: [Open In Colab](https://colab.research.google.com/drive/1WBYSPK4ZMQmemUXx0doPVDN52kMinLo6?usp=share_link)  
### 2.SQL
#### 2.1 Customer Segmentation Using RFM Model
**Situation**: A business was running a year-end sales campaign and needed to segment its large customer base to tailor marketing strategies and improve retention and revenue.

**Task**: Use transactional sales data to segment customers using the RFM (Recency, Frequency, Monetary) model and apply business frameworks (e.g. BCG Matrix) to guide targeted marketing strategies.

**Skills**: SQL querying, RFM scoring using quartiles, data transformation, customer profiling, behavioral clustering, Pareto principle analysis, BCG Matrix adaptation, report visualization.

**Tools**: MySQL and Excel

**Result**:
- Segmented thousands of customers into 16 RFM groups based on purchasing behavior
- Identified key revenue drivers:
- Top 3 RFM segments (344, 143, 144) contributed over 30% of total revenue
- Applied a modified BCG Matrix to categorize customers
- Visualized GMV contributions by group to support strategic marketing and retention focus

**Report File**: [PDF](https://github.com/KienHuynh104/Portfolio-Projects/blob/23fa7dceb16c8196c5b8c4c1fb480eed4a782833/Customer%20Segmentation%20Using%20RFM%20Model/Customer%20Segmentation%20Report%20Using%20RFM%20Model.pdf)

### 3.Power BI
#### 3.1 Mobile Sales Analysis – Power BI Dashboard
**Situation**: A mobile phone retailer operating across South Asia and the Middle East needed to understand product sales performance, customer segments, and channel distribution to optimize strategy and resource allocation.

**Task**: Build an interactive Power BI dashboard to visualize KPIs like revenue, units sold, and transactions, broken down by region, product, demographic, and channel. Enable business users to identify trends, top performers, and opportunities.

**Skills**: Data modeling, DAX calculations, KPI visualization.

**Tools**: Power BI, DAX, Power Query.

**Result**:

- Built a responsive dashboard with slicers for channel, country, age group, and OS
  - Enabled regional managers to:
  - Track KPIs monthly (revenue, units, transactions)
  - Drill down by customer segment, city, model, and brand
  - Identify sales patterns by storage size, color, and OS  

**Report File**: [PDF](https://github.com/KienHuynh104/Portfolio-Projects/blob/main/Mobile%20Sales%20Analysis%20Dashboard/Mobile%20Sales%20Analysis.pdf), [PBIX](https://github.com/KienHuynh104/Portfolio-Projects/blob/main/Mobile%20Sales%20Analysis%20Dashboard/Mobile%20Sales%20Analysis.pbix)
___

## III.Education
RMIT University – Saigon South Campus:  
Bachelor of Business (Economics and Finance), 2017-2020
- GPA: 3.6/4.0 (Top 5% of graduating cohort)  
- 25% Scholarship Recipient
___

## IV.Certificates
I believe the most meaningful way to demonstrate skills is through real projects and shared results. While certificates aren’t the focus of my learning, they often come as a natural outcome of exploring and practicing new tools. Most of what I’ve learned has come from self-study and hands-on work, reflecting a strong independent mindset and a commitment to continuous growth.  
- Data Analysis and Machine Learning with Python – University of Helsinki (MOOC)
- Google Project Management – [Coursera](https://coursera.org/verify/professional-cert/K94LVZACQXKK)
- SQL (Advanced) Certificate – [HackerRank](https://www.hackerrank.com/certificates/688bca04fa41)
___

## V.Contacts
- LinkedIn: [@kienhuynh](https://www.linkedin.com/in/kien-huynh-)
- Email: huynhnguyenthuongkien@gmail.com
- Phone: (+84) 903 810 376
