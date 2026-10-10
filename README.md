# Customer Shopping Behavior Analysis

An end-to-end data analysis project exploring customer purchase
patterns, product ratings, shipping preferences, subscriptions, and
customer segments to identify opportunities for better business
decisions.

## Project Overview

This project analyzes **3,900 purchase records** across **18 columns**
containing customer demographics and shopping behavior. The goal is to
turn transaction data into actionable insights that can support customer
retention, marketing, and revenue-growth strategies.

## Tools & Technologies

-   **Python**
-   **Pandas** --- data loading, exploration, cleaning, and feature
    engineering
-   **MySQL** --- database integration and SQL-based analysis
-   **Jupyter Notebook** --- interactive analysis environment

## Dataset Overview

  Metric              Details
  ------------------- ----------------------------
  Total purchases     3,900
  Number of columns   18
  Missing values      37, all in `Review Rating`

## Data Preparation

The project workflow included:

1.  **Data loading:** Imported the dataset using Pandas.
2.  **Initial exploration:** Checked the dataset structure and summary
    statistics.
3.  **Missing-value handling:** Filled missing `Review Rating` values
    using the median.
4.  **Feature engineering:** Created age groups and purchase-frequency
    features.
5.  **Database integration:** Connected the prepared data to MySQL
    for analysis.

## Key Insights

### 1. Revenue by Gender

Female customers generated slightly higher total revenue than male
customers. Gender-based marketing strategies may help optimize revenue
opportunities.

### 2. High-Value Discount Users

Some customers use discounts while still spending above average. These
value-conscious, high-spending customers may be suitable for targeted
premium offers.

### 3. Top-Rated Products

-   **Blouse:** Average rating of 5
-   **Dress:** Average rating of 5
-   **Shirt:** Average rating of 4

These products could be highlighted in relevant marketing campaigns.

### 4. Shipping Preferences

  Shipping type     Average purchase amount
  --------------- -------------------------
  Express                              \$65
  Standard                             \$58

The presentation reports that express-shipping customers spend
approximately **12% more per transaction**.

### 5. Subscription Impact

The analysis presentation reports the following subscription-related
metrics: - **68% higher spend** among subscribers compared with
non-subscribers - **45% revenue share** from subscription customers -
**78% loyalty rate** based on repeat-purchase frequency

### 6. Customer Segmentation

  Segment       Share
  ----------- -------
  Loyal           15%
  Returning       35%
  New             50%

A key opportunity is to convert new customers into returning shoppers,
then build loyalty among returning customers.

## Business Recommendations

-   **Boost subscriptions:** Promote exclusive benefits to encourage
    subscription adoption.
-   **Strengthen loyalty programs:** Reward repeat purchases and improve
    customer retention.
-   **Use targeted marketing:** Focus on high-revenue customer segments
    and express-shipping users.
-   **Promote top-rated products:** Feature highly rated products in
    campaigns where relevant.
-   **Encourage repeat purchases:** Develop campaigns that move
    customers from the new segment to returning and loyal segments.

## Project Workflow

``` text
Dataset
   ↓
Pandas: Loading and Exploration
   ↓
Data Cleaning and Feature Engineering
   ↓
MySQL: Database Integration and SQL Analysis
   ↓
Insights and Customer Segmentation
   ↓
Business Recommendations
```

## Repository Contents

A suggested repository structure:

``` text
customer-shopping-behavior-analysis/
├── README.md
├── Customer-Shopping-Behavior-Analysis.pptx
├── customer_shopping_behavior.csv
└── customer_shopping_behavior_analysis.ipynb
```

Update the filenames above to match the files you actually upload. Only
include the dataset if you are permitted to share it.

## Presentation

The project presentation summarizes the dataset, preparation workflow,
analysis, key findings, customer segments, and strategic
recommendations. Upload the PowerPoint to this repository and link it
here if you want readers to access it directly:

`Customer-Shopping-Behavior-Analysis.pptx`

## Conclusion

This project demonstrates how Python-based data preparation and SQL
analysis can be used to investigate customer shopping behavior and
identify business opportunities in subscriptions, retention, product
positioning, shipping preferences, and targeted marketing.

------------------------------------------------------------------------

*Note: The numerical findings above are reproduced from the project
presentation. Their interpretation depends on the dataset, calculation
methods, and definitions used in the original analysis.*
