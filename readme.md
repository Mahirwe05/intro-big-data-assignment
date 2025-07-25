
# Big Data Assignment: Uber Dataset Analysis with Power BI


## 1. Introduction
This project focuses on analyzing Uber ride data using big data techniques and Power BI visualizations. The primary objectives are to explore, clean, and visualize the Uber dataset to uncover trends, patterns, and actionable insights that can inform business decisions and improve operational efficiency.

## 2. Methodology
### Data Collection
- The raw Uber dataset (`uber.csv`) was sourced from [Kaggle/Uber](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) and contains detailed records of Uber rides.

### Data Cleaning & Preprocessing
- Removed duplicate records to ensure data quality.
- Addressed missing or null values in key columns.
- Standardized date and time formats for consistency.
- Engineered new features (e.g., ride duration, day of week) to enhance analysis.
- Exported the cleaned dataset as `uber_cleaned_dataset.csv` for use in Power BI.

### Data Analysis & Visualization
- Imported the cleaned dataset into Power BI (`intro-big-data-powerbi.pbix`).
- Created interactive dashboards to visualize ride trends, locations, peak times, and more.
- **uber.csv**: The raw dataset containing Uber ride records.
- **uber_cleaned_dataset.csv**: The cleaned and preprocessed version of the Uber dataset, ready for analysis and visualization.

## 3. Analysis
The analysis was conducted using Power BI dashboards and statistical summaries. Key areas explored include:
- **Total Rides Over Time**: Trends in ride volume by day, week, or month.
- **Popular Pickup/Dropoff Locations**: Identification of high-demand areas using heatmaps and bar charts.
- **Peak Hours and Days**: Analysis of ride frequency by hour and day of the week.
- **Trip Duration and Distance**: Distribution and averages to understand ride characteristics.
- **Revenue Analysis**: (If fare data is available) Insights into revenue trends and patterns.
- **Power BI**: For data visualization and dashboard creation (`intro-big-data-powerbi.pbix`).
- **Python/Excel/Other Tools (if used)**: For data cleaning and preprocessing (not included in this repo, but cleaning steps are described below).

## 4. Results
### Key Discoveries
- The busiest times for Uber rides are weekday mornings and evenings, indicating strong commuter demand.
- Certain neighborhoods consistently show higher ride demand, suggesting potential areas for targeted marketing or resource allocation.
- Average trip duration and distance vary by time of day and location, providing insights into rider behavior and operational planning.
```
├── intro-big-data-powerbi.pbix         # Power BI dashboard file
├── uber.csv                            # Raw Uber dataset
├── uber_cleaned_dataset.csv            # Cleaned Uber dataset
├── readme.md                           # Project documentation
```

## 5. Conclusion
The analysis of the Uber dataset revealed clear temporal and spatial patterns in ride demand. Understanding these patterns can help Uber optimize driver allocation, improve customer satisfaction, and increase operational efficiency. The use of Power BI enabled the creation of interactive dashboards for deeper exploration and communication of insights.
1. **Remove Duplicates**: Checked for and removed duplicate records to ensure data quality.
2. **Handle Missing Values**: Identified and addressed missing or null values in key columns.
3. **Format Dates/Times**: Standardized date and time formats for consistency.
4. **Feature Engineering**: Created new columns (e.g., ride duration, day of week) to enhance analysis.
5. **Export Cleaned Data**: Saved the cleaned dataset as `uber_cleaned_dataset.csv` for use in Power BI.

## 7. How to Use
1. **Open Power BI Dashboard**: Double-click `intro-big-data-powerbi.pbix` to open in Power BI Desktop.
2. **Explore Visualizations**: Interact with the dashboard to explore different aspects of the Uber data.
3. **Modify or Extend**: Use the cleaned dataset to create new visualizations or perform further analysis.



## 8. Credits
- Dataset Source: [Kaggle/Uber](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) *(or specify actual source)*
- Project by: Mahirwe Yvette

## 9. License
This project is for educational purposes only.
