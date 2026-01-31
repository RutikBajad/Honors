# Honors

# 📊 Comparative Analysis of Daily Temperatures Across Cities

## 📌 Project Overview

This project performs a **comparative statistical analysis of daily temperatures across different cities** using **mean, median, and mode**, along with **visualizations** to understand temperature distributions and trends.

The analysis helps identify:

* Which city is warmer on average
* How temperatures are distributed
* Variability and trends in daily temperatures

---

## 📂 Dataset

* **File name:** `city_temperature_dataset - city_temperature_dataset.csv`
* **Required columns:**

  * `City` → Name of the city
  * `Temperature` → Daily temperature values (in °C)

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **NumPy**
* **Pandas**
* **Seaborn**
* **Matplotlib**
* **Statistics module**

---

## ⚙️ Features Implemented

### 1️⃣ Descriptive Statistics

For each city:

* **Mean** – Average temperature
* **Median** – Middle value of temperatures
* **Mode** – Most frequently occurring temperature(s)

### 2️⃣ Visualizations

The following plots are generated:

* **Histogram with KDE** – Distribution of temperatures by city
* **Box Plot** – Comparison of temperature spread and variability
* **Line Plot** – Daily temperature trends across cities

---

## 🧪 Code Workflow

1. Load dataset using Pandas
2. Explore dataset structure
3. Visualize temperature distributions
4. Calculate mean, median, and mode city-wise
5. Print statistical results

---

## ▶️ How to Run the Project

1. Install required libraries:

   ```bash
   pip install numpy pandas seaborn matplotlib
   ```

2. Place the dataset CSV file in the project directory.

3. Run the Python script:

   ```bash
   python temperature_analysis.py
   ```

---

## 📈 Output

* Graphical plots displaying temperature distributions and trends
* Printed statistical measures:

  * Mean temperature per city
  * Median temperature per city
  * Mode temperature(s) per city

---

## 🧠 Interpretation

* Cities can be compared based on **average temperature**
* **Box plots** reveal variability and outliers
* **Line plots** help observe temperature trends over time
* **Mode values** indicate commonly occurring temperatures

---

## 🚀 Future Enhancements

* Add standard deviation and variance
* Include date-based time series analysis
* Support more cities and longer datasets
* Export results to Excel or PDF reports

---

## ✍️ Author: Rutik R Bajad

*Comparative Temperature Analysis Project*

---

