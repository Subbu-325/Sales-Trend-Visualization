# Sales-Trend-Visualization
# CODTECH-Task1

Name: CHAKIRI SUBRAMANYAM
Company: CODTECH IT SOLUTIONS
ID: CITS5137
Domain: DATA ANALYTICS
Duration: 18th JUNE 2026 to 16th JULY 2026
Mentor: NEELA SANTHOSH KUMAR

## 📊 Project Overview: Sales Trend Visualization

As part of my role at CODTECH IT SOLUTIONS, I completed a sales trend
visualization project on a synthetic retail sales dataset. This project
involved analyzing two years of daily transaction data to uncover revenue
trends, seasonality, and category/region performance. Here's an overview of
what I accomplished:

### Objective

The primary goal was to build a complete data visualization pipeline that
ingests sales data and produces clear, decision-useful charts on revenue
trends over time, by category, and by region.

### Steps Taken

**1. Data Generation and Loading:**
- Generated a synthetic two-year (2024–2025) daily sales dataset using `numpy`/`pandas`, covering 4 regions and 5 product categories.
- Built in realistic seasonal effects (holiday peaks in Nov–Dec, a February dip, weekend boosts, and year-over-year growth).
- Loaded the dataset with `pandas` and parsed dates for time-series analysis.

**2. Data Aggregation:**
- Grouped revenue by month for overall trend analysis.
- Grouped revenue by category and by region for comparative analysis.
- Built a month × category pivot table to study seasonality.

**3. Visualizations:**
- **Monthly Revenue Trend:** Line chart of total monthly revenue across the full period.
- **Revenue by Category:** Bar chart comparing total revenue per product category.
- **Revenue Share by Region:** Pie chart showing each region's contribution to total revenue.
- **Month vs Category Heatmap:** Heatmap visualizing seasonal demand patterns.
- **Year-over-Year Comparison:** Line chart comparing monthly revenue between 2024 and 2025.

### Key Insights

- Revenue peaks consistently in **November–December**, reflecting holiday seasonality.
- **Clothing** and **Electronics** are the strongest-performing categories.
- The **South** region contributes the largest share of total revenue.
- Year-over-year revenue shows a clear upward trend from 2024 to 2025.
- Weekend sales are noticeably higher than weekday sales across all categories.

### Conclusion

This project demonstrated how visualization techniques can transform raw
transactional data into actionable business insights. The trend, category,
regional, and seasonal breakdowns provide a solid foundation for forecasting
and inventory planning.

## Output
##Monthly Revenue Trend
<img width="1210" height="550" alt="01_monthly_revenue_trend" src="https://github.com/user-attachments/assets/b9a4bfe0-ed84-4b76-8d97-e063d17a069f" />
##Revenue by Category
<img width="990" height="550" alt="02_revenue_by_category" src="https://github.com/user-attachments/assets/467edadc-d361-4708-ac6f-d144ebde1e4f" />
##Revenue Share by Region
<img width="770" height="770" alt="03_revenue_share_by_region" src="https://github.com/user-attachments/assets/f2f8f3fa-6d34-4ae4-a42d-42bc15a86b3a" />
##Month vs Category Heatmap
<img width="1100" height="660" alt="04_month_category_heatmap" src="https://github.com/user-attachments/assets/6e98d8bc-a6f9-40cd-993a-fa278d3a75c0" />
##Year-over-Year Comparison
<img width="1210" height="550" alt="05_yoy_comparison" src="https://github.com/user-attachments/assets/bf0d6c5e-d5d5-4910-9e36-5444aa795465" />
## Files in this Repository

- `Sales_Trend_Visualization.ipynb` — full notebook with code and analysis
- `generate_data.py` — script to generate the synthetic dataset
- `data/sales_data.csv` — generated dataset
- `output/` — all generated chart images and summary stats
