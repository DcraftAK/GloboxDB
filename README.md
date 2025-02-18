# 📊 A/B Test Analysis: GloBox Marketplace

## 📌 Project Overview
In this project, we analyze the results of an **A/B test** and create a data-driven report with recommendations for stakeholders. The goal is to determine whether highlighting food and drink products via a website banner leads to increased conversions.

## 🚀 Project Logistics
This project is structured in **three stages**, each representing a sprint:
1. **Extracting Data**: Querying a relational database using **SQL**.
2. **Analyzing A/B Test Results**: Performing statistical analysis in spreadsheets and visualizing insights in **Tableau**.
3. **Reporting Findings**: Creating a written report and optionally recording a video presentation.

## 🎯 Project Background

### **Motivation**
A/B testing is a widely used experimentation technique that helps businesses determine the effectiveness of different variations of a webpage, advertisement, or product feature. GloBox, an e-commerce company specializing in boutique fashion and high-end decor, wants to **increase awareness and revenue** for its growing food and drink category.

### **A/B Test Setup**
- The test is **mobile-only**.
- Users are randomly assigned to a **control group** (no banner) or **test group** (sees the banner).
- If a user makes a purchase at any time after exposure, they are considered **converted**.

### **Stakeholders**
The results of this test will be presented to key stakeholders, including:
- **Growth Product & Engineering Team**: Develops features that drive user engagement and revenue.
- **Leila Al-Farsi (Product Manager, Growth)**: Leads growth initiatives and evaluates performance metrics.
- **Alejandro Gonzalez (User Experience Designer, Growth)**: Designs user-friendly website experiences.
- **Mei Kim (Head of Marketing)**: Aligns website experience with marketing strategies.

## 🗄️ The Dataset
GloBox stores its data in a **relational database**, which we access using SQL. The key tables include:

| Table | Description |
|-------|-------------|
| **users** | Contains user demographic information. |
| **groups** | Tracks A/B test group assignments. |
| **activity** | Records user purchases, including date, device, and amount spent. |

🔗 **Database Connection**: You can access the GloBox database using **Beekeeper Studio** with the following credentials:
```
postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Globox
```

## 📊 Analysis & Methodology
1. **Data Extraction**: Use SQL to retrieve relevant user, test group, and purchase data.
2. **Statistical Testing**: Apply methods such as **t-tests, chi-square tests, and confidence intervals** to compare conversion rates between groups.
3. **Visualization**: Use **Tableau** to create insightful dashboards.
4. **Business Recommendation**: Provide clear recommendations on whether to roll out the banner to all users.

## 📌 Key Findings & Recommendations
📌 *To be updated upon completion of analysis.*

## 🛠️ Tools & Technologies
- **SQL** (Data Extraction & Transformation)
- **Python (Pandas, NumPy, SciPy)** (Statistical Analysis)
- **Tableau / Power BI** (Data Visualization)
- **Excel / Google Sheets** (Additional Data Analysis)

## 📎 Project Deliverables
- **SQL Queries**: Extracting data from the database.
- **Data Analysis Report**: Statistical testing and insights.
- **Tableau Dashboards**: Interactive data visualizations.
- **Final Recommendations**: Data-driven business suggestions.

---

## 📩 Let's Connect!
💼 [LinkedIn](#) | 📧 [Email](#) | 🌍 [Portfolio](#)

🚀 *Stay tuned for updates as the analysis progresses!*
