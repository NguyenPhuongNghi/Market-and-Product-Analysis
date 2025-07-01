# Market and Product Analysis
Use Power BI to analyze the business performances of different markets and products to expand markets and choose product strategies
## :one: Project Overview:
**:round_pushpin: The purposes of this project are:**
- Analyse the business performances of each product categories/market/customer segment over 4-year-Period
- Suggest market expansion strategies and decide strategic products 
## :two: Dataset Description:
- **Company:** Globalstore (fictional)
- **Time period:** from 2011 to 2024
- **Dataset:**<br>
**🔻Descriptive Data:**
+ Market: Market, Region, Country, State, City
+ Product: Category, Sub-Category, Product Name
+ Customer: Customer Name, CustomerID
+ Delivery: Ship mode, Returned
+ Sales workforce: Person, Region<br>
**🔻Measures:**
+ Sales
+ Quantity
+ Profit
- **North-star metrics:** Sales and Profit Margin
## :three: Tools used:
- Power BI (Power Query, DAX measures, Visuals)
## :four: Dashboard Structure:
- Overview <br>
- Master Analysis (Category/Market/Segment) <br>
- Detailed View <br>
- Key Drivers Analysis (Product Mix Impact Analysis) <br>
- Conclusion <br>
- Insights <br>
## :five: Dashboard: [attached file](https://github.com/NguyenPhuongNghi/Market-and-Product-Analysis/blob/main/Global%20Superstore%20-%20Market%20Expansion%20and%20Product%20Strategy.pbix)
### :one: Overview: <br>
![alt](https://github.com/NguyenPhuongNghi/Market-and-Product-Analysis/blob/main/photo/Screenshot%202025-07-01%20140308.png?raw=true)
📍 **By time:**
- Sales: Consistent growth from 2011 to 2014 with seasonal fluctuations. Peaks appeared seasonally (possibly Q4), indicating cyclical profit patterns.
- Profit Margin: Fluctuated but remained between 10%–13% over the 4-year period. Profit margin is not as stable as sales, indicating potential cost management or pricing strategy issues.

📍 **By market:**
- Top 3 markets by sales: APAC (3.6M), EU (2.9M), US (2.3M).
- Lowest sales: Canada (0.1M), Africa (0.8M).
- Profit Margin: was the highest in Canada (~30%), even with low sales volume → indicates niche profitability and suggests investing more if scalable. It varied around 10%-13% in other markets (APAC, EU, US, LATAM) and was the lowest in EMEA (5.4%)


📍 **By Category:**
- Sales: Technology leads with 4.7M, followed by Furniture (4.1M) and Office Supplies (3.8M).
- Profit Margin: it is the highest in Technology, followed by Office Supplies (13.7%) and Furniture (6.9%)


📍 **By Segment:**
- Sales: Consumer segment dominates (6.5M), followed by Corporate (3.8M), and Home Office (2.3M). This indicates successful mass-market penetration.
- Profit Margin: relatively equal in 3 segments, around 11%-12%
  
### :two: Master Analysis <br>
![alt](https://github.com/NguyenPhuongNghi/Market-and-Product-Analysis/blob/main/photo/Screenshot%202025-07-01%20140433.png?raw=true)
### 📍By Category/Sub-Category:
#### 📌 Sales:
- All categories showed steady growth.
- Technology pulled ahead clearly since 2013, followed by Office Supplies and Furniture.
- Peaks appeared seasonally in Q4.

#### 📌 Profit Margin:
- Technology and Office Supplies took turns to lead margin, varying between 10%-15%
- Furniture showed volatile and lower margin historically, fluctuating between 3%-10%

#### 📌 Return Rate:
- Furniture and Technology had considerably high return rates, at 5.9% and 5.8% respectively, which may imply customer dissatisfaction or fulfillment issues.

#### 📌  Sub-Category Performance:
- **Average profit margin: 11.6%**

✅ High sales and high profit margin (Top-performing):

| Sub-Category         | Sales | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| Phones   | 1.70M | 12.7%   |
| Copiers   | 1.50M | 17.1% |
| Appliances    | 1.00M   | 14.0%|
| Accessories  | 0.75M   | 17.3%|

⚠️ High sales but low profit margin:

|   Sub-Category        | Sales  | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| Chairs   | 1.50M  | 9.4%   |
| Bookcases   | 1.47M   | 11.0%  |
| Storage   | 1.12M   | 9.6% |
| Machines   | 0.78M   | 7.6%   |
| Tables   | 0.76M   | -8.5% -> alarming   |

🧐 Low sales but high profit margin:

| Market         | Sales  | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| Binders   | 0.46M   |  15.7%  |
| Furnishings   | 0.38M  |  12.2%  |
| Art   | 0.37M  |  15.6%  |
| Paper   |0.24M  | 24.2  |
| Envelopers   |  0.17M  |  17.3%  |
| Fasteners   |  0.08M  |  13.8%  |
| Labels   |  0.07 | 20.4%  |

🚨 Low sales and low profit margin

| Market         | Sales  | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| Supplies   | 0.24M   | 9.3%   |

➡️**Overall:**
- Technology is both the revenue and profit leader but may face more returns.
- Most sub-categories had positive profit margins, except Table (-8.5%) --> analyze the performance of this category in different markets to identify areas of inefficiency
- Top-performing sub-categories: Phones (1.7M sales, 12.7% margin) and Copiers (1.5M sales, 17.1% margin)
- Highest profit margin: Paper (24.2% margin), Labels (20.4% margin)
- Worst profit margin: Machines (7.6%) and Tables (-8.5%)

### 📍By Market:
#### 📌 Sales:
- The sales trend increased steadily from 2010 to 2014. Sales seasonality is strong-likely around Q3 and Q4, suggesting marketing efforts align with seasonal demand.
- APAC (especially which region), EU (especially which region), and US (especially which region) are the dominant contributors to total sales in most years.
#### 📌 Profit Margin:
- The profit margin varies significantly by market and over time, suggesting differences in cost structure, pricing, or customer behavior.
- Some regions (Canada, EU, APAC) have strong profit margins, while others are less consistent over time.
#### 📌 Return Rate:
- Return rates are a concern in APAC-North Asia, US-West and LATAM-North, which may imply customer dissatisfaction or fulfillment issues.
#### 📌 Market Performance:
- **Average profit margin: 11.6%**

✅ High sales and high profit margin:

| Sub-category         | Sales Share (%) | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| APAC   | 28.3%   | 12.2%   |
| EU   | 23.2%   | 12.7% |
| US    | 18.1%   | 12.5%|

🔻**APAC:**
- All regions had considerably high sales but the profit margin was alarmingly low in Southeast Asia (2.0%) and lower than average in Oceania (10.9%)
- North Asia had the highest return rate (13.8%) among all regions, implying customer dissatisfaction or fulfillment issues --> need to adjust to increase the profit margin.
- Bookcases, Chairs, Copiers and Phones were top revenue-drivers in all 3 regions
- In Southeast Asia, half of the subcatories had negative profit margins, which might drag down the profit margin of the whole region.
- The profit margins of Tables were negative in 3 out of 4 regions in APAC, except for Central Asia, and was the lowest in Southeast Asia (-35.5%)--> considering restructuring costs or phasing out in these areas

🔻**EU:**
- Central (1.7M) had the considerably higher sales than North (0.63M) and South (0.6M), while the profit margins were strongest in North (14.7%), followed by Central (12.5%) and South (11.1%)
- Bookcases, Copiers, Phones and Storages were top revenue-drivers in all 3 regions
- In North, Furnishing had an alarmingly negative profit margin (-29.5%), which might drag down the overall profit margin of the whole region
- In South, the profit margins were negative in 5 out 17 subcategories and the lowest in "Tables" sub-cateogory (-59.3%).
- In Central, the profit margin were good in almost all sub-category, except for Table (-59.3%)
  
🔻**US:**
- The West was both revenue (0.7M) and profit leader (14.7%) in the US
- Chairs and Phones were top revenue-drivers in all 4 regions
- In the Central, 7 sub-categories had negative profit margins, draging the profit margin of the whole region down to only 7.9%
- The profit margins of Bookcases, Machines, and Tables were negative 3 out of 4 regions --> considering restructuring costs or phasing out in these areas


⚠️ High sales but lower profit margin:

| Market         | Sales Share (%) | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| LATAM   | 17.12%   | 10.2%   |

🔻**LATAM:**
- Sales of North, South, and Central in LATAM were relatively equal, around 0.6M-0.62M, while Caribbean was only haft of it.
- The profit margins were overall lower than average, except for North (16.5%)

➡️ The North was both revenue and profit leader in the LATAM

- Bookcases, Copiers, Chairs and Phones were top revenue-drivers in all 4 regions
- Furnishings, Machines, Tables had the lowest profit margins and were negative in some regions (detailed table)

🧐 Low sales but high profit margin:

| Market         | Sales Share (%) | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| Canada   | 0.53%   | 26.6%   |

🔻**Canada:**
- Storages and Phones were top revenue-drivers
- The majority of sub-categories had considerably high profit margin but the sales were still low --> need to scale up

🚨 Low sales and low profit margin

| Market         | Sales Share (%) | Profit Margin (%)      |
|-------------|:------:|:------------------:|
| EMEA   | 6.4%   | 5.4%   |
| Africa   | 6.2%   | 11.3% |

🔻**EMEA:**
- Storages, Phones and Bookcases were top revenue-drivers
- The profit margins of all sub-categories were positive but still lower than averange, except "chairs" (-0.9%)

🔻**Africa:**
- Storages, Phones, and Copiers were top revenue-drivers and had strong profit margins (14%-16%)
- The profit margins were overall good for most categories, except for Appliances (5.9%) and Chairs (5.0%)

➡️**Overall:**
- APAC and EU were the revenue leader, while Canada is the profit leader but with low sales
- Most sub-categories had positive profit margins, except Table (-8.5%) --> analyze the performance of this category in different markets to identify areas of inefficiency

### 📍By Customer Segment:

#### 📌 Sales:
- Sales from Consumer was the biggest (6.5M), followed by Corporate (3.8M) and Home Office (2.3M)
- Sales of all segments have grown steadily across years with peak-season in Q4 and Consumer segment showed the strongest growth trend. 
#### 📌 Profit Margin:
- Volatile across all segments, especially Home Office, which fluctuates significantly but remained in the 10–15% range for all segments.
- The profit margin was relatively equal, around 11.5%-12.0% 
#### 📌 Return Rate:
- Return rates are relatively the same across 3 customer segments, around 4,5%-5%
#### 📌 Segment Performance:
🔎 Top-performing category (true for all customer segments)
+ Phones
+ Copiers
+ Bookcases
+ Chairs

### :three: Details <br>
![alt](https://github.com/NguyenPhuongNghi/Market-and-Product-Analysis/blob/main/photo/Screenshot%202025-07-01%20140538.png?raw=true)

### :four: Key Drivers Analysis <br>
![alt](https://github.com/NguyenPhuongNghi/Market-and-Product-Analysis/blob/main/photo/Screenshot%202025-07-01%20140643.png?raw=true)

## :five: Insight:
#### :mag_right: Conlusion
<table>
  <tr>
    <th valign="top">Sales ↓ / Margin →</th>
    <th valign="top">High Profit Margin</th>
    <th valign="top">Low Profit Margin</th>
  </tr>
  <tr>
    <th valign="top">High Sales</th>
    <td valign="top">
      <b>🔻APAC </b>
      <br>- Top-performing Category (true for all regions)
      <br>+ Chairs - Consumer
      <br>+ Copiers - Consumer
      <br>+ Bookcases - Consumer
      <br>+ Phones – Consumer 
      <br><b>🔻 EU </b>
      <br>- Top-performing Category:
      <br>+ Central: Phones - Consumer, Storage - Consumer, Copiers - Consumer
      <br>+ North: Phones - Consumer, Bookcases - Consumer, Copiers - Consumer 
      <br>+ South: Bookcases - Consumer, Copiers - Consumer, Appliances – Corporate
      <br><b>🔻 US </b>
      <br>- Top-performing Category:
      <br>+ Central: Phones - Consumer, Copiers - Consumer, 
      <br>+ East: Phones - Consumer, Bookcases - Consumer, Copiers - Consumer
      <br>+ South: Phones - Consumer, Chairs - Consumer     
      <br>+ West: Storage - Consumer, Accessories - Consumer, Binders - Consumer
    <td valign="top">
      <b>🔻 LATAM </b>
      <br>- Top-performing Category:
      <br>+ Caribbean: Copiers - Consumer, Chair - Consumer, Phones - Consumer
      <br>+ Central: Bookcases - Consumer, Chairs - Consumer
      <br>+ North: Copiers - Consumer, Phones – Consumer
      <br>+ South: Chairs - Consumer
  </tr>
  <tr>
    <th valign="top">Low Sales</th>
    <td valign="top">
      <b>🔻 Canada </b>
      <br>- Top-performing Category:
      <br>+ Phones - Consumer
      <br>+ Storage - Consumer
    <td valign="top">
      <b>🔻 EMEA </b>
      <br>- Top-performing Category:
      <br>+ Bookcases - Consumer
      <br>+ Copiers - Consumer
      <br><b>🔻 AFRICA </b>
      <br>- Top-performing Category:
      <br>+ Phones - Consumer
      <br>+ Copiers - Consumer
      <br>+ Storage - Consumer
  </tr>
</table>


:bulb: **Market Strategy Matrix: Sales vs. Profit Margin**
<table>
  <tr>
    <th valign="top">Sales ↓ / Margin →</th>
    <th valign="top">High Profit Margin</th>
    <th valign="top">Low Profit Margin</th>
  </tr>
  <tr>
    <th valign="top">High Sales</th>
    <td valign="top">
      <b>✅ Scale Up Aggressively </b>
      <br>+ Increase investment in marketing and distribution.
      <br>+ Expand to similar or high-potential markets.
      <br>+ Prioritize inventory and logistics support.
      <br>+ Consider gradual price increases if the value proposition is strong.
    <td valign="top">
      <b>⚠️ Optimize Profitability – Improve Efficiency </b>
      <br>+ Optimize cost structure: renegotiate supplier terms, re-evaluate supply chain and production processes, use automation or scale to lower operational costs,...
      <br>+ Reevaluate pricing or promotional tactics.
      <br>+ Prioritize markets where value-based pricing is more accepted over price-based competition.
      <br>+ Explore upselling or bundling higher-margin products
      <br>+ Prioritize marketing & distribution for categories with strong margins.
      <br>+ Create premium versions of best-selling products to increase profit per sale
  </tr>
  <tr>
    <th valign="top">Low Sales</th>
    <td valign="top">
      <b>🧐 Selective Expansion – Niche Growth Potential </b>
      <br>+ Expand Lookalike Market (Run pilot campaigns in untapped regions with similar customer profiles)
      <br>+ Highlight premium value (performance, security, or exclusivity) in branding or storytelling.
      <br>+ Storage - Consumer
      <br>+ Create high-margin bundles
      <br>+ Focus on niche, high-value use cases
      <br>+ Consider repositioning or creating a “hero product” marketing push.
    <td valign="top">
      <b>🚨 Rationalize or Reposition – Divest or Redesign </b>
      <br>+ Investigate root causes (poor demand, high costs, weak fit).
      <br>+ Replace or reposition current low-performing categories with high-demand alternatives that fit local use
      <br>+ Bundle Low-Margin Items with High-Margin Ones
      <br>+ Either improve the value proposition, build brand recognition or exit the segment.
      <br>+ Form distribution partnerships with local retailers or e-commerce platforms
  </tr>
</table>














