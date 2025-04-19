# restaurant-analysis-hackathon

# 🍽️ Zomato Bangalore Restaurant Trends - Data Analysis & Visualization

This project focuses on cleaning, analyzing, and visualizing Zomato restaurant data for Bangalore to uncover insights and help make informed business decisions.

## 📊 Objective

- Understand food trends in Bangalore using Zomato data
- Analyze restaurant types, ratings, votes, costs, and geolocation
- Help Zomato identify profitable and high-potential areas for investment
- Build insightful visualizations using tools like `matplotlib`, `seaborn`, and `folium`

---

## 📁 Dataset

- **Primary Source**: Zomato Restaurants in Bangalore
- **Columns Used**:
  - Restaurant details: name, rest_incity, rest_intype, cuisines
  - Order-related: online_order, book_table, votes, rate
  - Cost-related: approx_costfor_two_people
  - Geographical data: longitude, latitude (merged for mapping)

---

## ⚙️ Key Features

- Data cleaning & preprocessing (null handling, type conversions)
- Merging datasets (e.g., restaurant info + coordinates)
- Exploratory Data Analysis (EDA)
- Geospatial visualization using Folium
- Insights generated through queries like:
  - Top-rated restaurant type with >1000 votes
  - Most profitable area based on cost × votes
  - Restaurant types to improve to reduce customer complaints
  - Locations with highest diversity in cuisines
  - Online order trends in specific localities

---

## 📌 Sample Insights

- **Top-rated restaurant type (>1000 votes)**: Casual Dining
- **Most profitable area**: Koramangala 7th Block
- **Lowest rated type (needs improvement)**: Quick Bites
- **Area for expansion**: BTM for its cuisine diversity
- **Best area for online orders**: Banashankari (based on vote share)

---

## 🛠️ Tools & Technologies

- **Language**: Python
- **Libraries**:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`, `seaborn`  
  - `folium` (for geospatial visualization)  
  - `re` (for cleaning strings)

---

## 📦 Setup & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Srijareddy01/zomato_analysis.git
   cd zomato_analysis
   pip install pandas numpy matplotlib seaborn folium
   jupyter notebook Zomato_Bangalore_Analysis.ipynb
## 🧹 Preprocessing Steps
-**Removed duplicate entries and null values**
-**Converted columns like approx_costfor_two_people to numeric**
-**Binary encoded online_order and book_table columns**
-**Cleaned rate column (removed /5, converted to float)**
-**Merged with coordinate dataset using location**

## 🗺️ Visualization Samples
Folium maps showing cuisine spread and order density

## 📧 Contact
Palla Srija
Email: srijapalla01@gmail.com
GitHub: @Srijareddy01
