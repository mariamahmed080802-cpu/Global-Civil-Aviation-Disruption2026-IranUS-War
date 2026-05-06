# Global Civil Aviation Disruption Analysis: 2026 Iran-US War Impact

<img width="1301" height="735" alt="image" src="https://github.com/user-attachments/assets/616bb0db-46d2-4937-aae8-35d3ae27aa02" />
<img width="1317" height="733" alt="image" src="https://github.com/user-attachments/assets/268efd30-13b2-44ad-b01a-56a9889a09c6" />
<img width="1308" height="738" alt="image" src="https://github.com/user-attachments/assets/7b9f3364-4ddb-4dff-90db-8799dbc595a6" />
<img width="1530" height="723" alt="image" src="https://github.com/user-attachments/assets/80908af0-99e8-4ab9-8eb7-24ad9ed29ff3" />

## Introduction

This Power BI dashboard analyzes the economic and operational impact of a hypothetical 2026 Iran-US military conflict on global civil aviation. The project demonstrates advanced data modeling, geospatial analysis, and business intelligence capabilities by simulating a real-world crisis scenario affecting international air travel.

## Problem Statement

Military conflicts in strategic regions can cause severe disruptions to civil aviation through airspace closures, flight cancellations, and mandatory rerouting. Understanding these impacts is critical for:

- **Airlines**: Assessing financial risk and operational vulnerability in conflict-prone regions
- **Governments**: Planning crisis response and aviation security protocols
- **Insurance Companies**: Pricing political risk insurance and evaluating exposure
- **Investors**: Understanding airline resilience and regional dependencies

**Why This Analysis Matters**: The Middle East hosts major aviation hubs (Dubai, Abu Dhabi, Doha, Istanbul) that connect East and West. A regional conflict could cascade into a global aviation crisis, affecting thousands of flights and causing billions in losses. This analysis quantifies that impact.

## Analysis Results

### Financial Impact
- **Total Economic Loss**: $8.52 billion across 33 airlines
- **Average Revenue Loss**: 15.22% per affected airline
- **Average Loss per Airline**: $258.15 million
- **Most Affected**: Emirates SkyCargo ($920M), Jazeera Airways ($905M), Emirates ($785M)

### Operational Disruption
- **Flights Affected**: 15,964 flights over one month (March 2026)
- **Total Cancellations**: 2,206 flights
- **Total Reroutes**: 1,150 flights
- **Disruption Duration**: 3,990 total hours of airspace closure
- **Geographic Spread**: 23 countries across Middle East, North Africa, and Europe

### Severity Analysis
- **Critical Disruptions**: 33% of flights (5,280 flights) - complete airspace closures
- **Severe Disruptions**: 29% of flights (4,658 flights) - major rerouting required
- **Peak Day Impact**: March 8-9 saw 1,200 flights disrupted per day

### Regional Vulnerability
- **UAE**: $2.7 billion in losses (32% of total) - Dubai and Abu Dhabi hubs most exposed
- **Kuwait**: $1.2 billion in losses (14% of total) - small market with high exposure
- **Iran**: $1.0 billion in losses (12% of total) - conflict epicenter
- **Top Affected Airports**: Istanbul (1,300 flights), Abu Dhabi (1,200 flights), Tehran Mehrabad (1,100 flights)

### Key Insights
1. **Hub Dependency Risk**: 70% of losses concentrated in 5 Gulf countries, exposing vulnerability of hub-and-spoke models
2. **Cargo Premium**: Cargo carriers (Emirates SkyCargo) face highest losses due to expensive rerouting vs. cancellation economics
3. **Sustained Impact**: Disruptions lasted entire month with recurring peaks, not just isolated incidents
4. **Spillover Effect**: Countries far from conflict zone (Libya, Lebanon, Jordan) experienced 400-650 hours of closures each

## Recommendations

### For Airlines
1. **Diversify Hub Operations**: Reduce dependence on Middle East hubs by developing alternative routing through Europe, Asia, or Africa
2. **Dynamic Routing Systems**: Invest in AI-powered real-time conflict zone avoidance and predictive rerouting

### For Governments & Regulators
1. **Regional Backup Hubs**: Develop contingency hub capacity in safer regions (Amman, Cairo) to absorb displaced traffic
2. **Crisis Coordination Protocols**: Establish international frameworks for rapid airspace information sharing during conflicts
3. **Infrastructure Resilience**: Invest in distributed aviation infrastructure to reduce single-point-of-failure vulnerabilities

### For Investors & Risk Analysts
1. **Portfolio Diversification**: Balance investments between hub-dependent and point-to-point carriers
2. **Scenario Modeling**: Incorporate geopolitical conflict scenarios into airline valuation models

## Conclusion

This analysis reveals that a regional Middle East conflict could trigger $8.5 billion in aviation losses within one month, affecting 16,000 flights and 23 countries. The hub-and-spoke model, while efficient in peacetime, creates systemic vulnerability during crises. Gulf carriers face existential risk with revenue losses exceeding 15%, while even peripheral countries experience severe spillover effects.

**Key Takeaway**: The global aviation industry's dependence on Middle Eastern hubs represents an under-priced geopolitical risk. Airlines, insurers, and investors should reassess their risk models and develop robust contingency strategies for conflict scenarios.

## Tools & Technologies

- **Business Intelligence**: Microsoft Power BI Desktop
- **Data Modeling**: Galaxy Schema with fact tables (Airport Disruptions, Airspace Closures, Airline Losses) and dimension tables (Date, Country, Disruption Severity, Airlines)
- **Visualization**: Interactive dashboards with geospatial mapping, time-series analysis, and drill-through capabilities
- **Analysis Techniques**: DAX measures, time intelligence, cross-filtering, severity classification

---

**Data Model Features**: 
- 3 fact tables tracking airport disruptions, airspace closures, and airline financial losses
- 6 dimension tables enabling multi-dimensional analysis by time, geography, severity, and airline
- Galaxy schema architecture optimized for analytical query performance

**Dashboard Capabilities**: 
- Interactive filtering by severity level, region, and airline type
- Geospatial heat mapping of losses by country
- Time-series analysis of daily disruption patterns
- Drill-through from regional to airline to airport-level analysis

