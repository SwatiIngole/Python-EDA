🌍 Web Scraping & Exploratory Data Analysis – Manali Tour Packages
📌 Project Overview

This project focuses on extracting and analyzing tour package data for Manali from TravelTriangle.

The main objective was to collect unstructured web data, transform it into a structured dataset, and perform Exploratory Data Analysis (EDA) to generate meaningful business insights related to pricing, destinations, duration, and hotel ratings.

🎯 Problem Statement

Travel information on tour package websites is often scattered across multiple pages and formats, making it difficult for users to:

Compare package prices

Understand duration and inclusions

Evaluate hotel ratings

Identify popular destinations

This project aims to scrape, clean, analyze, and visualize this data in a structured and insightful way.

🛠️ Tools & Technologies Used

Python

Requests – For sending HTTP requests

BeautifulSoup – For parsing HTML content

Pandas – For data cleaning and transformation

Matplotlib & Seaborn – For data visualization

🔎 Data Collection Process

Identified the target URL of Manali tour packages.

Sent HTTP requests using headers to fetch webpage content.

Parsed HTML structure using BeautifulSoup.

Extracted relevant fields:

Package Title

Destination

Duration (Days/Nights)

Original Price

Hotel Rating

Converted raw extracted data into a structured Pandas DataFrame.

🧹 Data Cleaning & Preparation

Removed duplicate records

Handled missing values

Converted price columns into numeric format

Standardized rating and duration columns

Structured dataset for analysis

📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

1️⃣ Price Distribution

Prices are right-skewed, indicating that most packages are budget-friendly.

A small number of high-priced packages represent premium/luxury tours.

2️⃣ Popular Destinations

Few top destinations dominate the majority of travel packages.

Other destinations contribute a smaller market share.

3️⃣ Hotel Rating Analysis

Ratings are mostly clustered between 3 to 4 stars, indicating good service quality.

Very few low ratings observed.

4️⃣ Price vs Rating Relationship

Positive relationship observed.

Higher-priced packages generally have better ratings.

5️⃣ Duration vs Price

Longer-duration packages tend to cost more.

Price variation within similar durations suggests influence of additional factors like quality and inclusions.

💡 Key Business Insights

Budget packages dominate the market demand.

Premium packages provide higher satisfaction levels.

Clear segmentation exists between budget and premium travelers.

Travel platforms can optimize pricing strategies using data-driven insights.

🚀 Project Outcome

This project successfully demonstrates:

Real-world web scraping

Data cleaning & transformation

Exploratory data analysis

Business insight generation

Data visualization

It strengthened my skills in handling unstructured web data and converting it into actionable insights using Python.

📌 Future Improvements

Automate scraping for multiple destinations

Store data in SQL database

Build interactive dashboard using Power BI or Streamlit

Perform predictive analysis on pricing trends

