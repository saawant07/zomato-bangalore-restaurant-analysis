# Zomato Bangalore Restaurant Analysis

## 📊 Project Overview

An exploratory data analysis project using Zomato restaurant data from Bangalore to understand restaurant ratings, pricing, locations, dining vs delivery experiences, and cuisine trends.

The goal is to turn restaurant data into practical business insights for someone planning to open or grow a restaurant in Bangalore.

## 🎯 Business Questions

This analysis explores:

1. Which Bangalore areas have the highest-rated restaurants?
2. Does spending more mean getting a better dining experience?
3. Are delivery ratings higher or lower than dinner ratings?
4. Which cuisines are most common, and which are most loved?
5. What opportunities and risks can be identified from the data?

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### 1. Area Analysis

Compared average dinner ratings across Bangalore areas while considering only areas with at least 10 rated restaurants.

**Key finding:**  
St. Marks Road had the highest average dinner rating among the qualifying areas, followed by Residency Road and Koramangala 6th Block.

### 2. Price vs Rating

Restaurants were grouped into Budget, Mid-range, and Premium categories based on average cost.

**Key finding:**  
Premium restaurants had an average dinner rating of approximately 3.92, compared with approximately 3.55 for Budget and 3.56 for Mid-range restaurants.

This suggests that higher-priced restaurants tend to receive better ratings in this dataset, although price alone does not guarantee a better experience.

### 3. Dinner vs Delivery

Compared dinner ratings and delivery ratings for restaurants where both ratings were available.

**Key finding:**  
Delivery ratings were higher on average (3.93) than dinner ratings (3.65).

The difference varied considerably between restaurants, meaning the delivery experience is not consistently better for every restaurant.

### 4. Cuisine Analysis

The comma-separated cuisine data was split and analyzed to compare cuisine popularity and customer ratings.

**Most common cuisines:**
- North Indian
- Beverages
- Chinese
- Desserts
- Fast Food

**Highly rated less-common cuisines:**
- Bar Food
- European
- Steak
- Japanese

## 💡 Business Insights

- **Opportunity:** Less common cuisines such as Bar Food, European, and Steak showed strong average ratings and could represent promising niches.
- **Location:** Areas such as St. Marks Road and Residency Road showed strong average dinner ratings and could be worth investigating for a new restaurant.
- **Pricing:** Premium restaurants received higher average ratings, suggesting that customers may value the experience offered at higher price points.
- **Delivery:** Delivery received higher average ratings than dinner, highlighting the importance of maintaining a strong delivery experience.
- **Competition:** Popular cuisines such as Street Food, South Indian, and Fast Food had comparatively lower ratings, so entering these categories would require a clear quality or customer-experience advantage.

## 📁 Project Structure

```text
zomato-bangalore-restaurant-analysis/
│
├── README.md
└── zomato_eda.ipynb
