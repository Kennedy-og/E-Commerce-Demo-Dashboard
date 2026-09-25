# E-Commerce Demo Dashboard
<img width="572" height="317" alt="Dashboard Snapshot" src="https://github.com/user-attachments/assets/e09ea328-4fba-4d17-a32a-91d6c0526d0b" />
<img width="584" height="317" alt="Screenshot 2026-09-24 132202" src="https://github.com/user-attachments/assets/c35c043c-566f-403b-967e-b392ca0bb865" />


> An interactive e-commerce sales dashboard designed to turn transactional data into clear, actionable insights.



---

## Table of Contents

- [Overview](#overview)
- [The Problem](#the-problem)
- [Objective](#objective)
- [Dashboard Overview](#dashboard-overview)
- [Key Metrics](#key-metrics)
- [Key Questions](#key-questions)
- [Analysis](#analysis)
- [Tools & Technologies](#tools--technologies)
- [What I Learned](#what-i-learned)
- [What I Would Improve](#what-i-would-improve)
- [Dashboard Preview](#dashboard-preview)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)

---

## Overview

The **E-Commerce Demo Dashboard** is an interactive sales analytics dashboard built to provide a clear view of e-commerce performance across revenue, quantity, pricing, customers, products, time, and geography.

Rather than presenting individual metrics in isolation, the dashboard brings these perspectives together into a single view so that users can quickly understand **what is happening in the data and where further analysis may be needed.**

---

## The Problem

E-commerce data can contain thousands of transactions across different products, customers, dates, and locations.

Looking through raw records makes it difficult to quickly answer questions such as:

- How much revenue was generated?
- How many units were sold?
- What is the average unit price?
- How is sales performance changing over time?
- Which units have the highest quantity sold?
- Which customers contribute the most spending?
- Where are sales geographically concentrated?

The dashboard was designed to make these questions easier to answer from a single analytical view.

---

## Objective

The objective of this project was to transform e-commerce data into an interactive dashboard that allows users to:

- Monitor overall sales performance
- Compare current performance with the previous year
- Identify changes in monthly sales
- Understand customer spending
- Identify top-performing units
- Explore geographical sales distribution

The focus was not simply on creating charts, but on creating a dashboard around **analytical questions**.

---

## Dashboard Overview

The dashboard contains several analytical areas:

### Revenue

Displays total revenue for the selected year and its comparison with the previous year.

### Quantity

Shows the total quantity sold and the year-over-year change.

### Average Unit Price

Provides the average price per unit and its comparison with the previous year.

### Customer Insight

Provides an overview of customer activity and highlights the top spending customers.

### Monthly Sales Trend

Shows how sales change throughout the selected year.

### Top 5 Units by Quantity Sold

Highlights the five units with the highest quantity sold.

### Geographical Sales Distribution

Provides a geographical view of sales and highlights locations with significant sales activity.

---

## Key Metrics

Example dashboard values for the selected period:

| Metric | Value |
|---|---:|
| Revenue | $15M |
| Quantity Sold | 852K |
| Average Unit Price | $17.6 |
| Customers | 9K |
| Selected Year | 2016 |

The dashboard is interactive, so displayed values change based on the selected filters.

---

## Key Questions

The dashboard was designed around the following questions:

### Sales Performance

- What is the total revenue?
- How many units were sold?
- What is the average unit price?
- How did performance change compared with the previous year?

### Customer Analysis

- How many customers are represented?
- Who are the top spending customers?
- How significant is the contribution of the top customers?

### Product Analysis

- Which units have the highest quantity sold?
- Which products are contributing most to sales volume?

### Time Analysis

- How does sales performance change throughout the year?
- Are there noticeable peaks or declines in monthly sales?

### Geographical Analysis

- Which locations generate the most sales?
- How is sales performance distributed geographically?

---

## Analysis

The analysis follows a simple workflow:

**Understand → Explore → Clean → Analyze → Communicate → Recommend**

### 1. Understand

Identify the questions the dashboard needs to answer before deciding which visualizations to create.

### 2. Explore

Examine the available sales, customer, product, date, and geographical data to understand the structure and available fields.

### 3. Clean

Prepare the data so that calculations, comparisons, and visualizations can be interpreted consistently.

### 4. Analyze

Analyze key measures including:

- Revenue
- Quantity
- Average unit price
- Customer spending
- Monthly sales
- Product quantity
- Geographical sales

### 5. Communicate

Translate the analysis into a dashboard that prioritizes important information and allows users to understand performance quickly.

### 6. Recommend

Use the patterns identified in the dashboard as a starting point for deeper investigation and business decisions.

> **Problem first. Tools second.**

---

## Tools & Technologies

- **Power BI** — Dashboard development and visualization
- **Data Analysis** — Exploratory and comparative analysis
- **Data Visualization** — KPI cards, trend analysis, rankings, and geographical visualization

---

## What I Learned

One of the main lessons from this project was that a dashboard should be designed around **questions, not charts**.

Instead of asking:

> *What chart should I create?*

I focused on:

> *What does the user need to understand?*

This influenced the selection and placement of the visualizations.

I also learned the importance of visual hierarchy. The most important metrics need to be immediately visible, while supporting analysis can sit deeper within the dashboard.

---

## What I Would Improve

Future iterations could include:

- More detailed customer segmentation
- Additional product-level analysis
- More flexible date filtering
- Deeper geographical drill-down
- Profitability analysis if cost data becomes available
- More detailed tooltips
- Drill-through pages for deeper analysis
- Additional business-focused KPIs

These improvements would depend on the available data and the intended business use of the dashboard.

---

## Dashboard Preview


<img width="572" height="317" alt="Dashboard Snapshot" src="https://github.com/user-attachments/assets/e09ea328-4fba-4d17-a32a-91d6c0526d0b" />

---

## Project Structure

```text
E-Commerce-Dashboard/
│
├── README.md
├── images/
│   └── dashboard-preview.png
│
└── dashboard fIle/
    └── E-commerce.pbix
