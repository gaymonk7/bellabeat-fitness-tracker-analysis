# Bellabeat Fitness Tracker Analysis

## Project Overview

This project analyzes publicly available Fitbit fitness tracker data to identify user behavior trends and translate those insights into actionable product and marketing recommendations for Bellabeat, a wellness technology company.

The analysis follows the data analytics process of **Ask, Prepare, Process, Analyze, and Act** and was completed using Microsoft Excel.

## Business Problem

Bellabeat wants to better understand how consumers use smart fitness devices so the company can improve its products, strengthen customer engagement, and develop more effective marketing strategies.

## Business Task

Analyze smart device usage data to identify trends in user activity and behavior and use those insights to develop marketing and product recommendations for Bellabeat.

## Stakeholders

- Bellabeat cofounders Urška Sršen and Sando Mur
- Bellabeat marketing analytics team

## Dataset

The analysis uses the Fitbit Fitness Tracker Dataset, which contains fitness and activity data from 30 Fitbit users. The dataset includes information related to physical activity, steps, sleep, calories, and heart rate.

The dataset was originally made publicly available by Mobius on Kaggle under a CC0 Public Domain license.

### Data Limitations

- The dataset contains only 30 users, limiting the generalizability of findings.
- Demographic information such as age, gender, and location is not available.
- Device wear consistency is unclear and may result in gaps in the data.
- The dataset represents Fitbit users rather than Bellabeat customers.

These limitations mean findings should be interpreted as general behavioral trends rather than precise predictions of Bellabeat customer behavior.

## Tools Used

- Microsoft Excel
- Pivot Tables
- Data Cleaning
- Data Validation
- Data Analysis
- Data Visualization

## Data Preparation & Cleaning

The dataset was prepared for analysis by:

- Removing duplicate entries
- Trimming unnecessary spaces
- Reviewing missing values
- Standardizing date formats
- Standardizing column data types
- Removing blank rows
- Reviewing unrealistic values
- Checking consistency of user IDs across datasets
- Reviewing consistency between activity and sleep data

Data integrity checks identified some potentially inaccurate records, including days showing zero steps, zero active minutes, and zero calories burned. These records were retained but noted as potential device syncing or data-quality issues.

## Analysis

The analysis examined patterns in:

- Daily steps
- Calories burned
- Active minutes
- Sedentary minutes
- Activity intensity
- Relationships between steps, calories, and sedentary behavior

### Key Findings

**Daily Activity**

Average daily step counts were approximately 6,500 steps, with substantial variation in activity levels across users.

**User Activity**

Average daily steps varied from under 1,000 to more than 17,000 steps per day, demonstrating significant differences in user activity patterns.

**Energy Expenditure**

Higher step counts generally aligned with higher calorie expenditure, although some days showed relatively high calorie burn with fewer steps, suggesting that activity intensity also contributes significantly to energy expenditure.

**Activity Intensity**

Lightly active minutes represented a larger portion of movement time than fairly active and very active minutes, suggesting that users generally engaged in lower-intensity movement.

**Sedentary Behavior**

Sedentary behavior was consistently high across the dataset, indicating an opportunity to encourage users to incorporate more movement throughout the day.

## Recommendations

Based on the analysis, Bellabeat could:

1. **Reduce sedentary time** through smart inactivity alerts, movement reminders, and short movement goals.
2. **Highlight activity intensity** rather than focusing solely on step counts.
3. **Personalize coaching** based on individual activity patterns.
4. **Improve daily routine awareness** by combining activity, intensity, and sedentary-time metrics.
5. **Strengthen product and marketing messaging** around holistic daily wellness and consistent movement.

## Project Deliverables

- `Bellabeat_Fitbit_Analysis.xlsx` — Cleaned dataset, PivotTables, analysis, and visualizations
- `Bellabeat_Analysis_Presentation.pptx` — Presentation of findings and recommendations

## Skills Demonstrated

Excel | Data Cleaning | Data Validation | Pivot Tables | Data Analysis | Data Visualization | Trend Identification | Business Analysis | Data-Driven Recommendations
