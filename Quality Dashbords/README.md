# Quality Control Dashboard - Senior Management Report

## Project Overview

This Power BI dashboard was created to demonstrate proficiency in data visualization and reporting, specifically tailored for a senior management audience. The primary objective is to provide a clear and concise overview of quality control metrics over a 12-month period, encompassing task completion, sampling, defect and error rates, and overall quality scores. This report offers insights into performance across various dimensions, including individual employee contributions, auditor effectiveness, and temporal trends (monthly and quarterly).

## Data Sources

* **Quality Data**: Main data table.
* **Emp Master**: Employee master table.
* **Auditors**: Auditors table.
* All data are contained within an Excel file (`Sample Data.xlsx`) which is included in the `Data` subdirectory of this project.

## Key Metrics and Visualizations

* **Total # of Tasks**: Provides a total number of tasks, displayed as a card.
* **Total # of Samples**: Displays the total samples count, displayed as a card.
* **Total # of Defects**: Show the total defects count, displayed as a card.
* **Total # of Errors**: Displays the total errors count, displayed as a card.
* **Total Quality Score**: Shows the total quality Score, displayed as a card.
* **Sampling %**: Visualized using a Donut chart to show the sampling percentage.
* **Defect %**: Donut chart displaying the defect percentage.
* **Fatal Errors**: Bar chart showing fatal error rates.
* **Sampling % by Auditor**: Bar chart comparing sampling percentages by different auditors.
* **Fatal Errors by Month**: Shows fatal errors trend by month.
* **Quality Score % for each Employee**: Displays the quality score percentage for each Employee using a scatter plot.
* **Total Quality Score by Supervisor**: bar chart shows the total quality Score by supervisor.
* **Total sample & Defects for Each Employee**: Displays a bar chart for sample and defects.
* **Location Map**: the locations of samples.

## Data Relationships

The dataset comprises three tables (Quality Data, Emp Master, Auditors) linked through a common key, enabling comprehensive analysis across different dimensions.

## Technical Details

* This report utilizes Power BI’s visualization capabilities to present data in an accessible format for executive decision-making.
* All relationships between tables where created inside power bi.
* No DAX was utilized to produce this project.
* Power query was used to clean up the data.
* Visuals include cards, donut charts, bar charts, scatter plots, and maps, each chosen for their ability to convey specific information effectively.

## Project Structure

PowerBI-Dashboards/ └── My_project_PB/ ├── Data/ │ └── Sample Data.xlsx ├── My_project_PB.pbix └── README.md

## Usage * Open the `My_project_PB.pbix` file using Power BI Desktop. * Review the visualizations to understand the quality control metrics. * Interacting with the report by clicking on various graphs is supported. ## Author * [Moshe Rechtman] - [https://www.linkedin.com/in/moshe-rechtman-08131b62]
