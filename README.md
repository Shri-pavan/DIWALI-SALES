# **Diwali Sales Data Analysis**

## **Project Objective**

This project aims to perform an in-depth exploratory data analysis (EDA) on Diwali sales data to uncover key trends and insights. The primary goal is to identify the most valuable customer demographics and popular product categories to help the business tailor its sales and marketing strategies for the upcoming holiday seasons.

## **Data Source**

The analysis is based on the `Diwali Sales Data.csv` file, which contains transactional information for Diwali purchases. The dataset includes the following key attributes:
* **Demographics:** Gender, Age Group, Marital Status
* **Geographics:** State, Zone
* **Professional:** Occupation
* **Product:** Product ID, Product Category
* **Transactional:** Orders, Sales Amount

## **Tools and Libraries Used**

* **Data Manipulation & Analysis:** Python, Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **IDE / Notebook:** Jupyter Notebook
* **Dashboarding & Reporting:** Power BI

## **Analysis & Dashboards**

This project includes two separate dashboards delivering insights: one developed in Python for detailed analysis and another in Power BI for an interactive overview.

### **1. Python Data Analysis (`Diwali new.ipynb`)**

The Jupyter Notebook performs a detailed, code-driven analysis.

* **Data Cleaning:** The dataset is prepared by handling missing values and dropping irrelevant columns (`Status`, `unnamed1`) to ensure data quality. The `Amount` column's data type was also converted for accurate calculations.
* **In-depth EDA & Visualizations:** The notebook uses **Matplotlib** and **Seaborn** to create a variety of plots (bar charts, count plots) that explore sales patterns based on:
    * Gender and Age Group
    * Geographic location (Top 10 States by Orders and Sales)
    * Marital Status and Occupation
    * Product Category and Product ID
* **Conclusion:** The analysis reveals that the primary customer demographic consists of **married women aged 26-35** from key states like **Uttar Pradesh, Maharashtra, and Karnataka**. These customers predominantly work in the **IT, Healthcare, and Aviation** sectors and show a higher purchasing interest in **Food, Clothing, and Electronics** categories.

### **2. Power BI Interactive Dashboard**

A Power BI dashboard was created to offer a high-level, interactive summary for business stakeholders.

* **KPIs:** Features key performance indicators like Total Revenue, Total Orders, and Customer Count.
* **Interactive Filters:** Includes dynamic slicers for Zone, State, and Product Category, allowing for easy data exploration.
* **Visualizations:** Uses visuals like maps to show sales distribution and donut charts for category breakdowns, providing a clear and accessible overview of the key findings.

## **How to Use This Project**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/diwali-sales-analysis.git
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Jupyter Notebook:**
    Open the `Diwali new.ipynb` file in Jupyter Notebook to view the complete data cleaning and analysis process.
4.  **View the Dashboard:**
    Open the `.pbix` file in Power BI Desktop to interact with the dashboard.
