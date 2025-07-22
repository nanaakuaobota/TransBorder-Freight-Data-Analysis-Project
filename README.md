#  Transborder Freight Analysis (2020–2024)

This project analyzes transborder freight data between the **U.S., Canada, and Mexico** from **2020 to 2024**, focusing on trade patterns, transport modes, cost efficiency, and environmental impact. The goal is to identify inefficiencies, recognize patterns, and propose actionable solutions to improve the overall performance and sustainability of transportation systems
---

##  Business Questions Addressed

1. **What are the major trade trends over time?**
2. **Which transport modes dominate trade, and how do they vary by weight and value?**
3. **How is trade distributed geographically (by country and U.S. state)?**
4. **Which regions experience the most congestion or inefficiency (freight cost burden)?**
5. **How do environmental metrics (e.g., CO₂ emissions) vary by transportation mode?**

---

##  Data Summary

- **Source**: [Bureau of Transportation Statistics](https://www.bts.gov/)
- **Time Period**: January 2020 – December 2024
- **Scope**: U.S. trade with Canada and Mexico
- **Key Columns**: 
  - `VALUE`, `FREIGHT_CHARGES`, `SHIPWT`, `CO2_ESTIMATES`
  - `DISAGMOT` (Mode of transport), `USASTATE`, `COUNTRY`, `MONTH`, `YEAR`

---

##  Key Insights

1. **Trade Surplus**: U.S. exports consistently exceeded imports across the period.
2. **Truck Dominance**: Trucking accounts for over **$21.4T** in trade value, making it the leading mode by far.
3. **Even Trade Split**: Trade with **Mexico ($17.19T)** slightly surpasses **Canada ($17.14T)**.
4. **Weight vs. Value**: While **vessels** carry the most weight, trucks dominate in value — reflecting different cargo types.
5. **Seasonality**: Peak trade occurs in **January–March**, especially January.
6. **Geographic Leaders**: **Texas** leads with ~$7.46T in trade value, followed by **Michigan** and **California**.
7. **Cost Inefficiency**: States like **Oklahoma (OK)** and **Delaware (DE)** have freight charges exceeding **3.5%** of trade value.
8. **Environmental Impact**: **Truck transport** emits over **1,070M kg CO₂**, far exceeding other modes.

---

## 💡 Recommendations

| Focus Area | Action |
|------------|--------|
| **Diversify Trade** | Expand trade partnerships beyond Canada & Mexico to reduce regional risk. |
| **Road Infrastructure** | Upgrade border facilities and highways to support truck freight. |
| **Modal Shifts** | Promote rail & vessel for bulk, long-haul, or low-emission shipping. |
| **State-Level Optimization** | Target cost-reduction efforts in inefficient states like OK, DE, WA. |
| **Seasonal Planning** | Align inventory and logistics with Q1 trade peaks. |
| **Green Logistics** | Invest in low-emission transport and alternative fuels. |

---

## 🛠️ Tools Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **Google Colab**
- **GitHub** (for version control & collaboration)

---

## 🚀 Reproduce This Analysis

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/transborder-freight-analysis.git
   cd transborder-freight-analysis
