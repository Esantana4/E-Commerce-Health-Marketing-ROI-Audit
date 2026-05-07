# E-Commerce-Health-Marketing-ROI-Audit

Author: Erik Santana   

Tools Used: BigQuery SQL, Excel, Power BI

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project Overview

This project evaluates the "health" of an e-commerce website by analyzing user behavior across different devices (Mobile, Desktop, Tablet) and marketing channels. The goal is to identify where customers "click away" and which platforms/tiers drive the most revenue.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Key Insights & Analytics

1. Funnel Performance (The Drop-Off)

The Question:

Where are we losing the most customers in the checkout process?

Findings: 

There is a 52.3% drop-off between the checkout and purchase stages.

Actionable Recommendation: 

Investigate shipping costs and checkout speed. A "guest checkout" option or a last-minute discount may prevent this high abandonment rate.


2. High-Value Channel Analysis

The Question: 

Which channel brings in "Big Spenders" regardless of total traffic?

Findings: 

The Direct channel has the highest Average Conversion Value, meaning these users spend more per transaction than those coming from social media or ads.


3. User Tier Monetization

The Question: 

Are "Premium" members our top spenders?

Findings: 

Surprisingly, Free users are the top spenders; there are zero Premium users in the Top 15.

Actionable Recommendation: 

Target the top 15 "Free" users with a trial or incentive to convert them into the Premium tier, as they already demonstrate high loyalty.


4. Platform Prioritization (Mobile vs. Tablet)

The Question: 

Should we prioritize a Tablet-specific UI update?

Findings: 

While Tablets have the highest conversion rate (5.11%), they only represent 10% of traffic. Mobile drives the most volume and the highest revenue per hour.

Actionable Recommendation: 

Prioritize the Mobile UI update first to maximize the impact on total revenue.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Technical Skills Demonstrated

Funnel Analysis: 

Built logic to track user progression, identifying a 52.3% drop-off at the checkout phase.

Performance Benchmarking: 

Compared Conversion Rates and Revenue-Per-Hour across Mobile, Tablet, and Desktop.

User Segmentation: 

Ranked top spenders using SQL window functions, discovering that Free users outpaced Premium members.

Marketing ROI: 

Calculated Average Conversion Value by channel to identify that "Direct" traffic provides the highest quality leads

Data Transformation: 

Extracted and cleaned raw data in BigQuery to create stakeholder-ready insights for Power BI.

