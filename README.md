# Reinaldi_Ragasa_SaaS_Sales_Capstone_M2

## 1. Business Understanding
**SaaS (Software as a Service) Sales** refers to selling cloud-based software through a subscription model, where customers pay recurring fees (monthly, quarterly, or annually) instead of a one-time purchase. Key aspects of SaaS sales include:

1. **Customer Acquisition** – Attracting and converting users via marketing (SEO, ads, demos) and sales efforts.
2. **Customer Onboarding** – Ensuring users quickly derive value from the product (tutorials, setup assistance).
3. **Customer Retention** – Keeping subscribers engaged to reduce churn (support, engagement strategies).
4. **Revenue Expansion** – Increasing revenue from existing customers (upselling, cross-selling).

## 2. Why SaaS Sales Matter
1. **Predictable Revenue**: Recurring subscriptions (MRR/ARR) ensure stable income.
2. **Scalability**: Low marginal cost per additional customer.
3. **High Retention Importance**: Churn directly impacts future revenue.
4. **Data-Driven Decisions**: Metrics like CLV, CAC, and churn rate guide strategies.
5. **Rapid Market Growth**: Global SaaS market projected to exceed $800B by 2030.

## 3. Problem Statement

This analysis examines how discounts impact profit margins in the **JAPN (Japan) and ANZ (Australia & New Zealand)** sub-regions, focusing on:

1. How do high discount rates affect profit margins in **AMER, APJ, and EMEA**?
2. Which **sub-regions** suffer the lowest profit margins due to excessive discounting?
3. Which **products** in these sub-regions have high discounts and negative profit margins?
4. Which **customer segments** contribute most to low-profit, high-discount scenarios?
5. How does the **discount-profit margin relationship** vary across cities in affected sub-regions?
6. What is the **optimal discount per product** to maximize profit margin above the 15% SaaS benchmark?

## 4. Analytical Approach

1. **Data Cleaning**
- Handle missing values, duplicates, and incorrect data types.
- Remove irrelevant columns, trim whitespace, and standardize entries.
- Detect outliers and assess variable relationships.
2. **Data Analysis**
- Visualizations: Bar/pie charts to identify trends.
- Statistical Tests:
- Kruskal-Wallis to check differences across categorical data.
- Spearman Correlation to measure relationships between numerical variables.
3. **Customer Segmentation**
- Identify regions/sub-regions with the lowest profit margins.
- Analyze companies, products, and segments contributing to low profitability.
4. **Optimal Discount Pricing**
- Determine discounts that maximize profit margin (>15%).
- Identify products with negative margins at optimal discounts.
- Assess discount thresholds where margins start declining.

## 5. Key Findings
### 1. **Discounts Strongly Impact Profit Margins**
- **Higher discounts correlate with lower profit margins**, especially in **APJ (median discount: 20%)**, which has the **lowest median profit margin** compared to **AMER & EMEA (0% discount, higher margins)**.
### 2. **Worst-Performing Sub-Regions: JAPN & ANZ**
- **JAPN & ANZ** have the **lowest profit margins** at a median **20%** discount, while **APAC & IND** perform better at **0%** discount.
- **Products with highest negative margins**:
    - **ContactMaster (80% discount)** → ~**-800%** margin
    - **OneView (60% discount)** → ~**-1300%** margin
### 3. High vs. Low Profit Segments
1. **Top Performers (High Profit Margins)**
- **JAPN**:
    - **Enterprise**: BMW
    - **SMB**: ExxonMobil
    - **Strategic**: General Motors, Phillips 66
- **ANZ**:
    - **Enterprise**: Hon Hai Precision, Kroger
    - **SMB**: Allstate
    - **Strategic**: Fannie Mae
- **Key Product**: **Support** (major contributor to positive margins).

2. **Worst Performers (Low Profit Margins)**
- **JAPN**:
    - **Enterprise**: Royal Dutch Shell, Pfizer
    - **SMB**: AT&T
    - **Strategic**: Bank of America
- **ANZ**:
    - **Enterprise**: Morgan Stanley
    - **SMB**: Humana
    - **Strategic**: Mitsubishi
- **Key Product**: ContactMatcher (main driver of negative margins).

### 4. **Optimal Discount Strategy**
1.  **0%** discount works best for **all products**, ensuring **margins exceed 15%**.
2.  **20%** discount works for **most products**, but **exceptions exist**:
- **JAPN**:
    - **MarketingSuite-Gold, DataSmasher, Storage in multiple cities (e.g., Hyogo, Osaka, Hiroshima)**.
- **ANZ**:
    - **MarketingSuite-Gold, DataSmasher in Brisbane, Adelaide, Geelong**.
3. **30%** discount only works for **BigOlDatabase (Perth & Sydney)**, but **Sydney** falls below benchmark **(6.12%)**.
4. **40%** discount is viable only for **BigOlDatabase in Aichi (19.44% margin)**.
5. Discounts **>40%** lead to **negative margins**, especially for **ContactMatcher & OneView**.

### 5. City-Level Profit Margins
- **All cities in JAPN & ANZ** fall **below 15%** margin at **20%-80%** discounts, except:
    - **Auckland & Wellington (ANZ)**: **Exceed benchmark** at **0%** discount.
 
## 6. Recommendations
1. **Avoid Excessive Discounts**: **0% discount maximizes margins for most products**.
2. **Review High-Discount Products**:
- **ContactMatcher & OneView** should not exceed **20%** discount.
- **MarketingSuite-Gold & DataSmasher** need pricing adjustments in high-discount cities.
3. **Focus on High-Margin Segments**:
- **Support** product drives profitability in **JAPN & ANZ**.
4. **Monitor Problematic Cities**:
- **Hyogo, Osaka, Hiroshima (JAPN) and Brisbane, Adelaide (ANZ) need revised discount strategies**.
5. **Expand Low-Discount Success**:
- **Auckland & Wellington (0% discount)** show strong performance—replicate in other cities.
