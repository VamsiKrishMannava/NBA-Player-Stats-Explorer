NBA Player Stats Explorer
Description
This Streamlit application allows users to explore NBA player statistics from Basketball-reference.com. Users can select a specific year, filter data by teams and positions, and visualize intercorrelations between player statistics.

Features
Data Source: Basketball-reference.com
Technologies Used: Python, Streamlit, Pandas, Base64, Matplotlib, Seaborn, NumPy
Functionalities
Web scraping NBA player stats for a selected year
Filtering player stats by team and position
Displaying filtered player stats in a table
Downloading filtered player stats as a CSV file
Visualizing intercorrelations between player statistics with a heatmap
Web Scraping
The application uses the Pandas library to scrape NBA player statistics from Basketball-reference.com. Specifically, the pd.read_html function reads the HTML table containing player stats for a selected year. The data is cleaned by removing redundant headers and filling missing values to ensure it is ready for analysis. The cleaned data is stored in a DataFrame, making it easy to filter and manipulate based on user inputs.

Utility of Player Stats
These statistics are incredibly useful for teams, analysts, and fans as they provide detailed insights into player performance. By filtering stats by team and position, users can:

Compare player performance across different teams and positions.
Identify key players and their contributions to the team.
Make data-driven decisions for team management, such as player trades, training focus areas, and game strategies.
Project Insights
Working on this project has enhanced my understanding of several key concepts and skills:

Web Scraping: Extracting and cleaning data from web pages using Python.
Data Filtering: Manipulating large datasets based on user-defined criteria.
Data Visualization: Creating informative visualizations to uncover patterns and correlations in the data.
Streamlit Framework: Building interactive web applications for real-time data exploration and analysis.
Statistical Analysis: Identifying relationships between different statistical measures through intercorrelation heatmaps.
Usage
Open the application in your web browser.
Use the sidebar to select a year, filter by teams, and filter by positions.
View the filtered player stats in the main area of the application.
Download the filtered data as a CSV file by clicking the provided download link.
Click the "Intercorrelation Heatmap" button to view a heatmap of correlations between player statistics.
