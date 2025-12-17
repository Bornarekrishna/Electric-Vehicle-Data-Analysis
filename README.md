# Electric Vehicle Data Analysis Project

## Project Overview
This project was completed as part of the Internshala Data Science Training Program. This project focuses on analysing electric vehicle (EV) data to extract meaningful insights related to pricing, performance, efficiency, and customer decision-making. The analysis is performed using Python and various data analysis libraries, following a structured problem statement provided by Internshala.

The project demonstrates data cleaning, exploratory data analysis, visualization, statistical testing, and object-oriented programming concepts.

---

##  Introduction
With the growing adoption of electric vehicles, understanding factors such as battery capacity, driving range, energy consumption, and engine performance is crucial for both consumers and manufacturers.

This project analyses a real-world EV dataset to:
- Assist customers in selecting suitable electric vehicles
- Identify efficiency patterns and outliers
- Study relationships between key performance variables
- Compare manufacturers using inferential statistics
- Build a basic EV recommendation system

The entire analysis was conducted using Python in a Jupyter Notebook environment.

---

## Project Objectives
- Analyse specifications and performance metrics of electric vehicles
- Filter EVs based on customer budget and range requirements
- Detect outliers in energy consumption
- Examine the relationship between battery capacity and driving range
- Build a recommendation system using Python classes
- Perform hypothesis testing to compare vehicle manufacturers

---

## Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – data cleaning and manipulation  
- **Matplotlib & Seaborn** – data visualization  
- **SciPy** – statistical analysis and hypothesis testing  
- **Jupyter Notebook** – project execution and documentation  

---

## Dataset Description
The dataset contains specifications of various electric vehicles, including:
- Price and battery capacity
- Driving range and energy consumption
- Engine power and torque
- Physical dimensions and load capacity
- Charging power and performance metrics

---

## Task-wise Explanation & Insights

### **Task 1: Customer-Based EV Filtering**
**Objective:**  
Identify electric vehicles within a budget of 350,000 PLN and a minimum driving range of 400 km.

**Approach:**
- Filtered EVs based on price and range
- Grouped results by manufacturer
- Calculated average battery capacity per manufacturer

**Insights:**
- Some manufacturers provide better battery capacity within budget constraints
- Long-range EVs are available even in mid-range pricing segments

---

### **Task 2: Outlier Detection in Energy Consumption**
**Objective:**  
Detect EVs with unusually high or low energy consumption.

**Approach:**
- Applied the Interquartile Range (IQR) method
- Visualised data distribution using boxplots

**Insights:**
- A small number of vehicles showed extreme energy consumption values
- Higher consumption is often associated with heavier or performance-focused models

---

### **Task 3: Battery Capacity vs Driving Range**
**Objective:**  
Analyse whether battery capacity strongly affects driving range.

**Approach:**
- Created a scatter plot to visualise the relationship
- Calculated correlation between battery capacity and range

**Insights:**
- A strong positive correlation exists
- Vehicle efficiency also plays a role beyond battery size alone

---

### **Task 4: EV Recommendation System**
**Objective:**  
Build a recommendation system to suggest EVs based on user preferences.

**Approach:**
- Implemented a Python class using object-oriented programming
- User inputs include budget, desired range, and minimum battery capacity
- System returns the top three matching EVs

**Insights:**
- Demonstrates practical application of Python OOP concepts
- Can be extended for real-world EV recommendation platforms

---

### **Task 5: Hypothesis Testing (Tesla vs Audi)**
**Objective:**  
Test whether there is a significant difference in average engine power between Tesla and Audi.

**Approach:**
- Conducted an independent two-sample t-test
- Compared engine power distributions of both manufacturers

**Insights:**
- The p-value was greater than 0.05
- No statistically significant difference in average engine power was found
- Both manufacturers offer comparable performance levels in the dataset

---

## Key Learnings
- End-to-end data analysis workflow using Python
- Handling missing values and outliers effectively
- Applying statistical reasoning to real-world data
- Translating numerical results into actionable insights
- Writing clean, structured, and readable analytical code

---

## Conclusion
This project highlights how data analysis can support informed decision-making in the electric vehicle domain. By combining data preprocessing, visualisation, statistics, and object-oriented programming, the project provides both technical depth and practical relevance.
