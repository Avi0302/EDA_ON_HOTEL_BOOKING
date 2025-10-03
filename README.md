# 🏨 EDA - Hotel Booking Analysis

This project was completed as part of the **Almabetter program** with the goal of analyzing and understanding the business performance of a **Hotel Group** that owns two hotels:  
- **City Hotel**  
- **Resort Hotel**

The dataset spans **3 years (2015–2017)** and provides detailed information on bookings, cancellations, customer demographics, revenue, and guest preferences.

---

## 📌 Project Objectives
- Perform **Exploratory Data Analysis (EDA)** to uncover insights.  
- Compare business trends between **City Hotel** and **Resort Hotel**.  
- Identify **factors impacting cancellations and revenue**.  
- Suggest **business strategies** for improving bookings, revenue, and guest satisfaction.

---

## 📂 Dataset Overview
- **Total Rows:** 119,389  
- **Total Columns:** 32  

### Key Features:
- `hotel`: Type of hotel (City or Resort)  
- `is_canceled`: Whether the booking was canceled (1) or not (0)  
- `lead_time`: Days before actual arrival  
- `arrival_date_year`, `arrival_date_month`, `arrival_date_week_number`  
- `stays_in_weekend_nights`, `stays_in_week_nights`  
- `adults`, `children`, `babies`  
- `meal`: Type of meal booked  
- `country`: Country of the guest  
- `market_segment`, `distribution_channel`  
- `is_repeated_guest`  
- `previous_cancellations`, `previous_bookings_not_canceled`  
- `reserved_room_type`, `assigned_room_type`  
- `booking_changes`  
- `deposit_type`  
- `agent`, `company`  
- `days_in_waiting_list`  
- `customer_type`  
- `adr`: Average Daily Rate  
- `required_car_parking_spaces`  
- `total_of_special_requests`  
- `reservation_status`, `reservation_status_date`

---

## 🔍 Steps Performed
1. **Data Cleaning**  
   - Handling missing values.  
   - Removing duplicates.  

2. **Data Wrangling**  
   - Transforming variables into meaningful formats.  
   - Creating new features for analysis.  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of bookings across years.  
   - Cancellation analysis.  
   - Customer demographics and preferences.  
   - Revenue comparison between hotels.  
   - Seasonal booking patterns.  

4. **Visualization**  
   - Used **Matplotlib & Seaborn** for plots.  
   - Comparative charts for **City Hotel vs Resort Hotel**.  

---

## 📊 Key Insights

- **Hotel Preference**
  - 61.07% preferred **City Hotel**, 38.93% preferred **Resort Hotel**.

- **Revenue**
  - City Hotels generated **higher ADR (Average Daily Rate)** → More revenue than Resort Hotels.

- **Parking**
  - 91.6% guests did **not require parking**; only 8.3% needed 1 parking space.

- **Cancellations**
  - Over **27% bookings were canceled**.

- **Seasonality**
  - Peak bookings in **July & August** → likely due to summer vacations.

- **Agents**
  - Agent **ID 9 and 240** made the highest bookings.  
  - Agents **1 and 6** made the least bookings.

- **Customer Origin**
  - Most bookings from **Portugal, UK, France, and Spain**.

- **Booking Channels**
  - **Online TA** and **Offline TA/TO** were the main booking sources.

- **Room Types**
  - Room **Type A and D** were most booked.

- **Guest Loyalty**
  - Very few repeated guests → scope for loyalty programs.

- **Stay Duration**
  - Average stay length ≈ **7 days** for both hotel types.

- **Meal Preference**
  - **Bed & Breakfast (BB)** was the most popular choice.

- **Correlation**
  - `arrival_date_year` vs `arrival_date_week_number`: **-0.51 (negative correlation)**  
  - `stays_in_week_nights` vs `total_stay`: **0.95 (strong positive correlation)**  
  - `adr` increases with **total number of people**.

---

## 💡 Business Recommendations
- **City Hotel is leading** in revenue; Resort Hotel needs new marketing strategies.  
- Diversify **meal plans beyond BB** to improve guest satisfaction.  
- Increase **international marketing** beyond Portugal for more global guests.  
- Focus on **cancellation reduction strategies** (e.g., flexible policies, discounts).  
- Invest in **facilities other than parking**, since demand for parking is low.  
- Encourage **longer stays**, as revenue increases with duration.  
- Introduce **loyalty programs** to increase repeat customers.

---

## 📸 Visualizations
Includes plots such as:
- Hotel type vs booking count  
- Monthly booking trends  
- Cancellation rates  
- ADR comparison  
- Country-wise booking heatmap  
- Meal preferences  
- Agent contribution  

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook** (for EDA & Visualization)  

---

## 📌 Conclusion
- **City Hotel** dominates in revenue and bookings.  
- **Resort Hotel** needs targeted marketing & strategic improvements.  
- Strong potential exists to **reduce cancellations** and **increase loyalty**.  
- With the right strategies, ADR and overall business performance can grow significantly.  



