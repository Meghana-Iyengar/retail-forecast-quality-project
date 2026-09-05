# Retail Forecast Quality & Process Redesign

Business analysis project applying standardized business rules to improve retail 
demand forecast reliability, using the Rossmann Store Sales dataset (1,115 stores, ~1M records, 2013-2015).

## Problem
Store-level sales forecasts drive inventory and staffing decisions, but naive 
forecasting approaches don't account for data quality issues — closed-store days, 
active promotions, and holidays — leading to inconsistent accuracy across stores.

## My approach
- Analyzed historical data to quantify data quality issues: 17% closed-store days, 
  38% promo days, 16% of stores with historical gaps (up to 184 missing days)
- Designed and implemented business rules to handle closures, promotions, and 
  holiday effects
- Built a forecast quality/confidence flagging system based on data completeness
- Documented full BA deliverables: BRD, user stories, process flow, stakeholder RACI

## Results
**WAPE reduced from 36.82% (naive baseline) to 13.95% (with business rules) — 
a 62.1% relative improvement.**

## Deliverables
- [Business Requirements Document, User Stories & RACI Matrix](https://app.notion.com/p/Retail-Forecast-Quality-Project-3d190780c32e800eb631d6af828d6f8d?source=copy_link)
- [Process Flow Diagram (Current vs Proposed)](https://miro.com/app/board/uXjVHqnsgPw=/?share_link_id=835797982195)
- [Interactive Dashboard](https://public.tableau.com/views/forecast_quality_dashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [Data Analysis Notebook](https://colab.research.google.com/drive/1P-6YA508Y7a_BJU-V4G5QdAOuLvqU2ia?usp=sharing)

## Tech used
Python (pandas), Google Colab, Tableau Public, Miro, Notion

## Skills demonstrated
Requirement gathering, BRD/FRD writing, business rule design, stakeholder analysis, 
process mapping, data quality analysis, forecast accuracy (WAPE) evaluation
