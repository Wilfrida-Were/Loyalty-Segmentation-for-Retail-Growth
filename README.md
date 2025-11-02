# Loyalty Segmentation for Retail Growth

## Project Goal: Segment, Quantify, and Act on Customer Loyalty

This project helps **retail founders, operators, and analysts** turn raw customer data into **loyalty intelligence** revealing who their most loyal customers are, how they behave, and how to retain them with precision.

Retailers collect vast data through loyalty programs, digital platforms, and point-of-sale systems. But most lack visibility. They treat all customers the same, send generic offers, and miss the signals that drive repeat revenue.

A founder put it simply:

> “We collect customer data, but we don’t know who our loyal customers are or how to keep them.”  

## Business Impact Summary

- Found the customer segments driving most of the revenue. Champions alone contribute 68%  
- Uncovered £3.8M in retention potential from Loyalists and At Risk customers  
- Highlighted repeat-buy products ideal for bundles, upsells, and loyalty campaigns  
- Flagged bulk-driven products to adjust pricing and avoid misleading popularity metrics  
- Identified the best time to run campaigns, Thursday mornings at 11AM  
- Focused loyalty strategy on the UK, where most customers and repeat buyers are concentrated  
- Prioritized retention over reactivation to save time and resources  
- Delivered clear, ready-to-use actions to grow revenue and customer lifetime value

For those who want to explore the  full code on Kaggle:

👉 [Loyalty Segmentation for Retail Growth](https://www.kaggle.com/code/wilfridawere/loyalty-segmentation-for-retail-growth)

## 📑 Table of Contents
* [Interactive Dashboard](#dashboard)
* [Key Insights](#key-insights)
* [Recommendations](#recommendations)
* [Client Scenario:Applying the Recommendations](#client-scenario)
* [Tech Stack](#tech-stack)
* [Workflow](#workflow)
* [Let’s Connect](#lets-connect)

<a id="dashboard"></a>
## Interactive Dashboard

This project includes **three dashboards**:  
1. Loyalty Segmentation Overview  
2. Customer Behaviour Insights 
3. Customer Loyalty Breakdown  

To keep things simple, we preview the first page below.  
Use the **page tabs at the top** of the Tableau dashboard to explore the others.

👉 [View the Interactive Dashboard on Tableau](https://public.tableau.com/app/profile/wilfrida.were/viz/LoyaltySegmentationforRetailGrowth/1_LoyaltySegmentationOverview)  

Preview (click image to open dashboard):  
[![Loyalty Segmentation Overview](https://raw.githubusercontent.com/Wilfrida-Were/Loyalty-Segmentation-for-Retail-Growth/main/1.%20Loyalty%20Segmentation%20Overview%20(1).png)](https://public.tableau.com/app/profile/wilfrida.were/viz/LoyaltySegmentationforRetailGrowth/1_LoyaltySegmentationOverview)

---

<a id="key-insights"></a>  
## 🔑 Key Insights

The goal isn’t just to describe loyalty. It’s to segment it, quantify its impact, and act on it.

Here’s what the data reveals:


### Key Performance Indicators (KPIs)

| KPI | Value |
|-----|-------|
| Total Customers | 5,852 |
| Total Revenue | £17.0M |
| Total Invoices | 36,582 |
| Total Quantity | 10.5M |
| Basket Size | 286.2 |
| ARPC (Avg Revenue per Customer) | £2,904 |
| Purchase Frequency | 6.25 |
| Repeat Purchase Rate | 72.33% |
| Avg Order Value | £464.6 |

The business attracts repeat buyers with strong basket sizes and frequent purchases. But loyalty isn’t evenly spread, and that’s where the story begins.

---

### 1. Champions Drive 68% of Revenue but Only 22% of Customers

- Just **1,288 Champions** generate **£11.6M**, the majority of revenue.
- This small group is your growth engine.
- If they churn, the impact is massive. If nurtured, the upside is even bigger.

---

### 2. Loyalists and At Risk Customers Hold £3.8M in Value

- **Loyalists (19%) and At Risk (11%)** are still active and spending.
- Loyalists are your “almost Champions”, but At Risk customers are fragile.
- Retention here offers high leverage.

---

### 3. Lost Customers Contributed £793K

- Though inactive, the **Lost segment (20%)** left a meaningful revenue footprint.
- These customers had meaningful spend before disengaging.
- Their history justifies targeted win-back campaigns, especially those with high basket sizes or sticky product behavior.

---

### 4. Thursday Is the Top Revenue Day Every Year

- Weekdays outperform weekends consistently.
- **Thursday leads across all years**, likely tied to restocking or pre-weekend buying.
- Campaigns and inventory should align with this midweek surge.

---

### 5. 11AM–12PM Is the Peak Shopping Hour

- This hour sees the **highest invoices, quantities, and revenue**.
- Activity builds from 8AM, peaks midday, and drops after 2PM.
- Ideal timing for flash sales, email drops, or support coverage.

---

### 6. Bulk Buyers Skew Product Popularity

- Top-selling items like **PAPER CRAFT, LITTLE BIRDIE** are driven by a few bulk buyers.
- Others like **lunch boxes and record frames** are bought repeatedly by many.
- Segmenting products by buyer type helps tailor promotions and bundles.

---

### 7. Lost Customers Had the Largest Basket Size

| Segment | Basket Size |
|---------|-------------|
| Lost | 340.5 |
| Champions | 315.3 |
| At Risk | 241.2 |
| Loyalists | 228.6 |
| Monitor | 218.9 |
| Low Value | 120.5 |

- Lost customers bought more per basket than any other segment.
- This suggests they were high-engagement buyers who churned.
- High volume doesn’t guarantee loyalty. Churn may have been driven by friction, unmet expectations, or lack of follow-up.

---

### 8. Repeat Products Show Strong Loyalty Signals

| Product | Purchase Frequency |
|---------|--------------------|
| RECORD FRAME 7" SINGLE | 4.83 |
| LUNCH BOX I LOVE LONDON | 4.79 |
| DOLLY GIRL LUNCH BOX | 4.63 |
| BLACK RECORD COVER FRAME | 4.50 |
| COOK WITH WINE METAL SIGN | 4.21 |
| CHILLI LIGHTS | 4.04 |

- These products are bought again and again, excluding bulk buyers.
- They’re **loyalty anchors**, ideal for bundling, upsell, and retention campaigns.

---

### 9. The UK Is the Primary Market and Loyalty Is Strong

- The **UK accounts for the majority of customers**, making it the core market for loyalty strategy.
- Within the UK, loyalty density is high.**Champions and Loyalists make up a significant share of the customer base**.
- This signals strong engagement and repeat behavior in the primary market.
- Loyalty efforts should focus on **reinforcing UK retention**, while tailoring re-engagement strategies for smaller regions.

---

### 10. Outreach Rank Helps Prioritize Retention

| Segment | Priority |
|---------|----------|
| At Risk | 🔴 Urgent, still active, but drifting |
| Loyalists | Valuable, protect them |
| Champions | High-value, reinforce loyalty |
| Monitor | Fragile, watch closely |
| Low Value | Minimal leverage |
| Lost | Inactive, reactivate selectively

- **At Risk customers are still reachable**. This is your core retention battleground.
- Champions and Loyalists deserve reinforcement to protect long-term value.

---

<a id="recommendations"></a>  
## ✅ Recommendations

| Segment or Signal | Recommended Action | Estimated Impact |
|-------------------|---------------------|------------------|
| **At Risk Customers** | Launch retention campaigns with personalized bundles | ↑ retention, ↓ churn risk |
| **Loyalists** | Offer early access to new arrivals and bundle sticky products (e.g. lunch boxes + record frames) | ↑ repeat rate, ↑ revenue |
| **Champions** | Protect with loyalty perks, feedback loops, and priority access | ↑ lifetime value, ↓ churn risk |
| **Lost Customers with High Basket Size** | Selectively deploy win-back emails referencing past spend | ↑ reactivation, ↑ CLV |
| **Bulk-Driven Products** | Flag SKUs bought by <13 customers and adjust pricing/messaging for bulk buyers | ↑ margin clarity, ↓ product distortion |
| **Sticky Products (high repeat rate)** | Feature in homepage bundles and loyalty campaigns (e.g. RECORD FRAME 7" SINGLE + BLACK RECORD COVER FRAME) | ↑ AOV, ↑ retention |
| **Thursday + 11AM–12PM peak** | Schedule flash sales, email drops, and inventory restocks for Thursday mornings | ↑ conversion, ↓ missed opportunity |
| **UK Loyalty Density** | Focus retention efforts on UK Champions and Loyalists with tailored messaging and perks | ↑ relevance, ↑ retention in core market |

---

<a id="client-scenario"></a>  
## Client Scenario: Applying the Recommendations

A founder opens the loyalty dashboard and sees that **Champions drive 68% of revenue**, while **At Risk and Loyalists still hold £3.8M in active value**. Instead of treating all customers the same, they act with precision:

### 🎯 Goal: Retain High-Value Customers Before They Slip—and Reactivate Selectively

1. **Re-engage At Risk Customers with Product-Based Offers**  
   Customers who bought CHILLI LIGHTS or COOK WITH WINE METAL SIGN are offered bundle discounts. These are familiar items with high repeat potential.

2. **Reward Loyalists with Early Access and Sticky Bundles**  
   Loyalists receive early access to new arrivals and curated bundles featuring RECORD FRAME 7" SINGLE and DOLLY GIRL LUNCH BOX—products they’ve bought repeatedly.

3. **Protect Champions with Exclusive Perks**  
   Champions are invited to a feedback loop and offered priority access to seasonal launches. Their loyalty is reinforced with recognition and rewards.

4. **Selectively Win Back Lost Customers with High Spend**  
   Lost customers with basket sizes over £300 are sent “We Miss You” emails referencing their past purchases and offering a tailored discount. Only those with high historical value are targeted.

5. **Segment Bulk Buyers for Strategic Pricing**  
   Products like WW2 Gliders, bought by <13 customers, are flagged for bulk pricing and B2B messaging, avoiding distortion in retail metrics.

6. **Feature Sticky Products in Loyalty Campaigns**  
   High-frequency items are bundled and promoted in loyalty emails and homepage features, driving repeat purchases and increasing AOV.

7. **Time Campaigns for Thursday at 11AM**  
   Flash sales and email drops are scheduled for Thursday mornings, when invoice volume and revenue peak. This aligns with real shopping behavior.

8. **Double Down on UK Retention**  
   With most customers in the UK, retention efforts focus here, reinforcing loyalty among Champions and Loyalists with tailored messaging and perks.

---

<a id="tech-stack"></a>
## ⚙️ Tech Stack

- **Python** – Data cleaning, EDA, correlation and RFM
- **Kaggle Notebook** – End-to-end workflow combining code, analysis, and documentation
- **Tableau Public** – Interactive dashboard visuals

---

<a id="workflow"></a>
## 🔄 Workflow

1. **Raw Data** → [Kaggle Dataset: Online Retail II UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)  
2. **Data Cleaning & Preprocessing** → Performed in Python (Pandas) to handle missing values, fix formatting, and prepare data for analysis.  
3. **Exploratory Data Analysis (EDA)** → Conducted in Python using Pandas for aggregations and Matplotlib/Seaborn for identifying trends and patterns.
4. **RFM segmentation** → Calculated Recency, Frequency, and Monetary scores to segment customer loyalty,
5. **Visualization & Storytelling** → Built charts in Tableau to present insights in a clear, business-focused manner.

---

<a id="lets-connect"></a>
## 🔗 Let’s Connect

Feel free to connect, follow, or support:  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/wilfridawere/)  

[![Twitter](https://img.shields.io/badge/X-Follow-black?style=flat&logo=twitter)](https://x.com/wilfridawere)  

[![Website](https://img.shields.io/badge/Website-Visit-orange?style=flat&logo=google-chrome)](https://www.wilfridawere.com/)  

[![Kaggle](https://img.shields.io/badge/Kaggle-Follow-blue?style=flat&logo=kaggle)](https://kaggle.com/wilfridawere)  

[![GitHub](https://img.shields.io/badge/GitHub-Projects-black?style=flat&logo=github)](https://github.com/Wilfrida-Were)  
