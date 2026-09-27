# 📊 Data Analytics – Excel Assignment 2: Data Cleaning & Preparation

## 📌 About the Project

This project is part of my **Data Analytics learning journey** and focuses on **data cleaning and preparation using Microsoft Excel**.

Real-world datasets often contain missing values, inconsistent text, duplicate records, formatting issues, and poorly structured fields. Before performing analysis, these issues need to be identified and addressed to improve data quality and reliability.

In this project, I worked with a **Product Dataset** and applied Excel techniques to clean, standardize, transform, and format the data for further analysis.

---

## 🎯 Objectives

The main objectives of this project were to:

* Identify and handle missing values
* Correct inconsistent text formats
* Fix category typos and inconsistencies
* Identify and remove duplicate records
* Split and restructure data
* Merge information from multiple columns
* Apply appropriate number and date formats
* Use conditional formatting to improve data readability
* Prepare a cleaner and more consistent dataset for analysis

---

## 📂 Dataset

The dataset contains product-related information with the following attributes:

| Column       | Description                                              |
| ------------ | -------------------------------------------------------- |
| Product ID   | Unique identifier containing product-related information |
| Product Name | Name of the product                                      |
| Brand Name   | Brand associated with the product                        |
| Quantity     | Number of products                                       |
| Category     | Product category                                         |
| Price        | Price of the product                                     |

---

## 🧹 Data Cleaning Tasks Performed

### 1. Handling Missing Values

Checked the **Price** column for missing values.

For products with missing prices, the appropriate treatment was considered based on the nature of the dataset. Missing prices should not be arbitrarily replaced without a valid basis. Where necessary, such records can be reviewed separately or excluded from price-based analysis.

The **Category** column was also checked for missing values. Possible approaches include:

* Reviewing the Product Name and other available information to determine the category
* Assigning the appropriate category where it can be reliably identified
* Using a suitable category such as `"Unknown"` when the category cannot be determined

This helps avoid introducing incorrect information into the dataset.

---

### 2. Correcting Inconsistent Data

The **Product Name** column was reviewed for inconsistent text formatting.

Excel's **Find and Replace** feature was used to standardize inconsistent product names where required.

The **Category** column was also checked for spelling errors and inconsistent category names.

Find and Replace was used to correct identified typos and standardize category values.

This improves consistency and ensures that categories can be analyzed correctly.

---

### 3. Removing Duplicate Records

The dataset was checked for duplicate rows based on the **entire row**.

Excel's **Remove Duplicates** feature was used to identify and remove duplicate records where applicable.

Removing duplicate records helps prevent the same product information from being counted more than once during analysis.

---

### 4. Splitting and Merging Data

#### Splitting Product ID

The **Product ID** column contains multiple pieces of information.

It was separated into:

* **Manufacturing Date**
* **Country Code**

Unnecessary characters were removed where required during the transformation.

This demonstrates how structured information can be extracted from a single text field.

#### Merging Brand and Product Information

The **Brand Name** and **Product Name** columns were combined into a new column named:

**Product Brand**

This creates a more descriptive field containing both the brand and product name.

Example formula:

```excel
=B2&" "&C2
```

---

### 5. Number and Date Formatting

#### Price

The **Price** column was formatted as a **currency** value to improve readability and clearly represent monetary values.

#### Manufacturing Date

The **Manufacturing Date** column was formatted to display dates in:

**DD-MM-YYYY**

This provides a consistent date representation throughout the dataset.

> **Note:** The original Product ID contains only the available date/month information and does not provide a year. Therefore, a year should not be invented. The date formatting was applied based only on the information reliably available in the source data.

---

### 6. Conditional Formatting

Conditional formatting was applied to improve the visual understanding of the dataset.

#### Price Column

A **Data Bar / Color Scale** was applied to the Price column to visually compare product prices.

This makes it easier to identify relatively lower and higher-priced products at a glance.

#### Category Column

A custom conditional formatting rule was applied to highlight products belonging to the:

**Electronics**

category.

This demonstrates how Excel conditional formatting can be used to quickly identify records matching a specific business condition.

---

## 🛠️ Excel Skills Demonstrated

* Data Cleaning
* Missing Value Identification
* Data Standardization
* Find and Replace
* Duplicate Detection and Removal
* Text Transformation
* Column Splitting
* Column Merging
* Currency Formatting
* Date Formatting
* Conditional Formatting
* Data Preparation
* Data Quality Improvement

---

## 📈 Key Learning Outcomes

Through this assignment, I gained practical experience in preparing raw data for analysis.

I learned how to:

* Identify common data quality issues
* Handle missing and inconsistent information
* Standardize text values
* Correct data entry errors
* Remove duplicate records
* Restructure columns for better usability
* Combine information from multiple fields
* Apply appropriate formatting
* Use conditional formatting to improve data visualization

This project helped me understand that **data cleaning and preparation are important steps before performing meaningful data analysis**.

---

## 📁 Project Files

```text
excel-data-cleaning-assignment-2/
│
├── README.md
├── Excel Assignment 2 - Data Cleaning.xlsx
└── Excel Assignment-2.pdf
```

### Files Description

* **Excel Assignment 2 - Data Cleaning.xlsx** – Dataset containing the completed data cleaning and transformation tasks.
* **Excel Assignment-2.pdf** – Assignment instructions.

---

## 🚀 My Data Analytics Journey

I am currently building my skills to pursue a career as a **Data Analyst**.

My learning roadmap includes:

**Excel → SQL → Power BI → Python → Data Analytics Projects**

Through these projects, I am developing practical skills in **data cleaning, data exploration, analysis, visualization, and business problem-solving**.

This GitHub repository documents my learning progress and practical projects as I build my **Data Analytics portfolio**.

---

## 👩‍💻 Author

**Monisha**

**Aspiring Data Analyst**

Skills in Progress:

* Microsoft Excel
* SQL
* Power BI
* Python
* Data Analysis

---

⭐ This project is part of my ongoing **Data Analytics learning journey** and portfolio development.
