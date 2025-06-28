# E-COMMERCE-SALES-DASHBOARD

### Title : Anuj Store Insights: E‑Commerce Sales Dashboard.<br>

An interactive Power BI dashboard designed to explore Anuj Store’s online sales performance—focusing on revenue distribution, customer behavior, product categories, payment trends, and regional dynamics.

### Description / Purpose

The Anuj Store Insights Dashboard is a visually engaging Power BI report built to help managers and decision-makers monitor key e-commerce metrics such as sales, profit, order volume, and average order value. It enables rapid identification of trends, high-value customers, and areas for strategic improvement to elevate overall performance.

### 	Tech Stack
List the key technologies used to build the dashboard.

Example:
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

###	Data Source

More info on where the data comes from and how it’s structured
Example:

Orders: Order ID, order date, total amount, quantity, profit, customer ID, product sub-category, payment mode, and state.<br>
Products: Category, sub-category, unit price, cost.<br>
Customers: Customer name, location, and segment.<br>
Payment Mode: Payment method for each order (COD, UPI, Debit Card, Credit Card, EMI).<br>
Traffic/Marketing (optional): Sessions, conversion events, marketing channel if available.<br>
All data is imported via CSV/SQL/API, cleansed in Power Query, and modeled with a Calendar (Date) table to support time-based analysis.<br>

###  Features / Highlights

• Business Problem<br>
Anuj Store lacked a centralized analytics tool to monitor sales trends, customer segments, state-level distribution, payment behavior, and product-level profitability—relying heavily on manual spreadsheets.<br>
• Goal of the Dashboard<br>
To deliver an intuitive, interactive platform enabling stakeholders to quickly assess sales health, identify opportunities in geography or product strategy, and optimize customer and payment experiences.<br>
• Walkthrough of Key Visuals<br>
  • Top KPIs (cards) – Display key metrics:<br>
    • Total Sales: 438K<br>
    • Quantity Sold: 5,615<br>
    • Profit: 37K<br>
    • Average Order Value (AOV): 121K<br>
• Profit by Month (column chart, top-right) – Visualizes monthly profit and loss, highlighting dips in May and July and a peak in December.<br>
• Sum of Amount by State (bar chart, mid-left) – Shows topline sales by state: Maharashtra (~0.1M), followed by Madhya Pradesh, Uttar Pradesh, and Delhi. A State slicer allows filtering.<br>
• Quantity by Category (donut chart, mid-center) – Presents product volume breakdown: Clothing 63%, Electronics 21%, Furniture 17%.<br>
• Amount by Customer (bar chart, bottom-left) – Highlights top customers: Harivansh, Madhav, Madan Mohan, and Shiva.<br>
• Quantity by Payment Mode (donut chart, bottom-center) – Reflects payment preference: COD 44%, UPI 21%, Debit Card 13%, Credit Card 12%, EMI 10%.<br>
• Profit by Sub‑Category (horizontal bar chart, bottom-right) – Ranks sub-categories by profit contribution: Printers, Bookcases, Saree, Accessories, Tables.<br>

• Business Impact & Insights<br>
• Targeted Marketing: Pinpoint high–selling states and customers for personalized campaigns.<br>
• Digital Payment Strategy: COD dominance suggests growth potential through digital payment incentives.<br>
• Product Mix Optimization: Emphasize high-profit sub-categories like Printers and Bookcases.<br>
• Seasonal Strategy: Understand low-profit months (May, July) and prepare promotional efforts accordingly.<br>

### 	Screenshots / Demos

Show what the dashboard looks like. - ![Alt text](https://github.com/anujpal2310/E-COMMERCE-SALES-DASHBOARD/blob/main/Anuj_E-commerce_sales.png)
