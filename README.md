# 🚕 Uber Trips Data Analysis Using Python

## 📌 Project Objective

To analyze Uber trip data and extract valuable insights related to ride frequency, time-based trends, and operational efficiency. The goal is to use Python-based data analysis techniques to explore patterns in Uber rides and identify actionable insights.

---

## 📁 Dataset

- **File Name**: `Uber Project.ipynb`
- **Source**: Sample Uber dataset (e.g., NYC rideshare data)
- **Key Features**:
  - Date/Time of ride
  - Pickup location
  - Base (code for Uber dispatch centers)
  - Weekday and hour of day (extracted)
  - Latitude & Longitude

---

## ❓ Key Questions Explored

- What are the peak hours for Uber rides?
- Which days have the highest number of trips?
- How does ride frequency vary across months?
- Which bases handle the most rides?
- What are the most common pickup locations?
- Are there any seasonal or hourly trends in ridership?

---

## ⚙️ Workflow

### 🔹 Data Cleaning

- Converted `Date/Time` to datetime format
- Extracted new features: `Hour`, `Day of Week`, `Month`
- Handled missing values (if any)
- Removed duplicates

### 🔹 Data Analysis

- Grouped and aggregated data based on:
  - Hours of the day
  - Days of the week
  - Monthly trends
  - Base usage

### 🔹 Data Visualization

- Libraries Used: `matplotlib`, `seaborn`, `pandas`
- Charts Created:
  - Hourly trip frequency bar chart
  - Trips per weekday bar chart
  - Monthly trends using line plots
  - Heatmaps for day-hour combinations
  - Pie chart for base-wise trip distribution

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📌 Key Insights

- **Peak hours**: Uber usage is highest during 5 PM to 7 PM.
- **Busiest day**: Fridays tend to have the most trips.
- **Base B02617** had the highest ride count.
- Trip frequency shows a **sharp rise during weekends**.
- Certain **locations and hours** dominate Uber demand, useful for surge pricing or driver allocation.

---

## 📸 Sample Visuals



