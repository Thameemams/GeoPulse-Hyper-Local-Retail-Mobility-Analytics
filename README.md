# ***GeoPulse: Hyper-Local Retail Mobility Analytics***

## 📋 Executive Summary
GeoPulse addresses a critical challenge in retail real estate strategy, the reliance on static demographic and census data for high-stakes store opening decisions. Traditional approaches fail to capture dynamic intra-day foot traffic patterns, frequently leading to sub-optimal site placement and revenue cannibalization between nearby franchise locations.

This project delivers an enterprise-grade, geospatial analytics pipeline and interactive visualization suite that translates raw, anonymized mobile GPS mobility data into actionable location intelligence.

# TASK I
## 🎯 Aim of the Project

- **Transition to Dynamic Mobility Intelligence**: Replace traditional, static census datasets with real-time, high-resolution mobile GPS mobility data to capture actual human movement and footfall dynamics in urban retail environments.

- **Optimize Site Selection & Expansion Strategy**: Provide a rigorous geospatial framework to evaluate prospective retail locations based on empirical foot traffic density rather than surface-level demographics.

- **Mitigate Intra-Brand Cannibalism**: Accurately quantify spatial overlap and commuter interception rates to ensure new store placements capture net-new customers instead of cannibalizing traffic from existing outlets.

- **Enable Interactive Geospatial Visualizations**: Leverage spatial databases and Kepler.gl to generate dynamic, time-scrubbable footfall heatmaps that illustrate how pedestrian volume shifts across different hours of the day.

## 📌 Problem Definition
Traditional retail site selection relies heavily on static demographic markers, historical census records, and aggregate foot-traffic estimates. However, these static sources fail to capture the dynamic temporal shifts of modern urban movement—such as shifting morning commuter corridors, lunchtime foot-traffic peaks, and evening travel patterns.

Without granular, time-aware mobility data, expanding retail chains face two critical strategic risks:

- **Inaccurate Revenue Forecasting**: Relying on static resident demographics fails to account for transient non-resident foot traffic (e.g., commuters, office workers, tourists), leading to poor site valuation and suboptimal store placement.

- **Intra-Brand Revenue Cannibalization**: Without visibility into movement trajectories and footfall origins, retailers risk opening new locations that intercept existing customer flows. This results in severe self-cannibalization—where a new store merely absorbs revenue from an established nearby location rather than capturing net-new market share.

## About the Dataset
* Domain: Retail Strategy & Geospatial Analytics
* Dataset Source Code: df_master = pd.read_csv("geo_pulse_master_dataset.csv")
* Data Type: Comma Separated Values 
* Rows: 1000
* Columns: 15

## Key Features Evaluated include:
**1. Core Mobility & Ping Attributes:** ping_id,device_id,timestamp,latitude,longitude,horizontal_accuracy.

**2. Store Proximity & Catchment Attributes:** nearest_store_id,nearest_store_name,nearest_store_status,distance_to_store_meters,is_within_catchment.

**3. Commercial Zoning & Temporal Features:** zone_id,zone_name,zone_type,base_footfall_category.  
  
