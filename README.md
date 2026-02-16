**📊 Finance P&L Analytics Platform
End-to-End Financial Data Modeling, FX Normalization & CFO-Level Dashboards**

Overview
This project delivers an end-to-end Finance Analytics solution that converts raw P&L and balance sheet data into standardized CFO-level KPIs and executive dashboards. The platform supports multi-company analysis, yearly/quarterly views, dynamic currency conversion (Naira ↔ USD), and automatic value scaling (Millions/Billions), with outputs available in both Excel dashboards and a Python (Plotly/Dash) web application.
![WhatsApp Image 2026-02-17 at 00 05 36](https://github.com/user-attachments/assets/1836d5ec-04f1-4e58-9be0-62a084e46e5e)

Business Objective
Enable Finance leadership to:
* Monitor profitability and margin trends
* Evaluate capital efficiency
* Compare performance across companies and periods
* Assess FX impact on financial results …using a single, automated, and reliable analytics framework.

Data Sources
* P&L Excel data: Revenue, GP, EBITDA, EBIT, PAT (quarterly & yearly)
* Balance Sheet Excel data: Capital, assets, FX rates (Naira ↔ USD)

Data Processing & Modeling
* Ingested and validated raw Excel financial data
* Cleaned, standardized, and reconciled financial metrics
* Integrated balance sheet data for FX-based currency conversion
* Implemented dynamic scaling logic to auto-display values in Millions or Billions
* Built a reusable finance KPI base table consumed by both Excel and Python dashboards

Finance KPI Framework
Core P&L Metrics
* Revenue, Gross Profit, EBITDA, EBIT, Net Profit (PAT)
Margin Metrics
* GP %, EBITDA %, EBIT %, PAT %, Operating Margin
Capital & Efficiency Metrics
* Average Capital Employed
* ROCE
* Fixed Asset Utilization
* Capital Absorption Ratio
Comparative Analysis
* QoQ and YoY variance (absolute & %)
All KPIs are explicitly defined, standardized, and reproducible, ensuring a single source of truth for Finance.

![WhatsApp Image 2026-02-16 at 22 59 21](https://github.com/user-attachments/assets/b14e12d0-9ae9-4e17-bad3-0b849929ac48)


Excel Dashboard (CFO View)
* Fully automated Excel dashboard with:
    * Company selector
    * Yearly / Quarterly toggle
    * Currency toggle (Naira / USD)
    * Automatic Million / Billion scaling
![WhatsApp Image 2026-02-17 at 00 04 54](https://github.com/user-attachments/assets/f49a55de-dfbe-4a38-9ce1-b9ccfd674d2d)

* Executive-friendly KPI layout with clear variance indicators
* Eliminates manual recalculations during finance reviews


Python Dashboard (Plotly / Dash)
In parallel, the same analytics logic is implemented as a Python-based interactive dashboard.
Design Principles
![WhatsApp Image 2026-02-17 at 00 08 48](https://github.com/user-attachments/assets/accd5ecb-d12f-47ae-b061-a279b2693264)

![WhatsApp Image 2026-02-17 at 00 09 04](https://github.com/user-attachments/assets/e7fc5209-cba4-4a85-bb59-7eb254ff9f24)

* Modular, production-style codebase
* Clear separation of:
    * Data loading
    * FX conversion
    * KPI computation
    * Filter controls
    * UI layout
* Logic parity with Excel dashboards
Capabilities
* Interactive KPI tiles and charts
* Dynamic filtering by company, period, and currency
* Designed to be hosted as a web application for broader access
This ensures consistency between traditional Finance reporting and scalable web-based analytics.

Data Governance & Quality Controls
* Standardized KPI calculation definitions
* Reconciliation and sanity checks for financial accuracy
* Period completeness and consistency validation
* Audit-friendly and explainable calculations
These controls make the platform suitable for Finance and leadership reporting.

Technology Stack
* Python: Pandas, NumPy, Plotly, Dash
* Excel: Automated Finance dashboards
* Analytics: P&L, margin analysis, ROCE, capital efficiency
* Data Modeling: Multi-source financial data integration

Business Impact
* Reduced manual P&L preparation and reconciliation effort
* Improved visibility into profitability and capital efficiency drivers
* Enabled faster, more confident CFO-level decision-making
* Created a scalable foundation for future Finance analytics and hosting

Author
Parveen Sharma Senior Data Analyst | Finance, BI & Analytics
