# 🏙️ Airbnb Listings EDA Project: New York 2025

---

## 🔍 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on **New York Airbnb listings** to uncover trends and patterns in short-term rentals.  
We used 🐼 **Pandas**, 📊 **Seaborn**, 📈 **Matplotlib**, and 🔢 **NumPy** for data cleaning, visualization, and statistical exploration.

---

## 🎯 Objective  
The goal of this project is to:
1. 📌 Analyze **room types, prices, and availability** across neighborhoods  
2. 🧑‍💼 Understand **host behavior** and listing patterns  
3. 🚨 Detect potential **outliers** in price distributions  
4. 💡 Provide actionable **recommendations** for guests and hosts  

---

## 🗃️ Dataset  
This dataset contains **20,765 entries and 22 features**, including:

- 🆔 `id`: Unique listing identifier  
- 🏠 `name`: Title of the Airbnb listing  
- 👤 `host_name`: Name of the host  
- 🌍 `neighborhood_group`: Borough where listing is located  
- 📍 `latitude`, `longitude`: Geolocation of the listing  
- 💵 `price`: Nightly rental cost  
- 🛏️ `room_type`: Accommodation type  
- ⭐ `reviews_per_month`: Monthly average reviews  
- 📆 `availability_365`: Days available per year  

---

## 🔁 Steps & Workflow

### 🧹 1. Data Cleaning
- 🧼 Handled null values in `price`, `neighborhood`, and `beds`  
- 🕓 Converted `last_review` to **datetime format**  
- 🚫 Removed extreme outliers (e.g., prices > $1,000)

### 📊 2. Exploratory Data Analysis
- 🛌 **Room Type Distribution**: Bar plots show majority listings are **Entire homes/apartments**
- 🏙️ **Neighborhood Insights**:  
  - Manhattan = 💸 most expensive  
  - Brooklyn = more budget options  
- 📅 **Availability Trends**: Correlation heatmap shows relationship between `availability`, `price`, and `reviews`
- 💲 **Price Distribution**: Histogram shows most listings priced between **$50 - $300**
- 📦 **Host Listings**: Boxplots reveal professional hosts with multiple listings
- 💬 **Review Behavior**: Pair plots show how reviews relate to price and availability

### 🧮 3. Data Visualization
- 🔥 Pairplot — price vs reviews & availability  
- 🌡️ Heatmap — correlation among numerical features  
- 📉 Boxplots & Histograms — outlier detection in `price`  
- 📊 Bar Charts — room type and borough distributions

---

## 📌 Key Findings
- 💰 **Manhattan** has the highest average listing prices  
- 🛏️ **Entire homes/apartments** dominate listings  
- ⚠️ Price outliers (e.g., $10,000+) exist and skew averages  
- 📆 Highly available listings get more reviews and lower pricing  
- 🧑‍💼 Some hosts operate **multiple listings**, showing professional hosting trends

---

## ⚙️ How to Run This Project  
1. 🧬 Clone the repository:
   ```bash
   git clone https://github.com/DeepikaKgithub/AirBnb-nyc-EDA.git

2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the **Jupyter notebook** or **Python script**:
   ```bash
   jupyter notebook day23_airbnb_eda.ipynb
   ```

---

## 💡 Recommendations
-For Guests:

 -✅ Choose listings with many reviews and high availability for better experience

 -🏠 Private rooms in Brooklyn = 💸 cost-effective compared to Manhattan

-For Hosts:

 -📈 Increase availability & maintain review quality to boost bookings

 -🎯 Adjust pricing to compete within your neighborhood's average

---

##🔮 Future Work
-🤖 Apply machine learning to predict optimal pricing

-💬 Use sentiment analysis on reviews for deeper guest feedback

-📊 Build an interactive dashboard using Plotly or Tableau



---

## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using **EDA techniques**, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
---
