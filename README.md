# 📊 Customer Churn Analysis Dashboard (Power BI)

An interactive **Power BI dashboard** designed to analyze customer churn patterns and user engagement across different segments such as **age group, gender, device type, network type, and subscription plans**.  
The dashboard helps identify high-risk users and provides insights to support **data-driven retention strategies**.

---

# 🎯 Project Objective

The objective of this project is to analyze **customer churn behavior** and identify key factors that influence user retention.  
Using interactive visuals and KPIs, the dashboard helps businesses:

- Monitor overall churn performance
- Identify high churn segments
- Understand user behavior patterns
- Compare churn across subscription plans
- Improve customer retention strategies

---

# 📌 Key Performance Indicators (KPIs)

The dashboard tracks the following core KPIs:

| KPI | Description |
|----|----|
| **Total Users** | Total number of registered users |
| **Active Users** | Number of users currently active on the platform |
| **Churned Users** | Number of users who have stopped using the service |
| **Churn Rate (%)** | Percentage of churned users compared to total users |

Example from the dashboard:

- **Total Users:** 589  
- **Active Users:** 411  
- **Churned Users:** 178  
- **Churn Rate:** 30.22%

---

# 📊 Dashboard Insights & Metrics

## 1️⃣ Customer Churn by Gender
Analyzes churn distribution between **male and female users**.

Metrics Used:
- Male Users
- Female Users
- Churned Users by Gender
- Active Users by Gender

---

## 2️⃣ Age Group Analysis
Identifies which **age groups have the most active users and churned users**.

Age Groups:
- 18 – 25
- 26 – 35
- 36 – 45
- 46+

Metrics:
- Active Users by Age
- Churned Users by Age

---

## 3️⃣ Device Type Churn Rate
Shows which device platform has the highest churn.

Device Types:
- Android
- iOS
- Web

Metric:
- Churn Rate by Device Type

---

## 4️⃣ Buffering Time Impact on Churn
Analyzes how **buffering time affects customer churn behavior**.

Buffering Time Categories:
- 0–1 sec
- 1–2 sec
- 2–3 sec
- 3–4 sec
- 4+ sec

Metric:
- Churn Percentage by Buffering Time

---

## 5️⃣ Genre Retention Analysis
Shows which **music genres retain users better**.

Genres:
- Jazz
- Rock
- HipHop
- Classical
- Pop
- EDM

Metrics:
- Active Users by Genre
- Retention Rate

---

## 6️⃣ Network Type Churn
Analyzes churn by network connection.

Network Types:
- WiFi
- 4G
- 5G

Metric:
- Churn Rate by Network Type

---

## 7️⃣ Subscription Plan Churn
Compares churn trends across subscription plans.

Plans:
- Premium
- Family
- Free

Metrics:
- Current Plan Churn
- Previous Plan Churn
- Churn Difference
- Churn % Change

---

# 📐 DAX Measures Used

Below are the main DAX measures used in this project.

### Total Users
```DAX
Total Users = COUNT('Customer Data'[User ID])
