Data Analytics Internship – Project 2 (COVID-19 Global Impact Analysis)

This repository contains my submission for the COVID-19 Global Impact Analysis Project of the Data Analytics Internship.

Dataset - Our World in Data COVID-19 Dataset

Objective - The objective was to analyze reported COVID-19 cases and deaths across selected countries, identify trends over time, compare population-adjusted case and death rates, calculate seven-day rolling averages and reported case fatality ratios, and present key findings through visualizations and an interactive Power BI dashboard.

Tools Used
1. Google Colab
2. Python (Pandas and Matplotlib)
3. Power BI Desktop
4. ReportLab for PDF generation

COVID-19 Global Impact Analysis
1. Used the Our World in Data COVID-19 dataset containing 44,785 records and 41 columns.
2. Selected Brazil, India, Japan, the United Kingdom, and the United States for comparative analysis.
3. Inspected the dataset for missing values, duplicate country-date records, data types, and relevant COVID-19 metrics.
4. Converted date information into a consistent format and prepared the selected-country dataset for analysis.
5. Retained missing values where appropriate rather than automatically replacing them with zero.
6. Created seven-day rolling averages for new cases and new deaths to identify trends while reducing daily fluctuations.
7. Analyzed cumulative reported cases and deaths over time.
8. Compared reported cases and deaths per million people across the selected countries.
9. Calculated the reported case fatality ratio using total reported deaths and total reported cases.
10. Created visualizations using Matplotlib to explore country-level trends and comparisons.
11. Developed an interactive Power BI dashboard containing KPI cards, line charts, country comparison charts, and a country slicer.
12. Prepared an executive summary highlighting the key findings, assumptions, and limitations of the analysis.

Key Results
1. Original Dataset - 44,785 records and 41 columns.
2. Cleaned Selected-Country Dataset - 1,320 records and 17 columns.
3. Countries Analyzed - Brazil, India, Japan, the United Kingdom, and the United States.
4. Study Period - 31 December 2019 to 19 September 2020.
5. Highest Cumulative Cases - United States, with approximately 6.72 million reported cases.
6. Highest Cumulative Deaths - United States, with 198,589 reported deaths.
7. Highest Peak Seven-Day Average of New Cases - India, at approximately 93,199 cases per day.
8. Highest Peak Seven-Day Average of New Deaths - United States, at approximately 2,715 deaths per day.
9. Highest Reported Cases per Million at the End of the Study Period - Brazil, at approximately 21,148 cases per million.
10. Highest Reported Case Fatality Ratio - United Kingdom, at approximately 10.81%.

Key Insights
1. The United States recorded the highest cumulative number of reported cases and deaths among the five selected countries by 19 September 2020.
2. India experienced the highest peak seven-day average of new reported cases, demonstrating the rapid increase in reported infections during the study period.
3. The United States recorded the highest peak seven-day average of new reported deaths among the selected countries.
4. Brazil had a higher reported cumulative case rate per million people than the United States at the end of the study period.
5. The United Kingdom had the highest reported case fatality ratio among the five countries. Differences in testing, case detection, reporting, and the timing of cases and deaths must be considered when interpreting this result.

Recommendations
1. Use seven-day rolling averages alongside daily figures to better understand changes in reported cases and deaths.
2. Compare countries using population-adjusted metrics as well as absolute totals to provide additional context.
3. Monitor cumulative cases, cumulative deaths, and reported case fatality ratios together rather than relying on a single metric.
4. Consider differences in testing, reporting practices, and missing data before drawing conclusions from cross-country comparisons.
5. Update the analysis with newer data when conducting research on current COVID-19 trends.

Files
1. Project_2.ipynb - Google Colab notebook containing data cleaning, analysis, visualizations, and findings.
2. COVID19_Cleaned_Selected_Countries.csv - Cleaned dataset for the five selected countries.
3. COVID19_Executive_Summary.pdf - Executive summary of the project findings.
4. Project 2.pbix - Power BI dashboard containing KPI cards, trend charts, country comparisons, and a country slicer.
5. README.md - Summary of the COVID-19 Global Impact Analysis Project.
6. `DEPLOYMENT.md` - Instructions for opening the project, version control, and the rollback procedure.

Conclusion
The COVID-19 Global Impact Analysis Project was completed using Python, SQL-related data analysis workflows where applicable, and Power BI for interactive visualization. The analysis identified differences in reported cases, deaths, population-adjusted rates, and seven-day trends across five selected countries. The findings demonstrate the value of data cleaning, time-series analysis, and dashboard development in communicating public health information. The results should be interpreted within the limitations of the selected countries, study period, and available data.
