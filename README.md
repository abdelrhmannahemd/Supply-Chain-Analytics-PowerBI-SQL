# Supply Chain Analytics Dashboard | Power BI & SQL Server

A comprehensive Supply Chain Analytics project built using **Power BI** and **SQL Server** to analyze operational and financial performance across suppliers, products, transportation, and manufacturing processes.

This project demonstrates how business intelligence can transform raw operational data into actionable insights through interactive dashboards and SQL-driven analysis.

---

# Project Overview

The goal of this project is to monitor and evaluate supply chain performance by analyzing:

- Revenue Performance
- Operational Costs
- Product Performance
- Supplier Performance
- Transportation Efficiency
- Manufacturing Performance
- Product Quality & Inspection Results

The dashboard was intentionally designed with **two focused pages** to keep the analysis clear, simple, and business-oriented.

---

# Business Objectives

This dashboard helps answer questions such as:

- Which product category generates the highest revenue?
- Which supplier has the highest operational cost?
- Which transportation carrier is the most expensive?
- Which supplier has the highest defect rate?
- How long does shipping take for each transportation mode?
- Which locations generate the highest revenue?
- What is the company's overall Gross Margin?
- How do inspection results vary across suppliers?

---

# Tools & Technologies

- Microsoft Power BI
- SQL Server
- DAX
- Power Query
- Row Level Security (RLS)
- SQL Window Functions
- SQL Subqueries
- Aggregate Functions

---

# Dashboard Pages

## Overview Dashboard

This page focuses on business performance through high-level KPIs.

### KPIs

- Total Revenue
- Total Cost
- Average Unit Price
- Gross Margin

### Visualizations

- Revenue by Product Type
- Total Cost by Supplier
- Revenue by Customer Segment
- Revenue by Location

---

## Operations Dashboard

This page focuses on operational efficiency.

### KPIs

- Average Lead Time
- Average Shipping Time
- Manufacturing Cost
- Average Defect Rate

### Visualizations

- Shipping Cost by Carrier
- Average Shipping Time by Transportation Mode & Supplier
- Average Defect Rate by Supplier
- Inspection Results by Supplier

---

# SQL Analysis

The project also includes SQL analysis covering:

## Basic SQL

- SELECT
- WHERE
- ORDER BY
- TOP
- DISTINCT

## Aggregations

- SUM()
- AVG()
- COUNT()
- MIN()
- MAX()

## GROUP BY & HAVING

Business-oriented aggregation queries including:

- Revenue by Supplier
- Cost by Product Type
- Average Manufacturing Cost
- Supplier Performance

## Subqueries

Examples include:

- Products with revenue above average
- Top-performing products
- Revenue comparisons
- Supplier revenue analysis

## Window Functions

Implemented:

- ROW_NUMBER()
- RANK()


Examples:

- Ranking suppliers by revenue
- Ranking products within each category
- Top-performing products

---

# Row-Level Security (RLS)

Row-Level Security was implemented to restrict dashboard visibility by supplier.

This allows different users to access only the data assigned to them while maintaining data security and confidentiality.

---

# Key Business Insights

- Skincare products generate the highest revenue.
- Supplier 1 contributes the highest operational cost.
- Carrier B has the highest shipping cost.
- Supplier 5 records the highest defect rate.
- Mumbai and Kolkata generate the highest revenue.
- Shipping performance varies significantly across transportation modes.
- Inspection outcomes reveal differences in supplier quality performance.

---

# Skills Demonstrated

## Power BI

- Data Modeling
- Data Cleaning with Power Query
- DAX Measures
- KPI Cards
- Interactive Dashboards
- Navigation Buttons
- Slicers & Filters
- Row-Level Security (RLS)

## SQL

- Data Retrieval
- Filtering & Sorting
- Aggregate Functions
- GROUP BY & HAVING
- Subqueries
- Window Functions
- ROW_NUMBER()
- RANK()

---

# Business Value

This dashboard enables decision-makers to:

- Monitor supplier performance
- Evaluate operational efficiency
- Identify quality issues
- Compare supplier costs
- Analyze product performance
- Support data-driven decision making

