# RFM Customer Segmentation Analysis


---

## Executive Summary

This project presents a comprehensive Recency, Frequency, and Monetary (RFM) analysis of 18,484 customers across multiple geographic regions, generating $29.36M in total sales. The analysis segments customers into actionable groups to enable targeted marketing strategies and improve customer retention and lifetime value.

**Key Insight:** The customer base shows significant opportunity for re-engagement and loyalty programs, with high-value Champions and Loyal customers accounting for substantial revenue, while at-risk segments require immediate intervention.

---

## Project Overview

### Objective
To segment the customer base using RFM analysis and provide data-driven recommendations for marketing teams to optimize customer engagement, reduce churn, and maximize profitability.

### Dataset Scope
- **Total Customers:** 18,484
- **Total Sales:** $29.36M
- **Geographic Coverage:** North America, Europe, Asia, South America, Australia, and Africa
- **Customer Demographics:** Mixed gender (49.54% Female, 50.46% Male) and marital status distribution (48.27% Married, 51.73% Single)

  <img width="906" height="510" alt="1" src="https://github.com/user-attachments/assets/39d99e68-79b6-419e-8dbc-1ecaf472ca17" />


---

## Methodology

### RFM Framework

The analysis utilizes three core metrics to evaluate customer behavior:

**Recency (R):** Measures how recently a customer made a purchase or interacted with the business. Customers with recent activity are more responsive to marketing campaigns.

**Frequency (F):** Tracks how often customers engage or purchase. Frequent customers demonstrate strong loyalty and are ideal candidates for retention programs and upselling initiatives.

**Monetary Value (M):** Quantifies the total spend by each customer. High-value customers represent the greatest profit potential and warrant premium treatment.

---

## Key Findings

### Customer Segmentation Results

| Segment | Customer Count | Total Sales | Key Characteristics |
|---------|---|---|---|
| **Champions** | 1.7K | $8.3M | Most loyal, high frequency, recent activity |
| **Loyal** | 1.8K | $6.2M | Consistent engagement, steady spend |
| **Potential Loyalty** | 1.0K | $0.1M | Growing engagement, opportunity for growth |
| **Promosing** | 2.6K | $2.9M | Moderate frequency, responsive to incentives |
| **New Customers** | 3.2K | $0.1M | Recent acquisitions, building relationship |
| **About To Sleep** | 1.1K | $0.3M | Declining engagement, at-risk |
| **Hibernating Customers** | 1.5K | $0.1M | Previously active, now dormant |
| **Need Attention** | 0.3K | $0.0M | Low engagement across all metrics |
| **At Risk** | 1.8K | $7.3M | High value but declining engagement ⚠️ |
| **Cannot Lose Them** | 2.0K | $3.5M | High-value, show signs of churn |
| **Lost Customers** | 1.4K | (churned) | No recent activity |

<img width="902" height="504" alt="2" src="https://github.com/user-attachments/assets/236087bc-6ee0-454e-9fac-7751cfbd04c5" />


### Critical Insights

**1. At-Risk High-Value Segment (Priority Alert)**
- **1,800 customers** representing **$7.3M in sales** (25% of revenue) are classified as "At Risk"
- These customers show declining recency and frequency despite high monetary value
- Immediate re-engagement campaigns are essential to prevent significant revenue loss

**2. Champion & Loyal Segments Are Revenue Powerhouses**
- **Champions** (1.7K) and **Loyal** (1.1K) customers generate **$9.0M combined** (31% of total revenue)
- These segments demonstrate consistently high recency, frequency, and monetary values
- Represent the most profitable customer cohort,priority for retention and loyalty rewards

**3. New Customer Pipeline Strength**
- **3,200 new customers** acquired recently, generating $1.0M in initial sales
- Significant opportunity to nurture this segment into the Champion/Loyal categories through targeted engagement

**4. Churn Risk: Hibernating & Cannot Lose Them**
- **1,500 hibernating customers** and **2,000 "Cannot Lose Them"** customers require immediate reactivation
- Combined potential revenue of **$4.5M** at risk if no intervention occurs

### Demographic Insights

**Age Distribution & Sales Performance:**
- **45-54 age group** leads with $6.4M in sales, representing the most valuable demographic
- **55-64 age group** follows with $11.4M, indicating strong purchasing power in the 55+ segment
- **65-74 age group** contributes $7.7M, suggesting brand loyalty in mature customer base
- **Younger segments (<45)** show lower sales volumes but represent future growth potential

<img width="384" height="137" alt="6" src="https://github.com/user-attachments/assets/9ece422a-1ae7-4791-9106-67f7b0ac1ea4" />

**Geographic Concentration:**
- **North America and Europe** drive the majority of sales volume, indicating established market presence
- **Asia and Australia** show growing customer bases with significant untapped potential
- Regional expansion opportunities exist in underdeveloped markets

<img width="351" height="382" alt="6" src="https://github.com/user-attachments/assets/622d0d5c-7d1e-441e-87e3-f7b23e859659" />

---

## Recommended Marketing Actions

### 1. Immediate Actions (0-30 Days)

**At-Risk Segment ($7.3M revenue):**
- Launch personalized win-back campaigns with special incentives
- Implement exclusive offers and loyalty rewards to re-engage declining customers
- Conduct customer satisfaction surveys to identify pain points

**Cannot Lose Them Segment ($3.5M revenue):**
- Assign dedicated account managers to high-value customers
- Provide VIP treatment, early access to new products, and personalized service
- Monthly check-ins to strengthen relationships and prevent churn

### 2. Short-Term Initiatives (1-3 Months)

**Hibernating Customers ($1.0M potential):**
- Launch "We Miss You" reactivation campaigns with exclusive comebacks
- Offer time-sensitive discounts or product upgrades
- Segment by previous purchase behavior to tailor messaging

**New Customers ($1.0M recent sales):**
- Implement onboarding programs to guide early purchases
- Establish regular touchpoints to increase purchase frequency
- Provide educational content and product recommendations

### 3. Long-Term Strategy (3+ Months)

**Champions & Loyal Segments ($9.0M revenue):**
- Establish premium loyalty programs with tiered rewards
- Create exclusive community or membership benefits
- Solicit feedback to guide product development and improve satisfaction

**Promoting Segment ($2.8M revenue):**
- Develop upsell and cross-sell campaigns
- Introduce subscription or recurring purchase models
- Create referral incentive programs to expand customer base

---

## Dashboard Features & Functionality

The Power BI dashboard provides three integrated views for comprehensive analysis:

**Customer Demographics Dashboard:**
- High-level KPIs: Total Sales ($29.36M), Customer Count (18.484K)
- Sales breakdown by gender, marital status, and age band
- Geographic distribution map for regional analysis
- Enables filtering by product for targeted insights

**RFM Segmentation Dashboard:**
- Visual representation of customer distribution across 11 segments
- Side-by-side comparison of sales performance by segment
- RFM metric visualization (Recency, Frequency, Monetary) for each segment
- Highlights relative strength of each dimension per customer group

**Customer Details Dashboard:**
- Granular customer-level data with all relevant attributes
- Segment classification for each customer record
- Email contact information for targeted campaign execution
- Sortable and filterable by any demographic or behavioral attribute

---

## Expected Business Impact

| Metric | Target | Potential Impact |
|--------|--------|---|
| **At-Risk Customer Retention** | 50% recovery | +$3.65M annual revenue |
| **New Customer Conversion to Loyal** | 25% upgrade | +$700K annual revenue |
| **Hibernating Reactivation Rate** | 30% | +$300K annual revenue |
| **Customer Lifetime Value Increase** | 15-20% overall | Enhanced profitability |

---

## Technical Implementation

**Tools & Technologies:**
- **Power BI:** Interactive dashboards and real-time analytics
- **Data Source:** Customer transaction database with 18,484 records
- **Segmentation Method:** RFM scoring model with quartile-based segmentation
- **Refresh Cadence:** Recommended monthly for trending analysis and timely intervention

---

## Conclusion

This RFM analysis reveals a customer base with significant untapped potential. While Champions and Loyal segments provide a strong revenue foundation, the critical $7.3M at-risk segment demands immediate strategic attention. By implementing targeted marketing actions aligned with customer segment characteristics, the organization can expect substantial improvements in retention rates, customer lifetime value, and overall profitability.

The interactive Power BI dashboard enables agile decision-making and allows stakeholders to monitor progress against recommended initiatives in real time.

---

## Appendix: Segment Definitions

- **Champions:** Bought recently, buy often, and spend the most
- **Loyal:** Consistently engaged with high purchase frequency and spend
- **Potential Loyalty:** Show signs of growth in engagement; nurture for loyalty conversion
- **Promoting:** Moderate engagement; responsive to promotional offers
- **New Customers:** Recent acquisitions; establish foundation for long-term relationship
- **About To Sleep:** Recent purchases declining; requires re-engagement
- **Hibernating:** Once active; now dormant; reactivation opportunity
- **Need Attention:** Low activity across all metrics; minimal priority
- **At Risk:** High-value but declining engagement; urgent intervention needed
- **Cannot Lose Them:** High-value showing churn signals; VIP retention focus
- **Lost Customers:** No recent activity; churned; consider win-back campaigns
