# E-commerce Funnel Analysis Using Python

## Project Overview

Funnel analysis helps businesses understand how users move through different stages of an online shopping journey and identify where potential customers drop off before completing a purchase.

This project analyses e-commerce user journey data using Python to evaluate funnel performance, identify conversion gaps and understand how marketing channels, devices, regions, product categories and time periods relate to purchasing behaviour.

The objective is to turn raw event data into meaningful business insights that can help improve the customer journey and support data-driven decisions.

## Project Objectives

- Analyse user progression through the e-commerce conversion funnel.
- Calculate conversion and drop-off rates at each stage.
- Compare marketing channel performance and purchasing behaviour.
- Evaluate conversion rates and revenue across different devices and regions.
- Identify high-performing product categories.
- Explore daily, weekly and hourly shopping activity.
- Develop actionable business recommendations based on the findings.

## Dataset Overview

**Dataset:** Funnel Analysis Dataset  
**File:** `Funnel_Analysis_Data.csv`  
**Records:** 21,409 rows  
**Columns:** 10  
**Period:** 9 December 2025 – 8 January 2026

Each row represents one recorded event during a user's shopping session.

### Key Columns

| Column | Description |
|---|---|
| User ID | Unique identifier for a user |
| Session ID | Identifier for a shopping session |
| Event Time | Timestamp of the recorded event |
| Event | Shopping action: Browse, Add to Cart, Checkout or Purchase |
| Device | Device used to access the website |
| Region | Geographical region |
| Channel | Marketing channel |
| Product Category | Category of the product |
| Revenue | Revenue associated with the event |
| Bonus Flag | Yes/No indicator |

## Tools & Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualisation
- **Seaborn** – Statistical visualisation
- **Plotly** – Interactive visualisations
- **Jupyter Notebook** – Development environment

## Project Workflow

### 1. Data Loading and Inspection
- Imported the required Python libraries.
- Loaded the CSV dataset into a Pandas DataFrame.
- Examined the dataset structure, dimensions, columns and data types.
- Inspected unique values and categorical distributions.

### 2. Data Cleaning and Preparation
- Checked for missing values and duplicate records.
- Converted `Event Time` into datetime format.
- Checked for invalid timestamps and unusual revenue values.
- Standardised categorical text values.
- Examined unique users, sessions and event sequences.
- Extracted date, weekday, month, week and hour information for time-based analysis.

### 3. Exploratory Data Analysis

The analysis is organised into six sections:

**1. Overall Funnel Performance**
- Examined the number of users at each funnel stage.
- Calculated stage-wise conversion and drop-off rates.
- Identified the biggest drop-off point in the shopping journey.

**2. Marketing Channel Performance**
- Compared Google Ads, Email, Organic and Social Media.
- Analysed user distribution, purchasing users, conversion rates and revenue.
- Identified the strongest-performing marketing channel.

**3. Device Performance**
- Compared Desktop, Mobile and Tablet performance.
- Evaluated purchase conversion rates and revenue.
- Used a boxplot to compare purchase value distributions across devices.

**4. Regional Performance**
- Compared North, South, East and West regions.
- Examined user distribution, conversion rates and purchase revenue.
- Identified regional differences in purchasing performance.

**5. Product Category Performance**
- Compared activity and completed purchases across product categories.
- Analysed total revenue and average purchase value.
- Examined the relationship between purchase count and revenue.

**6. Time-Based Performance**
- Analysed daily website activity, purchase trends and revenue.
- Identified weekly peak days for activity, purchases and revenue.
- Examined hourly website activity and purchasing patterns.

## Key Findings

- **Checkout Drop-off:** The highest drop-off occurs between Checkout and Purchase, at **70.95%**.
- **Marketing Channel:** Google Ads records the highest purchase conversion rate at **10.63%** and the highest channel revenue of **73,862.32**.
- **Device Performance:** Desktop has the highest purchase conversion rate at **10.58%**, while Mobile has the lowest at **9.47%**.
- **Regional Performance:** South records the highest regional conversion rate at **10.54%** and the highest revenue of **77,421.45**.
- **Product Category:** Electronics generates the highest revenue (**62,938.46**) and records the most purchases (**229**).
- **Average Purchase Value:** Sports has the highest average purchase value at **295.53**.
- **Time-Based Insights:** Website activity peaks at 2 AM with 985 events, whereas purchase activity peaks at 12 PM with 53 purchases.
- **Daily Sales:** 26 December 2025 records the highest daily revenue of **12,796.90**, while 7 January 2026 records the highest number of daily purchases (44).

## Business Recommendations

Based on the analysis, the following actions could be considered:

1. **Improve the Checkout Experience:** Investigate payment failures, checkout errors and unexpected costs to understand the high checkout abandonment rate.
2. **Optimise Mobile Checkout:** Review mobile usability, page loading speed and payment options to improve mobile conversion.
3. **Evaluate Marketing Performance:** Investigate the effectiveness of high-performing channels such as Google Ads alongside advertising spend and customer acquisition costs.
4. **Investigate Regional Opportunities:** Explore why the East region has a relatively large user base but a lower conversion rate.
5. **Strengthen Product Strategies:** Review inventory, promotions and marketing opportunities for high-performing categories such as Electronics and Sports.

## Conclusion

This project demonstrates how Python can be used to clean, explore and analyse e-commerce event data to understand customer progression through a shopping funnel.

The analysis identifies checkout abandonment as the main area requiring further investigation and highlights differences in performance across marketing channels, devices, regions, product categories and time periods.

By translating these findings into practical recommendations, the project demonstrates the use of data analysis to support business decision-making.

---

**Project Type:** Exploratory Data Analysis | E-commerce Analytics | Funnel Analysis  
**Tools:** Python | Pandas | Matplotlib | Seaborn | Plotly | Jupyter Notebook
