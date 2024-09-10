# Metrocar - Data Analytics Project

## Overview

This repository contains a data analytics project focused on optimizing Metrocar's platform performance and user funnel through various analyses such as conversion rates (CVR), and platform budget allocation. The project aims to provide actionable insights for Metrocar's decision-making process by analyzing data related to app usage, age demographics, platform distribution, and ride funnel drop-offs. The final goal is to improve app functionality, pricing strategies, and overall customer experience.

This project was conducted for educational purposes, showcasing data research and analysis in both Python and SQL. It serves as a learning resource for applying data science techniques to real-world business problems.

## Project Structure

- **Data Source**: The dataset includes ride requests, user information, and platform performance statistics across iOS, Android, and Web platforms. Data was processed using Python and popular data analysis libraries, along with SQL for data extraction and manipulation.
- **Conversion Rate Analysis**: The project includes funnel analysis to identify bottlenecks and optimize the app’s conversion rates at different stages (e.g., app download to signup, ride request to ride completion).
- **Platform Budget Allocation**: A key insight into platform performance reveals the need for higher budget allocation to iOS due to stronger CVR and user engagement.
- **Demographics Analysis**: The project explores user demographics (age groups) and their influence on platform engagement and conversion rates.

## Data Pipeline

### 1. Data Extraction
The data was extracted from internal Metrocar databases using both Python and SQL. The SQL queries were used for filtering, joining tables, and gathering specific user and ride data. This dual approach demonstrates the use of SQL for efficient data extraction before processing the data in Python.

### 2. Funnel Analysis
Conversion rates (CVRs) were calculated for each stage of the funnel:

- App Download → Signup: 53% drop-off
- Ride Accepted → Ride Completed: 49% drop-off
- Ride Completed → Ride Paid: 3% drop-off

Insights derived from this funnel led to recommendations to improve app usability, introduce loyalty programs, and enhance customer-driver interactions.

### 3. Platform Budget Allocation
An analysis of platform performance indicates that the highest CVRs come from iOS users, making it a priority for budget allocation, particularly in the US market, where iPhone users have higher average incomes. This analysis is crucial for targeting high-revenue markets and devices.

### 4. Age Group Analysis
Primary demographics identified were users aged 35-44 (29.4%) and 25-34 (19.6%). The conversion rates for different age groups showed minor variations, but a significant portion (30.1%) of users is classified as "Unknown," making it difficult to target specific age groups effectively.

### 5. Price Strategy
A surge pricing strategy was developed based on ride request patterns throughout the day and across weekdays versus weekends. Peak hours were identified between 8-9 AM and 4-7 PM on weekdays, and pricing recommendations include:

- Increase prices during peak hours
- Adjust pricing for midday and evening demand fluctuations

### 6. Ride Funnel Optimization
The largest drop-off (49%) occurred from "Ride Accepted" to "Ride Completed." Further analysis revealed no significant technical or device issues, leading to recommendations for app and driver improvements:

- Enhance the ride confirmation process
- Provide driver training for app proficiency
- Offer loyalty programs and first-ride discounts

## Results

### Key Insights
- **Platform Allocation**: iOS users show the highest initial interest and engagement, making them the primary target for future marketing and budget allocation.
- **Age Group Consistency**: There is no significant variation in CVRs among identified age groups, but a significant percentage of users remain uncategorized.
- **Price Strategy**: Surge pricing should be applied during morning and evening peaks, with possible adjustments during midday to boost demand.
- **Ride Funnel Drop-Offs**: The largest drop-off occurs at the "Ride Accepted to Ride Completed" stage, necessitating both app improvements and enhanced driver support.

### Evaluation Metrics
- Conversion rates were measured across the funnel stages to identify significant drop-offs.
- User sentiment was analyzed using review data, revealing common negative experiences such as driver unprofessionalism and ride discomfort.

## Key Libraries

- **Pandas**: For data extraction and manipulation.
- **SQLAlchemy**: For database connection and querying with SQL.
- **Matplotlib/Seaborn**: For data visualization and trend analysis.

## Conclusion and Recommendations

The project provides insights into optimizing Metrocar's app performance, with actionable recommendations to improve conversion rates, allocate platform budgets efficiently, and implement a dynamic pricing strategy. Future efforts should focus on refining the app experience, enhancing driver training, and increasing user engagement through loyalty programs and promotions.

This project demonstrates applying the same data research and analysis approach using both SQL and Python in a business context.

## Co-authors:
- [Lana Frenzel](https://github.com/lanafrenzel)
- [Claire Briatore](https://github.com/clairebriatore)
- [Prudensy Opit](https://github.com/prudensy)
- [Rama Al Homsi](https://github.com/rama-alhomsi)
