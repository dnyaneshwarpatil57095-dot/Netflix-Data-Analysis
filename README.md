Netflix Movies & TV Shows Data Analysis

# Project Overview
This project analyzes the Netflix Movies & TV Shows dataset using Python and Pandas. The objective is to understand the dataset, clean the data, perform exploratory data analysis (EDA), create visualizations, and generate business insights and recommendations based on the findings.

# Dataset Information
**Dataset Name:** Netflix Movies & TV Shows
**Source:** Kaggle
The dataset contains information about movies and TV shows available on Netflix, including:
* Show ID
* Type (Movie/TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre (Listed In)
* Description

## Tools and Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* GitHub

## Project Objectives
1. Load and inspect the dataset.
2. Clean and preprocess the data.
3. Perform exploratory data analysis.
4. Create visualizations to identify trends and patterns.
5. Generate business insights and recommendations.

## Data Cleaning Steps
The following preprocessing steps were performed:
* Filled missing values in Director, Cast, and Country with "Unknown".
* Filled missing Rating values using the most frequent rating.
* Converted Date Added column to datetime format.
* Removed duplicate records.
* Verified data types and handled invalid dates.

## Exploratory Data Analysis Questions
The following questions were answered:
1. How many Movies and TV Shows are available on Netflix?
2. Which countries produce the most Netflix content?
3. Which release years have the highest number of titles?
4. What are the most common content ratings?
5. Which genres are most frequently available on Netflix?

## Visualizations
The following charts were created:
1. Bar Chart – Movies vs TV Shows
2. Line Chart – Netflix Releases Over Years
3. Histogram – Distribution of Release Years
4. Scatter Plot – Movie Releases by Year
5. Pie Chart – Content Distribution
6. Heatmap – Correlation Between Release Year and Year Added
7. Bar Chart – Top 10 Countries Producing Netflix Content
8. Bar Chart – Most Common Ratings

## Key Findings
### 1. Movies Dominate Netflix
Movies make up a significantly larger portion of Netflix's catalog compared to TV Shows.

### 2. Rapid Growth After 2015
The number of titles released increased substantially after 2015, indicating rapid content expansion.

### 3. United States Leads Content Production
The United States contributes the highest number of titles available on Netflix.

### 4. Mature Audience Content is Common
TV-MA and TV-14 are among the most common ratings, showing a strong focus on mature and teenage audiences.

### 5. International Movies and Dramas are Popular
International Movies and Drama categories appear frequently in the dataset, indicating strong global demand.

## Business Recommendations
1. Increase investment in original TV Shows to balance the content portfolio.
2. Expand content production partnerships in emerging markets.
3. Continue investing in popular genres such as Dramas and International Movies.
4. Maintain focus on content for mature and teenage audiences.
5. Continue the content expansion strategy that has driven growth since 2015.

## Repository Structure
Netflix-Data-Analysis/
├── netflix_analysis.ipynb
├── netflix_titles.csv
├── README.md
└── screenshots/
    ├── chart1.png
    ├── chart2.png
    ├── chart3.png
    ├── chart4.png
    ├── chart5.png
    └── chart6.png   ,etc.


## Author
**Dnyaneshwar Patil**
AIML Student , Data Analytics Project.