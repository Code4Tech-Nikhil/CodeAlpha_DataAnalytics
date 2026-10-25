# CodeAlpha_DataAnalytics


CodeAlpha Data Analytics Internship Project

Project Description

This repository contains the data analytics projects I completed during the CodeAlpha Internship Program. The projects cover the data analytics workflow, including data collection, cleaning, exploration, analysis, visualization, and interpretation using Python.

Tasks Completed

Task 1: Web Scraping

- Scraped book information from the "Books to Scrape" (https://books.toscrape.com/) website.
- Collected book titles, prices, ratings, and availability.
- Used Python, Requests, and BeautifulSoup for data extraction.

Task 2: Exploratory Data Analysis (EDA)

- Explored and analyzed the collected dataset.
- Identified patterns, trends, and meaningful insights.
- Used Pandas and NumPy for data cleaning, preprocessing, and analysis.

Task 3: Data Visualization

- Created charts and graphs to understand the dataset.
- Analyzed book price and rating distributions.
- Used box plots and statistical techniques to identify potential price outliers.

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Requests
- BeautifulSoup
- Matplotlib
- Seaborn

Dataset Information
The dataset was collected from "Books to Scrape" (https://books.toscrape.com/), a practice website designed for learning web scraping.

The dataset includes:
- Book Title
- Price
- Rating
- Availability

Project Workflow

1. Collected book data through web scraping.
2. Stored the extracted information in a Pandas DataFrame.
3. Cleaned and prepared the dataset for analysis.
4. Performed exploratory data analysis.
5. Created visualizations to identify patterns and trends.
6. Detected potential price outliers using the Interquartile Range (IQR) method.

Key Insights and Results

Price Statistics

- Total books analyzed: 100
- Minimum book price: £10.16
- Maximum book price: £58.11
- Average book price: £34.24
- Median book price: £35.98
- First quartile (Q1): £19.92
- Third quartile (Q3): £48.41

Rating Distribution

Rating| Number of Books| Percentage
1 star| 22| 22%
2 stars| 19| 19%
3 stars| 23| 23%
4 stars| 17| 17%
5 stars| 19| 19%

- Most common rating: 3 stars, with 23 books.
- Least common rating: 4 stars, with 17 books.

Price Outlier Detection

Potential price outliers were evaluated using the Interquartile Range (IQR) method.

- IQR: £28.49
- Lower bound: £0.00
- Upper bound: £91.15
- Number of detected outliers: 0

No statistical price outliers were detected in the dataset. The lowest price (£10.16) and highest price (£58.11) were both within the calculated bounds.

Summary of Findings

- Book prices ranged from £10.16 to £58.11.
- The average book price was £34.24, while the median was £35.98.
- The 3-star category had the highest number of books, with 23 books.
- The rating distribution was relatively balanced across the five categories.
- The IQR method detected no potential price outliers in the dataset.

How to Run the Project

1. Open the required Jupyter Notebook (".ipynb") file from this repository.
2. Open the notebook in Google Colab or upload it to "Google Colab" (https://colab.research.google.com/).
3. Install any required libraries if they are not already available.
4. Run the notebook cells sequentially.
5. Review the generated tables, charts, and analysis results.

Project Files

- "CodeAlpha_Web_Scraping.ipynb" — Web scraping and data collection.
- "CodeAlpha_EDA.ipynb" — Exploratory data analysis.
- "CodeAlpha_Data_Visualization.ipynb" — Data visualization and outlier detection.
- "books_dataset.csv" — Collected dataset.

Learning Outcomes
Through these projects, I gained practical experience in:

- Web scraping and data collection.
- Data cleaning and preprocessing.
- Exploratory data analysis.
- Data visualization and interpretation.
- Statistical outlier detection.
- Using Python libraries for data analytics.

Author
Nikhil Bhardwaj
B.Tech in Artificial Intelligence and Data Science

Acknowledgement
I would like to thank CodeAlpha for providing the opportunity to gain practical experience and strengthen my data analytics skills through hands-on projects.
