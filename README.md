# Wavecon-Telecom-Analytics---5G-Performance-Analysis

![Wavecon Banner](https://img.shields.io/badge/Power%20BI-Dashboard-yellow) ![Status](https://img.shields.io/badge/Status-Complete-success) ![Analysis Period](https://img.shields.io/badge/Analysis-Jan--Sep%202022-blue)

A comprehensive Power BI dashboard analyzing the impact of 5G implementation on Wavecon Telecom's business performance across 15 major Indian cities.

## Live Dashboard :-https://app.powerbi.com/view?r=eyJrIjoiMDc4MWY4MmUtYTQ4MC00NzE3LTg2ZGItYjNlN2M2ZDUyY2NjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9


## 📊 Project Overview

This project analyzes consumer behavior and business results following Wavecon Telecom's 5G launch in May 2022. Through detailed KPI tracking and city-wise performance analysis, the dashboard provides actionable insights for strategic decision-making in the post-5G landscape.

### About Wavecon Telecom
- India's leading telecom provider with significant market presence
- Known for innovative services and customer-focused approach
- Recently launched 5G services for enhanced connectivity and faster speeds

## 🎯 Business Objectives

The analysis addresses five critical business questions:

1. **Revenue Impact**: What has been the impact of the 5G launch on overall revenue performance?
2. **KPI Performance**: Which key performance indicators have shown underperformance following the 5G launch?
3. **Plan Performance**: Which subscription plans demonstrated strong revenue performance vs. underperformance?
4. **Strategic Planning**: Should any plans be continued or discontinued based on post-launch performance?
5. **Discontinuation Analysis**: What were the reasons for plan discontinuations following the 5G launch?

## 📈 Key Metrics & KPIs

### Overall Performance
- **Total Revenue**: ₹31.87 billion (9-month period)
- **Pre-5G Revenue**: ₹15.98 billion (Jan-Apr 2022)
- **Post-5G Revenue**: ₹15.90 billion (Jun-Sep 2022)
- **Revenue Change**: -0.50% (-₹80 million)

### User Metrics
- **Total Active Users (TAU)**: 161.7M
- **TAU Change**: -8.3% (Lost 7M users)
- **Total Unsubscribed Users (TUsU)**: 12.6M
- **TUsU Change**: +23.5% (1.4M increase)
- **Average Revenue Per User (ARPU)**: ₹200.7

## 🗺️ Geographic Coverage

The analysis covers **15 strategic cities** across India, categorized into:

### Tier-I Mega Cities (6 cities)
- Delhi
- Mumbai
- Chennai
- Kolkata
- Bangalore
- Hyderabad

### Tier-II Strategic Growth Centers (9 cities)
- Pune
- Ahmedabad
- Jaipur
- Lucknow
- Chandigarh
- Gurgaon
- Patna
- Coimbatore
- Raipur

## 🔍 Critical Findings

### 1. Revenue Performance
- **Modest Decline**: 0.5% revenue decrease post-5G implementation
- **Geographic Pattern**: Tier-2 cities outperformed Tier-1 metros
- **Top Performers**: Lucknow (+1.8%), Gurgaon (+1.5%), Patna (+1.5%)
- **Underperformers**: Delhi (-2.8%), Chennai (-2.6%), Ahmedabad (-2.0%)

### 2. User Base Challenges
- **Critical User Attrition**: 8.3% decline in active users
- **Severe Unsubscribe Spike**: 23.5% increase in churn
- **Highest Attrition Cities**: Ahmedabad (-18.9%), Delhi (-17.6%), Raipur (-16.7%)
- **Growth Leader**: Pune (+18.1% active users)

### 3. Plan Performance Analysis

#### High Performers
- **P1 - Smart Recharge Pack**: +33.3% growth (₹2.4bn post-5G revenue)
- **P11 - New Ultra Plans**: Strong 5G adoption
- **P12 - Premium Plans**: Consistent performance

#### Underperformers
- **P4 - Mini Data Saver**: -20.3% decline
- **P5 - Rs. 99 Talktime**: -34.8% decline
- **P6 - Xstream Data Pack**: -33.9% decline
- **P7 - 25GB Combo Pack**: -73.3% critical decline

#### Discontinued Plans (P8, P9, P10)
Combined revenue contribution: Only 2.5% of total
- **P8 - Daily Saviour**: Low adoption & demand (1.4% of revenue)
- **P9 - Combo TopUp**: Limited flexibility (0.7% of revenue)
- **P10 - Big Combo Pack**: Mismatch with 5G behavior (0.4% of revenue)

## 💡 Strategic Recommendations

### 1. Operational Excellence
- **Focus on High-Growth Hubs**: Investigate Pune's success factors and replicate across network
- **Bridge Network Gaps**: Prioritize service quality improvements in underperforming metros (Bangalore, Chennai)
- **Ensure Reliable 5G**: Address connectivity inconsistencies to stabilize performance

### 2. Portfolio Optimization
- **Scale Up Winners**: Aggressively promote high-performing plans (P1, P11, P12)
- **Phase Out Losers**: Revamp or discontinue underperforming plans (P4, P5, P6, P7)
- **Replace Discontinued**: Introduce new 5G-compatible offerings to fill gaps from P8, P9, P10

### 3. Customer Retention
- **Segmented Pricing**: Launch affordable, tailored plans for students, families, and low-income segments
- **Proactive Churn Mitigation**: Implement loyalty rewards, user education, and improved support
- **Value Communication**: Educate customers on 5G benefits to justify premium pricing

## 📅 Project Timeline

```
2022 ANALYSIS WINDOW
─────────────────────────────────────────────
PRE-5G (4 months) | 5G LAUNCH | POST-5G (4 months)
─────────────────────────────────────────────
JAN  FEB  MAR  APR  |  MAY  |  JUN  JUL  AUG  SEP
└────────────────┘      │      └─────────────────┘
  Baseline Period    Implementation  Evaluation Period
```

## 🛠️ Tools & Technologies

- **Business Intelligence**: Microsoft Power BI
- **Data Analysis**: Advanced Excel, SQL
- **Data Processing**: Python, ETL processes
- **Presentation**: Canva

## 📂 Repository Structure

```
wavecon-telecom-analytics/
│
├── README.md                          # Project documentation
├── dashboard/
│   └── Wavecon_Dashboard.pbix        # Power BI dashboard file
├── data/
│   ├── pre_5g_data.csv               # Pre-5G baseline data
│   └── post_5g_data.csv              # Post-5G evaluation data
├── analysis/
│   ├── revenue_analysis.xlsx         # Revenue breakdown
│   ├── kpi_tracking.xlsx             # KPI performance metrics
│   └── city_performance.xlsx         # Geographic analysis
├── presentation/
│   └── Wavecon_Presentation.pdf      # Executive presentation
└── docs/
    ├── business_requirements.md      # Project requirements
    └── data_dictionary.md            # Data definitions
```

## 📊 Dashboard Features

- **Interactive City Filtering**: Drill down into specific geographic markets
- **Plan Comparison**: Side-by-side performance analysis
- **Time-Series Analysis**: Monthly trend tracking
- **KPI Cards**: Real-time performance indicators
- **Heat Maps**: Geographic performance visualization
- **Trend Indicators**: Growth, stable, decline, and critical status markers

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version)
- Basic understanding of telecom industry metrics
- Access to the Wavecon dataset

### Installation
1. Clone this repository
   ```bash
   git clone https://github.com/dharsoumyadeep96/wavecon-telecom-analytics.git
   ```
2. Open the `.pbix` file in Power BI Desktop
3. Refresh data connections if needed
4. Explore the interactive dashboard

## 📧 Contact

**Soumyadeep Dhar**  
Data Analyst | Virtual Intern at AtliQ Technologies

- **Email**: soumyadeepdhar433@gmail.com
- **LinkedIn**: www.linkedin.com/in/soumyadeep-dhar-785724333
- **GitHub**: https://github.com/dharsoumyadeep96

## 🎓 Skills Demonstrated

- Advanced Excel Analysis
- SQL Querying & Data Manipulation
- Power BI Dashboard Development
- Python for Data Processing
- ETL Pipeline Design
- Business Intelligence & Reporting
- Strategic Business Analysis
- Data Visualization & Storytelling

## 📝 License

This project is part of a virtual internship program and is intended for educational and portfolio purposes.

## 🙏 Acknowledgments

- **AtliQ Technologies** for the virtual internship opportunity
- **Wavecon Telecom** (fictional company for analysis purposes)
- Canva for presentation design resources

---

⭐ If you found this project helpful, please consider giving it a star!

**Last Updated**: February 2026
