Deployment Configuration and Rollback Evidence

1. Deployment Overview
This project is delivered as a local Power BI Desktop dashboard supported by a cleaned dataset, Python notebook, and executive summary.

The project has not been published as a live web application or Power BI Service report.

2. Deployment Configuration

Requirements
1.Power BI Desktop
2.The cleaned COVID-19 dataset in CSV format
3.The project Power BI report (`.pbix` file)

Setup Instructions
1. Download or clone the public GitHub repository.
2. Keep the Power BI report and cleaned CSV in an accessible project folder.
3. Open Project 2.pbix in Power BI Desktop.
4. If Power BI requests the dataset location, update the file path to COVID19_Cleaned_Selected_Countries.csv.
5. Refresh the data if required.
6. Verify that the KPI cards, line charts, bar charts, and country slicer work correctly.

3. Version Control
GitHub is used to maintain the project files and track changes through commits.
Meaningful commit messages should describe changes to the dashboard, dataset, notebook, and documentation.

4. Rollback Procedure
If a new change causes a problem:
1. Open the project's GitHub repository.
2. Locate the previous working commit using the commit history.
3. Restore the affected file from the previous version, or revert the relevant commit.
4. Open the restored Power BI report in Power BI Desktop.
5. Verify that the report opens and its visuals work correctly.

5. Rollback Evidence
Evidence will be added after a rollback test has been performed.
The evidence should include:
A screenshot of the GitHub commit history showing the original and test changes.
A screenshot or other record showing the previous working version was restored.
Confirmation that the restored project file opens and the dashboard visuals work.

6. Status
Deployment method: Local Power BI Desktop report.
Rollback status: Pending practical test and verification.
Evidence status: To be added after testing.
