# Amazon Women Fashion Sales Dashboard (India, Q2 2022)

## Overview

This project presents an interactive dashboard analyzing Amazon sales data for the women’s fashion category in India during April, May, and June 2022. The goal was to uncover actionable insights into sales trends, customer preferences, and fulfillment patterns, while also demonstrating end-to-end data analytics and visualization skills.

## Why I Created This Report

- **Industry Relevance:** Women’s fashion is a rapidly evolving sector in India, with e-commerce platforms like Amazon playing a pivotal role in shaping consumer trends.
- **Skill Development:** I wanted to showcase my ability to handle real-world data, perform thorough cleaning, and create compelling visualizations using Power BI and Figma.
- **Portfolio Enhancement:** By publishing this project on GitHub, I aim to provide tangible evidence of my data analytics, visualization, and UI/UX design skills to potential employers.

## Insights Gained

- **Sales Trends:** The dashboard highlights monthly sales volumes, revealing peak periods and identifying which subcategories and styles were most popular.
- **Fulfillment Analysis:** All orders were fulfilled via Amazon’s “Easy Ship” service, with expedited delivery being a preferred option for many customers.
- **Geographical Reach:** The data shows strong demand not only in metro cities but also in tier-2 and tier-3 cities, reflecting the growing penetration of online fashion retail across India.
- **Product Preferences:** Ethnic wear such as kurtas and sarees remained popular, but there was also notable growth in western wear and contemporary styles, especially among younger demographics.

## How I Created the Report

### 1. Data Acquisition

- Searched for publicly available Amazon sales datasets relevant to women’s fashion in India for Q2 2022.

### 2. Data Cleaning (Python, Pandas)

- **Initial Dataset:** ~129,000 rows, 24 columns.
- **Cleaning Steps:**
  - Removed ~7,800 rows (about 6%) due to missing or inconsistent values, ensuring data quality while maintaining a robust sample size[4].
  - Dropped columns unrelated to trend analysis (e.g., courier status, promotion IDs).
  - Filled missing values in key columns (e.g., fulfillment method) with logical defaults.
  - Ensured all remaining data was complete and ready for analysis.

### 3. Data Visualization (Power BI)

- Imported the cleaned dataset into Power BI.
- Created visuals to track:
  - Monthly sales and revenue trends.
  - Fulfillment and delivery type breakdowns.
  - Top-selling categories and styles.
  - Geographic distribution of orders.
- Focused on clarity, interactivity, and actionable insights.

### 4. UI/UX Enhancement (Figma & Power BI)

- Designed a modern, user-friendly dashboard layout in Figma.
- Imported the Figma design into Power BI for a polished, professional look.
- Applied finishing touches to ensure the dashboard was visually appealing and easy to navigate.
- Dashboard snapshot - https://github.com/DikshanshRaipure/Amazon-Sales-Analysis/blob/main/Amazon%20Sales%20Report.pdf

## What I Learned

- **Data Cleaning:** Real-world datasets often require significant cleaning. Strategic removal of incomplete data (within a reasonable buffer) can improve analysis without compromising results.
- **Visualization:** Effective dashboards require not just technical skill but also thoughtful design to ensure insights are clear and actionable[5][6].
- **UI/UX Integration:** Combining Figma with Power BI elevated the dashboard’s usability and aesthetics, demonstrating the value of cross-tool workflows.
- **Domain Knowledge:** Gained deeper understanding of the Indian women’s fashion market, including regional and generational trends.
- **Project Documentation:** Learned the importance of clear, structured documentation for reproducibility and professional presentation.

## Acknowledgments

- Data sources: Amazon sales data (publicly available on Kaggle).
- Tools used: Python (Pandas), Power BI, Figma.

*For questions or collaboration, feel free to open an issue or contact me via GitHub.*
