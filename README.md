# Transborder Freight Analysis (2020–2024)

This project analyzes **transborder freight data** between the U.S., Canada, and Mexico from 2020 to 2024, focusing on trade patterns, transport modes, cost efficiency, and environmental impact.  
The goal is to identify inefficiencies, recognize patterns, and propose actionable solutions to improve the overall performance and sustainability of transportation systems.

---

## Business Questions Addressed
- What are the major trade trends over time?  
- Which transport modes dominate trade, and how do they vary by weight and value?  
- How is trade distributed geographically (by country and U.S. state)?  
- Which regions experience the most congestion or inefficiency (freight cost burden)?  
- How do environmental metrics (e.g., CO₂ emissions) vary by transportation mode?  

---

## Data Summary
- **Source:** Bureau of Transportation Statistics  
- **Time Period:** January 2020 – December 2024  
- **Scope:** U.S. trade with Canada and Mexico  
- **Key Columns:**  
  - `VALUE` – Trade value (USD)  
  - `FREIGHT_CHARGES` – Shipping costs  
  - `SHIPWT` – Shipment weight  
  - `CO2_ESTIMATES` – Environmental impact estimates  
  - `DISAGMOT` – Mode of transport  
  - `USASTATE` – U.S. state  
  - `COUNTRY` – Trade partner (Canada or Mexico)  
  - `MONTH`, `YEAR` – Time period  

---

## Key Insights
- **Trade Surplus:** U.S. exports consistently exceeded imports across the period.  
- **Truck Dominance:** Trucking accounts for over **$21.4T** in trade value, making it the leading mode by far.  
- **Even Trade Split:** Trade with Mexico (**$17.19T**) slightly surpasses Canada (**$17.14T**).  
- **Weight vs. Value:** Vessels carry the most **weight**, but trucks dominate in **value**, reflecting different cargo types.  
- **Seasonality:** Peak trade occurs in **January–March**, especially January.  
- **Geographic Leaders:** Texas leads with **$7.46T** in trade value, followed by Michigan and California.  
- **Cost Inefficiency:** States like **Oklahoma (OK)** and **Delaware (DE)** have freight charges exceeding **3.5%** of trade value.  
- **Environmental Impact:** Truck transport emits over **1,070M kg CO₂**, far exceeding other modes.  

---

## Recommendations
| Focus Area             | Action                                                                 |
|-------------------------|------------------------------------------------------------------------|
| Diversify Trade         | Expand partnerships beyond Canada & Mexico to reduce regional risk.   |
| Road Infrastructure     | Upgrade border facilities and highways to support truck freight.      |
| Modal Shifts            | Promote rail & vessel for bulk, long-haul, or low-emission shipping. |
| State-Level Optimization| Target cost-reduction efforts in inefficient states (OK, DE, WA).    |
| Seasonal Planning       | Align inventory and logistics with **Q1 trade peaks**.                |
| Green Logistics         | Invest in low-emission transport and alternative fuels.               |

---

## Tools Used
- **Python (Pandas, Matplotlib, Seaborn)**  
- **Google Colab**  
- **GitHub** (version control & collaboration)  

---

## Conclusion
This analysis provided a **comprehensive view** of U.S. transborder freight activity with Canada and Mexico from 2020 to 2024.  
By leveraging the **CRISP-DM framework**, I uncovered key patterns in trade dynamics, transportation efficiency, and environmental impact.  

The insights gained equip stakeholders with the **data-driven perspective** needed to:  
- Inform logistics strategy  
- Optimize trade operations  
- Support sustainable cross-border commerce  

Access PowerPoint Presentation [here](https://azubiafrica-my.sharepoint.com/:p:/g/personal/barbara_addo_azubiafrica_org/EdnzqG0F3olKr4WR4Sv4NkEBmFKppKimvWtdPnNJi1BwWg?e=ulDFAG)
