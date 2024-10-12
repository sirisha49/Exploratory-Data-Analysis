# Exploratory Data Analysis (EDA)

## Project 1: Social Media Analysis
Description:
This project examines social media usage patterns, aiming to uncover insights into user behavior across different platforms and interest groups. The analysis focuses on key variables such as hours spent on social media, user age, and platform preferences.

### Detailed Steps Involved
1. Introduction

- The dataset contains variables related to social media usage, such as hours spent, user interests (e.g., sports, education, entertainment), and platform preferences (e.g., Instagram, Facebook).
- The goal is to identify patterns in how users engage with various social media platforms based on their interests and demographics.
Data Loading and Initial Exploration:
- The dataset is loaded using pandas, followed by a quick examination of its structure, including the number of rows, columns, and data types.
Basic exploratory commands (.head(), .info(), .describe()) are used to understand the dataset and identify any immediate issues such as missing values or inconsistencies.

2. Data Cleaning

- Handle missing data: Missing values in the dataset are dealt with by either filling them in with appropriate replacements or removing rows with insufficient information.
- Standardize and format variables where needed (e.g., ensuring age is a numerical value, hours spent is in consistent units).

3. Exploratory Data Analysis (EDA):

- Descriptive statistics are calculated to understand the central tendencies (mean, median) and distribution (standard deviation, min/max) of numerical variables such as user age and time spent on social media.
- Categorical analysis: The frequency of different user interests (e.g., sports, education) and platform preferences (Instagram, Facebook) is analyzed using bar charts and frequency counts.

3. Data Visualization

- Bar plots: Used to visualize the distribution of platform preferences across different interest groups.
- Histograms: Show the distribution of user ages and the amount of time spent on social media.
- Scatter plots: Used to investigate the relationship between hours spent on social media and user age.

Key Insights

- Most users aged 18-25 spend the highest amount of time on platforms like Instagram and YouTube.
- Entertainment and education are the two most common interests driving social media usage.
- Peak social media usage tends to be in the evenings, indicating that users primarily engage after work or school hours.

### Packages Used
```
Pandas, Matplotlib, Seaborn
```

## Project 2: Student Performance Indicator

### Description:
This project analyzes factors influencing student performance in three core subjects: math, reading, and writing. The dataset contains demographic information such as gender, parental education, and lunch type (standard or free/reduced), allowing us to explore correlations between these factors and academic outcomes.

### Detailed Steps Involved:

1. Introduction:

- The dataset includes demographic information (gender, parental education, lunch type) and scores in three subjects: math, reading, and writing.
- The goal is to explore the relationships between these factors and academic performance.
- The dataset is loaded using pandas, followed by an initial exploration using functions like .head(), .info(), and .describe() to understand its structure.
- Preliminary data checks are performed to identify any missing or inconsistent data.

2. Data Cleaning:

- Missing data is handled by either filling or dropping incomplete records.
- Categorical variables (e.g., parental education, gender) are converted into a suitable format for analysis.

3. Exploratory Data Analysis (EDA):

- Descriptive statistics are generated for numerical variables (math, reading, writing scores), including mean, median, standard deviation, and minimum/maximum values.
- Correlations between the three subjects (math, reading, writing) are calculated using corr(), and a heatmap is created to visualize these relationships.

4. Data Visualization:

- Box plots: Created to compare student performance across different gender groups and parental education levels.
- Bar charts: Used to visualize the relationship between lunch type (standard or free/reduced) and academic performance.
- Heatmaps: Correlation heatmaps show the strength of relationships between subjects.

### Key Insights:

- Students who completed the test preparation course performed better in all three subjects.
- There is a strong positive correlation between math, reading, and writing scores, indicating that students who perform well in one subject tend to perform well in others.
- Socioeconomic factors (represented by lunch type) significantly influence academic performance, with students receiving free or reduced lunch generally scoring lower than those with standard lunches.

### Packages Used:
```
Pandas, Matplotlib, Seaborn, Scikit-Learn
```
## Project 3: Car Selling Price Analysis

### Description:
This project focuses on analyzing factors that affect the selling price of used cars. The dataset includes attributes such as car brand, model, age, mileage, and selling price, with the goal of uncovering the key drivers of price variations.

### Detailed Steps Involved:

1. Introduction:

- The dataset comes from a Kaggle competition, containing over 15,000 observations with attributes like brand, model, vehicle age, mileage, fuel type, and selling price.
- The objective is to analyze the factors affecting the selling price of used cars.

- The dataset is loaded using pandas for inspection. Key statistics like the number of missing values, data types, and basic descriptive statistics are obtained using .info() and .describe() functions.

2. Data Cleaning:

- Missing values are addressed by either removing incomplete rows or filling missing values based on logical assumptions.
- The dataset is checked for outliers, particularly in terms of mileage and price, as they could significantly affect the analysis.

3. Exploratory Data Analysis (EDA):

- Descriptive statistics (mean, median, range, etc.) are computed for numerical variables such as vehicle age, mileage, and selling price.
- Scatter plots are used to explore the relationship between the car's age and its selling price, as well as between mileage and price.

4. Data Visualization:

- Box plots: Visualize price variations across different car brands.
- Scatter plots: Investigate the relationships between key variables (age, mileage) and the selling price.
- Histograms: Show the distribution of selling prices, vehicle ages, and mileage.

### Key Insights:

- As expected, vehicle age and mileage are negatively correlated with the selling price—older cars and those with higher mileage tend to sell for less.
- Certain brands retain their value better than others; luxury car brands tend to have a higher selling price even for older models.
- The selling price distribution shows a wide range, with a large cluster of cars priced between $3,000 and $10,000.

### Packages Used:

```
Pandas, Matplotlib, Seaborn, Scikit-Learn

```

## How to Run Each Analysis:

1. Clone the Repository:
```
git clone https://github.com/sirisha49/Exploratory-Data-Analysis.git
```

2. Navigate to the Project Folder:
```
cd exploratory-data-analysis
```

3. Install Required Packages:
```
pip install -r requirements.txt
```

4. Open the Jupyter Notebooks:
```
jupyter notebook
```


Yes!! Now you can start Analysing 🙂

# Author:
```
Author: Sai Sirisha NK
Role  : Data Analyst
Email : sirishank49@gmail.com
```
