# Introduction
As part of the SabiCAMP **2025** Data Analytics track, I undertook a simulated project analyzing SwiftMart, a fast-growing online retailer. 
The company had been collecting large volumes of sales, customer, and website traffic data, but struggled to extract actionable insights. My role was to act as the lead Data Analyst, responsible for cleaning, modeling, and visualizing the data to uncover trends and provide recommendations. 
This project allowed me to apply end-to-end analytics skills — from data preparation to dashboard design — using Power BI as the primary tool.

# Business Challenge
SwiftMart was data-rich but insight-poor. Management lacked clarity on key performance drivers and needed answers to critical questions:

- Which products and regions generate the most revenue?

- Who are repeat customers and how do they behave?

- Which marketing channels convert best, and where are sales being lost?

- How can operational inefficiencies be identified and addressed?

The challenge was to transform raw, fragmented data into structured insights that could guide executive decision-making and improve overall business performance.

# Data Overview & Preparation
**Datasets Used:**

- **Sales & Transactions:** Revenue, quantity, product, date, region

- **Customers:** Customer ID, gender, purchase frequency, status

- **Website Analytics:** Traffic sources, devices, conversion, bounce, abandonment

- **Product Images:** Pinterest URLs for product visualization

# Preparation Steps:

- Removed duplicates and standardized formats

- Validated data types and segmented numerical values

- Created calculated columns (e.g., discount %, MoM growth, YoY variance)

- Built a clean, structured dataset ready for modeling and visualization

# Data Modeling & DAX Measures
I designed a star schema with a central Fact Table (Sales & Transactions) and supporting Dimension Tables (Customers, Website, Date, Product Images). 
Relationships enabled seamless filtering and cross-analysis across dashboards.

## Key DAX Measures:

- **Anchor Metrics:** Total Revenue, Quantity Sold, Avg Order Value, Conversion Rate

- **Time Intelligence:** Month-over-Month Growth, YTD vs PYTD Revenue

- **Variance Measures:** Revenue YoY %, Customer Growth MoM %, Units Sold MoM %

# Dashboard Design & Insights

**Sales Performance:**

- **Total Revenue:** **$221.6M** | Avg Order Value: **$221.6K**

- **Top Locations:** Kano ($52M), Abuja **($47M)**, Enugu **($42M)**

- **Top Products:** Gaming Console ($57M), Laptop **($50M)**, Camera **($41M)**

- **Revenue YoY decline:** **-69%** → signals over-reliance on a few high-performing regions and products

**[View My Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmYxNTZmNjItYTEyZi00NWQyLTg4NjAtNjE1YzI0M2VhMjRhIiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)**

**Customer Insights:**

- **Total Customers:** **1,000** | Active Customers: **286**

- Repeat purchases concentrated among top customers (e.g., C293)

- Gender distribution includes the “Others” category for inclusivity

- **Growth months:** July and November showed spikes in new customer acquisition

**Website Insights:**

- **Conversion Rate:** **41.1%** | Abandonment Rate: **49.9%** | Bounce Rate: **11.6%**

- Referral and Google Ads are the most effective traffic sources

- Desktop and mobile usage are evenly split

- High drop-off during checkout suggests friction in the final purchase stage

# Recommendations
As a Data Analyst, I would recommend that SwiftMart prioritize Kano and Abuja for regional campaigns, as they consistently generate high revenue. I would suggest bundling top-performing products, such as gaming consoles, with accessories to increase average order value and encourage upselling. Given the sharp YoY revenue decline, I would advise management to investigate pricing strategies, promotional timing, and product fatigue in key categories.

For **customer engagement**, I would recommend launching loyalty programs targeting repeat buyers and designing personalized offers based on purchase history. I suggest reactivating inactive customers through targeted email campaigns, especially during high-growth months like **July and November**.

On the **website front**, I would recommend optimizing the checkout experience to reduce abandonment and tailoring landing pages for mobile and desktop users. Since referral and Google Ads drive strong conversions, I would advise doubling down on those channels while testing new ones for diversification.

# Conclusion
This project was a rewarding opportunity to apply my data analytics skills in a real-world business context. From cleaning and modeling the data to building interactive dashboards and generating insights, I was able to uncover patterns that matter, revenue concentration, customer loyalty, and digital engagement gaps. The experience reinforced the importance of structured analysis and storytelling in driving business decisions. I am proud of the work I completed and confident that these insights can help SwiftMart or any e-commerce brand grow smarter and faster through data-driven strategies.
