### **SKYPATH – Airline Analytics Dashboard**  
A professional Power BI dashboard providing an end-to-end analysis of flight operations, airport performance, and delay patterns across the U.S. aviation network.

---

## **Short Description**  
This dashboard enables airline managers and analysts to monitor key flight metrics such as total flights, punctuality, delays, and cancellations.  
It provides a high-level overview of operations, identifies performance bottlenecks, and highlights the major causes of delays to support data-driven operational decisions.

---

##  **Tech Stack**  
- **Power BI** – Data modeling, visualization, and dashboard creation  
- **DAX** – Custom measures for KPIs and calculated insights  

---

## **Data Source**  
The dataset was sourced from the **U.S. Department of Transportation (DOT) 2015 flight performance data**, containing flight-level details such as origin, destination, airline, delay times, and cancellation reasons.  
It was cleaned and modeled in Power BI using Power Query for transformation and a star schema for optimization.

---

## **Features and Highlights**

### **The Business Problem**  
Airline operations involve large volumes of flight data, making it challenging to quickly identify performance trends, delay causes, and airport efficiency.  
Decision-makers need a centralized and intuitive view to monitor performance and improve reliability.

---

### **The Goal of the Dashboard**  
To design an interactive and executive-friendly analytics solution that provides:  
- A comprehensive **overview of flight performance**  
- **Airport-level operational insights**  
- **Detailed delay and cancellation analysis** to pinpoint root causes

---

### **Key Visuals**

#### **1. Overview Dashboard**  
- **KPI Cards:** Display Total Flights, % On-Time, % Cancelled, and Avg Delay for a quick performance summary.  
- **Line Chart:** Monthly trend showing total flights and on-time percentage.  
- **Combo Chart:** Visualizes the relationship between on-time and cancellation rates.  
- **Bar Chart:** Highlights top airlines by flight volume.  
- **Donut Chart:** Summarizes flight status distribution (On-Time, Delayed, Cancelled).  
- **Matrix Table:** Compares top routes by delay percentage and reliability.  

#### **2. Airport Performance Dashboard**  
- **Map Visual:** Top 5 airports by on-time performance (bubble size = total flights).  
- **Bar Chart:** Displays average delay per airport.  
- **Area Chart:** Shows cancellation trends by airport.  
- **Matrix Table:** Summarizes airport-level reliability and performance metrics.  
- **KPIs:** Highlight busiest airport, average delay, and overall on-time rate.  

#### **3. Delay & Cancellation Analysis Dashboard**  
- **KPI Cards:** Show delayed and cancelled flight percentages, and average delay minutes.  
- **Donut Chart:** Displays cancellation reasons (Carrier, Weather, NAS, Security).  
- **Line Chart:** Monthly delay and cancellation trends.  
- **Bar Charts:** Show delay percentage by city and day of week.  
- **Scatter Plot:** Relationship between flight distance and average delay.  

---

### **Business Impact and Insights**
- **LAX** emerged as the busiest and most reliable airport by flight volume.  
- **57%** of flights arrived on time, with delays peaking in **June–August** due to summer congestion.  
- **Carrier-related issues** caused the majority of delays, overshadowing weather or air traffic factors.  
- **Fridays** recorded the highest cancellation rates, likely driven by weekend travel surges.  
- **Distance showed minimal impact on delay times**, implying operational or scheduling inefficiencies were the main contributors.  

---

## **Screenshot**  
(Add your dashboard images here)  
You can upload screenshots to your GitHub repository and paste their links here:  
- [Dashboard 1 – Overview](https://github.com/shandilyaswagat/SKYPATH---Airline-Analytics-Dashboard/blob/main/Overall_Dashboard.heic)  
- [Dashboard 2 – Airport Performance](https://github.com/shandilyaswagat/SKYPATH---Airline-Analytics-Dashboard/blob/main/Airport_analysis.heic)  
- [Dashboard 3 – Delay & Cancellation Analysis](https://github.com/shandilyaswagat/SKYPATH---Airline-Analytics-Dashboard/blob/main/Delay_Analysis.heic)  


