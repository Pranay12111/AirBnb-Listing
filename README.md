# 🏙️ EDA & Data Visualization – Airbnb Listing 2024 (New York)

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **Data Visualization** of **Airbnb listings in New York City (2024)**. The goal is to uncover insights into pricing trends, neighborhood popularity, availability patterns, and host activity using Airbnb’s open dataset.

By applying data cleaning, transformation, and visualization techniques, we aim to answer key business and customer-oriented questions such as:

* Which neighborhoods are the most popular among Airbnb guests?
* How do prices vary across room types and locations?
* What seasonal or availability patterns can we identify?
* Who are the most active hosts in the city?

---

## 📂 Dataset

* **Source:** Airbnb Open Data (Inside Airbnb or Kaggle)
* **File:** `AB_NYC_2024.csv`
* **Size:** \~48,000+ listings
* **Features Include:**

  * `id` – Listing ID
  * `name` – Listing name
  * `host_id` – Unique host ID
  * `neighbourhood_group` – Borough (Manhattan, Brooklyn, etc.)
  * `neighbourhood` – Local neighborhood
  * `room_type` – Type of property (Entire home, Private room, Shared room)
  * `price` – Price per night (USD)
  * `minimum_nights` – Minimum stay required
  * `availability_365` – Availability throughout the year
  * `number_of_reviews` – Count of reviews received

---

## 🛠️ Tools & Technologies

* **Python** 🐍
* **Libraries:**

  * `pandas` → Data cleaning & manipulation
  * `numpy` → Numerical computations
  * `matplotlib` & `seaborn` → Data visualization
  * `plotly` → Interactive dashboards
  * `folium` → Geospatial mapping

---

## 🔍 Key Steps in EDA

1. **Data Cleaning**

   * Handling missing values
   * Removing outliers (e.g., unrealistic prices & minimum nights)
   * Formatting categorical & numerical features

2. **Univariate Analysis**

   * Distribution of room types, prices, availability
   * Review counts per listing

3. **Bivariate & Multivariate Analysis**

   * Price variation across neighborhoods
   * Correlation between reviews, availability, and pricing
   * Host activity vs. room type preference

4. **Geospatial Visualization**

   * Heatmaps of listings by borough
   * Price distribution across New York City

---

## 📊 Visualizations & Insights

* **Top Neighborhoods:** Identifying the most booked and highly priced areas.
* **Price Analysis:** Detecting average, median, and outlier pricing.
* **Room Type Popularity:** Entire homes vs. private/shared rooms.
* **Availability Trends:** Seasonal or year-round availability patterns.
* **Host Analysis:** Most active hosts and their impact on listings.

---

## 🚀 Project Outcomes

* A **cleaned and well-structured dataset** for analysis.
* **Interactive and static visualizations** highlighting Airbnb trends in NYC.
* **Business insights** that could help hosts optimize pricing and customers make better booking choices.

---

## 📌 Future Scope

* Build a **predictive pricing model** using machine learning.
* Develop a **dashboard in Power BI / Tableau** for dynamic reporting.
* Perform **sentiment analysis** on listing reviews (if available).

---

## 🙌 Acknowledgments

* **Airbnb Open Data** – For providing the dataset.
* **Inside Airbnb** – For detailed NYC Airbnb data.
* **Community** – For open-source tools and visualizations.
