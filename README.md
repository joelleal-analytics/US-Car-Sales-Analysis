# Evaluating US Car Sales Trends, Regional Demand, and Market Share (2018-2024)
A data analytics portfolio case study project analyzing **1M+** rows of raw US car sales data from 2018 to 2024.

## Executive Summary

In the modern automotive industry, understanding macro-level sales volume trajectories, regional demand density, and targeted consumer demographics is critical to sustaining operational efficiency and market dominance. This case study analyzes an expansive dataset comprising over 1,000,000 rows of real-world automotive transaction records spanning from 2018 to 2024.

The core business challenge was to take an unorganized, high-volume database ledger and extract actionable operational intelligence. This project addresses four central business questions: How did macro-economic shocks impact sales trajectories? Which geographical macro-regions dictate enterprise profitability? How are consumer demographics segmented by age and gender? And what financing methodologies drive sales friction reduction?

## Data Preparation and Business Problem

Handling over one million rows natively within Microsoft Excel pushed physical computing hardware boundaries and required structured, optimized formulas to eliminate computational lag. The data preparation phase converted a raw, uncurated data dump into an enterprise-ready relational data model through three clear engineering actions:
* **Chronological Standardization:** Raw transactional timestamp records were isolated, re-formatted, and bucketed into explicit fields for Year and Month, enabling deep temporal timeline charting.
* **Relational Data Mapping:** The original data contained fifty distinct fields for individual U.S. states, creating immediate cognitive overload when visualized. To address this, a secondary relational reference grid mapping the fifty states into the four official U.S. Census Bureau macro-regions (West, South, Midwest, Northeast) was engineered. A highly optimized XLOOKUP column matrix was deployed across the 1,000,669 rows to systematically assign geographical cohorts.
* **Metric & Structural Integrity:** Column numeric values representing vehicle sale prices were stripped of data noise, formatted using appropriate currency notations, and decimal points were cut to achieve standard corporate accounting views. 

[![Macro Sales and Revenue Lifecycle](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Macro%20Sales%20and%20Revenue%20Lifecycle.png)](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Macro%20Sales%20and%20Revenue%20Lifecycle.png)

## Data-Driven Strategic Observations

To deliver professional-grade executive answers, raw chart configurations were interpreted using the structured Observation-Insight-Recommendation (O.I.R.) Matrix. This transitions simple visual summaries into corporate strategy.

#### A. Macro Sales & Revenue Lifecycles
Historical transaction value totals plateaued and retrograded between 2018 and late 2020, establishing a historical floor. Conversely, fiscal year 2021 initiated an aggressive, near-exponential hockey-stick growth trajectory that continued through 2024, scaling aggregate cumulative revenue to $86,700,611,567.

The 2018–2020 market constraint mirrors macro-economic automotive headwinds, including severe pandemic-driven global semiconductor supply chain bottlenecks and temporary dealer network closures. The unprecedented 2021–2024 surge represents the release of historic pent-up consumer demand alongside substantial vehicle price inflation.

As the expansion curve begins showing natural stabilization traits toward late 2024, leadership must pivot from raw volume acquisition to product margin protection, auditing supply distribution channels to prevent expensive localized overstocking.

[![Geographical Revenue Optimization](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Geographical%20Revenue%20Optimization.png)](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Geographical%20Revenue%20Optimization.png)

#### B. Geographical Revenue Optimization

The geographic distribution analysis explicitly points to the South and West macro-regions as the dominant drivers of enterprise scale, significantly outpacing the combined volume totals of the Midwest and Northeast territories.

This geographical disparity aligns with domestic migration indicators toward the sun belt states and fundamentally reflects the infrastructure realities of these regions. Southern and Western territories rely far more heavily on personal vehicle ownership compared to high-density, public-transit-dominant Northeast metros.

Allocate 65% of the upcoming fiscal year's dealership real estate expansion and targeted regional marketing budgets to the South and West corridors. Concurrently, freeze capital expenditures in the Northeast and commission a specialized competitive audit to determine if the lower volumes stem from poor regional dealer footprint placement or localized competitive pressure.

[![Demographic Profiling and Customer Segementation](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Demographic%20Profiling%20and%20Customer%20Segmentation.png)](https://github.com/joelleal-analytics/US-Car-Sales-Analysis/blob/main/Demographic%20Profiling%20and%20Customer%20Segmentation.png)

#### C. Demographic Profiling & Consumer Segmentation

The target market exhibits an almost exact 50% Female to 50% Male gender equilibrium. Age distribution modeling shows that the Middle Age (40-59) and Seniors (60-70) brackets command the overwhelming majority of buying transactions, whereas Adults (30-39) and Young Adults (20-29) hold minimal market share.

Automotive capital investments are deeply bound to household life-stages and peak career earning capacities, which cluster heavily within the 40–59 window. Gender plays a negligible role in transactional intent, proving the brand possesses universal consumer appeal.

Copywriting architectures, visual creative branding, and marketing budgets should entirely abandon gender-specific targeting. Instead, focus communications on structural vehicle asset values—such as financing versatility, multi-passenger safety ratings, and long-term asset value retention—that align with the practical motivations of Gen X breadwinners.

#### D. Transactional Friction Analysis 

Transaction capital methods are almost perfectly distributed into exact thirds across all completed sales: 34% Lease, 33% Loan, and 33% Cash setups.

Consumers actively look for diverse financial structuring when acquiring high-ticket assets. The fact that nearly 67% of the entire $86.7B volume relies on transactional leverage (loans and leases) highlights that affordable localized payment options are just as vital to closing a deal as the underlying vehicle retail sticker price.

Establish stronger institutional credit partnerships with tier-1 lenders to secure exclusive, low-interest vehicle financing rates. Using flexible loan structures as competitive marketing hooks will directly convert credit-conscious buyers who are currently sitting on the fence.

## Conclusion and Technical Competencies Demonstrated

This project successfully demonstrates the processing of scale data infrastructures within an agile analytics environment. By engineering automated lookup architecture, cleaning chaotic raw tables, restructuring multi-variable pivot fields, and introducing strict visual hierarchies, a massive ledger was successfully compressed into a dynamic corporate steering instrument.

---
## Tools and Concepts Used
* **Microsoft Excel:** Large dataset standardization, data modeling, dynamic slicers, pivot tables, trend analysis
*  **Data Visualization:** KPI cards, customer demograpic segmentation, transaction capital methods, annual and regional bar charts.
  
## How to View the Project
> **Note on the Dataset Size:** Due to GitHub's 25 MB file limit, the full 257 MB interactiveExcel Workbook (1M+ rows) is hosted on Google Drive.

**Click here to download the full interactive Excel file on Google Drive**
  
(https://docs.google.com/spreadsheets/d/1hEtWUjCvK-zgHI-7Jb3tLMxT9gDVRNRH/edit?usp=sharing&ouid=111368309867430580226&rtpof=true&sd=true)
  
> *Note: Google Drive will show a preview warning due to file size, but the file can be downloaded normally.*

* You can also see the case study, by clicking the "Evaluating US Car Sales Trends, Regional Demand, and Market Share (2018-2024).pdf" above.
