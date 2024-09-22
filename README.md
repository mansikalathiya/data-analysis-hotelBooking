# Hotel Booking Analysis
### 📊 Project Overview
This project demonstrates my ability to analyze and visualize data trends using Python, focusing on Average Daily Rate (ADR) in hotel reservations. The analysis compares ADR between cancelled and non-cancelled bookings over a specified period (2016 to September 2017), showcasing insights into pricing behavior for different booking outcomes.

**Skills Demonstrated:**

- Data Cleaning & Transformation
- Data Visualization with Python
- Analytical Thinking
- Trend Analysis

  
### 🧩 Key Project Objectives

**1) Data Filtering & Preparation:**  
Filtering the dataset to include relevant reservation records between 2016 and 2017.

**2) Trend Analysis:**  
Comparing ADR trends for cancelled and non-cancelled reservations to identify pricing patterns.

**3) Data Visualization:**  
Creating informative visualizations to communicate data trends clearly and effectively to stakeholders.

### 🚀 Tools & Technologies

**Programming Language**: Python  
**Data Analysis**: pandas  
**Data Visualization**: matplotlib, seaborn  
**Jupyter Notebook**: For an interactive data analysis environment

## 📈 **Analysis & Results**

### 1. **Data Filtering**
The dataset was carefully filtered to include only relevant booking data from 2016 to September 2017, focusing separately on cancelled and non-cancelled reservations. This step ensured that our analysis would be timely and accurate.

```python
cancelled_df_adr = cancelled_df_adr[
    (cancelled_df_adr['reservation_status_date'] > '2016') &
    (cancelled_df_adr['reservation_status_date'] < '2017-09')
]

not_cancelled_df_adr = not_cancelled_df_adr[
    (not_cancelled_df_adr['reservation_status_date'] > '2016') &
    (not_cancelled_df_adr['reservation_status_date'] < '2017-09')
]
```
### 2. **Trend Analysis**
To understand how ADR changes over time, we plotted line charts comparing ADR for both cancelled and non-cancelled bookings. This analysis provides insights into potential differences in pricing strategies and can be useful for identifying trends that might impact future decision-making.

![Screenshot 2024-09-22 123002](https://github.com/user-attachments/assets/0204dec6-0bcb-4bba-9005-54214d43a915)

## 3. Visualization Output

The plots show how the Average Daily Rate (ADR) fluctuates for canceled vs. non-canceled reservations over time. Understanding these fluctuations provides businesses with valuable insights into how pricing decisions affect cancellations and overall revenue.

### Graphs
You can find the visualizations in the `images` folder:

## Key Visualizations and Insights

### 1. Overall Reservation Status
[View Image](images/Overall_Reservation_Status.png)

### 2. Reservation Status by Hotel Type
[View Image](images/Reservation_Status_by_Hotel_Type.png)

### 3. Monthly Reservation Trends
[View Image](images/Monthly_Reservation_Trends.png)

### 4. Average Daily Rate (ADR) per Month
[View Image](images/ADR_per_Month.png)

### 5. Cancellation Rates by Country (Top 10)
[View Image](images/Cancellation$20rate%20in%20countries.png)

Feel free to explore the images for detailed visual insights!


## 🌟 Project Impact & Skills Highlighted

This project showcases:

- **Handle Real-World Data Sets:** Expertise in cleaning, filtering, and extracting insights from complex data.
- **Visualize Complex Trends:** Present data trends in a clear and visually compelling manner.
- **Provide Actionable Insights:** Analyze data to inform pricing strategies and guide business decisions.
