# 🚦 Road Accident Risk Monitoring System (Excel)

## 📊 Dashboard Preview

![RoadAccident Dashboard](./dashboard.png)


## 🧩 Problem  
Accident data came from multiple sources with missing fields, inconsistent location names, and irregular date formats.  
Using this data directly would distort risk patterns and lead to incorrect safety insights.

## 🎯 Objective  
Build a reliable, repeatable system that converts messy accident records into trustworthy risk indicators for analysis and reporting.

## 🚨 Data Issues Identified  
- Missing severity and location fields  
- Inconsistent region and road-type names  
- Duplicate accident records  
- Date and time format mismatches  
- Category drift across datasets  

## 🛠️ Approach  
1. Separated raw data from clean processing layers  
2. Standardized location, road type, and severity fields  
3. Built validation checks for:  
   - Missing critical fields  
   - Duplicate accident IDs  
   - Category inconsistencies  
4. Created structured Excel summaries for risk review  
5. Modeled clean data in Power BI  
6. Designed dashboards to surface high-risk zones and trends  

## 🛡️ Validation & Control Logic  
- Record-count reconciliation between raw and clean layers  
- Null-value flags for critical safety fields  
- Category-mapping checks  
- Sanity checks on daily and regional totals  

Any failure blocks reporting.

## 📊 Output  
- Clean, standardized accident dataset  
- Risk indicators by region, time, and road type  
- Dashboard for trend and hotspot analysis  

## 💡 Why This Matters  
Safety analysis is only as good as the data behind it.  
This system is designed to:

- Expect broken inputs  
- Surface hidden inconsistencies  
- Prevent misleading patterns  
- Protect decision-makers from false risk signals  

The goal is not visualization.  
The goal is **trustworthy insight**.

## 🧰 Tools Used  
- **MS Excel** – Cleaning, Mapping, Validation, Reconciliation  
 
