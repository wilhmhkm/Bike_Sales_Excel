# 🚲 Bike Sales

![Image Alt](https://github.com/wilhmhkm/Bike_Sales/blob/278f07183cdeda1d3cb39222d45bbb7f5584e56d/Project%20Dashboard.jpg)

## 📌 Executive Summary

In this project, I demonstrate a complete end-to-end data analytics workflow using Microsoft Excel, starting from raw data preparation all the way to building an interactive dashboard.  

I work with a dataset that captures customer demographics and purchasing behavior, with the goal of uncovering patterns that influence bike purchases. The final output is a dynamic dashboard that allows users to explore insights across income, commute distance, age groups, and key demographics such as marital status, region, and education.  

Through this project, I showcase core analytics capabilities including data cleaning, transformation, exploratory analysis, and dashboard development, all within Excel.

---

## 🛠️ Tools & Technologies
- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Slicers (Interactive Filters)
  - Conditional Formatting
  - Find & Replace
  - IF (Nested Functions)
- **Techniques**
  - Data Cleaning
  - Data Transformation
  - Feature Engineering
  - Dashboard Design

---

## 🚀 Data Processing Steps

I begin by structuring the workbook into three sheets: Raw Data, Working Sheet, and Dashboard. The raw data remains unchanged, while all cleaning and transformation are performed on a duplicated dataset to preserve data integrity.  

I remove duplicate records to ensure accuracy and standardize categorical values such as converting `M / S` into `Married / Single` and `M / F` into `Male / Female`. I also verify consistency across fields like education, occupation, and home ownership, and ensure numerical columns such as income are properly formatted.  

I create age brackets using nested IF statements, grouping customers into Adolescent (≤30), Middle Age (31–54), and Old (55+). This improves both aggregation and clarity in the analysis.  

I use pivot tables to analyze patterns such as average income by gender and purchase decision, purchase trends by commute distance, and distribution across age groups.  

I build charts directly from the pivot tables, including bar charts for income comparison, line charts for age trends, and column charts for commute analysis. I enhance readability by adding titles, labeling axes, and formatting numbers for clarity.  

I consolidate all visualizations into a single dashboard, remove gridlines for a cleaner interface, and apply consistent formatting and alignment to improve storytelling and usability.  

To make the dashboard interactive, I add slicers for marital status, region, and education, and connect them across all visualizations to enable seamless filtering.

---

## 📊 Key Insights

From the analysis, I observe that higher-income individuals are more likely to purchase bikes, with male customers showing slightly higher average income in this dataset.  

I find that the middle-aged group (31–54) represents the strongest purchasing segment, while younger individuals (≤30) show lower engagement.  

Customers with moderate commute distances tend to be more inclined to purchase bikes, while extremely short or long commutes are associated with lower purchase rates.  

I also notice that married individuals tend to earn more on average, and filtering by education and region reveals deeper behavioral patterns.

---

## 💡 Recommendations

I focus on targeting middle-aged, higher-income individuals and aligning marketing strategies with this segment.  

I position bikes as efficient solutions for moderate-distance travel, highlighting both cost savings and convenience.  

I tailor strategies based on demographic factors such as marital status, education level, and geographic region to improve targeting.  

I use grouped features like age brackets instead of raw values and maintain clean, intuitive dashboards to support better decision making for stakeholders.  

To take the analysis further, I look into integrating additional variables such as pricing and time trends, and developing KPI-focused dashboards for deeper insights.
