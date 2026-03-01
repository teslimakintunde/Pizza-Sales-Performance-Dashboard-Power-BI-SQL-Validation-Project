# Pizza Sales Performance Intelligence
**Power BI • SQL • KPI Validation • Business Intelligence**

## Project Overview
This project analyzes transactional pizza sales data using SQL for metric validation and Power BI for interactive visualization. The objective was to transform raw sales records into executive-level insights covering revenue performance, product contribution, and customer purchasing behavior.
All KPIs displayed in Power BI were validated using SQL queries to ensure accuracy and metric integrity.

## Data Preparation & Quality Governance
- Thoroughly cleaned and standardized all data before any analysis or visualization.
- Fixed messy date fields → proper DATE type, YYYY-MM-DD format, added Day/Month/Quarter/Hour.
- Removed spaces, standardized category names, eliminated duplicates, validated IDs & quantities, zero NULLs in revenue.
- Prevented duplicate counting, inflated metrics, wrong groupings, and misleading KPIs/trends.
- Built a clean, reliable base for accurate Power BI dashboards and business decisions.



## Executive Summary
This project delivers a strategic revenue intelligence dashboard built in Power BI and validated through structured SQL analysis. The objective was not merely to visualize sales data, but to:
- Diagnose revenue concentration risk
- Identify product-level profit drivers
- Analyze demand seasonality & intraday monetization patterns
- Surface optimization levers for revenue growth and operational efficiency
  
All KPIs displayed in Power BI were independently validated using SQL queries to ensure metric governance and analytical integrity.

## Financial Performance Summary

| Metric                        | Value          |
|-------------------------------|----------------|
|  Total Revenue              | $817,860       |
| Total Orders               | 21,350         |
| Total Pizzas Sold          | 49,574         |
| Avg Order Value            | $38.31         |
| Avg Pizzas per Order       | 2.32           |

## Product Revenue Intelligence
### Top Revenue-Generating Product
**The Classic Deluxe Pizza**  
- Units Sold: **2,453** pizzas  
- Revenue Generated: **$58,750+**
- Contribution to Total Revenue: ~7.2%
  
This single SKU represents a significant revenue anchor and should be protected from pricing errors, stockouts, or operational inefficiencies.

### Lowest Performing Pizza
**The Brie Carre Pizza**  
- Units Sold: **490** pizzas  
- Revenue Generated: **$11,200**

Strategic Consideration:
- Candidate for promotional bundling
- Possible menu rationalization review
- Margin-based evaluation recommended

## Revenue Distribution & Risk Analysis
Revenue by Pizza Category

| Category | Revenue Share |
|----------|---------------|
| Classic  | 27%           |
| Supreme  | 25%           |
| Chicken  | 24%           |
| Veggie   | 24%           |

**Strategic Insight:** Revenue distribution across categories is balanced, reducing overdependence risk on a single segment. This improves revenue stability and portfolio resilience.


### Revenue by Pizza Size
| Size | Revenue Share |
|------|---------------|
| Large| **45%**       |
| Medium| 30%          |
| Small| 18%           |
| XL   | 7%            |

Financial Interpretation
- Large pizzas are the primary revenue engine.
- Nearly half of total revenue is size-driven rather than category-driven.
- Strategic pricing adjustments in the Large segment would have outsized revenue impact.

## Demand Timing & Monetization Windows
**Peak Revenue Window:**

**6 PM – 8 PM**
- It accounts for ~40% of daily revenue

This confirms strong evening monetization dependency.

Operational Implication:
- Staffing optimization required during peak window
- Potential surge pricing experiments
- Upsell prompts during high-demand hours

## Weekly Revenue Pattern
- Friday & Saturday generate highest order volumes
- Monday consistently underperforms
  
Revenue concentration toward weekend implies:
- Demand elasticity during weekdays
- Opportunity for targeted weekday promotions
- Capacity optimization through demand smoothing strategies

## Revenue Concentration 
Top 5 products contribute approximately 28% of total units sold, indicating moderate revenue concentration.

Strategic Risk:
- Overreliance on a narrow product set
- Supply chain sensitivity to high-volume SKUs

Mitigation Strategy:
- Diversify promotional emphasis
- Introduce dynamic bundling strategies

## Technical Implementation

### SQL Validation Layer
All core KPIs were computed directly in SQL:

- Total revenue, orders, pizzas sold  
- Average order value & pizzas per order  
- % revenue by category & size  
- Daily / hourly order & revenue trends  
- Top / bottom products by volume & revenue  

This ensures numerical integrity and eliminates reporting discrepancies.

### Power BI Implementation
- Optimized star schema data modeling
- DAX measures for KPI calculation
- Time intelligence measures (Month, Quarter filtering)
- Interactive slicers for executive drill-down
- Clean, decision-focused dashboard layout

## Business Recommendations

1. Stock & promote Large sizes aggressively – they drive almost half the revenue  
2. Increase marketing during low-performing weekdays  
3. Bundle underperforming pizzas with best sellers
4. Optimize staffing & kitchen prep for 6–8 PM peak window  
5. Targeted Monday promotions (e.g. lunch deals, BOGO on slow movers)  
6. Review low performers — consider limited-time offers, price adjustments or menu refresh

## Conclusion

This project demonstrates advanced capabilities in:

- Revenue analytics
- Product portfolio performance assessment
- Financial KPI governance
- Demand pattern analysis
- Executive-level BI storytelling
- SQL + Power BI integration

Rather than simply reporting numbers, this solution identifies revenue drivers, concentration risks, and monetization levers that directly support strategic business decisions.

The combination of SQL validation and Power BI visualization ensures both accuracy and strategic clarity.

--
