📊 Exploratory Data Analysis (EDA) Project

This repository contains structured Exploratory Data Analysis for four different datasets covering bikes, cars, Amazon products, and Spotify tracks.

📁 EDA 1 - Bike Details Dataset

Goal: Understand the resale bike market and factors impacting prices.

Data Features:

name, selling_price, year, seller_type, owner, km_driven, ex_showroom_price

Key Analysis:

Price distribution and median

Ownership patterns and kilometers driven

Missing values and outlier detection (IQR)

Depreciation and correlation heatmap

🚗 EDA 2 - Car Sales Dataset

Goal: Explore second-hand car market and consumer behavior.

Data Features:

Company, Model, Price, Annual Income, Transmission, Dealer Region, etc.

Key Analysis:

Average price by dealer and region

Price variation by gender and income

Car model popularity

Correlation between price, engine size, and income

🛍️ EDA 3 - Amazon Sales Dataset

Goal: Examine ratings, pricing, and popularity of Amazon products.

Data Features:

product_name, category, discounted_price, actual_price, rating, rating_count

Key Analysis:

Rating analysis by category

Discount vs. pricing patterns

Most reviewed and popular items

Correlation between rating and price

🎵 EDA 4 - Spotify Music Dataset

Goal: Analyze popularity trends in hip-hop music tracks.

Data Features:

Artist, Track Name, Popularity, Duration (ms), Track ID

Key Analysis:

Popularity distribution

Most/least popular tracks

Track duration and popularity correlation

Artist-wise duration and popularity comparison (violin, swarm, scatter plots)

⚙️ Tools Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Google Colab / Jupyter Notebook

📆 Folder Structure

EDA_Project/
├── EDA_1_Bike_Data.ipynb
├── EDA_2_Car_Sales.ipynb
├── EDA_3_Amazon_Sales.ipynb
├── EDA_4_Spotify_Tracks.ipynb
├── data/
│   ├── bike.csv
│   ├── car.csv
│   ├── amazon.csv
│   └── spotify.csv
└── README.md
