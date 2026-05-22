# Australian NEM Carbon Emission & Renewable Energy Analysis

🚀 **Runner-up – Business Analytics Project Competition (Macquarie University)**  
👩‍⚖️ Judged by Snowy Hydro representatives: Carley Beever, Corrine Li, Linda Carlanita

---

## Overview

Electricity generation remains one of the largest contributors to carbon emissions in Australia’s National Electricity Market (NEM). Understanding how carbon intensity changes throughout the day is critical for improving renewable integration, demand-side planning, and sustainable energy consumption.

This project analyzes intra-daily carbon emission intensity patterns across major NEM regions between 2019 and 2025 using CSIRO emissions data and generator bidding behavior.

The analysis identifies:
- High and low emission time blocks
- Regional renewable performance differences
- Household vs company emission behavior
- Seasonal emission trends
- Future emission forecasts

The project combines time-series analytics, data visualization, and machine learning forecasting to generate actionable insights for policymakers, businesses, and energy consumers.

---

## Executive Summary

- Victoria and New South Wales consistently recorded the highest carbon emission intensity due to fossil-fuel dependence.
- South Australia emerged as the strongest renewable benchmark, maintaining lower and more balanced emissions throughout the day.
- Midday periods in South Australia and Tasmania consistently showed the lowest carbon intensity, making them ideal for cleaner electricity usage.
- Business operating hours aligned closely with the highest-emission periods across most regions.
- Random Forest forecasting suggested NSW emissions remain consistently high into 2026, while South Australia maintains lower but more variable emissions due to renewable dependence.
- The strongest opportunities for decarbonization lie in demand shifting, renewable expansion, storage integration, and grid flexibility improvements.

---

## 🎥 Project Presentation

This project was presented during the final round of the Macquarie University Business Analytics Project Competition.

[👉 Watch the Presentation Video](https://drive.google.com/file/d/1wSMOMRh4vxKqcSD58TXr_cW-mGnShLkw/view?usp=sharing)

The presentation focused on:
- Intra-daily carbon emission trends
- Renewable vs fossil-fuel emission behavior
- Household vs company electricity usage
- Regional renewable benchmarks
- Forecasting future emission intensity trends

---

## Dataset

This project uses carbon emission intensity and electricity generation data sourced from the CSIRO Emissions Intensity API and National Electricity Market (NEM) datasets.

### Key Features
- Region (NSW, VIC, QLD, SA, TAS)
- Emission intensity (gCO₂/kWh)
- Timestamp (hourly granularity)
- Generation technology type
- Generator bidding behavior
- Electricity consumption patterns

### Data Characteristics
- Time-series dataset spanning 2019–2025
- Hourly-level granularity
- Multi-region comparative analysis
- Renewable vs fossil-fuel segmentation
- Seasonal and intra-daily trend analysis

---

## Methodology

### 1. Data Collection & Preparation
- Retrieved carbon emission intensity data from the CSIRO Emissions Intensity API
- Merged multi-year regional datasets
- Cleaned timestamp inconsistencies and aligned hourly intervals
- Structured datasets for regional and temporal analysis

### 2. Time-Series Analysis
- Analyzed intra-daily carbon emission curves across NEM regions
- Compared yearly and seasonal emission trends
- Evaluated time-of-day emission intensity patterns

### 3. Behavioral & Regional Analysis
- Compared household vs company electricity usage periods
- Evaluated regional differences in renewable integration
- Identified low-emission time blocks suitable for cleaner electricity consumption

### 4. Visualization & Insight Generation
- Built line plots, heatmaps, stacked charts, boxplots, and comparative bar charts
- Generated regional emission profiles and renewable performance comparisons
- Highlighted carbon-intensive operational periods across regions

### 5. Predictive Modeling
- Applied a Random Forest Regressor using historical emission intensity data
- Forecasted 2026 daily carbon emission intensity for South Australia and New South Wales
- Compared renewable-heavy and fossil-fuel-dominant emission behavior

---

## Key Insights & Visualizations

### Intra-Daily Regional Emission Patterns

- NSW, VIC, and QLD showed strong morning and evening emission peaks aligned with residential and industrial demand.
- SA and TAS maintained significantly lower midday emissions due to stronger renewable integration.
- Fossil-fuel dominant regions exhibited consistently higher baseline emissions throughout the day.

### South Australia as a Renewable Benchmark

- South Australia demonstrated one of the most balanced low-emission profiles across the NEM.
- Renewable-heavy generation reduced carbon intensity during peak demand periods.
- The region showed how renewable integration can support both grid flexibility and lower emissions.

### Household vs Company Emissions

- Business operating hours aligned closely with high-emission periods across most regions.
- Household electricity usage during non-peak periods showed noticeably lower average carbon intensity.
- Tasmania and South Australia maintained relatively balanced emission levels across both user types.

### Forecasting Analysis

- Forecasting results showed NSW maintaining consistently high projected emissions into 2026.
- South Australia displayed greater short-term variability but significantly lower long-term carbon intensity.
- Results highlighted the importance of renewable expansion and storage systems for long-term decarbonization.

---

## Business & Policy Recommendations

- Encourage demand shifting toward low-emission midday periods.
- Expand renewable infrastructure in fossil-fuel dominant regions such as NSW and Victoria.
- Improve grid flexibility using battery storage and demand management systems.
- Encourage businesses to align operational loads with cleaner energy periods.
- Support renewable transition strategies through policy incentives and infrastructure upgrades.

---

## My Contribution

I independently led the development of Question 2 of the project, focusing on intra-daily carbon emission analysis and time-series insight generation.

### Responsibilities
- Collected and merged hourly carbon intensity and generator bidding datasets
- Cleaned and aligned multi-year regional data (2019–2025)
- Built visualizations including line plots, heatmaps, boxplots, and comparative charts
- Applied Random Forest forecasting for 2026 emission predictions
- Identified low-emission time blocks for households and businesses
- Designed presentation visuals and delivered the Question 2 presentation segment
- Connected analytical findings to strategic recommendations for decarbonization and renewable adoption

---

## Recognition

🏆 Runner-up – Business Analytics Project Competition (Macquarie University)

The project was recognized for:
- Strong analytical storytelling
- Regional emission insight generation
- Renewable energy benchmarking
- Actionable decarbonization recommendations

Judged by Snowy Hydro representatives:
- Carley Beever
- Corrine Li
- Linda Carlanita

---
