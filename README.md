# small-biz-analytics-poc
This lab demonstrates a scalable data infrastructure for a niche retailer, Terry’s Trousers, transitioning from manual tracking to an automated analytics workflow. It bridges the gap between raw business operations and actionable data visualization.


# Small Business Analytics POC | Terry's Trousers
**Strategic Proof of Concept: Bridging E-commerce Operations and Generative AI Analytics**

## 1. Executive Summary
This project demonstrates the transition of a niche retailer, **Terry’s Trousers**, from static data tracking to an automated, AI-assisted analytics workflow. By leveraging raw website data and applied Generative AI logic, this lab establishes a scalable framework for identifying high-value revenue drivers and optimizing marketing spend.

## 2. The Problem 
Standard retail reporting often suffers from **Operational Blindness**. In analyzing the Terry's Trousers dataset, I identified three critical friction points:
* **Data Silos:** Revenue and session data were trapped in spreadsheets without actionable context.
* **Context Gaps:** Raw numbers:  total revenue of $127,282.20 failed to explain the *velocity* of specific channels.
* **Resource Misalignment:** Identifying that high-intent traffic Email/Direct was being under-leveraged compared to low-intent discovery traffic (Social).

## 3. The Technical Solution 
This lab utilizes a multi-layered approach to data interpretation:
* **Data Source:** Structured Google Sheets/CSV exports containing session-level data (Users, Sessions, Transactions, Revenue).
* **Logic Layer:** Integration of Gemini (Generative AI) to perform rapid SQL-style aggregations and sentiment/intent analysis.
* **Visualization Layer:** Automated KPI dashboards focused on **ARPS (Average Revenue Per Session)** rather than just total volume.

## 4. Key Performance Insights
Through AI-driven analysis, the following critical business logic was established:
* **Revenue Efficiency Leaders:** Email marketing emerged as the most efficient channel, generating **$5.76 per session**, significantly higher than Organic Social at **$0.62 per session**.
* **High-Intent Re-engagement:** The high ARPS for Email (4.0% – 6.0% conversion rate) indicates a pre-qualified audience that warrants increased CRM automation.
* **Segmented Performance:** Top revenue-generating segments identified include **Direct (desktop)** at $28,520.00 and **Paid Search (desktop)** at $22,500.00.

## 5. Dev Notes & Methodology
The development process followed a rigorous "Proof of Work" cycle:
1. **Exploratory Data Analysis (EDA):** Aggregating 1,529 total transactions into channel-specific buckets.
2. **Hypothesis Testing:** Diagnosing the "User Intent Profile" of traffic sources to determine where to scale spend.
3. **Architecture documentation:** Maintaining a clean "Dev Notes" log to ensure
