# Hotel-Booking-Analysis-

## Overview
This data analysis project investigates hotel booking patterns using the **Hotel Booking Demand Dataset**. It focuses on identifying trends in bookings by country, determining the best time to book a hotel, and finding the optimal length of stay for favorable rates. The dataset was loaded from `hotel_bookings.csv` using Pandas and analyzed through visualizations and statistical summaries.

---

## Dataset
- **File:** `hotel_bookings.csv`  
- **Source:** [Hotel Booking Demand Dataset on Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)  
- **Records:** 119,390 rows  
- **Features:** Hotel type, lead time, arrival date, length of stay, number of guests, booking channel, cancellation status, average daily rate (ADR), and more.

---

## Objectives
- Load and explore the dataset
- Clean and preprocess missing or inconsistent values
- Visualize booking trends by:
  - Country
  - Month
  - Hotel type
- Analyze average daily rates (ADR) and booking channels
- Extract actionable insights for hotel managers and booking platforms

---

## Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas`, `numpy` (data manipulation)
  - `matplotlib`, `seaborn` (visualizations)

---

## Sample Visualizations

### 1. ADR by Month  
**May** recorded the lowest average daily rate (ADR), making it the most cost-effective month to book a hotel, followed by **April** and **October**. 

### 2. Hotel Type Distribution  
**66.4%** of guests booked **City Hotels**, while **33.6%** booked **Resort Hotels**.  

### 3. Top Booking Countries  
The highest number of bookings came from **Portugal (PRT)**.  

### 4. Booking Channel  
A majority of bookings were made via **Online Travel Agents (OTA)**.  

---

## Key Insights
- **Best Month to Book:** May offers the lowest ADR, followed by April and October.
- **Booking Channel:** Most guests used **Online Travel Agents (OTA)**.
- **Hotel Preference:** City Hotels are more popular, accounting for over 66% of bookings.
