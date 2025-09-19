# 🚚 FreshFables – Delayed Delivery Analysis

## 📝 Project Overview  
This project analyzes **operational bottlenecks in FreshFables' delivery system**, using order-level data from dark stores.  
The focus is on understanding **where delays occur** (processing, packaging, driver assignment, or delivery) and providing **actionable insights** to reduce late deliveries.

---

## 📂 Dataset Details  

- **Total Records:** 800 orders  
- **Dark Stores Covered:** Vaishali Nagar, Malviya Nagar, and others  
- **Columns (27):**
  - **Order Information** → OrderID, DarkStore, Total Revenue, Weekday/Weekend, Meal Time  
  - **Operational Timings** → Processing, Packaging, Assign, Delivery Times  
  - **Performance vs SLA** → Variance% for Assign & Delivery Times  
  - **Labels** → On Time/Delayed status for each stage  
  - **Remarks & Root Cause** → Overall remark + Major Issue (Delivery/Assign/Processing)  

---

## ⚙️ Key Analysis Performed  

1. **Overall Delay Rate**  
   - ~22–23% of orders were delayed.  

2. **Weekday vs Weekend**  
   - Weekend orders show slightly higher delays.  

3. **Peak-Time vs Non-Peak**  
   - Peak-time deliveries have the highest risk of being delayed.  

4. **Process Bottlenecks**  
   - **Delivery Time** is the major issue, flagged as *Immediate Attention* in most delayed cases.  
   - Secondary contributors: Driver Assignment delays.  

5. **Store-Level Performance**  
   - Variance observed across different dark stores, indicating store-level operational inefficiencies.  

---

## 📈 Insights  

- **Delivery Time is the #1 bottleneck** across all stores.  
- **Driver Assignment delays** strongly correlate with final delivery delays.  
- **Peak hours (Evening/Night)** show a higher delay ratio compared to mornings.  
- **Dark Store variation** suggests targeted interventions (training, staffing, route optimization).  

---

## 🚀 Tools & Skills Demonstrated  

- **Excel / Tableau** → KPI design, dashboarding, variance-to-standard analysis.  
- **Data Analytics** → Delay classification, variance breakdown, root-cause analysis.  
- **Business Insights** → Identified bottlenecks, quantified risks, and proposed operational improvements.  

---

## 🔗 Dashboard Access  

You can explore the interactive dashboard here:  
[[View Dashboard]](https://lookerstudio.google.com/u/0/reporting/e94315db-5f74-4944-a300-9dcfedd48d65/page/wA2SF)

## 📸 Dashboard Preview 

![Overview Dashboard](https://github.com/ritom0/Operation-Process-Analysis-Dashboard/blob/main/Order%20Analysis.png)


![Overview Dashboard](https://github.com/ritom0/Operation-Process-Analysis-Dashboard/blob/main/Delayed%20Delivery%20Analysis.png)

![Overview Dashboard](https://github.com/ritom0/Operation-Process-Analysis-Dashboard/blob/main/Opreation%20Process%20Analysis.png)



