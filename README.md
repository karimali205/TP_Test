## HR Attrition Analytics — Power BI Case Study

A full data-to-decision analysis of employee attrition, built on a governed star-schema data model in Power BI. The project identifies where turnover risk concentrates across the workforce and translates that into a prioritized retention roadmap.

**Highlights**
- 1,470 employee records modeled into a star schema (`FactEmployee` + `DimDepartment` / `DimJobRole`)
- 11+ DAX measures covering attrition rate, risk segmentation, satisfaction scoring, and early/stagnation risk
- 4-page interactive dashboard: Executive Overview, Outlier Detection, Attrition Trends, and Segment Deep Dive
- Key finding: attrition is not company-wide — it concentrates in overtime-heavy, single, early-tenure employees in Sales and Lab Technician roles, at up to 3× the company average

**Stack:** Power BI · DAX · Power Query (M) · Star schema modeling

**Files**
- `HR_Attrition.pbix` — full Power BI report
- `HR_Attrition_PreDashboard_Analysis.md` — full analysis write-up (data profiling, EDA, KPI/DAX design)
- `TP_Workforce_Attrition_Insights.html` — standalone executive summary page

