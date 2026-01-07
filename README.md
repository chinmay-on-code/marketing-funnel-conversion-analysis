# marketing-funnel-conversion-analysis
End-to-end marketing funnel and conversion analysis using event-level e-commerce data to identify drop-off points and optimization opportunities with SQL and Python.
## 📌 Project Overview

This project analyzes user behavior across a marketing funnel to identify conversion drop-off points and uncover data-driven optimization opportunities.
The analysis focuses on how users progress from product views → add to cart → purchase, using event-level data similar to real-world product analytics tools (GA4, Mixpanel).

## 🎯 Business Objective

The business wants to understand user behavior across the marketing funnel to identify drop-off points, improve conversion rates, and optimize acquisition and engagement strategies.

This analysis helps stakeholders:

Identify where users abandon the funnel

Understand conversion efficiency at each stage

Prioritize high-impact optimization actions

## 🧠 Funnel Definition
Funnel Stage	User Action
Visit	Product View
Consideration	Add to Cart
Conversion	Purchase

Funnel stages were defined based on increasing levels of user intent, aligned with standard e-commerce behavior.

## 📂 Dataset Description

Dataset: E-commerce Events History (Cosmetics Shop)

The dataset contains event-level user interactions, enabling detailed funnel and behavioral analysis.

Key Columns:

user_id – Unique user identifier

event_type – User action (view, cart, purchase)

event_time – Timestamp of the event

product_id – Product identifier

category – Product category

price – Product price

## 🧹 Data Cleaning & Preparation

Key preparation steps included:

Converting timestamps to datetime format

Removing records with missing user identifiers

Filtering only funnel-relevant events (view, cart, purchase)

Creating derived fields for segmentation (price bands, time-based features)

These steps ensure accurate and reliable funnel metrics.

## 📊 Analysis Performed
1. Funnel Conversion Analysis

Calculated unique users at each funnel stage

Computed stage-wise and overall conversion rates

2. Drop-Off Analysis

Identified stages with the highest user leakage

Quantified drop-off percentages between stages

3. Funnel Segmentation

Conversion analysis by:

Product category

Price bands

Time-based behavior (where applicable)

4. Time-to-Conversion Analysis

Analyzed how long users take to convert from view to purchase

Identified fast vs slow converting user groups

## 🔍 Key Insights

A large proportion of users drop off before completing purchases

The cart → purchase stage shows the highest abandonment

Higher-priced products have lower conversion rates

Certain product categories outperform others in conversion

Conversion speed varies significantly across users

## ✅ Recommendations

Based on the analysis, the following actions are recommended:

Product & UX

Improve product page clarity and trust signals

Add urgency indicators such as limited stock messaging

Marketing

Implement cart abandonment reminders and retargeting

Use time-based nudges for slow-converting users

Pricing & Offers

Introduce bundles or limited-time discounts

Test pricing strategies for high-friction products

## 📈 Business Impact

This analysis enables the business to:

Improve conversion rates without increasing traffic spend

Reduce funnel leakage at critical stages

Optimize marketing and product decisions using data

## 🛠 Tools & Technologies

SQL – Funnel aggregation and segmentation

Python (Pandas) – Data cleaning, analysis, metrics

Excel / Tableau – Visualization and stakeholder dashboards
