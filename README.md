# Diabetes Risk Dashboard

This dashboard uses the [CDC Diabetes Health Indicators dataset](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators), derived from the Behavioral Risk Factor Surveillance System.

## Live Dashboard

The live dashboard is available here:

https://samridhipurohit.github.io/diabetes-risk-dashboard/

## Data Source

This project uses [`diabetes_012_health_indicators_BRFSS2015.csv`](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators), a cleaned version of the CDC Diabetes Health Indicators dataset derived from the Behavioral Risk Factor Surveillance System. The dataset includes 253,680 U.S. adult survey responses and contains health, lifestyle, healthcare access, and demographic indicators related to diabetes status.

## Dashboard Contents

The dashboard includes two interactive visualizations. The first visualization shows diabetes prevalence hotspots across age and BMI categories. The second visualization compares diabetes prevalence gaps across selected risk factors among adults aged 55–64 with Obese I BMI.

## Real-World Impact

This dashboard helps identify population subgroups where diabetes prevalence is most concentrated. These findings can support public health communication, screening priorities, and prevention strategies focused on high-risk groups.

## Files in This Repository

- `index.Rmd`: source code for the dashboard
- `index.html`: rendered dashboard file for GitHub Pages
- `README.md`: project description and dashboard documentation
- Source dataset: linked above through the UCI Machine Learning Repository