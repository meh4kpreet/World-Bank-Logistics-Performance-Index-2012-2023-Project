🎯 Project Objective:
To analyze and understand the impact of the COVID-19 pandemic on global logistics performance using the World Bank’s Logistics Performance Index (LPI). The project focuses on evaluating trends across countries from 2012 to 2023 and predicting India’s LPI score for 2026.


📦 Dataset Source:
World Bank Logistics Performance Index (LPI) – https://lpi.worldbank.org/report  
Dataset includes country-level LPI data and its components: Customs, Infrastructure, International Shipments, Logistics Quality, Tracking & Tracing, and Timeliness.



🔍 Methods Used:
- Data Cleaning & Wrangling using Pandas
- Exploratory Data Analysis (EDA) and Visualisation using Matplotlib & Seaborn
- Time Series Forecasting:
   • Prophet for India’s LPI trend


📈 Key Findings:
1. Global Logistics Performance Peaked Around 2016
Average global LPI score peaked at ~3.15 in 2016, followed by a decline till 2020 and only partial recovery by 2023.

*  Indicates pre-COVID maturity, then pandemic-related disruption.

2. COVID-19 Severely Impacted Logistics Efficiency
All LPI components dropped significantly in 2020.

*   Timeliness Score saw one of the sharpest drops.
*   Tracking & Tracing and International Shipments also fell.

3. Germany and Singapore Consistently Top Performers
Held #1 and #2 ranks across most years.Both showed minor declines post-COVID but remained global logistics benchmarks.

4. India and China Showed Steady Improvement
India’s LPI score increased from ~2.88 in 2012 to ~3.2 in 2023.

5. U.S. Logistics Rank Volatile Despite High Score
United States maintained a good LPI score (~3.5) but dropped in global ranking post-2018.

6. Global Average LPI Declined Post-COVID
*   Pre-COVID (2012–2018): Avg LPI ≈ 3.12
*   Post-COVID (2020–2023): Avg LPI ≈ 2.95

7. Among all LPI metrics, Timeliness Score shows least volatility over the decade.



⚙️ Tools & Libraries:
- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- Prophet 



✅ Conclusion:
COVID-19 significantly disrupted global logistics, especially in low- and middle-income countries. While recovery is visible in 2023 data, infrastructure and shipment reliability remain major concerns. Insights can help policymakers prioritize investments in customs and tracking systems.



📅 Forecast for 2026:
Based on Prophet & ARIMA models, **India's LPI score is expected to rise slightly to ~3.18 by 2026**, indicating a slow but steady post-pandemic recovery.

