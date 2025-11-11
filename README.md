#  Blinkit Performance Triad: CX, Marketing & Operations Monitor
## Purpose

This comprehensive, three-page Tableau dashboard provides Blinkit management with a **unified, actionable view** of the business. Its core purpose is to track key performance indicators (KPIs) across the customer journey—from marketing reach (ROAS) to service fulfillment (delivery efficiency) and post-purchase feedback (customer sentiment)—enabling data-driven decisions for retention, budget allocation, and operational excellence.

---

## Tech Stack

| Category | Tool/Language | Use |
| :--- | :--- | :--- |
| **Visualization** | **Tableau Desktop** | Interactive dashboard creation and visual analysis. |
| **Data Cleaning / Pre-processing** | Excel | Data cleaning, and calculated field preparation. |
| **Source Data Format** | CSV | Raw input files. |

---

## Data Source

The analysis is based on a simulated set of transactional, customer, and marketing data for a quick commerce platform, segmented into the following files:

* `blinkit_marketing_performance.csv`
* `blinkit_customers.csv`
* `blinkit_orders.csv`
* `blinkit_customer_feedback.csv`
* `blinkit_products.csv`
* `blinkit_order_items.csv`

---

## Project Features & Analysis

### 1. Business Problem

Blinkit faces the challenge of managing growth while maintaining service quality and profitable marketing spend. Specifically, management lacked a consolidated view to answer critical questions simultaneously:
1.  **Retention Risk:** Which service categories are generating the most negative feedback and driving potential customer churn?
2.  **Budget Waste:** Which marketing channels or campaigns are underperforming (low ROAS) and need immediate budget reallocation?
3.  **Service Reliability:** Where are the operational bottlenecks (slow stores, high cancellation rates) impacting the core promise of quick delivery?

### 2. Goal of the Dashboard

The goal is to provide a **"single pane of glass"** that delivers actionable insights, enabling teams to:
* **Customer Service:** Pinpoint geographic areas and service categories demanding corrective action to reduce customer dissatisfaction.
* **Marketing:** Optimize budget allocation by identifying high-efficiency campaigns and maximizing Return on Ad Spend (ROAS).
* **Operations:** Monitor delivery metrics in real-time to maintain service reliability and efficiency.

### 3. Walkthrough of Key Visuals (Briefly!)

The dashboard is divided into three interconnected pages:

* **Page 1: Customer Experience & Sentiment Pulse:**
    * **Focus:** Tracks the trend of Average Rating and isolates the **Root Cause of Feedback** by category (Delivery, Product, App). This allows for targeted quality improvements.
* **Page 2: Marketing Performance & Growth Engine:**
    * **Focus:** Uses a **Scatter Plot** to visualize **Conversions vs. Spend** by Channel (ROAS). This instantly flags high-efficiency channels (low spend, high conversions) and informs budget strategy.
* **Page 3: Operational Efficiency & Fulfillment Monitor:**
    * **Focus:** Displays the **On-Time Delivery Rate** KPI and uses a color-coded bar chart to highlight the **Average Delivery Time by Store**. This identifies operational bottlenecks for logistical audits.

### 4. Business Impact & Insights

| Key Insight/Impact | Actionable Takeaway |
| :--- | :--- |
| **Identified Low ROAS Channels:** | Reallocate 25% of spend from the two lowest-performing marketing channels to the highest-efficiency channel (e.g., App Push). |
| **Pinpointed Service Bottlenecks:** | Stores with the highest average delivery times are prioritized for operational audits and additional staffing partner allocation. |
| **Quantified Feedback Drivers:** | **Delivery** was confirmed as the largest driver of negative feedback, justifying immediate investment in real-time tracking systems and. |
| **Established Key Performance Baseline:** | Provided clean, single-source KPIs (e.g., Average ROAS: 3.5x, On-Time Rate: 92.5%, Avg Rating: 4.1) for future strategic monitoring. |

---

### 5. Screenshots

| Page Name | Screenshot |
| :--- | :--- |
| Executive Summary | ![Page 1](https://github.com/YashMastakar/Tableau-Blinkit-Performance-Dashboard/blob/main/Blinkit_Performance_Dashboard_pg2.png) |
|Marketing Performance | ![Page 2](https://github.com/YashMastakar/Tableau-Blinkit-Performance-Dashboard/blob/main/Blinkit_Performance_Dashboard_pg3.png) |
|Operational Efficiency |![Page 3](https://github.com/YashMastakar/Tableau-Blinkit-Performance-Dashboard/blob/main/Blinkit_Performance_Dashboard_pg4.png)|


## 6. License

This project is licensed under the **APACHE 2.0 LICENSE** - see the [LICENSE](https://github.com/YashMastakar/Tableau-Blinkit-Performance-Dashboard/blob/main/LICENSE)) file for details.
