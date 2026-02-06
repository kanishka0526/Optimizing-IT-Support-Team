# 🚀 Optimizing IT Support Team Performance Using Analytics

## 📌 Project Overview
This project focuses on analyzing **IT Support Ticket data** to understand customer issues, optimize resolution time, and improve overall support service efficiency using **data analytics and visualization tools**.

The project involves **data extraction, cleaning, exploratory analysis, and dashboard creation** using Power BI and Python.

---

## 🗓️ Weekly Work Breakdown

---

## 📅 Week 1: Project Introduction & Power BI Fundamentals

### 🔹 Activities
- Self-introduction and overview of the project
- Explanation of real-world IT support scenarios:
  - Customers face transaction issues such as delayed money transfer or difficulty fetching transaction details
  - Such issues are raised as **support tickets** by customers
- Introduction to **Power BI**:
  - Ribbon
  - Power Query
  - Report (Visual) View
  - Table View
  - Model View
- Extracted datasets from different websites
- Performed data cleaning using **Power Query**

### 🔹 Data Cleaning Steps (Power BI)
- Removed duplicate records
- Handled missing values using aggregation where applicable
- Removed unnecessary columns
- Standardized column values
- Rearranged columns
- Replaced incorrect values
- Removed white spaces using **Trim**
- Removed special characters using **Replace Values**
- Split columns using **Delimiter**

### ✅ Task
- Extracted and cleaned dataset using **Power BI Power Query**

---

## 📅 Week 2: Python, Pandas & Data Cleaning in VS Code

### 🔹 Activities
- Presented cleaned dataset from Week 1
- VS Code setup and explanation of project folder structure
- Introduction to **Jupyter Notebook (.ipynb)**
- Explanation of **DataFrame** and **Pandas library**

### 🔹 Key Concepts
- **DataFrame:** A tabular structure used to store and analyze data in Python
- **Pandas:** A Python library used to load and manipulate CSV and Excel datasets

### 🔹 Data Cleaning Using Python (Pandas)
- Loaded dataset using Pandas
- Removed duplicate records
- Removed white spaces and special characters
- Replaced categorical values (Yes/No → Y/N)
- Removed unnecessary rows and columns
- Filled null values
- Filtered invalid records
- Reset index and renamed columns

### ✅ Task
- Data cleaning and preprocessing using **Python (Pandas)** on customer call list dataset

---

## 📅 Week 3: Exploratory Data Analysis (EDA)

### 🔹 Introduction to EDA
- EDA (Exploratory Data Analysis) helps explore, understand, and summarize data before visualization
- Without EDA → dashboards are just charts
- With EDA → dashboards answer business questions

### 🔹 Key Factors of EDA
- Data volume
- Data distribution
- Comparisons
- Relationships between variables

### 🔹 Activities
- Framed analytical questions based on dataset
- Reviewed data patterns and trends for dashboard creation

### ✅ Task
- Dataset review and EDA planning

---

## 📅 Week 4: Live Data, APIs & GitHub

### 🔹 Activities
- Imported live data into Power BI using **Get Data → Web**
- Understood challenges of live data refresh and data flooding
- Compared public and restricted datasets:
  - W3Schools (public)
  - NSE Stocks (restricted)
- Learned API concepts:
  - API Endpoint as a URL used by systems to fetch data
- Introduction to **Zendesk**:
  - Ticket creation
  - Ticket assignment
  - Status tracking
  - Performance measurement
- Example use case: Late order → ticket created in Zendesk
- Created and managed **GitHub repository**

### ✅ Task
- Created GitHub repository and structured project files

---
# 📊 Week 5 – Power BI Basics

## 🔑 KPI (Key Performance Indicator)
- Numeric value that shows performance
- Summarizes complex data into one insight
- Used in dashboards
- Easy to understand at a glance
- Example: Total Sales, Profit

---

## 📂 Types of Data in Power BI

### 1. Categorical Data
- Cannot perform mathematical operations
- Used for grouping and comparing
- Example: Product Category, Country

### 2. Numerical Data
- Mathematical operations can be performed
- Used for measures, averages, percentages
- Example: Sales, Quantity

### 3. Time-Based Data
- Data recorded over time
- Shows trends, growth, or decline
- Example: Date, Month, Year

> **Data type decides the chart type**

---

## 📈 Charts in Power BI

**Bar Chart**
- Compare categories

**Pie Chart**
- Shows proportions (100% total)
- Best for 5–6 categories

**Card**
- Shows a single value
- Represents KPI

**Line Chart**
- Used for time-based data
- Shows trends over time

---

## 🧩 Data Modeling

**Data Modeling**
- Organizing tables and defining relationships

**Fact Table**
- Contains measurable data
- Large table
- Contains foreign keys

**Dimension Table**
- Contains descriptive data
- Provides context to fact table

---

## 🔑 Keys

**Primary Key**
- Unique identifier
- Cannot be NULL

**Foreign Key**
- Connects to primary key of another table
- Used to create relationships

---

## ⭐ Star Schema
- One fact table connected to multiple dimension tables
- Simple and recommended structure in Power BI

---

## 🔗 Relationships

**One-to-Many:** One record → Many records  
**Many-to-One:** Many records → One record  
**Many-to-Many:** Many ↔ Many  
**One-to-One:** One ↔ One  

---
### ✅ Task
- Created Star Schema using Data Modeling.

---
  # 📊 Week 6 – DAX and Measures in Power BI

## 🧠 DAX (Data Analysis Expressions)
- The brain of Power BI
- Used to summarize data for better visualization
- Used to create measures
- Used to perform calculations
- Requires tables with relationships

---

## 📏 Measures in Power BI
- Created using DAX
- Used to calculate numeric values
- Not stored as part of the table
- Used in visuals for analysis

---

## ➕ Creating a Measure
- Created using the New Measure option
- Written using DAX expressions

---

## 🎯 Why Use Measures
- Provide better control over calculations
- Improve report performance
- Can be reused across multiple visuals

---

## 📂 Types of Measures

**Base Measure**
- Created from a column in a table

**Composite Measure**
- Created using two or more measures

---

## 🔥 CALCULATE Function
- One of the most important DAX functions
- Used to apply filters inside a measure
- Used to calculate values under specific conditions

**Syntax:**

---

## 🎛️ Slicers
- Interactive filters in reports
- Used in report view
- Allow users to select and filter values

---

## ⚙️ Conditional Logic in DAX

**IF**
- Executes logic when condition is TRUE

**IF ELSE**
- Executes one logic when condition is TRUE and another when FALSE

**Nested IF**
- Uses multiple IF conditions to handle multiple scenarios

---

## 🛠️ Tools & Technologies Used
- Power BI
- Python
- Pandas
- VS Code
- Jupyter Notebook
- GitHub

---

## 📌 Learning Outcomes
- Hands-on experience with **data cleaning, EDA, and visualization**
- Understanding of real-world IT support ticket systems
- Improved analytical and problem-solving skills
- Practical exposure to Power BI, Python, APIs, and GitHub

---

## ✅ Conclusion
This project demonstrates how **data analytics and visualization** can be used to analyze IT support operations, identify inefficiencies, and support data-driven decision-making for improving service performance.
