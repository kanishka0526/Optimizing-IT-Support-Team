# 🎫 Customer Support Ticket Analysis – Data Modeling README

---

## 🌟 Project Overview

Every customer support ticket tells a story — a problem faced, a response given, and a resolution achieved.
This project transforms raw customer support data into a structured, analytical model using **Power BI Data Modeling best practices**.

The objective was to convert unstructured ticket data into a **high-performance Star Schema**, enabling powerful insights, faster queries, and scalable dashboard analytics.

---

## 🧹 From Raw Data to Analytical Model

After performing data cleaning, transformation, and feature engineering, the dataset was prepared with structured columns across key domains:

### 👤 Customer Information

* Customer Name
* Customer Email
* Customer Age
* Customer Gender

### 🎫 Ticket Information

* Ticket Id
* Ticket Subject
* Ticket Type
* Ticket Status
* Ticket Priority
* Ticket Channel
* Resolution
* Resolution Status

### 📦 Product Information

* Product Purchased

### 📅 Time Intelligence

* Date of Purchase
* Day
* Month Number
* Month Name
* Year
* Response Date
* Resolution Date
* Response Time
* Resolution Time

### ⭐ Feedback Metrics

* Customer Satisfaction Rating

---

## 🧠 Data Modeling Strategy

To ensure scalability, performance, and analytical flexibility, the dataset was structured into a **Star Schema model**, the gold standard for BI systems.

This separates:

* **Transactional data** → Fact Table
* **Descriptive data** → Dimension Tables

This approach improves:

⚡ Performance
📊 Analytical clarity
🔎 Filtering efficiency
📈 Dashboard responsiveness

---

## 🏛️ Model Architecture

### ⭐ Fact Table: Fact_Tickets

The central table storing transactional ticket-level information.

Contains:

* Ticket Id
* Customer Email
* Product Purchased
* Ticket Type
* Ticket Status
* Ticket Priority
* Ticket Channel
* Date of Purchase
* Response Time
* Resolution Time
* Customer Satisfaction Rating
* Resolution Status

This table acts as the analytical engine of the model.

---

### 🧭 Dimension Table: Dim_Date

Provides structured time intelligence for trend analysis.

Enables analysis such as:

* Monthly trends
* Yearly performance
* Daily ticket distribution

---

### 👥 Dimension Table: Dim_Customer

Stores unique customer attributes.

Supports analysis like:

* Customer demographics
* Satisfaction by age or gender
* Customer behavior analysis

---

### 📦 Dimension Table: Dim_Product

Contains product-level information.

Supports:

* Product issue tracking
* Product performance analysis

---

### 🎫 Dimension Table: Dim_Ticket

Stores ticket classification attributes.

Supports:

* Priority analysis
* Status tracking
* Channel performance

---

## 🔗 Relationship Design

Each dimension table connects to the Fact_Tickets table using **Many-to-One relationships** and **Many-to-Many relationships** , creating a clean and optimized analytical structure.

```
Dim_Date
Dim_Customer
Dim_Product
Dim_Ticket

        ↓
    Fact_Tickets
```

This creates a **Star Schema**, the most efficient model for analytics.

---

## 🚀 Why Star Schema?

Star Schema provides:

* Faster query execution
* Reduced redundancy
* Better scalability
* Professional BI architecture
* Industry-standard design

Used by companies like:

* Microsoft
* Amazon
* Google
* Netflix

---

## 📊 Analytical Capabilities Enabled

This model enables powerful insights such as:

* 📈 Ticket volume trends over time
* ⏱️ Resolution time analysis
* ⭐ Customer satisfaction tracking
* 📦 Product issue analysis
* 🚨 Priority and escalation analysis
* 📡 Channel performance analysis

---

## 🛠️ Tools & Technologies Used

* Power BI Desktop
* Power Query Editor
* DAX (Data Analysis Expressions)
* Star Schema Modeling

---

## 🎯 Project Outcome

Successfully transformed raw customer support data into a professional analytical model ready for:

* Interactive dashboards
* KPI tracking
* Business intelligence reporting
* Decision-making support

---

## 🌟 Final Note

This project demonstrates how proper data modeling transforms raw data into meaningful insights.
A well-designed data model is the foundation of every powerful dashboard.

---
