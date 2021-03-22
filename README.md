# Hourly Demand Analysis

Quick analysis to see if a [solar-based daytime demand dip](https://twitter.com/BPBartholomew/status/1373658562988154885) is occurring in a particular locale, using the [EIA Hourly Electric Grid Monitor](https://www.eia.gov/beta/electricity/gridmonitor/dashboard/electric_overview/US48/US48) data.

# Instructions for use

This is for lower-48 US state analysis:

* Determine your [local interchange / balancing authority](https://www.eia.gov/beta/electricity/gridmonitor/dashboard/electric_overview/US48/US48)
* Download the [full demand file](https://www.eia.gov/opendata/qb.php?category=2122628)
* Run [python notebook analyses](hourly_demand_analysis.ipynb)

Generates:

* Lowest Load Day of Year by Hour analysis
![lowest load day of year](images/lowest_by_year.png)

* Average Load by Hour analysis, stratified by weekday / weekend
![average load by hour](images/avg_by_year.png)
