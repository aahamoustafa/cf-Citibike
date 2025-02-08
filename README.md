# **Analyzing Citibike Usage Trends in NYC**

## **📌 Overview**
This case study explores the **usage trends of Citibike in New York City**, using a **data-driven approach** to identify patterns in user behavior, peak demand, and trip characteristics. The study leverages **historical Citibike trip data** (2013-2017) to generate **insights that can optimize Citibike’s operations and improve customer experience.**


## **📊 Data Collection & Processing**
- **Source:** Citibike trip data from **Kaggle**.
- **Time Range:** 2013 - 2017.
- **Size:** Sampled dataset with **470,000 rows** (~0.01% of original data).
- **Data Cleaning:**
  - Removed null values and inconsistencies in date-time fields.
  - Standardized station names and user type classification.
  - Converted trip duration into minutes for better analysis.

**Key Variables Used:**
- `Trip Duration` (minutes)
- `Start Time`, `Start Station`, `End Station`
- `User Type` (Subscriber vs. Casual Rider)
- `Start Hour`, `Weekday`



## **🔍 Research Questions**
This study aims to answer the following questions:
1️⃣ **Where do most Citibike trips start and end?**
2️⃣ **How do Subscribers and Casual Users differ in riding behavior?**
3️⃣ **What are the peak hours of Citibike usage?**
4️⃣ **How do weekday and weekend usage patterns compare?**
5️⃣ **What are the most heavily used stations?**
6️⃣ **How can Citibike optimize bike availability and station balancing?**



## **📊 Key Insights from the Analysis**
### **1️⃣ Citibike is primarily used for commuting** 🚲
- **Peak usage occurs at 8 AM and 5-7 PM**, aligning with work commute hours.
- **Subscribers take shorter trips (~12 min),** indicating daily use for short-distance travel.
- **Casual riders take longer trips (~25 min),** suggesting recreational/tourist use.

### **2️⃣ Most trips originate from Midtown & Downtown Manhattan** 🗺️
- High-frequency stations include **E 17 St & Broadway, Pershing Square, and 8 Ave & W 31 St**.
- This aligns with **major business districts and transit hubs**.

### **3️⃣ Weekday vs. Weekend Behavior Differs** 📆
- **Weekday trips peak between Tuesday-Thursday**, reinforcing commuter behavior.
- **Weekend trips are fewer,** indicating more casual/tourist riders.

### **4️⃣ Subscribers and Casual Users Prefer Similar Stations** 🏙️
- Both user types heavily use **Central Park, Downtown Manhattan, and Waterfront areas**.
- **This suggests that Citibike is used both for commuting and leisure.**

Check out the Tableau Dashboard: [Citibike Story](https://public.tableau.com/app/profile/abdelrahman.moustafa7565/viz/CitiBikeWorkbook_17390447645370/Story1)

## **📢 Recommendations for Citibike**
📌 **1. Optimize bike availability during peak commuting hours.**
   - Ensure **high bike supply** between **7-9 AM and 5-7 PM**.

📌 **2. Expand station coverage in high-demand areas.**
   - Increase docking stations in **Midtown & Downtown Manhattan**.

📌 **3. Implement dynamic pricing strategies.**
   - Offer **discounts for weekend rides** to encourage casual users.
   - Increase **subscription incentives** to retain regular commuters.

📌 **4. Improve bike redistribution logistics.**
   - Use real-time demand prediction to **relocate bikes more efficiently**.

📌 **5. Launch targeted marketing for different user types.**
   - Promote **membership benefits** to frequent users.
   - Advertise **tourist-friendly routes & pricing** to casual riders.


## **⚠️ Limitations & Future Considerations**
📌 **1. Weather Impact Not Considered** 🌦️
- Citibike usage is **likely affected by weather conditions**, but this analysis does not include weather data.

📌 **2. Traffic Congestion Not Integrated** 🚦
- The study does not assess **how Citibike usage fluctuates with subway delays or road congestion**.

📌 **3. Sampled Data May Exclude Certain Trends** 📊
- The dataset represents only **0.01% of total trips**, meaning **some granular trends may not be captured**.

📌 **4. No Seasonal Analysis** 🍂❄️☀️
- This study does not differentiate usage trends across **summer, winter, or major city events**.

### **🔍 Next Steps for Deeper Insights**
✅ **Incorporate weather and traffic data** to assess external impacts.  
✅ **Use machine learning** to predict future demand and station-level bike shortages.  
✅ **Analyze pricing models** to optimize revenue and improve accessibility.  
✅ **Compare different city bike-sharing programs** for competitive benchmarking.  



## **🎯 Conclusion**
This **case study provides actionable insights** to optimize **Citibike operations, improve user experience, and enhance resource allocation.** 

By **adjusting pricing, expanding stations, and redistributing bikes efficiently**, Citibike can **better serve both daily commuters and casual riders**, ultimately **increasing ridership and revenue**. 







