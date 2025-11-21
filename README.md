🏙️ Hyderabad Real Estate Web Scraping & Data Analysis
📌 Overview

This project focuses on extracting real estate data related to Flats for Sale in Hyderabad from a public listing platform using web scraping techniques. The collected dataset was cleaned, transformed, and analyzed to uncover pricing patterns, location-wise trends, and market insights.

🔍 Project Objectives

Scrape flat listings from a real-estate website.

Convert raw HTML content into a structured dataset.

Clean and preprocess the data for analysis.

Analyze pricing trends, property distribution, and influential factors.

Visualize insights to understand the Hyderabad property market.

🛠️ Tools & Technologies
Purpose	Tools
Web Scraping	Python, Requests, BeautifulSoup
Data Cleaning & Processing	Pandas, Regex
Visualization	Matplotlib, Seaborn
File Format	CSV
📥 Data Collected

The following fields were extracted:

Location

Price (converted to Lakhs)

BHK

Facing

Property Type

Property Name

Area (Sq. Ft)

Property Status (Ready / Under Construction)



🧹 Data Cleaning Steps

Removed special characters (₹, \n, extra spaces, text noise).

Extracted numeric values for Price, BHK, and Area using Regex.

Converted all price formats (Lakhs / Crores) into a single numeric unit (Lakhs).

Handled missing values using mean/mode.

Dropped irrelevant entries (like Studio / RK listings).

Converted final cleaned columns into correct data types.

📊 Key Insights from Analysis

Most flats fall within the 80–250 Lakhs range, showing strong demand for mid-range housing.

Western Hyderabad (Narsingi, Kokapet, Kondapur) shows the highest listing density and price growth.

Price increases with both BHK count and Area, indicating a strong positive correlation.

Ready-to-Move homes show wider price variation compared to Under-Construction properties.

Area has the strongest influence on price, followed by BHK.

🧪 Visualizations Included

Histogram (Price Distribution)

Bar Plot (Top Locations by Listings)

Violin Plot (Price Variation by Location)

Scatter Plot (Area vs Price by BHK)

Correlation Heatmap

Pair Plot (Price, Area, BHK vs Property Status)

❓ Key Business Questions Answered

What locations have the highest availability of flats?

How do prices vary across BHK configurations?

Which areas are luxury vs budget-friendly?

Do Ready-to-Move properties cost more?

What factors influence pricing the most?

🚧 Challenges Faced

Inconsistent price units (Lakhs/Crores)

Missing values like "Price on Request"

Complex patterns requiring regex extraction

Paginated website structure

Converting raw scraped text into structured numeric format

📁 Project Workflow
Scraping → Cleaning → Transformation → Analysis → Visualization → Insights# WebScraping-Project
