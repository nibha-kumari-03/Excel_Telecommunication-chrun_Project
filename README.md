# 📊 Churn Quest: Navigating the Waves of Customer Retention in Telecommunications

## 📌 Project Overview

**Churn Quest** is a customer churn analysis project based on a telecommunications dataset.

In this project, I analyzed customer information and service usage patterns to understand **why customers leave a telecommunications company** and which factors may be linked to higher churn.

The analysis focuses on customer behavior, service usage, subscription plans, customer service interactions, and call charges to identify useful insights that can support **customer retention strategies**.

---

## 🎯 Problem Statement

The telecommunications company has noticed an increase in customers discontinuing their services.

The main objective of this project is to:

* Identify the factors contributing to customer churn.
* Compare churned and non-churned customers.
* Understand customer usage and service patterns.
* Identify customer groups that may have a higher risk of churn.
* Provide insights that can help improve customer retention.

---

## 📂 Dataset Information

The dataset contains customer-level information such as:

* Customer state
* Account length
* International plan
* Voice mail plan
* Day, evening, and night call usage
* International call usage
* Customer service calls
* Customer churn status

### 🎯 Target Variable

**Churn**

* `Yes` → Customer has left the company
* `No` → Customer is still with the company

---

## 📋 Important Features

| Feature                         | Description                                    |
| ------------------------------- | ---------------------------------------------- |
| `state`                         | US state of customer residence                 |
| `account_length`                | Number of months with the telecom provider     |
| `area_code`                     | Customer's area code                           |
| `international_plan`            | Whether the customer has an international plan |
| `voice_mail_plan`               | Whether the customer has a voicemail plan      |
| `number_vmail_messages`         | Number of voicemail messages                   |
| `total_day_minutes`             | Total minutes of daytime calls                 |
| `total_day_calls`               | Total number of daytime calls                  |
| `total_day_charge`              | Total charge for daytime calls                 |
| `total_eve_minutes`             | Total minutes of evening calls                 |
| `total_eve_calls`               | Total number of evening calls                  |
| `total_eve_charge`              | Total charge for evening calls                 |
| `total_night_minutes`           | Total minutes of night calls                   |
| `total_night_calls`             | Total number of night calls                    |
| `total_night_charge`            | Total charge for night calls                   |
| `total_intl_minutes`            | Total international call minutes               |
| `total_intl_calls`              | Total international calls                      |
| `total_intl_charge`             | Total international call charges               |
| `number_customer_service_calls` | Number of customer service calls               |
| `churn`                         | Whether the customer churned                   |

---

## 🔍 Key Analysis Questions

### Basic Analysis

The project investigates questions such as:

1. How many customers have churned?
2. What percentage of customers have churned?
3. Does account tenure influence churn?
4. Does having an international plan affect churn?
5. Do customer service calls have a relationship with churn?
6. Does total day usage affect churn?
7. How does a voicemail plan affect churn?
8. Does international usage influence customer churn?
9. Is there a relationship between total day calls and churn?
10. Do evening charges differ between churned and non-churned customers?

---

## 🛠️ Analysis Approach

The project follows a structured data analysis process:

### 1. Data Understanding

* Reviewed the dataset structure.
* Understood the meaning of each column.
* Identified the target variable.

### 2. Data Cleaning

* Checked for missing values.
* Checked data types.
* Reviewed duplicate records.
* Standardised categorical values where required.

### 3. Exploratory Data Analysis

* Compared churned vs. non-churned customers.
* Calculated averages and percentages.
* Analysed customer usage patterns.
* Studied relationships between variables and churn.

### 4. Segmentation Analysis

Customers were analysed based on:

* Area code
* International plan
* Voice mail plan
* Account length
* Customer service calls
* Call usage
* International usage

### 5. Visualization

Charts and graphs were used to make patterns easier to understand, including:

* Bar charts
* Column charts
* Pie/Donut charts
* Comparison charts
* Scatter plots
* Distribution charts
* Segmented analysis

---

## 💡 Key Outcomes

The analysis helps identify the major factors that may be associated with customer churn.

Some important areas of focus include:

* **Customer service interactions:** Customers making several customer service calls may represent a higher churn-risk group.
* **International plans:** International plan subscribers can be compared to non-subscribers to understand differences in churn behavior.
* **Call usage:** Day, evening, and night usage can help identify differences between churned and retained customers.
* **International usage:** International minutes, calls, and charges provide useful information about customer behavior.
* **Account tenure:** Comparing newer and longer-tenure customers helps understand retention patterns.
* **Voice mail plans:** Voice mail subscription and message usage can be analyzed to understand their relationship with churn.
* **Customer segmentation:** Grouping customers based on usage patterns can help identify different customer profiles and potential high-risk segments.

---

## 📈 Business Recommendations

Based on the analysis, a telecommunications company can consider:

1. **Monitor customers with frequent customer service interactions** and investigate their concerns before they decide to leave.

2. **Identify high-risk customers** using factors such as service calls, usage levels, plans, and tenure.

3. **Improve customer support** by identifying common issues faced by customers who are likely to churn.

4. **Create targeted retention offers** for customers showing high churn-risk behavior.

5. **Review international plans and charges** to understand whether pricing or usage patterns are contributing to customer dissatisfaction.

6. **Focus on newer customers** if analysis shows that customers with shorter account lengths have higher churn rates.

7. **Use customer segmentation** to provide more personalized plans and offers.

---

## 📊 Skills Demonstrated

Through this project, I practiced:

* Data Cleaning
* Data Analysis
* Exploratory Data Analysis (EDA)
* Customer Segmentation
* Churn Analysis
* Data Visualization
* Comparative Analysis
* Business Problem Solving
* Data-Driven Decision Making
* Business Insights & Recommendations

---

## 🎯 Business Impact

Customer churn can directly affect a telecommunications company's **revenue, customer base, and market position**.

By identifying customers who are more likely to churn and understanding the reasons behind their behavior, businesses can take proactive steps to:

* Improve customer satisfaction
* Reduce customer churn
* Increase customer retention
* Improve customer experience
* Develop targeted retention campaigns
* Support better business decisions

---

## 📁 Project Structure

```text
Telecommunication-Customer-Churn-Analysis/
│
├── 📊 Telecommunication_Churn_Analysis.xlsx
│
├── 📄 README.md
│
└── 📁 Images/
    └── Dashboard / Analysis screenshots
```

---

## 🚀 Conclusion

This project provided practical experience in analyzing customer churn and converting raw customer data into meaningful business insights.

The analysis demonstrates how data analytics can help telecommunications companies **understand customer behavior, identify churn-risk segments, and develop better customer retention strategies**.

---

## 👩‍💻 Author

**Nibha Kumari**

Aspiring Data Analyst | Business Analyst

**Skills:** Excel | SQL | Power BI | Python | Data Analysis | Data Visualization
