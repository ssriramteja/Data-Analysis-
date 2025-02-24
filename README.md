# 🛒 Supermarket Sales Analysis 📊

## 🚀 Project Overview

This project involves the analysis of sales data from a supermarket using various **Exploratory Data Analysis (EDA)** techniques. The dataset is analyzed using **Univariate**, **Bivariate**, and **Multivariate Analysis** methods to uncover valuable insights and trends. The goal of this project is to understand the key factors driving supermarket sales, identify patterns, and support data-driven decision-making. 

The analysis will provide insights into:
- Sales performance 📈
- Customer preferences 🛍️
- Operational strategies 🧑‍💼

## 🛠️ Libraries Used

The following libraries were utilized for data manipulation and visualization:

### 1. **Pandas** 📚
   - **Purpose**: Used for data manipulation and analysis, particularly for reading CSV files (`pd.read_csv()`) and handling data in tabular form as DataFrames.
   - **Key Features**:
     - Data cleaning 🧹
     - Data transformation 🔄
     - Aggregation and summarization 📊

### 2. **Matplotlib** 🎨
   - **Purpose**: A general-purpose plotting library used to create visualizations and plots in Python.
   - **Key Features**:
     - Basic plotting capabilities 🖼️
     - Customization of plots (e.g., titles, labels, gridlines)
   - **Common Plot Types**:
     - **Line plot**: `plt.plot()`
     - **Bar plot**: `plt.bar()`
     - **Scatter plot**: `plt.scatter()`
     - **Histogram**: `plt.hist()`
     - **Pie chart**: `plt.pie()`
     - **Subplots**: `plt.subplots()` (for multiple plots in one figure)

### 3. **Seaborn** 🌈
   - **Purpose**: Built on top of Matplotlib, Seaborn provides a high-level interface for creating attractive and informative statistical visualizations.
   - **Key Features**:
     - Enhanced statistical visualizations 📊
     - Easy-to-use functions for complex plots 🔧
   - **Common Plot Types**:
     - **Scatter plot**: `sns.scatterplot()`
     - **Box plot**: `sns.boxplot()`
     - **Histogram**: `sns.histplot()`
     - **Count plot**: `sns.countplot()` (useful for categorical data)
     - **Bar plot**: `sns.barplot()`
     - **Heatmap**: `sns.heatmap()` (for correlation matrices or 2D data)

### 4. **Warnings** ⚠️
   - **Purpose**: Used to handle warning messages that may arise during code execution, ensuring smoother execution and better control over the process.
   - **Key Features**:
     - Manage warnings that may not affect the result but may require attention.

## 🔍 Analytical Approach

### Univariate Analysis 🔢:
   - This analysis focuses on individual variables in the dataset, providing insights into their distribution, central tendencies (mean, median), and spread (variance, standard deviation). Common visualizations include:
     - **Histograms** 📊
     - **Box plots** 📦
     - **Count plots** for categorical data 🏷️

### Bivariate and Multivariate Analysis 🔄:
   - Bivariate analysis looks at the relationship between two variables, while multivariate analysis extends this to more than two variables. Techniques used include:
     - **Scatter plots** (for numerical variables) 📉
     - **Heatmaps** (for correlation matrices) 🌡️
     - **Bar plots** and **Box plots** for comparisons between categorical variables 🔲

## 🏁 Conclusion

This project provides valuable insights into supermarket sales trends and factors influencing customer behavior. By leveraging powerful Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**, we gain a deeper understanding of:
- Sales performance 📈
- Customer preferences 🛒
- Operational strategies 📊

---



# 📑 Detailed Business Rules

### 1. **Dataset Exploration and Overview** 🧐:
- **Display the top 5 rows** of the dataset for an initial review.
- **Display the last 5 rows** of the dataset to ensure all data is being captured correctly.
- **Print a random sample of 5 rows** to check for data consistency and variability.
- **Determine the shape of the dataset**, including the total number of rows and columns.
- **Check for any null or missing values** within the dataset to ensure completeness.
- **Provide detailed information** about the dataset, including the number of rows, columns, data types for each column, and memory usage.
- **Generate an overall summary of statistics** for the dataset, including count, mean, standard deviation, min, max, and quartiles.

### 2. **Sales and Payment Insights** 💳:
- **Aggregate sales by branch**: Analyze and aggregate the total sales across different branches (categorical column) to assess branch performance.
- **Most popular payment method**: Identify the most commonly used payment methods by customers to understand payment preferences.
- **Distribution of Cost of Goods Sold (COGS)**: Visualize and analyze the distribution of COGS (numerical column) to understand cost patterns.

### 3. **Customer Rating and Income Analysis** 💰:
- **Impact of Cost of Goods Sold (COGS) on customer ratings**: Determine whether there is a correlation between the cost of goods sold and the ratings provided by customers (numerical vs. numerical).
- **Impact of Gross Income on customer ratings**: Evaluate whether gross income influences the ratings that customers provide (numerical vs. numerical).

### 4. **Branch and Profitability Analysis** 💸:
- **Most profitable branch by gross income**: Identify the branch with the highest gross income to determine the most profitable location.
- **Gender and gross income relationship**: Assess whether there is any relationship between the gender of the customers and the gross income generated by them (numerical vs. categorical).
- **Most profitable product line**: Identify the product line that generates the highest income across branches (numerical vs. categorical).
- **Highest unit price within product lines**: Determine which product line has the highest unit price across all items (numerical vs. categorical).

### 5. **Payment Methods and Demographics** 💳🏙️:
- **Payment methods used by customers, segmented by city**: Analyze the distribution of payment methods across different cities to identify city-wise preferences (categorical vs. categorical).
- **Product line with the highest quantity purchased**: Identify which product line is purchased in the highest quantity across all transactions.

### 6. **Sales Trends and Insights** 📅:
- **Daily sales analysis by day of the week**: Analyze and visualize daily sales trends based on the day of the week to identify peak sales days.
- **Monthly sales forecast**: Determine which months show the highest sales to anticipate seasonal fluctuations and inform inventory planning.
