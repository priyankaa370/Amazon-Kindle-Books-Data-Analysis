# Amazon Kindle Books Data Analysis

## Project Overview

This project analyzes sales performance, review behavior, genre trends, and vendor distribution within the Amazon Kindle ecosystem.

Using a dataset of 133,103 records across Books, Categories, and Ratings tables, this analysis explores what drives engagement and commercial performance on Amazon’s Kindle platform.

The objective is to generate actionable business insights that could support vendor management, marketing strategy, and subscription growth (Kindle Unlimited).

## Business Questions

This analysis focuses on three core questions:

How do different genres impact sales performance?

How have book reviews evolved over time?

Which vendors dominate the Kindle marketplace?

## Dataset Structure

The dataset consists of three relational tables:

• Books

• Categories

• Ratings


![Amazon Kindle book data drawio](https://github.com/user-attachments/assets/f7e3f910-7a0f-4052-98ed-375edcdcd171)

Total Records: 133,103

The structure allows joining sales, genre classification, publishing date, and review metrics for multidimensional analysis.

## Key Findings

### 1. Genre Impact on Sales 
  
  Genre plays a major role in Kindle performance.
  
  **Top Performing Genre:**
  
  Mystery, Thriller & Suspense
  → 6,250 books sold (as of October 2023)
  
  **Lowest Performing Genre:**
  
  Comics
  
  This suggests that certain genres translate better to digital formats, while others (like comics) may still perform stronger in physical formats.
  
  **Kindle Unlimited Insights:**
  
  High Availability in Subscription:
  
  Romance – 74.83%
  
  LGBTQ+ – 71.10%
  
  Science Fiction – 59.78%
  
  Low Availability:
  
  Political & Social Sciences – 6.53%
  
  Science & Math – 6.51%
  
  **Business Insight:**
  There is an opportunity to expand underrepresented genres in Kindle Unlimited to diversify subscription appeal.

### 2. Book Review Trends (Reader Engagement Analysis)

Review volume shows a strong upward trend beginning around 2011, accelerating significantly after 2015.

**Peak engagement:**

5,717,924 reviews recorded in 2020

Recent publications (2021–2023) show consistently high review counts, indicating strong reader engagement with newer titles.

**Business Insight:**
Growing review activity suggests increasing reader interaction. This can be leveraged through:

- Targeted marketing campaigns

- Highlighting highly reviewed titles

- Encouraging review-based recommendation systems

Reviews are a powerful feedback loop in digital marketplaces. They influence conversion rates, visibility, and ranking algorithms.

### 3. Vendor Performance Analysis

The vendor landscape shows significant concentration.

Top Vendors by Books Sold (as of October 2023):

- Amazon.com – 48,962

- Hachette Book Group – 3,627

- Penguin Group USA LLC – 3,225

There is a large disparity between Amazon and third-party publishers.

**Business Insight:**
While Amazon dominates distribution, strategic partnerships with major publishers could enhance catalog depth and category diversity.

An interactive Tableau dashboard allows vendor-level filtering to explore individual vendor sales performance.

## Dashboard

An interactive Tableau dashboard was developed to:

- Filter vendor performance

- Compare genre-level distribution

- Visualize Kindle Unlimited penetration

- Analyze review trends over time

![image](https://github.com/user-attachments/assets/da437aa5-5cea-4680-b7d6-1665dd35bb07)

## Strategic Recommendations

- Expand Kindle Unlimited coverage in underrepresented genres such as:

  - Law
  
  - Parenting & Relationships
  
  - Business & Money

- Leverage high-engagement genres (Mystery, Romance, Sci-Fi) in targeted acquisition campaigns.

- Use review growth strategically:

  - Highlight books with rapid review accumulation
  
  - Promote top-reviewed new releases
  
  - Integrate review velocity into marketing triggers

- Strengthen partnerships with top-performing publishers to balance marketplace dominance and diversify catalog quality.

## Technical Stack

- SQL (data modeling and joins)

- Tableau (interactive dashboard development)

- Excel / Data preprocessing

- Data visualization and exploratory analysis

## Project Impact

This project demonstrates the ability to:

- Translate raw marketplace data into business insights

- Identify growth opportunities in subscription services

- Analyze engagement behavior at scale

- Communicate findings through executive-ready dashboards

The analysis combines commercial thinking with data-driven storytelling — a critical skill in product analytics and marketplace optimization roles.











