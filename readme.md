# 🍽️ **Swiggy Delivery Performance Analytics**

Food delivery platforms generate massive data every second — from customer orders to delivery times, traffic, weather, and profitability.
This project analyzes Swiggy’s delivery performance to uncover insights into **operations efficiency, customer behavior, profitability, and real-world business patterns**.
Using **Python, Excel, and interactive dashboards**, this project simulates analysis typically done inside food delivery companies.

---

## ❗ **Problem Statement**

Food-delivery businesses often struggle to understand the hidden factors behind delivery delays, profit loss, high cancellations, and fluctuating customer behavior.
Without proper analytics, identifying patterns related to distance, traffic, weather, and discounts becomes difficult.

This project solves that gap through structured analysis, modeling, and dashboarding to highlight the most important operational and financial insights.

---

# 📊 **Swiggy Analytics Dashboard**

### **Executive Overview**

<img width="1301" height="728" alt="Executive Overview" src="https://github.com/user-attachments/assets/7726f02a-fbb9-4be2-916e-cb0f29e9b452" />

### **Delivery Operations Efficiency**

<img width="1302" height="727" alt="Delivery Operations" src="https://github.com/user-attachments/assets/cf88deb0-51d4-4eaa-b37f-f7cb7ff7e57f" />

### **Customer Analytics & behaviour**

<img width="1300" height="727" alt="Customer Analytics" src="https://github.com/user-attachments/assets/56b1a146-9e0b-445f-8f41-b84ae3f9e26e" />

### **Profitability & Finance**

<img width="1297" height="728" alt="Profitability   Finance" src="https://github.com/user-attachments/assets/6a47d90d-7487-484a-9657-de25f43ea85a" />

---

## 📊 **Dashboard Development Data**

| Page    | Title                              | What It Shows                                                                                                                                                    |
| ------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1️⃣** | **Executive Insights**             | • Total orders, delivered %, cancellation rate <br> • Revenue & average delivery time <br> • Demand trends and top-performing cities                             |
| **2️⃣** | **Delivery Operations Efficiency** | • Traffic, weather, vehicle type & distance impact <br> • Delay reasons analysis <br> • Delivery time vs distance patterns                                       |
| **3️⃣** | **Customer Analytics**             | • Customer age groups & spending behavior <br> • Cuisine preferences <br> • Payment method trends <br> • City-wise customer behavior                             |
| **4️⃣** | **Profitability & Finance**        | • Revenue vs cost vs profit <br> • Discount impact & margin analysis <br> • Loss-making order identification <br> • Profit segmentation across cuisines & cities |

---

## 🧩 **Project Workflow**

| Step                             | Task                         | Key Actions                                                                             |
| -------------------------------- | ---------------------------- | --------------------------------------------------------------------------------------- |
| **1️⃣ Data Collection**          | Import raw food delivery CSV | 45K+ Swiggy/Zomato-like records                                                         |
| **2️⃣ Data Enrichment (Python)** | Add calculated features      | Delivery distance, cost, profit, discount %, final amount, customer age, cuisine, flags |
| **3️⃣ Data Cleaning (Excel)**    | Validation & correction      | Missing values, outliers, formatting, consistency                                       |
| **4️⃣ Data Modeling (BI)**       | Relationship building & DAX  | KPI measures, calculated columns, field grouping                                        |
| **5️⃣ Dashboard Development**    | 3-page report                | Executive Insights, Delivery Operations, Profitability & Finance                        |

---

## 📈 **Key Insights**

| Insight                                                     | Explanation                                                                                                                                                         |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🚦 High traffic increases delivery time by ~25%**         | During peak hours and high-traffic zones, delivery riders take longer routes or face slowdowns, increasing total delivery time and reducing operational efficiency. |
| **💸 Discounts above 20% sharply reduce profit margins**    | Heavy discounts directly cut into revenue, and after platform fees + delivery costs, orders often generate little to no profit when discount % exceeds 20%.         |
| **🍽️ Snacks & Biryani are the most profitable categories** | These cuisines have high order frequency, low preparation time, and healthy margins—making them top contributors to overall profitability.                          |
| **📍 Long-distance orders (> 6 km) often result in losses** | Higher fuel costs, longer delivery time, and increased rider payout make long-distance orders less profitable or even loss-making.                                  |
| **🌆 Evening hours show the highest order volume**          | Customer ordering peaks between 7 PM–10 PM due to dinner demand, leading to increased order density and higher revenue during these hours.                          |

---

## 🛠️ **Tech Stack Used**

| Tool                              | Purpose                                                 |
| --------------------------------- | ------------------------------------------------------- |
| **Python (Pandas, NumPy)**        | Data enrichment, calculations, preprocessing            |
| **Excel**                         | Data cleaning, consistency checks                       |
| **Power BI (DAX + Dashboarding)** | Building visuals, KPIs, calculations, and relationships |
| **GitHub**                        | Documentation & version control                         |

---

# 🧠 **Conclusion / Benefits**

This project delivers a complete analytical view of Swiggy’s delivery ecosystem, helping different teams make smarter decisions:

### 💡 **For Business Strategy**

* Identify profitable vs loss-making order segments
* Understand discount thresholds affecting margin

### 🚴 **For Delivery Operations**

* Detect patterns causing delays: traffic, weather, distance
* Optimize delivery time and fleet planning

### 🧾 **For Finance Teams**

* Evaluate profit vs cost across cuisines, cities, and order types
* Spot financial leaks caused by distance or heavy discounts

### 📊 **For Data Teams**

* Learn an end-to-end analytics workflow from raw data → cleaning → analysis → dashboard
* Demonstrate practical use of Python, Excel, and BI tools

Overall, this project provides clear operational, financial, and strategic insights that can improve delivery performance, profitability, and customer satisfaction in real food-delivery businesses.
