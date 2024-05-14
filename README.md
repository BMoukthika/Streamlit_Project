# Streamlit_Project

This is a Streamlit application for exploring and visualizing data from a dataset, particularly focusing on analyzing sales data from a sample superstore. Here's a brief overview of what the script does:

1. **Imports**: The script imports necessary libraries such as Streamlit, Plotly Express, Pandas, and warnings. It also sets up warning suppression for cleaner output.

2. **Page Configuration and Title**: It sets the page configuration, including the page title and icon.

3. **File Upload and Data Loading**: Allows the user to upload a file (CSV, TXT, XLSX, or XLS) containing the dataset. If no file is uploaded, it loads a default dataset from the local directory.

4. **Date Range Selection**: Enables the user to select a date range for filtering the data based on order dates.

5. **Sidebar Filters**: Provides sidebar filters for selecting regions, states, and cities to further filter the dataset.

6. **Visualization**: Generates visualizations such as bar charts, pie charts, line charts, treemaps, scatter plots, and tables based on the filtered data.

7. **Data Download**: Allows users to download filtered data as CSV files.

8. **Time Series Analysis**: Conducts time series analysis on sales data.

9. **Summary Tables**: Displays summary tables and pivot tables for insights into sales data.

10. **Download Original Dataset**: Provides an option to download the original dataset.

The script leverages Streamlit for building interactive web applications with simple Python scripts. It integrates seamlessly with Plotly Express for creating interactive visualizations and Pandas for data manipulation. This application is useful for exploratory data analysis and gaining insights into sales data from the sample superstore dataset.
