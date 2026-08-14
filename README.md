#  Power BI Housing Market & Real Estate Analytics Dashboard

##  Overview
This repository contains a comprehensive 3-page **Power BI Housing Market Analysis Dashboard** designed to track regional real estate performance, analyze sales velocity, evaluate property type pricing metrics, and uncover key drivers affecting purchase prices vs. offer prices.

---

##  Dashboard Pages & Visualizations

###  Page 1: House Market Overview
<img width="1916" height="881" alt="image" src="https://github.com/user-attachments/assets/e82e1b22-dc31-4937-9722-ad4447bcbc88" />

* **Median Sales Price Change by Region:** Tracks percentage changes in property values across major regions (*Jutland, Zealand, Fyn & Islands, Bornholm*).
* **KPI Metrics:** High-level overview showing total units sold (e.g., **77 units**) and overall 12-month sales volume (**13bn**).
* **Offer Price vs. Purchase Price:** Scatter plot evaluating valuation accuracy and price negotiation margins across listings.
* **YOY Sales Growth by Sales Type:** Area chart tracking YoY performance across transactions (*Auctions, Regular Sales, Family Sales, Other Sales*).

---

###  Page 2: Sales Performance
<img width="1919" height="886" alt="image" src="https://github.com/user-attachments/assets/51646cac-47fe-4f7b-a169-ff4372bba3e7" />


* **Sales Volume by Region:** Funnel visual highlighting regional sales revenue distributions (led by *Zealand* at **95bn** and *Jutland* at **81bn**).
* **Key Influencers & Segments:** AI-driven analysis uncovering key drivers behind low or high purchase prices.
* **Offer to SQM Ratio by Sales Type:** Bar chart comparing price-per-square-meter metrics across transaction categories.
* **Average Price / SQM by Region:** Donut chart breaking down relative property cost densities per region.
* **Detailed Sales Matrix:** Granular tabular view displaying YoY sales totals and purchase volume aggregated by year, quarter, month, and day.

---

###  Page 3: House Type Analysis
<img width="1919" height="876" alt="image" src="https://github.com/user-attachments/assets/71fc93bf-4034-4d33-bb43-37a110c6d0aa" />


* **Dynamic Slicers:** Interactive filtering by *Area, City, Sales Type,* and *Region*.
* **Avg Offer/Purchase Price by House Type:** Comparative bar chart assessing list price vs. final price across property formats (*Farms, Apartments, Townhouses, Villas, Summerhouses*).
* **Macroeconomic Factors:** Evaluates inflation rates, interest rates, and rental yields across property segments.
* **SQM vs. Price per SQM:** Combined bar and line chart comparing physical property size against unit pricing trends.

---

##  Tools & Technologies Used
* **Business Intelligence:** Power BI Desktop
* **Data Modeling & DAX:** Custom measures for YoY calculations, pricing ratios, and regional aggregations
* **Data Transformation:** Power Query ETL pipeline
* **Analytics Features:** Key Influencers visual, Scatter Plots, and Cross-Filtering

---

##  Repository Structure
```text
├── Housing Data.pbix            
├── Data/                        
└── README.md                    
